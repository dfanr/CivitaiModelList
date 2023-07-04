## Widowmaker (Overwatch) LORA
### 一、模型概述

- 标签：`character`, `female`, `widowmaker`, `game character`, `overwatch`
- 下载数：2379
- 收藏人数：356
- 评论人数：4
- 评分人数：7
- 评分：4

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v.2

- 统计数据
  - 发布时间：2023-04-27T14:21:22.792Z
  - 原始模型：SD 1.5
  - 下载数：1389
  - 评分人数：6
  - 评分：4.33
- 下载地址
  - [widowmakerLast.safetensors](https://civitai.com/api/download/models/56570)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/eb7f4226-4be1-41ef-ced5-468b4ab68200/width=450/613483.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2612cc87-c706-4659-597a-486fc6104a00/width=450/613426.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8b5b2ef6-cf79-42da-8d22-e83a9993c900/width=450/613898.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d9ad3e1a-3af8-4465-f5fa-786f26fb3900/width=450/613054.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v.1

- 统计数据
  - 发布时间：2023-04-27T12:31:21.107Z
  - 原始模型：SD 1.5
  - 下载数：990
  - 评分人数：1
  - 评分：2
- 下载地址
  - [widowmakerOverwatchLORA_v1.safetensors](https://civitai.com/api/download/models/14168)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ce8f3ff2-7005-4f45-cc81-7473b5353700/width=450/137891.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3e5f4071-89db-4a3c-beb2-8320e9972400/width=450/137897.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/74fb8e8c-98c7-47a6-4a7d-111c3ee9b000/width=450/137896.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/65c668d1-6fcd-4254-7263-8ffa6581c000/width=450/137895.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>v.2 Update</strong>: going back to update a few of my first LORA's to be more in-line with my newer ones, starting with Widowmaker, hopefully improving accuracy and stability. Updated triggers below, everything should be flexible.</p><p>Checked strength range is 0.6-0.8.</p><p>Triggers for prompting are:</p><ul><li><p><strong>Main\Face</strong> - <em>widowmaker, ponytail, purple skin (</em>drop it for pale\beige skin<em>)</em></p></li><li><p><strong>Outfit </strong>- <em>head-mounted display, visor, bodysuit, gloves, high heels</em></p></li><li><p><strong>Talon outfit</strong> - <em>widowmaker_talon, armor, black pants, midriff, navel</em></p></li><li><p><strong>Miscellaneous</strong> - <em>cote d'azur, back\arm tattoo, pauldrons, armored boots, gauntlets, sarong</em></p></li></ul><p><strong><span style="color:rgb(193, 194, 197)">If you liked my work, you can donate</span></strong><span style="color:rgb(193, 194, 197)"> </span><a target="_blank" rel="ugc" href="https://www.buymeacoffee.com/gertan"><strong>here</strong></a><span style="color:rgb(193, 194, 197)">.</span></p><p>Review and comment with your experiences, I would appreciate it.</p><p><strong>Inpaint guide</strong>: if face on full body shots comes out deformed\not detailed enough - it's easily fixed with single inpaint, whole process takes half a minute. Press "Send to inpaint" button under generated image, mask the face area with drawing tool, choose DDIM sampler, set "Inpaint area" to "only masked", and set denoising strength to 0,5. Press generate and you done!</p><p>Review and comment with your experiences, I would appreciate whatever feedback you can provide in order to continue improving my technique.</p><p>Trained on Anything V4.5 with anime.vae.pt and CLIP Skip 2.</p><p>Samples are 512x768, without HighRes.fix, using <a target="_blank" rel="ugc" href="https://civitai.com/models/4355/orangecocoa-5050-mix"><strong>OrangeCocoa 50/50 Mix</strong></a> , with<strong> </strong><a target="_blank" rel="ugc" href="https://huggingface.co/WarriorMama777/OrangeMixs/blob/main/VAEs/orangemix.vae.pt"><strong>OrangeMix VAE</strong></a>, and using <a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative"><strong>EasyNegative</strong></a> embedding, CLIP Skip 2.</p>