## Humans
### 一、模型概述

- 标签：`people`, `photorealistic`, `base model`, `portrait`, `woman`, `man`, `photorealism`, `skin`
- 下载数：668
- 收藏人数：135
- 评论人数：14
- 评分人数：6
- 评分：4.17

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-28T05:01:41.664Z
  - 原始模型：SD 1.5
  - 下载数：668
  - 评分人数：6
  - 评分：4.17
- 下载地址
  - [humans_v10.safetensors](https://civitai.com/api/download/models/105639)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/097f95ba-a2fa-4a41-a66c-634828d733a4/width=450/1316596.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cec39533-bf07-4b12-9f8d-db4c695b029a/width=450/1316688.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7e5cfdcc-4f7c-4903-a8ac-2f3b0a73ff9b/width=450/1316705.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f453fb88-04cf-4742-aacc-c8a3308b0e8a/width=450/1316710.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This model is designed to produce photo realistic images of normal people. Most SD models can only produce beautiful people. This is not that. You will get acne, moles, ratty hair, crooked teeth, wrinkles, and well, ordinary people.</p><p></p><h2 id="heading-6"><strong>The short version:</strong></h2><p></p><p>There are thousands of trigger words which can be found at<a target="_blank" rel="ugc" href="https://gist.github.com/jaretburkett/cf8c224243834172fc13f72aaf49811d"> https://gist.github.com/jaretburkett/cf8c224243834172fc13f72aaf49811d</a> , or for a sorted list based on frequency, see here<a target="_blank" rel="ugc" href="https://gist.github.com/jaretburkett/41370fdf69b791d2b406f3fa538d4b32"> https://gist.github.com/jaretburkett/41370fdf69b791d2b406f3fa538d4b32</a> . The big one to know is the word “face”. A significant portion of the dataset has faces, and they were all tagged with face. Use it to get faces, without it you will get farther away shots, usually portraits. The model will do well with simple as well as much more complex prompts than normal SD models can handle. It will generate massive variations of people from seed to seed, even with the same prompt. Trained on bucket sizes of [328, 512, 640, 768, 896] at various aspect ratios, and should be able to produce images at those sizes without any hi-res fixes.</p><p></p><h2 id="heading-7"><strong>The long version:</strong></h2><p></p><p><strong>The Dataset:</strong> I have been building this dataset for around a decade. It has around 100k (and growing) carefully curated, balanced, and labeled images with the goal to remove the bias in generative AI models. It was built and added to over the years for various products I have created, and I figured it would be good to throw Stable Diffusion at it. The dataset is designed to have mostly normal people though there are some beautiful people in it as well. I always tried to keep it as balanced with the general population as I could, which is hopefully apparent from the images this model can generate. There are a lot of faces in the dataset, and they are labeled with the key word “face” to help trigger or not trigger a close up of a face. Around half of the dataset if faces only, I am working on balancing this with more portraits, headshots, full body shots for version 2.</p><p></p><p><strong>Labeling: </strong>Labeling was done partially by hand over the years, but mostly by BLIP2 more recently. I created a custom key word list for people’s photos that I use for the tagging library in addition to the standard BLIP2 captions. You can find this keyword list here <a target="_blank" rel="ugc" href="https://gist.github.com/jaretburkett/cf8c224243834172fc13f72aaf49811d">https://gist.github.com/jaretburkett/cf8c224243834172fc13f72aaf49811d</a> . It is mostly made with the help of GPT-4, and I plan to manually prune and improve this for version 2. I also plan to release my tagging code soon, but those familiar with custom interrogators can probably put this to use, if you want. The main purpose of the labeling process is to be thorough in describing people. Most SD models will do little more than old, young, man, woman, hair color and maybe race. I wanted to be able to do specifics with nose shapes, cheekbone depth, complexion, national origin, eye shape, hair styles, and very nuanced specifics, and so far I am very pleased with the results. The model now knows subtle details of the human face. This should aid in creating embeddings (textual inversions) as the model will know how to create these unique features of a face, they just need to be triggered by the embedding.</p><p></p><p><strong>What is Next: </strong>This is version 1, and really an alpha version. I am still working on it and hope that version 2 will be mind blowing. I am already training it, and improving the dataset. Currently, this one is not perfect with some details. Eyes can get wonkey, and so can teeth, more than intended at least. It will take some time to train this out, and I plan to do just that as well as add more variety of image types of normal people.</p><p></p><p><strong>Your Current LoRAs and embeddings: </strong>Yeah.. Your LoRA’s of beautiful people trained on models that can only create beautiful people are not going to work the same way here. You will likely get a picture of their back woods cousin instead of the intended subject, which is fun to play with. Give it a shot.<br /></p>