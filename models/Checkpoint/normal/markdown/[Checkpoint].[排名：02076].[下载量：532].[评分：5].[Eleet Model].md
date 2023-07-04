## Eleet Model
### 一、模型概述

- 标签：`anime`, `character`, `2d`
- 下载数：532
- 收藏人数：132
- 评论人数：7
- 评分人数：1
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.1

- 统计数据
  - 发布时间：2023-06-10T16:24:35.495Z
  - 原始模型：SD 1.5
  - 下载数：363
  - 评分人数：1
  - 评分：5
- 下载地址
  - [eleetModel_v11.safetensors](https://civitai.com/api/download/models/93131)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0c3140d1-b6e8-402e-a79a-806160f6f65f/width=450/1098029.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7fec08a2-1097-43e9-b5c7-b74c29ece06a/width=450/1098032.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/31856a75-4c2b-44f2-974d-7603c38fa5b3/width=450/1098042.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b5b133ac-d59f-4f1f-93dd-2ea045ab07d6/width=450/1098036.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-06-10T15:36:36.280Z
  - 原始模型：SD 1.5
  - 下载数：169
  - 评分人数：0
  - 评分：0
- 下载地址
  - [eleetModel_v10.safetensors](https://civitai.com/api/download/models/82565)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fb813560-0c58-42a2-8696-84a9099dd141/width=450/954709.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ab6f996f-09bf-4c00-bf03-9643f1125d3d/width=450/929600.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dd7dde4e-71d1-45e1-8270-cf4f71e5cc12/width=450/953976.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/94528fd2-0f3d-4865-9c7e-e46d3aeda526/width=450/929599.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><span style="color:rgb(212, 212, 212)">Eleet model is a block-weighted merged stable diffusion model aiming at generating good quality 2D anime style images that satisfy my personal taste and, hopefully, your taste.</span></p><p></p><p>The model name ELEET commemorates the wide use of its numerical spelling (31337) to set the Eta Noise Seed Delta (ENSD) parameter when using stable diffusion models.</p><p></p><p><strong><span style="color:rgb(86, 156, 214)">About samples</span></strong></p><p>The model is tested on anime girls and scenery outputs. Most samples are all made of pure txt2img or txt2img+highres fix, while one or two may be done with the help of the CFG fix extension (<a target="_blank" rel="ugc" href="https://github.com/mcmonkeyprojects/sd-dynamic-thresholding">https://github.com/mcmonkeyprojects/sd-dynamic-thresholding</a>). No controlnet are used for generating the samples. No any LoRA or embeddings. No any regional control extensions.</p><p></p><p>Due to my GPU limitation, I couldn't generate ultra-high resolution images and I didn't use Highres Fix very often. Therefore, none of my sample images of this model are of high resolution (at most ~1000 pixels on the long side). But these images are still able to show the model style and basic prompt use cases, so it's probably enough… I guess?</p><p></p><p><strong><span style="color:rgb(86, 156, 214)">Suggested settings</span></strong></p><p><span style="color:rgb(212, 212, 212)">For users who know little about stable diffusion settings, I recommend:</span></p><ul><li><p><strong><span style="color:rgb(86, 156, 214)">Prompt</span></strong><span style="color:rgb(212, 212, 212)">: Start with </span><code>masterpiece, best quality</code><span style="color:rgb(212, 212, 212)">. Personally I also like to add:</span></p><ul><li><p><span style="color:rgb(212, 212, 212)">  </span><code>high-resolution</code><span style="color:rgb(212, 212, 212)"> or </span><code>aesthetic</code></p></li><li><p><span style="color:rgb(212, 212, 212)">  Photography phrases such as </span><code>cinematic lighting</code><span style="color:rgb(212, 212, 212)">, </span><code>sharp focus</code><span style="color:rgb(212, 212, 212)">, etc.</span></p></li></ul></li><li><p><strong><span style="color:rgb(86, 156, 214)">Negative prompt</span></strong><span style="color:rgb(212, 212, 212)">:</span></p></li></ul><pre><code>(worst quality, low quality:1.4), lowres, bad anatomy, ((blurry, depth of field, bokeh)), (text, logo, watermark, signature, username)</code></pre><ul><li><p><strong><span style="color:rgb(86, 156, 214)">Sampler</span></strong><span style="color:rgb(212, 212, 212)">: DPM++ 2M Karras, or DPM++ 2M SDE Karras if your WebUI version &gt;= 1.3. Sometimes I feel SDE samplers are overcooking images, so I personally still prefer DPM++ 2M Karras.</span></p></li><li><p><span style="color:rgb(212, 212, 212)">CFG Scale: 7~12</span></p></li><li><p><span style="color:rgb(212, 212, 212)">Steps: 16~25</span></p></li><li><p><strong><span style="color:rgb(86, 156, 214)">Clip skip</span></strong><span style="color:rgb(212, 212, 212)">: 2</span></p></li><li><p><span style="color:rgb(212, 212, 212)">No external VAE file required</span></p></li></ul><p></p><p><strong><span style="color:rgb(86, 156, 214)">Change logs</span></strong></p><ul><li><p>2023/06/10: Update v1.1.</p></li><li><p>2023/05/29: (1) Update sample images using the latest WebUI version (v1.3) and its new <span style="color:rgb(212, 212, 212)">DPM++ 2M SDE Karras sampler; (2) Replace the previous model cover image with a portrait one, as the site doesn't seem to be friendly for displaying landscape cover images.</span></p></li></ul>