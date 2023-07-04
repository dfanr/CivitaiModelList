## YUZUFinetune
### 一、模型概述

- 标签：`anime`, `style`
- 下载数：470
- 收藏人数：117
- 评论人数：6
- 评分人数：1
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.2

- 统计数据
  - 发布时间：2023-04-14T10:22:58.977Z
  - 原始模型：SD 1.5
  - 下载数：370
  - 评分人数：1
  - 评分：5
- 下载地址
  - [yuzufinetune_v12.safetensors](https://civitai.com/api/download/models/44828)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f0b0936d-4043-43d3-12a7-49072ab3d400/width=450/487328.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/07bc6bd1-41ab-45c2-b335-e69d392cfe00/width=450/487330.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/470fa550-85e2-4a8e-7100-07e42f594000/width=450/487316.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cb21bc77-a11b-489a-6ac5-14bdd5fe1700/width=450/487339.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-04-13T15:52:47.135Z
  - 原始模型：SD 1.5
  - 下载数：100
  - 评分人数：0
  - 评分：0
- 下载地址
  - [yuzufinetune_v10.safetensors](https://civitai.com/api/download/models/43620)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2571e738-11b1-40b7-1dbf-1806a1914c00/width=450/477081.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/722c0db9-e29b-4f14-ff8a-1f203fb24200/width=450/476878.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0d0d5c7c-5e21-4ad8-c5cd-0fa44ae7b800/width=450/476879.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7e12c58d-0247-4c94-b574-6140151a0c00/width=450/477060.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is a finetune model based on <a target="_blank" rel="ugc" href="https://civitai.com/models/24383/grapefruit-hentai-model">grapefruit</a> checkpoint.</p><p>I used around 1k images from gelbooru by artist Muririn and Kobuichi for finetuning. Initially, I wanted to just train a Lora or standard dreambooth, but neither really achieve anything even remotely useful. If anyone have tips for finetune SD models, I am all ears.</p><p></p><p>About the examples:</p><p>The first one (hot spring one) was created with simple prompts, I selected this one because it also genereated text windows just like a galgame. But this can be negated with negative prompts.</p><p>The second one (Ningguang) used <a target="_blank" rel="ugc" href="https://civitai.com/models/8546/ningguang">this </a>Lora. I tested a little bit, for all loras I tested, the image will be over saturated if I don't lower the lora weight. I simply dialed the weight down to 0.5. Maybe there are better solutions.</p><p>The third one used the same prompt with <a target="_blank" rel="ugc" href="https://civitai.com/images/329636?modelVersionId=29179&amp;prioritizedUserIds=39650&amp;period=AllTime&amp;sort=Most+Reactions&amp;limit=20">grapefruit intro image.</a></p><p></p><p>I didn't really play around with the parameters to explore further. These are just some random samples that look okay-ish. Overall, I found the finetune model is more susceptible to distorted images such as missing limbs (hot spring example). I assume some merging with more stable models or more prompts are needed to mitigate these issues.</p><p></p><p>Lastly, trigger words yuzu$style is not a must, but it does emphasize the style a little more.</p><p></p>