## Mosaic Art
### 一、模型概述

- 标签：`style`
- 下载数：386
- 收藏人数：137
- 评论人数：0
- 评分人数：2
- 评分：4

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2-768

- 统计数据
  - 发布时间：2022-12-15T19:59:23.362Z
  - 原始模型：SD 1.5
  - 下载数：299
  - 评分人数：0
  - 评分：0
- 下载地址
  - [mosaicArt_v2768.ckpt](https://civitai.com/api/download/models/1497)
  - [mosaicArt_v2768_trainingData.zip](https://civitai.com/api/download/models/1497?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c97d17d8-d0ac-4fc6-b277-675c95b4ae00/width=450/13118.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c32a5b50-5856-4687-9f47-6712ff0e3700/width=450/13117.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fadc96c6-9d6b-4351-f5f0-009b33c55300/width=450/13116.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e9f908ef-6b79-4342-790b-60d0038f1500/width=450/13115.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1

- 统计数据
  - 发布时间：2022-12-15T19:59:23.362Z
  - 原始模型：SD 1.5
  - 下载数：87
  - 评分人数：2
  - 评分：4
- 下载地址
  - [mosaicArt_v1.ckpt](https://civitai.com/api/download/models/1179)
  - [mosaicArt_v1_trainingData.zip](https://civitai.com/api/download/models/1179?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/857bbe24-e607-497a-87a4-eb50c3ccc000/width=450/9627.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/418fdf11-f3dd-409d-7f60-0c2a1a3f7e00/width=450/9635.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2f7c0930-0cf0-430a-b2d0-95a134f8a800/width=450/9634.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ca6c3f04-b4d0-4dc4-7b58-e03f8d63f400/width=450/9633.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is a Dreamboothed Stable Diffusion model trained on pictures of mosaic art.</p><p>The total dataset is made of 46 pictures, and the training has been done on <a href="https://huggingface.co/runwayml/stable-diffusion-v1-5" rel="ugc" target="_blank">runawayml 1.5</a> and the <a href="https://huggingface.co/stabilityai/sd-vae-ft-mse" rel="ugc" target="_blank">new VAE</a>. I used <a href="https://github.com/victorchall/EveryDream-trainer" rel="ugc" target="_blank">EveryDream</a> to do the training, using full caption on the pictures with almost no recurring word outside the main concept, so that no additionnal regularisation was needed. Out of e0 to e11 epochs, e8 was selected as the best application of style while not overtraining. Prior preservation was constated as good. A total of 9 epochs of 40 repeats with a learning rate of 1e-6.</p><p>The token "Mosaic Art" will bring in the new concept, trained as a style.</p><p>The recommended sampling is k_Euler_a or DPM++ 2M Karras on 20 steps, CFGS 7.5 .</p>