## Lowdef
### 一、模型概述

- 标签：`anime`, `landscapes`, `character`, `subject`, `art`, `digital art`, `illustration`, `2d`, `artstyle`, `digital illustration`, `fantasy`, `video game`
- 下载数：374
- 收藏人数：60
- 评论人数：2
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0.1

- 统计数据
  - 发布时间：2023-03-31T17:44:49.530Z
  - 原始模型：SD 1.5
  - 下载数：300
  - 评分人数：0
  - 评分：0
- 下载地址
  - [lowdef_v101.pt](https://civitai.com/api/download/models/32634)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/65ca62e3-2e67-49d8-cd3c-bbab9ef32d00/width=450/371846.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1a435bfe-774a-4c13-e9a4-8b902dba8700/width=450/371845.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bf58796b-682b-48ef-d8ac-6aa61e159200/width=450/371844.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/79d6ac56-ee98-4f8c-fbe8-560371b86c00/width=450/371843.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0.0

- 统计数据
  - 发布时间：2023-03-31T17:44:49.530Z
  - 原始模型：SD 1.5
  - 下载数：74
  - 评分人数：0
  - 评分：0
- 下载地址
  - [lowdef_v100.pt](https://civitai.com/api/download/models/32434)
- 样例图像：

### 三、详情
<h1>Lowdef</h1><p>Lowdef is a model trained on a stylized lowpoly dataset that captures a unique low-definition style (base model <a target="_blank" rel="ugc" href="https://huggingface.co/runwayml/stable-diffusion-v1-5">SD 1.5</a>). It's not meant to be used stand-alone but with other checkpoints.</p><h2>Auto1111 Quick Start</h2><p>Instructions for use with Stable Diffusion Web UI.</p><ol><li><p>Download the model. Rename the file to <strong>lowdef.pt</strong> or alternatively, adjust your prompts to match the file name.</p></li><li><p>Place the downloaded file inside <em>stable-diffusion-webui/models/hypernetworks</em> directory. If the <em>hypernetworks</em> directory doesn't exist create it.</p></li><li><p>Add &lt;hypernet:lowdef:0.25&gt; to your prompt and adjust the blend to your liking.</p></li></ol><p><strong>Example</strong></p><p>Your Prompt &lt;hypernet:lowdef:0.25&gt;</p><h2>Best Practices</h2><p>⚠️ The model is quite aggressive and more unpredictable at higher blend values.</p><ul><li><p>Use a blend between 0.1 and 0.3.</p></li><li><p>Generate multiple images at once, minimum 4.</p></li><li><p>Use Lowdef with other artistic checkpoints.</p></li></ul>