## <MAGIFACTORY> t-shirt diffusion
### 一、模型概述

- 标签：`t-shirt`, `logo`
- 下载数：3633
- 收藏人数：1085
- 评论人数：73
- 评分人数：15
- 评分：4.67

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] MAGIFACTORY t-shirt model - 1.1

- 统计数据
  - 发布时间：2023-02-25T17:31:04.039Z
  - 原始模型：Other
  - 下载数：2858
  - 评分人数：7
  - 评分：5
- 下载地址
  - [MAGIFACTORYTShirt_magifactoryTShirtModel.safetensors](https://civitai.com/api/download/models/7554)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6e047362-192e-4609-c694-786e07880e00/width=450/70770.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/28f8f100-23e7-452e-3597-900363cf7900/width=450/70768.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3f654919-d567-4c90-4d55-45b44b2ae700/width=450/70772.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/75d8ab18-bf90-4bfd-101b-2379e0a9b600/width=450/70771.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] MAGIFACTORY t-shirt model

- 统计数据
  - 发布时间：2023-02-25T17:31:04.039Z
  - 原始模型：Other
  - 下载数：775
  - 评分人数：8
  - 评分：4.38
- 下载地址
  - [MAGIFACTORYTShirt_magifactoryTShirt.ckpt](https://civitai.com/api/download/models/5365?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [MAGIFACTORYTShirt_magifactoryTShirt.safetensors](https://civitai.com/api/download/models/5365)
  - [MAGIFACTORYTShirt_magifactoryTShirt_trainingData.zip](https://civitai.com/api/download/models/5365?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/89a2dba5-b8a7-497a-4e01-6c749398c800/width=450/42014.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9e68f3c5-3a0a-427f-9225-95f94742ed00/width=450/42018.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/90fee73d-94e6-4569-5b45-faf778a6b500/width=450/42022.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/88402ea1-bfab-4ce8-4255-755413889b00/width=450/42028.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>new test model v 1.1 - try it, it is mainly for testing purposes. Let me know in the comments what you think, I can tune it more in case of problems</p><p></p><p><a target="_blank" rel="ugc" href="https://www.magifactory.com"><strong><u>MAGIFACTORY</u></strong></a> model is trained to generate t-shirt logos based on text input. The model takes in a text description of the desired t-shirt logo and generates a corresponding image. It is trained on a dataset of t-shirt logos with resolution 512x512px. Ideally use hires-fix rescale to 896x896 ( for not having repeated artifacts ) in automatic1111 WebUI with "Latents antialiased" and finally upscale 4x with SwinIR_4x. <code>Euler a</code> scheduler preferred. You can also try <code>DPM++ 2S a Karras</code> scheduler. I am running <a target="_blank" rel="ugc" href="https://www.instagram.com/magifactory">Instagram</a> with top designs, so you can download and use them.</p><h3>prompts:</h3><pre><code>cyberpunk astronaut flying in space (on a black background:1.4) as a t-shirt logo in the style of &lt;MAGIFACTORY&gt; art</code></pre><pre><code>a symbol of a car (on a black background:1.2) as t-shirt logo in the style of &lt;MAGIFACTORY&gt; art</code></pre><h3>negative prompt:</h3><pre><code>badly drawn, noisy, noise, blurred, ugly, cropped, out of frame, (double:1.4), (repeated:1.4), (repeating:1.4), signature, text, font, watermark</code></pre>