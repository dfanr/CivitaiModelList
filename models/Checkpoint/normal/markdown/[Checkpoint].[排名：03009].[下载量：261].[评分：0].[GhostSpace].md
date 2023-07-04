## GhostSpace
### 一、模型概述

- 标签：`abstract`, `dark`, `style`
- 下载数：261
- 收藏人数：60
- 评论人数：5
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-15T03:48:26.922Z
  - 原始模型：SD 1.5
  - 下载数：261
  - 评分人数：0
  - 评分：0
- 下载地址
  - [ghostspace_v10.safetensors](https://civitai.com/api/download/models/96284?type=Model&format=SafeTensor&size=pruned&fp=fp32)
  - [ghostspace_v10.safetensors](https://civitai.com/api/download/models/96284)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0782d59c-63cc-4de3-9d47-57734d4e6fa9/width=450/1148918.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/87fcc534-ef51-4a8d-84b0-eecbf9e576ea/width=450/1148919.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b7bef441-3d74-45c8-b3f3-1b9f667d3e15/width=450/1148920.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3d6cbff8-203e-4556-a8c4-025b0636f8f6/width=450/1148921.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>GhostSpace is a model designed to convey a dark and muted style that feels like a memory. This model is experimental with heavy stylistic bias - it is not a general purpose model. Despite this, the model is quite easy to prompt (prompt examples attached on the model images).</p><p><em>Note: The example image seeds will not yield identical results in the automatic1111 webui. I use a custom noise generator that has incompatible seeds.</em></p><p><strong>Recommendations:</strong></p><ul><li><p>Configuration scale can affect the sharpness of the image. You can get very interesting images at a wide range of config scales. A scale of 13 can yield sharp edges and bold contrast, whereas a config scale of 5 might lean closer to a watercolor look.</p></li><li><p><strong>(highly recommended)</strong> Upscaling is a very important for getting a clean look. If you don't, then the model can tend to generate a heavily compressed "jpeg" look, which is generally undesirable. I personally switch between R-ESRGAN 4x+ Anime6B and ESRGAN 4x at a denoising strength of 0.5, but any upscaler works fine.</p></li><li><p>This model is designed for artistic exploration, so I'd recommend being experimental with your prompting style. Example prompts are provided attached to the example images.</p></li><li><p>If you want to avoid the watercolor look, adding "watercolor winter cloudy" to the negative prompt can help with that</p></li></ul>