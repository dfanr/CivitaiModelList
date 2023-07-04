## facialized
### 一、模型概述

- 标签：`photorealistic`, `female`, `facial`, `cumshot`, `style`, `woman`, `cum`, `realistic`, `nsfw`
- 下载数：12161
- 收藏人数：1492
- 评论人数：8
- 评分人数：16
- 评分：4.69

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v0.1

- 统计数据
  - 发布时间：2023-05-23T09:53:47.491Z
  - 原始模型：SD 1.5
  - 下载数：12161
  - 评分人数：16
  - 评分：4.69
- 下载地址
  - [facialized.safetensors](https://civitai.com/api/download/models/78701)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/93ff8f1b-19c0-4c15-9dfd-554bf5997ce6/width=450/882110.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1e2e64b4-b579-4676-aa07-4d995f0acb63/width=450/894628.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2f5a1217-3909-4814-b89e-d223b3f83947/width=450/894630.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/25613f77-0e4b-4433-b04d-6c5e327d11a5/width=450/882113.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1><code>facialized</code>: a new LoRA for facials on women</h1><p>LoRA to generate photo-realistic images of women with cum on their face.</p><p>Include in your prompt <code>&lt;lora:facialized:1&gt;, cum, facial</code>.You might want to include in your negative prompt <code>cum on breasts, cum on body</code>.</p><p>The model works best with low steps and CFG, I get good results with 10 steps and a CFG of 3 or 4.</p><p><strong><u>I am open to advice to improve this LoRA.</u></strong> Training methodology below.</p><p></p><h2>Know issues with the model</h2><p>As rightly noted by some comments, the model is still imperfect. Here is a list of a few issues I found, along with ways to circumvent them when possible. <br />I will share tags present in the training dataset that might help you circumvent some of these issues in the format <code>the tag in question [number of images out of 2676 that were associated with this tag]</code>. For example <code>smiling at camera [486]</code> means that 486 images in the dataset (composed of 2676 images in total) had the tag <code>smiling at camera</code>.</p><h3>Cum on the body / torso</h3><p>Most of the generated images depict women with cum on their body / torso / breasts. It is currently hard to remove it and ensure that cum only appears on the face.</p><p>Here are some tags present in the training dataset that might help you with this issue:</p><ul><li><p><code>cum on breasts [195]</code></p></li><li><p><code>cum on body [472]</code></p></li><li><p><code>cum on clothes [10]</code></p></li></ul><h3>Bad eyes</h3><p>The model might generate faces with non-symmetrical eyes or ill-formed eyes. You can try to alleviate this by using tags such as:</p><ul><li><p><code>symmetric eyes</code></p></li><li><p><code>same color eyes</code></p></li><li><p><code>bad eyes</code> (negative prompt)</p></li><li><p><code>strange eyes</code> (negative prompt)</p></li></ul><p>These tags do not appear in the training data but help the underlying stable diffusion checkpoint generating correct faces.</p><p></p><h2>Training methodology explained</h2><p><strong>Disclaimer</strong>: this is my first time making a LoRA and I am more than open to advice to improve it! I am detailing my methodology below, if you have any idea on how to improve it please feel free to comment.</p><h3>Dataset</h3><p>The full dataset is composed of 2676 images, hand-picked from one source. Their quality varies greatly, but nearly all of them show a unique women with cum on her face. Some outliers show 2 women (~10 images).</p><p>The image sizes are very disparate, I am reproducing here a count of the number of images for each resolution that has 10 or more images (there are 1454 different resolutions in the whole dataset).</p><pre><code>    154 3024x4032
     98 1536x2048
     96 2316x3088
     51 960x1280
     46 750x1000
     36 768x1024
     27 853x1280
     25 510x680
     25 1920x1080
     22 1080x1920
     20 1000x1333
     19 1280x960
     17 1024x768
     14 1280x1707
     14 1000x750
     13 854x1280
     13 2268x4032
     13 1200x1600
     12 2448x3264
     11 1280x1920
     11 1067x1600
     11 1024x1365
     10 600x800
     10 2000x2666</code></pre><h3>Filtering and tagging</h3><p>I used <a target="_blank" rel="ugc" href="https://colab.research.google.com/github/hollowstrawberry/kohya-colab/blob/main/Dataset_Maker.ipynb">https://colab.research.google.com/github/hollowstrawberry/kohya-colab/blob/main/Dataset_Maker.ipynb</a> to filter the dataset. Duplicates have been found with FiftyOne AI and a similarity threshold of 0.985.</p><p>Image tagging has been performed locally in stable-diffusion-ui <a target="_blank" rel="ugc" href="https://github.com/toriato/stable-diffusion-webui-wd14-tagger">stable-diffusion-webui-wd14-tagger</a> extension. Duplicate tags are removed, I used the <code>wd14-vit-v2-git</code> interrogator with a threshold of 0.35. I also added the additional tags <code>"facial", "cum", "1girl", "1women", "face", "sperm"</code>.</p><h3>Training</h3><p>I used <a target="_blank" rel="ugc" href="https://colab.research.google.com/github/hollowstrawberry/kohya-colab/blob/main/Lora_Trainer.ipynb">https://colab.research.google.com/github/hollowstrawberry/kohya-colab/blob/main/Lora_Trainer.ipynb</a> to train the LoRA. The training model was <code>sd-v1-5-pruned-noema-fp16.safetensors</code>. Tags are automatically shuffled and there is no activation tags (<code>activation_tags</code> set to 0).</p><p>Due to the size of the dataset, each image is only repeated once (i.e., no repetition). I used 5 epochs, with a batch size of 2. The UNet learning rate was set to <code>5e-4</code>. The LoRA network dimension was set to 32, and the network alpha to 16.</p><h2>Further notes on other tentatives</h2><p>I tried to manually filter images to only include "nice" images:</p><ul><li><p>high enough resolution and quality</p></li><li><p>no cum on body</p></li><li><p>"pretty" women (according to my taste)</p></li></ul><p>I filtered down the dataset to 1170 images, re-trained a LoRA, but the resulting model is clearly under-performing. I even have hard times trying make cum appear on the generated images with this model.</p><p>I tried different LoRA network dimension and alpha dimension (<code>(16, 8)</code>, <code>(32, 16)</code> and <code>(64, 32)</code>), but the best performing one seems to be the <code>(32, 16)</code>.</p>