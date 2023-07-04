## Milky-Chicken
### 一、模型概述

- 标签：`character`, `3d`, `digital art`, `portrait`, `woman`, `illustration`, `fantasy`, `man`, `realistic`, `landscape`, `2.5d`
- 下载数：878
- 收藏人数：151
- 评论人数：3
- 评分人数：5
- 评分：4.6

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.1

- 统计数据
  - 发布时间：2023-06-25T07:20:14.708Z
  - 原始模型：SD 1.5
  - 下载数：655
  - 评分人数：4
  - 评分：4.5
- 下载地址
  - [milkyChicken_v11.safetensors](https://civitai.com/api/download/models/103542)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/48fc767b-9577-4bf1-b3e6-223e11a5e93a/width=450/1280939.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/356e4c51-ba89-4c52-bd20-9ce9f60124b5/width=450/1280942.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8d4d4c90-3fae-4f3b-bf21-dd8e568e7b48/width=450/1280953.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7c46215c-b61c-417e-ac8d-674cc1abd0ee/width=450/1280950.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-06-25T07:13:14.290Z
  - 原始模型：SD 1.5
  - 下载数：223
  - 评分人数：1
  - 评分：5
- 下载地址
  - [milkyChicken_v10.safetensors](https://civitai.com/api/download/models/97714)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fcbe265f-59e7-4e21-b510-d7aeeec65d8b/width=450/1175115.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7d742bb9-02ec-4a5a-8db5-bfbf028c891c/width=450/1175098.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1f158c1d-4ad0-4c56-b77b-8bc8f23ab0a4/width=450/1175102.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/65848715-0da3-429f-80b7-f71887df6b5c/width=450/1175099.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-2494">MilkyChicken Mix</h1><p>This model is an attempt at introducing simple stylistic elements from my favourite models without losing the flexibility of robust prompting when desirable.</p><p></p><p>For testing purposes, the demonstration images are not cherry-picked. Instead, they use<em> fairly</em> light prompting and are generate<s>d from a </s><strong><s>static seed</s></strong><em> (v1.0 only).</em> While this undoubtably hindered the potential outputs, it provided a surprisingly decent baseline for this initial comparison.</p><p></p><p>I am interested to see how it performs for you =]</p><p></p><p><strong>Suggested settings:</strong></p><ul><li><p>CLIP Skip: 2</p></li><li><p>Size: 512x512, 512x768, 512x900, 768x512</p></li><li><p>ENSD: 31337</p></li><li><p>Highres fix: ESRGAN 4x or Latent (nearest) w/ denoise @ 0.55</p></li><li><p>Sampler: DPM++ 2M SDE</p></li><li><p>Steps: 20</p></li><li><p>CFG: 8</p></li><li><p>VAE: vae-ft-mse-840000-ema-pruned</p></li></ul><p></p><p><strong>Prompt:</strong></p><p>(masterpiece), (best quality), (detailed), (realistic), 8k,</p><p><strong>Neg:</strong></p><p>(worst quality), (low quality)</p><p></p><p><strong>Tips:</strong></p><ul><li><p><em>For better quality, try using more/less weight, i.e. (best quality:1.3), etc...</em></p></li><li><p><em>For complex scenes, try using more steps in sampler, 25-50.</em></p></li><li><p>Textual embeddings may improve output quality, such as BadDream, easynegative, etc...</p></li><li><p>For better lighting, try describing it, i.e. (dramatic lighting), (sunshine), etc...</p></li></ul>