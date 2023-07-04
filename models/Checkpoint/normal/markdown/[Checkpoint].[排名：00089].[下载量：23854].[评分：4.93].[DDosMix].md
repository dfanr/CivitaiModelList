## DDosMix
### 一、模型概述

- 标签：`girl`, `person`, `female`, `realism`, `mix`, `model`, `woman`, `girls`, `photography`, `photorealism`, `portraits`, `realistic`, `real person`, `semi-realistic`
- 下载数：23854
- 收藏人数：5192
- 评论人数：25
- 评分人数：42
- 评分：4.93

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] DDosMix_v2

- 统计数据
  - 发布时间：2023-03-24T09:19:51.645Z
  - 原始模型：SD 1.5
  - 下载数：22181
  - 评分人数：36
  - 评分：4.94
- 下载地址
  - [ddosmix_V2.safetensors](https://civitai.com/api/download/models/12183)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/71398988-0c9a-4e01-6eb7-5654d7cf6f00/width=450/132965.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2064fde9-33d7-45a3-48a0-abcd8258ab00/width=450/138118.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cf2f55d1-e0fe-488e-99bf-2151bb958600/width=450/138117.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6d07e306-f1be-4909-bdbb-f3d0a1a06300/width=450/138136.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1

- 统计数据
  - 发布时间：2023-03-24T09:19:51.645Z
  - 原始模型：SD 1.5
  - 下载数：1673
  - 评分人数：6
  - 评分：4.83
- 下载地址
  - [ddosmix_v1.safetensors](https://civitai.com/api/download/models/9950)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d57c66c0-0cdf-4a1d-81d0-8ed671d05400/width=450/96940.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cbed005c-9e79-41b2-f058-4fbbbc8f8800/width=450/96941.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b7a872a4-b646-4ef5-b1d0-42e59717c500/width=450/96939.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f9737b9f-4444-4992-cf5e-3135ca840200/width=450/96938.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>v2: 2023-02-20 I erased the roughly made picture and put in the painstakingly made picture.</p><p>Do img2img SD upscaling.</p><p>img2img SD upscale method: scale 20-25, denoising 0.2-0.3 After selecting SD Upscale at the bottom, tile overlap 64, scale factor2</p><p>caution! Sampler must be DPM++SDE karras.</p><p></p><p>If you want to make it more realistic, use DPM++ SDE Karras. If you want a clean face, use eluer a.</p><p>Have fun using it.</p><p>I used vae kl f8 anime for the example meme, but I recommend using 840000.</p><p>clip skip 2</p><p><a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt">https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt</a>

<a target="_blank" rel="ugc" href="https://huggingface.co/AIARTCHAN/aichan_blend/tree/main/vae">https://huggingface.co/AIARTCHAN/aichan_blend/tree/main/vae</a>

Apply VAE.

You will get better color results.</p><pre><code></code></pre><p><br /></p><p></p><p>v1: I don't like the model with too many prompts and forcing you to use LoRa.</p><p>So it was created.</p><p></p><p>Let's extract high-quality images with 6-word prompts!</p><p></p><p>Check the sampler, scale and step in the example image.</p><p>Looking at the example image, there is a repeating prompt.</p><p></p><p>VAE: vae-ft-mse-840000-ema-pruned</p><p></p><p>Skip Clips: 2</p><p></p><p>It was a very simple test, so I think there will be many better results.</p><p>I didn't even do upscale testing.</p><p></p><p>Have fun while testing!</p><p>!There is one downside. It's fine for dark eyes, but for other eye colors, the pupils often collapse without upscaling.</p><pre><code></code></pre><p><br /></p>