## Korean Gal LoCon / LoRA - Nini
### 一、模型概述

- 标签：`character`, `girl`, `photorealistic`, `asian`, `woman`, `cute`, `portraits`
- 下载数：2689
- 收藏人数：478
- 评论人数：1
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] 1

- 统计数据
  - 发布时间：2023-03-14T08:54:17.520Z
  - 原始模型：SD 1.5
  - 下载数：2689
  - 评分人数：1
  - 评分：5
- 下载地址
  - [AG-nini.safetensors](https://civitai.com/api/download/models/22971)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/20380b66-6225-4160-4c41-d98d5ab52100/width=450/248387.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/89dc2fc6-93fb-4541-5c8a-09ef39317f00/width=450/248389.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9a53f7bd-3771-45d4-61d3-810707e20300/width=450/248388.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<h1>Intro</h1><p>I'm lazy af so I'll just copy paste the details. They are basically the same for all of my LoRA.</p><p></p><p>This is a LoCon / LoRA model of beautiful Korean girl face. Model was trained on various irl photos, however it does not depict any real person. Consider it a virtual character.</p><p>Trained on chillout. Offset noise has been applied.</p><p>-</p><h1>Settings</h1><p></p><h3>1 - Not necessary but highly recommended</h3><p>Get this extension: <a target="_blank" rel="ugc" href="https://github.com/pkuliyi2015/multidiffusion-upscaler-for-automatic1111">MultiDiffusion with Tiled VAE</a></p><p><strong>Use Tiled VAE only.</strong></p><p>Set encoder/decoder tile size to what your gpu can handle, and get faster image generation speed. This extension also allows you to upscale image to much higher resolution, beyond your gpu normally could handle. No more OOM errors!</p><p>I have 1080Ti with 11Gb VRAM, here's my setting for Upscale by 2.</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/940bc0d6-658b-480a-0791-687cd5c86400/width=525/940bc0d6-658b-480a-0791-687cd5c86400" /><p>For Upscale by 3 (which was impossible for 1080Ti to handle before), I change tile size to be smaller.</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f23ff3b6-97cd-474f-165b-c16f4b3d9100/width=525/f23ff3b6-97cd-474f-165b-c16f4b3d9100" /><h3>2 - Parameters</h3><p>base res is 512*768</p><p>Sampler: Euler a / DPM++ SDE Karras</p><p>Enable Hires. fix</p><p>upscale by 2 or higher.</p><p>Hires step: 8 / 12 / 18</p><p>Upscaler: R-ESRGAN 4x+</p><p>Denoising strength: 0.1 / 0.2 / 0.3</p><p>-</p><p>Enjoy.</p>