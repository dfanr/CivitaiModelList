## Kincora  Style LoRA (6.6 MB)
### 一、模型概述

- 标签：`anime`, `azur lane`, `style`, `art style`, `artist`, `azur_lane`, `video game`
- 下载数：1539
- 收藏人数：372
- 评论人数：1
- 评分人数：3
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] 8 dim UNET only    (FOR NAI/AnythingV3 based models)

- 统计数据
  - 发布时间：2023-02-16T02:32:31.542Z
  - 原始模型：SD 1.5
  - 下载数：1539
  - 评分人数：3
  - 评分：5
- 下载地址
  - [Kincora_8dim_V2U_e8.safetensors](https://civitai.com/api/download/models/10996)
  - [Kincora.zip](https://civitai.com/api/download/models/10996?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a546cb3c-3718-4899-da6b-6b1b878c9a00/width=450/106319.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/eb4ccb93-f910-4efc-31ce-13f05d5d7600/width=450/106347.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d2134f5a-e6e5-468a-013b-33304cd86e00/width=450/106326.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ce9fdcca-63b8-4ece-c783-261d0d279400/width=450/106346.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>Kincora Style LoRA</h1><p>This is a style LoRA inspired by Kincora's art style (<a target="_blank" rel="ugc" href="https://twitter.com/KIncoraK">https://twitter.com/KIncoraK</a> )</p><p><strong>Please, do not harass them and do not sell image generated with that LoRA.</strong></p><p></p><p></p><p>I'm still doing some experiments with low net dim LoRA (8 net dim / 1 Alpha). I only trained the UNET part (without the text encoder) because I wanted it to avoid learning characters from the learning set (and reduce the risk of overfitting). I wonder if I should re-train my previous LoRAs since 160/128 dim is overkill and tend to overfit.</p><p></p><p>This LoRA was trained on 177 images (half of them are cowboy shot,upper body versions of the second half) and most of them come from Azur Lane this mean that this LoRA can generate suggestive outfits (big  cleavage, swimsuit, maids,etc...) if you don't prompt an outfit.</p><p></p><h2>Weight:</h2><p>I only tested it at weight <code>1.0</code>  but you will probably have to decrease it weight (or other LoRA weight) if you want to use it with some character LoRA (especially high dim ones)</p><p>I have not tested this on default NAI so I don't know if it's too strong for the base model.</p><p></p><h2>Recommended prompt:</h2><p>That LoRA doesn't have any activation prompt or recommended pormpt (this is a style LoRA and not a character one).</p><p>Maybe <code>eyelashes</code> for close up or portrait shot ?</p><p></p><h2>Model used for the example:</h2><p>AnythingV4.5</p><h3></h3><p></p>