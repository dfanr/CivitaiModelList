## BohoTI
### 一、模型概述

- 标签：`style`, `illustration`, `photorealism`, `boho`
- 下载数：599
- 收藏人数：108
- 评论人数：2
- 评分人数：2
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] 7.5

- 统计数据
  - 发布时间：2023-05-09T16:31:08.149Z
  - 原始模型：SD 1.5
  - 下载数：350
  - 评分人数：1
  - 评分：5
- 下载地址
  - [kcboho07-5000.pt](https://civitai.com/api/download/models/66429)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ffa9a4e7-a629-47a7-a7a4-17745fd7a5e3/width=450/737246.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/37ad4629-9af1-4642-993c-35926cc63cce/width=450/737257.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/82272092-07e1-4153-a8a3-9bc5e967c102/width=450/737262.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0a4b91bd-719b-45bd-8043-00d0628f71ee/width=450/737276.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v7.4

- 统计数据
  - 发布时间：2023-05-09T16:21:31.584Z
  - 原始模型：SD 1.5
  - 下载数：74
  - 评分人数：0
  - 评分：0
- 下载地址
  - [kcboho07-4000.pt](https://civitai.com/api/download/models/66377)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0cfb5a34-b040-4787-b16d-81854be2b084/width=450/736281.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ab99f57b-7499-46d0-85f6-588af17669bd/width=450/736279.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a35bfd00-d685-47cc-b8a5-11c1fafd4c10/width=450/736278.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/299b9795-2178-40f4-9b28-7398b1f19f38/width=450/736276.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v7.0

- 统计数据
  - 发布时间：2023-05-09T16:21:31.584Z
  - 原始模型：SD 1.5
  - 下载数：175
  - 评分人数：1
  - 评分：5
- 下载地址
  - [kcboho07-3000.pt](https://civitai.com/api/download/models/65711)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/06bc5e3b-4be4-48c3-b2bf-a416a14d9a59/width=450/727831.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2bda0794-9c3c-4e8b-8b1c-b5fec7b84ecb/width=450/727843.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/852feb5f-410b-470e-933f-e4d9e5f59c9a/width=450/727855.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/27c1322f-7c94-4c66-b8ca-a5d9ac1a03d3/width=450/727859.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is an experiment to see if I can make a TI embedding that gets the flavour of konyconi’s BohoAI LORA.</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/51966/bohoai">https://civitai.com/models/51966/bohoai</a></p><p>Thank you to @konyconi for sharing his dataset for the excellent BohoAI LORA.</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/52697/tutorial-konyconi-style-lora">https://civitai.com/models/52697/tutorial-konyconi-style-lora</a></p><p>The showcase uses 2 models:</p><p>revAnimated_v122.safetensors [4199bcdd14] with clip skip = 2</p><p>avalonTruvision_v2.safetensors [a4df55d292] with clip skip = 1</p><p>This TI can produce some decent Boho pix but it gets confused sometimes... eg asking for a spaceship and getting a truck. Perhaps for this sort of TI you need to use a lot more pictures in the training dataset, with more subject variation?</p><p>---------------------------</p><p>Update 09 May 2023</p><p>Continued the training to step 4000, and then 5000.</p><p>kcboho07-4000 produces a stronger Boho style.</p><p>kcboho07-5000 is stronger again but has increased duplication/repetition. e.g. more fingers, more hands, duplicate cities floating in the sky.</p><p>Tried 6000 steps but it’s even worse - overcooked.</p><p>I’ve uploaded the 4000 step version as, probably, the best result for this experiment.</p><p>Also uploaded the 5000 step version since it can produce nice results with careful object prompts.</p><p>---------------------------</p><p>I’ve been struggling to work out how to make a style TI...</p><p>what makes a good training dataset?</p><p>what training settings should I use in automatic1111?</p><p>how long to cook the TI for?</p><p>For my training dataset I copied konyconi’s 76 1024x1024 images to a new folder without the associated TXT files, and reduced them all to 512x512. Then I renamed them “01 aeroplane.png”, “02 city.png”, “03 tank.png” etc.</p><p>Why? Because I was trying to match what I’ve done in the past for TIs that ended up usable. The reduced images dataset folder is what I used in the settings below.</p><p>The wikipage for automatic1111 Textual Inversion is here:</p><p><a target="_blank" rel="ugc" href="https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Textual-Inversion">https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Textual-Inversion</a></p><p>but way out of date. Last rev Jan 5, I’m writing this May 8.</p><p>I found this thread useful in parts. It’s a long read!</p><p><a target="_blank" rel="ugc" href="https://github.com/AUTOMATIC1111/stable-diffusion-webui/discussions/1528">https://github.com/AUTOMATIC1111/stable-diffusion-webui/discussions/1528</a></p><p>Training model: v1-5-pruned.ckpt [e1441589a6]</p><p>I used this because I don’t know any better, and it’s been useful in the past. Should I be using a different model for training, or is the base SD15 the best thing to use? No idea.</p><p>Create embedding:</p><p>name: kcboho07</p><p>initialization text: boho style photo</p><p>number of vectors per token: 4</p><p>Train embedding:</p><p>Embedding name: kcboho07</p><p>Embedding Learning Rate: 0.001:250, 0.0005:500, 0.00075:1000, 0.001</p><p>Gradient Clipping: disabled</p><p>Batch size: 1</p><p>Dataset directory: wherever you’ve put it on your computer</p><p>Log directory: textual_inversion</p><p>Prompt template: minimum_style_2.txt</p><p>The template has 3 lines:</p><p>&lt;&lt;&lt;</p><p>[name] style, [filewords]</p><p>[name] style, a photo of [filewords]</p><p>[name] style, an illustration of [filewords]</p><p>&gt;&gt;&gt;</p><p>Width = Height = 512</p><p>Do not resize images: OFF</p><p>Max steps: 3000</p><p>Save image steps: 25</p><p>Save embedding steps: 25</p><p>Use PNG alpha channel: OFF</p><p>Save images with embedding in PNG chunks: ON</p><p>Read parameters from txt2img tab: OFF</p><p>Shuffle tags: OFF</p><p>Drop out tags: 0</p><p>Latent sampling method: deterministic</p><p>Training time: about 50mins per 1000 steps on a 2060/6GB.</p><p>The TI at 3000 steps does produce a Boho style, although I think it’s a bit hit-and-miss compared to the BohoAI LORA.</p><p>If anyone has suggestions about what I should be doing differently please add a comment. Or if I’m doing anything obviously stupid! :-)</p>