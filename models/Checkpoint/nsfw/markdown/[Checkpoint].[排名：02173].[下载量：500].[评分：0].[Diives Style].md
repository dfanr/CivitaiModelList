## Diives Style
### 一、模型概述

- 标签：`draw style`, `diives style`, `diives`, `artstyle`
- 下载数：500
- 收藏人数：111
- 评论人数：2
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] 1.0

- 统计数据
  - 发布时间：2023-01-24T04:03:11.557Z
  - 原始模型：Other
  - 下载数：500
  - 评分人数：0
  - 评分：0
- 下载地址
  - [anything-v4.0.vae.pt](https://civitai.com/api/download/models/5951?type=VAE&format=Other)
  - [diivesStyle_10.ckpt](https://civitai.com/api/download/models/5951)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cfddc96d-e517-4842-a922-1690e3098e00/width=450/50514.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f7bc12d3-ce34-48bf-7e7f-ca9e94f00700/width=450/50524.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5d758f20-12c8-4e78-3f20-7a6bba957e00/width=450/50523.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/be95af75-6c23-4344-8fa7-8d979b273900/width=450/50522.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This model was trained with the <a rel="ugc" href="https://gelbooru.com/index.php?page=post&amp;s=list&amp;tags=diives">Diives art available at Gelbooru.</a></p><p>to force the style you must use the prompt <strong><em>diives, diives art, by diives, art by diives, in the style of diives, diives style, cartoon, drawing</em></strong></p><p>training was done in 6000 steps with a learning rate 2e-6.</p><p>The text encoder was not trained. No regularization images were used.</p><p>the base model was <a rel="ugc" href="https://huggingface.co/andite/anything-v4.0">Anything V4</a> with 512 x 512 images</p><p>all training was done on Google Colab free with a Tesla T4 and took about 1 hour.</p><p>the notebook used was the one from <a target="_blank" rel="ugc" href="https://colab.research.google.com/github/TheLastBen/fast-stable-diffusion/blob/main/fast-DreamBooth.ipynb">TheLastBen</a>.</p><p>just in case I attach the VAE of Anything V4. I'm not sure yet if it improves the results much, but you don't lose anything by using it.</p><p><strong>Typical negative prompts:</strong></p><p>Disfigured, bad art, amateur, poorly drawn, ugly, flat, deformed, poorly drawn, extra limbs, close up, b&amp;w, weird colors, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits , cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), out of frame, extra fingers, mutated hands, ((poorly drawn hands)), (( poorly drawn face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs )), cloned face, (((disfigured))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck)))</p>