## Photon
### 一、模型概述

- 标签：`photorealistic`, `sexy`, `female`, `base model`, `clothes`, `woman`, `fantasy`, `girls`, `portraits`, `realistic`, `landscape`, `backgrround`
- 下载数：8287
- 收藏人数：1172
- 评论人数：31
- 评分人数：53
- 评分：4.91

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1

- 统计数据
  - 发布时间：2023-06-06T15:57:53.203Z
  - 原始模型：SD 1.5
  - 下载数：8287
  - 评分人数：53
  - 评分：4.91
- 下载地址
  - [photon_v1.safetensors](https://civitai.com/api/download/models/90072)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6d896331-6c3c-4c67-9ee8-15ab093b76d1/width=450/1044327.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4a3bf887-9e0e-482f-bb33-e42adb34ba00/width=450/1044343.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0f4a9add-1e54-4317-a1ec-c46dbb4afa4e/width=450/1044341.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8372a4b8-b81d-4f31-97a0-c86f3af2887f/width=450/1044356.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>Photon</strong> aims to generate photorealistic and visually appealing images effortlessly.</p><p>Recommendation for generating the first image with Photon:</p><ul><li><p><strong>Prompt:</strong> A simple sentence in natural language describing the image.</p></li><li><p><strong>Negative:</strong> "<em>cartoon, painting, illustration, (worst quality, low quality, normal quality:2)</em>"</p></li><li><p><strong>Sampler:</strong> DPM++ 2M Karras | Steps: 20 | CFG Scale: 6</p></li><li><p><strong>Size:</strong> 512x768 or 768x512</p></li><li><p><strong>Hires.fix:</strong> R-ESRGAN 4x+ | Steps: 10 | Denoising: 0.45 | Upscale x 2</p></li><li><p>(avoid using negative embeddings <span style="color:rgb(209, 213, 219)">unless absolutely necessary</span>)</p></li></ul><p>From this initial point, experiment by adding positive and negative tags and adjusting the settings. Most of the sample images follow this format.</p><h3 id="heading-6">Development</h3><p>The development process was somewhat chaotic but essentially:</p><ul><li><p>It started from an old mix.</p></li><li><p>LORAs were trained on various topics using AI-generated photorealistic images.</p></li><li><p>These LORAs were mixed within the model using different weights.</p></li><li><p>In the midst of this mixing, hand generation broke.</p></li><li><p>LORAs were generated and remixed in an attempt to fix hand generation (not entirely successful).</p></li></ul><p>In future versions, I will try to:</p><ul><li><p>Completely eliminate the need for a negative prompt to generate high-quality images.</p></li><li><p>Fix the hand generation issue to minimize instances of poorly drawn hands.</p></li><li><p>Explore more automated training processes. I would love to have <span style="color:rgb(209, 213, 219)">5,000 or 50,000 high-quality AI-generated photorealistic images for training purposes.</span></p></li></ul><p>I hope you enjoy using it as much as I enjoyed creating it! If you have any questions or suggestions, feel free to share. Have fun creating amazing images! 🎨</p>