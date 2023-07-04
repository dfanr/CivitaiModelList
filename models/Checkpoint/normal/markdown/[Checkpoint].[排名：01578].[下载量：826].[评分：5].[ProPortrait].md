## ProPortrait
### 一、模型概述

- 标签：`character`, `photorealistic`, `portrait`, `girls`, `photography`, `realistic`
- 下载数：826
- 收藏人数：194
- 评论人数：2
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-21T14:35:30.574Z
  - 原始模型：SD 1.5
  - 下载数：826
  - 评分人数：2
  - 评分：5
- 下载地址
  - [proportrait_v10.safetensors](https://civitai.com/api/download/models/76852?type=Model&format=SafeTensor&size=full&fp=fp32)
  - [proportrait_v10.safetensors](https://civitai.com/api/download/models/76852)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c482e7e9-36ee-424d-9e61-097006e7a2ff/width=450/861261.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/07a97d1a-149c-4649-b908-13f95d4317ba/width=450/862078.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7ae37f3d-b058-44b2-a044-8a7c87e2e6d6/width=450/861347.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e3a6e21c-7c21-4131-9196-1dcf8fd2ee4e/width=450/861635.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3>Built with the concept “Prompt less, Post more”</h3><p>Just only short prompt and you will get a realistic portrait photo. Let you focus on posting on social media, building engagement, and doing other things that are important to you.</p><p></p><p><strong>*** This Model needs VAE !!! ***</strong></p><p></p><h3>Overview:</h3><ul><li><p>The purpose of this model is to generate a portrait photo.</p></li><li><p>These models require a VAE. You can try mse-840000-ema or anything. I have a photo of the comparison in the Comparison section (below)</p><ul><li><p>If you got bugs, adding '--no-half-vae' to the argument will solve it.</p></li></ul></li></ul><p></p><h3>Recommends:</h3><ul><li><p><strong>Prompt:</strong></p><p>Try to <strong>start with</strong><code>(skindentation:1.2), (realistic:1.1), best quality, photorealistic,</code> + your prompt (eg. 1 girl, wearing a white shirt)</p><p><strong>Negative:</strong> <code>lowres, normal quality, ((monochrome)), ((grayscale)), BadHand v4</code></p></li><li><p><strong>Steps:</strong> I recommend 30-45 (You can use higher, but many times do not have a big difference)</p></li><li><p><strong>Sampling Methods:</strong> You can see the comparison in the Comparison section (below).</p></li><li><p><strong>Sizes:</strong></p><p><strong>Medium shot:</strong> 512x512, 512x768, 512x904</p><p><strong>Long shot (full body):</strong> 768x1152, 768x1356</p><p><em>Can be used both vertically and horizontally</em></p></li><li><p><strong>Hires. fix:</strong> Use Denoising strength less than 0.6 (but you can try &gt;= 0.7, sometimes you will get problems with the hands)</p></li></ul><p></p><h3>Comparison:</h3><p><strong># VAE</strong></p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a413c594-0262-4f2a-acdc-afc9f28d5884/width=525/a413c594-0262-4f2a-acdc-afc9f28d5884.jpeg" /><p><a target="_blank" rel="ugc" href="https://github.com/Jirayu-ninl/SD-IceJi-ProPortrait/blob/main/vae-xyz_grid-0000-3322330494.png?raw=true">full-size image</a></p><p></p><p><strong># Steps</strong></p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/14a700c7-a4a8-494f-b801-861d230aae66/width=525/14a700c7-a4a8-494f-b801-861d230aae66.jpeg" /><p><a target="_blank" rel="ugc" href="https://github.com/Jirayu-ninl/SD-IceJi-ProPortrait/blob/main/steps-xyz_grid-0000-349146491.png?raw=true">full-size image</a></p><p></p><p><strong># Sampling Methods (with steps 45)</strong></p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5b4f40e4-f6c1-4637-bac3-24a5a4655a27/width=525/5b4f40e4-f6c1-4637-bac3-24a5a4655a27.jpeg" /><p><a target="_blank" rel="ugc" href="https://github.com/Jirayu-ninl/SD-IceJi-ProPortrait/blob/main/samplers-xyz_grid-0000-349146491-min.png?raw=true">full-size image</a></p><p></p><h3>Ingredients:</h3><ul><li><p>ProFantasy II C-Base Model (<a target="_blank" rel="ugc" href="https://civitai.com/models/52298">ProFantasy</a>)</p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/25494/">BRA</a></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/9052">LOFI</a></p></li><li><p>Portrait Photo Training Checkpoint (by <a target="_blank" rel="ugc" href="https://civitai.com/user/DimensionsAI">DimensionsAI</a>)</p></li></ul><p>(Merge with U-Net weight-block technique)</p><p></p><h3>Disclaimers:</h3><ul><li><p><strong>Do not sell:</strong> on any website.</p></li><li><p><strong>Credit:</strong> If you use my model in your own merges</p></li><li><p><strong>Not authorized:</strong> to be used on <strong>generative services</strong> (without my permission)</p></li></ul>