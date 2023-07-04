## Steins;Gate/Huke Lora
### 一、模型概述

- 标签：`anime`, `city`, `watercolor`, `steins;gate`, `style`, `steins gate`, `video game`
- 下载数：791
- 收藏人数：131
- 评论人数：10
- 评分人数：4
- 评分：4.75

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] 1.0

- 统计数据
  - 发布时间：2023-02-10T01:41:40.209Z
  - 原始模型：SD 1.5
  - 下载数：791
  - 评分人数：4
  - 评分：4.75
- 下载地址
  - [hukemoreely.safetensors](https://civitai.com/api/download/models/4665)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ae5b6abb-b320-455b-1c96-f3e3294a2400/width=450/32844.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/74a13112-36cf-42a0-476a-f49b617e7000/width=450/32843.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c5eb00ac-334e-459a-5f5a-0d2e9b1a7600/width=450/32838.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b62be1ba-b2cd-4f56-81df-865858d4f700/width=450/32837.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>WORK IN PROGRESS, but capable of giving some pretty nice results.</p><p></p><p>IMPORTANT: LORAs work differently from normal models. To use them, install this extension, then use WITH Elysium Anime v3:</p><p></p><p><a target="_blank" rel="ugc" href="https://github.com/kohya-ss/sd-webui-additional-networks">https://github.com/kohya-ss/sd-webui-additional-networks</a></p><p>You can grab elysium anime v3 HERE:</p><p><a target="_blank" rel="ugc" href="https://huggingface.co/hesw23168/SD-Elysium-Model/tree/main">https://huggingface.co/hesw23168/SD-Elysium-Model/tree/main</a></p><p></p><p>As the name implies, this is a LoRA that draws heavily from Steins;Gate illustrator Huke's stylings. The strange, photorealistic cities, the splotchy watercolors, the near-blinding brights, it's all here. Trained with 150+ images. Use with Elysium Anime v3. The safetensors version works identically to the ckpt.</p><p></p><p>TO DO:<br />-Add a prompt frequency list</p><p>-Refine training data to prevent having to prompt wrangle</p><p>-Add daru :,( and everyone besides the main 3 I guess</p><p>-Make this description better when not tired</p><p></p><p></p><p>Training data is here, since it's been requested! Had a data loss incident shortly after training, so not everything is here yet, but I'm working on recovering stuff. Here's the main chunk of data I DO have, which are 104/109 images for the style:</p><p><a target="_blank" rel="ugc" href="https://mega.nz/folder/pHcTjKZQ#p0iagKQhr_CDm-gUWcAp4A">https://mega.nz/folder/pHcTjKZQ#p0iagKQhr_CDm-gUWcAp4A</a></p><p></p><p>LORA training for the style was 8 epochs, 5 repeats. Also used were three twenty image folders of Mayuri, Okabe and Kurisu, repeated twice each. It wasn't enough to change output too meaningfully, but I have a feeling if you experiment with more repeats on similar folders, you might get better results.</p>