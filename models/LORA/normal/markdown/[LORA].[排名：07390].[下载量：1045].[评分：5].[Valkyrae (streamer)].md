## Valkyrae (streamer)
### 一、模型概述

- 标签：`girl`, `person`, `female`, `woman`, `celebrity`, `faces`, `real person`
- 下载数：1045
- 收藏人数：112
- 评论人数：0
- 评分人数：2
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v_portrait

- 统计数据
  - 发布时间：2023-03-03T03:06:59.053Z
  - 原始模型：SD 1.5
  - 下载数：860
  - 评分人数：2
  - 评分：5
- 下载地址
  - [valkyrae_v_portrait.safetensors](https://civitai.com/api/download/models/17781)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d68b310f-370e-43a4-d13e-f51294706500/width=450/181991.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f61d4f1a-f08c-4da3-f8c0-3206a2764100/width=450/181994.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0628c3d2-739e-4268-3d7c-b6ef4f46f100/width=450/181993.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7959a62c-292e-46fe-9dbb-fefaf126b200/width=450/181992.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v_flex

- 统计数据
  - 发布时间：2023-03-03T03:06:59.053Z
  - 原始模型：SD 1.5
  - 下载数：185
  - 评分人数：0
  - 评分：0
- 下载地址
  - [valkyrae_v_flex.safetensors](https://civitai.com/api/download/models/17782)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/26b7ff6c-a3ce-4856-ebfe-f052e323ec00/width=450/181997.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7940dfe0-7c4c-4e88-4250-7bdebfe4e200/width=450/181996.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/78c22215-b48a-4bc1-2e22-f6c2b246cf00/width=450/181995.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<h3>General info</h3><p>My first attempt at creating a Lora. Recently hopped on the SD bandwagon and learning as we go along. </p><p><strong>Which version should you use?</strong></p><p>There are 2 versions. V_portrait for most consistent likeness, but v_flex if you want to try and get a shot from a bit further away. You might get a good one.</p><p><strong>Performance</strong></p><p>At specific facial angles from up close it manages to capture her likeness fairly well. Quickly breaks down from farther away or odd side/back angles. Basically if it's from far away enough that you can see below the chest, the likeness usually just isn't there (or maybe I just can't bring it out). </p><p><strong>Strength</strong></p><p>Starts convincing me at strengths 0.7 and up, but your mileage may vary. Sometimes I get a lucky roll with 0.5 strength. </p><p><strong>Side notes</strong></p><p>In a lot of the training images she was wearing a choker/necklace. Add <code>choker, necklace</code> to your negative prompt to try and mitigate this if you don't want them in your images.</p><p>She might look a bit young sometimes, because some training images are from when she was younger.</p><p>If your images don't turn out exactly like the sample images, even when copying the generation data, it might be because you're running Stable Diffusion with xformers enabled. This sacrifices reproducibility on the same seed for faster image generation. Sample images were generated with xformers disabled.</p>