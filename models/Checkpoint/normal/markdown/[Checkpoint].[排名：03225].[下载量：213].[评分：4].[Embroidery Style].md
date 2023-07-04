## Embroidery Style
### 一、模型概述

- 标签：`versatile`, `embroidery`, `realistic`
- 下载数：213
- 收藏人数：75
- 评论人数：1
- 评分人数：1
- 评分：4

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] 1.0

- 统计数据
  - 发布时间：2023-01-22T01:08:10.622Z
  - 原始模型：SD 2.1 768
  - 下载数：213
  - 评分人数：1
  - 评分：4
- 下载地址
  - [embroideryStyle_10.ckpt](https://civitai.com/api/download/models/5754)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e08f26d8-bf5a-4fb4-dc15-dd71e942d600/width=450/47495.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0f796f23-0734-4927-5b92-7562eb4aad00/width=450/47513.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/36bcc389-6e82-4790-5337-60a3a977cb00/width=450/47512.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/10550603-8060-4d49-2e13-5bfc92819a00/width=450/47511.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>this model was trained with almost 400 images of the embroidery works of "<a rel="ugc" href="https://www.instagram.com/bordando_personajes_arg">Bordando Personajes Argentina</a>".</p><p>the model specializes more in generating anime embroidery but can be quite versatile if you experiment enough.</p><p>to force the style you must use the prompt <strong><em>embroidery by embarg</em></strong><em>.</em></p><p><em>I have not achieved good results with img2img. more experimentation is needed.</em></p><p>training was done in 3000 steps with a learning rate 2e-6.</p><p>The text encoder was not trained. More than 6000 regularization images from the datasets <a target="_blank" rel="ugc" href="https://huggingface.co/datasets/waifu-research-department/regularization/tree/main">waifu-regularization-3.3k and </a><a target="_blank" rel="ugc" href="https://huggingface.co/datasets/waifu-research-department/regularization/blob/main/husbando-regularization-3.5k.zip">husbando-regularization-3.5k</a> were used.</p><p>the base model was the SD 2.1 with 768 x 768 images.</p><p>all training was done on Google Colab free with a Tesla T4 and took about 1 hour.</p><p>the notebook used was the one from <a target="_blank" rel="ugc" href="https://colab.research.google.com/github/TheLastBen/fast-stable-diffusion/blob/main/fast-DreamBooth.ipynb">TheLastBen</a>.</p><p></p><p>Typical negative prompts:</p><p></p><p>Disfigured, bad art, amateur, poorly drawn, ugly, flat, deformed, poorly drawn, extra limbs, close up, b&amp;w, weird colors, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits , cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), out of frame, extra fingers, mutated hands, ((poorly drawn hands)), (( poorly drawn face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs )), cloned face, (((disfigured))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck)))</p>