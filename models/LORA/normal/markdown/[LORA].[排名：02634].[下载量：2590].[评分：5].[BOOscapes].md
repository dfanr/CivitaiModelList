## BOOscapes
### 一、模型概述

- 标签：`landscapes`, `colorful`, `forest`, `desert`, `mountains`, `flowers`, `background`, `cloud`, `noise offset`, `landscape`, `sky`, `garden`, `meadow`, `waves`
- 下载数：2590
- 收藏人数：482
- 评论人数：0
- 评分人数：5
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-08T05:00:37.527Z
  - 原始模型：SD 1.5
  - 下载数：2590
  - 评分人数：5
  - 评分：5
- 下载地址
  - [booscapes.safetensors](https://civitai.com/api/download/models/65374)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9fefd979-9d6b-47d6-90fc-b88197558ee0/width=450/723566.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/84301c39-456c-4beb-903b-b9a41b3d9913/width=450/723567.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/329d28a8-4c4c-4a96-88fc-95f01a0fe900/width=450/1187543.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/09fe5770-2800-47f9-90d2-c4ff26fb1ced/width=450/1187541.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Add some wonder to your generations. Trained on photos of large landscapes, garden photos, photos of wildflowers. Trained on tall portrait to wide landscape images. Consider 768x786 box and tall/short resolutions in that range (448x768, 768x448).</p><p></p><p>Considerations:</p><ul><li><p>The colors are intense and sometimes the weights cause it to be unstable with some generations. Lower the weight of the LoRA to 0.75 or lower the UNet specifically can help. </p></li></ul><ul><li><p>Going too large can cause some latent space overlap with the resolution of the model creating irregularities in the composition. Keep it closer to the trained size of the original model, up to 768x768, for best results. Has worked great at high resolution for me.</p></li></ul>