## REV Mix
### 一、模型概述

- 标签：`photorealistic`, `fantasy`, `photorealism`, `portraits`, `sci fi`
- 下载数：3060
- 收藏人数：687
- 评论人数：26
- 评分人数：14
- 评分：4.71

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v1.3

- 统计数据
  - 发布时间：2023-03-24T19:15:36.760Z
  - 原始模型：SD 1.5
  - 下载数：1763
  - 评分人数：8
  - 评分：4.5
- 下载地址
  - [revMix_v13.safetensors](https://civitai.com/api/download/models/7589?type=Model&format=SafeTensor&size=full&fp=fp16)
  - [revMix_v13.ckpt](https://civitai.com/api/download/models/7589?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [revMix_v13.ckpt](https://civitai.com/api/download/models/7589?type=Pruned%20Model&format=PickleTensor&size=pruned&fp=fp16)
  - [revMix_v13.safetensors](https://civitai.com/api/download/models/7589)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f54ceac1-add6-4bdf-61bf-20acbae14000/width=450/71166.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a5dede68-3739-482e-f752-465dd8b39900/width=450/71165.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a99f1fd2-7376-4185-2239-d1595ffa9a00/width=450/71167.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b967b5d4-4d1c-40fc-6504-2ba4e30f2600/width=450/71163.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v1.2

- 统计数据
  - 发布时间：2023-03-24T19:15:36.760Z
  - 原始模型：SD 1.5
  - 下载数：387
  - 评分人数：3
  - 评分：5
- 下载地址
  - [revMix_v12.safetensors](https://civitai.com/api/download/models/6361?type=Model&format=SafeTensor&size=full&fp=fp16)
  - [revMix_v12.ckpt](https://civitai.com/api/download/models/6361?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [revMix_v12.safetensors](https://civitai.com/api/download/models/6361)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/380db0d0-71ac-4810-4a3d-12c68b893b00/width=450/56782.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/29834ac8-b285-4602-91b6-8c86f9c61000/width=450/56781.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8acc3fff-5b17-490e-d7a9-f08fcb667100/width=450/56780.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/84c03063-9661-40fe-e57c-c296febbe400/width=450/56779.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v1.0

- 统计数据
  - 发布时间：2023-03-24T19:15:36.760Z
  - 原始模型：Other
  - 下载数：910
  - 评分人数：3
  - 评分：5
- 下载地址
  - [revMix_v10.ckpt](https://civitai.com/api/download/models/6048?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [revMix_v10.safetensors](https://civitai.com/api/download/models/6048)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/49efa0f4-080c-4ebe-e23c-5d5e3984de00/width=450/52038.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3218543c-9429-46d6-dea8-ee233fe07a00/width=450/52039.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/995156ac-2893-4c2e-5eb2-76ce40cb7300/width=450/52037.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9bb21560-2cbc-4fc1-f8f3-c2a280927300/width=450/52036.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3><u>Update 2:</u></h3><p>ReV_3 released. Read model version description for more info</p><p></p><h3><u>Update</u></h3><p>ReV_2 released. Read model version description for more info<br /><br /><u>Intro</u></p><p><br />This model is mainly intended for <strong>Portraits</strong> and <strong>Full Body (Depth of Field) </strong>like semi-photorealistic pictures. This <em>can </em>do landscape however, not well. I like this model, jack of all trades, master of none. <strong><u>No restrictions on use of this model, just credit to me and other model creators used in this merge.</u></strong></p><p></p><h3><u>Workflow</u></h3><p>minimal workflow logic based on Protogen's: <a target="_blank" rel="ugc" href="https://www.reddit.com/r/StableDiffusion/comments/1079c0d/protogen_checkpoint_merging_data_reference/"><u>Reddit</u></a></p><p>(Mainly used Difference sum from SD1.5-pruned as tertiary model)<br /></p><h3><br /><u>Recommends</u></h3><p>Resolution:</p><ul><li><p><strong>2:3</strong> ratio (i.e 512x768)</p></li><li><p><strong>1:1</strong> ratio (i.e 512x512 or 576x576)</p></li></ul><p></p><p>Best Samplers:</p><ul><li><p><strong>Euler a <em>(Recommended)</em></strong></p></li><li><p><strong>DPM++ 2M Karras</strong></p></li><li><p><strong>DPM++ SDE Karras</strong></p></li><li><p><strong>PLMS</strong></p></li></ul><p></p><p>CFG scale:</p><ul><li><p><strong>Portraits</strong>: 7-9</p></li><li><p><strong>Landscape</strong>: 9-12</p></li></ul><p></p><p>Steps:</p><ul><li><p><strong>Portraits</strong>: 30-40</p></li><li><p><strong>Landscape</strong>: 40-100</p></li></ul><p></p><p><strong>Hires.fix: </strong></p><ul><li><p><strong>Upscaler:</strong> ESRGAN_4x or ESRGAN_4x+</p></li><li><p><strong>Upscale by: </strong>1.5-2</p></li><li><p><strong>Denoising </strong>strength: 0.3-0.5 (0.3 used in samples)</p></li><li><p><strong>Clip</strong>: 1</p></li></ul><p></p><p></p><p>For best results use the: <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/tree/main"><u>Standard SD VAE</u></a></p><p></p><p><a target="_blank" rel="ugc" href="https://drive.google.com/file/d/1kJsQ4GSoPDfuworuajvTo4xIS-GJUkkX/view">bad-image-prompt-v2</a></p><p></p><p>SFW: put 'NSFW' and 'uncensored' in negative prompt, SFW in regular prompt</p><p>NSFW: put 'SFW' and 'censored' in negative prompt, NSFW in regular prompt<br /></p><p>Less negative prompts the better</p><h3><br /><u>License</u></h3><p><a target="_blank" rel="ugc" href="https://huggingface.co/spaces/CompVis/stable-diffusion-license"><u>creativeml-openrail-m</u></a></p>