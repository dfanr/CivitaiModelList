## Myne Factory - Base
### 一、模型概述

- 标签：`anime`, `landscapes`, `style`, `portraits`
- 下载数：369
- 收藏人数：117
- 评论人数：1
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-02-15T13:12:56.643Z
  - 原始模型：Other
  - 下载数：369
  - 评分人数：2
  - 评分：5
- 下载地址
  - [myneFactoryBase_v10.ckpt](https://civitai.com/api/download/models/10764?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [myneFactoryBase_v10.safetensors](https://civitai.com/api/download/models/10764)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6255b0af-dfb9-48f2-dc04-34d9700cc100/width=450/104184.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a3ef29d0-14ea-44a9-74fe-00e1a2a31c00/width=450/104280.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/00c5d285-2f46-4e15-620b-0f21f2ac7400/width=450/104194.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9bb3fd5e-5461-45a8-849e-7e4f001d0200/width=450/104183.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<img src="http://logo.mynefactory.ai/" alt="http://logo.mynefactory.ai/" /><h1>Myne Factory Base Model</h1><p>The foundation of our models</p><p></p><h3><strong>Technical Details</strong></h3><p><strong>Model Training</strong></p><p>MyneFactoryBase was trained using ~18000 high scored samples from <a target="_blank" rel="ugc" href="http://Yande.re">Yande.re</a> and ~5000 high scored samples from Konachan. File captions were generated using 3 iterations of WD1.4 tagger to ensure maximum identification of objects within the training data. A second captioning run was done using one tagger with a reduced threshold to produce shorter captions for later use. Adam optimizer was used with a manually set maximum learning rate and cosine decay. Training was done on an RTX 4090 with a batch size of 4, utilizing DDIM sample scheduler and DDPM noise scheduler with mix precision.</p><p><strong>Text Encoder Training</strong></p><p>Text Encoder was trained for 50% of the training durations, freezing and unfreezing every 10ep. During the final 20ep of finetuning, the TE was frozen.</p><p><strong>Block Merge</strong></p><p>At the ep20 milestone, a block merge was done with BasilMix. However, it was evident that the merged weights were being trained out quickly, and the weights had entirely shifted back to the training data by the end of the training. Ultimately, the decision was made to not use a block merge for the final release.</p><p>For more detailed technical information on the training process and model architecture, please refer to <a target="_blank" rel="ugc" href="https://docs.google.com/document/d/1smqGRy3Y2ADGWAXMLs9LoYmw9-_7M9f1bzlbux-O56w">this document</a>.</p><p><strong>Authors: </strong>金Goldkoron, tsmkirby, Juusoz</p><p>Visit our <a target="_blank" rel="ugc" href="https://discord.gg/GdJBzaTSCF">Discord</a> community if you have any questions.</p><p></p><h2><strong>Prompt Format</strong></h2><p>It is recommended to use booru styled tags to for the prompts.</p><p><strong>Example:</strong> <code>woman, decorated horns, long robes, fog, long curly hair, freckles, solo, masterpiece, reflective, depth of field, caustics, detailed night, forest, leaves, moonlight, eyes, orange hair, green eyes, vines</code></p><p><strong>Example:</strong> <code>1girl, solo, skirt, book, glasses, long hair, looking at viewer, bookshelf, jacket, plaid skirt, school uniform, long sleeves, parted lips, semi-rimless eyewear, bangs, blush, holding, blazer, indoors, sweater, under-rim eyewear, red-framed eyewear, holding book, brown eyes, library, sitting</code></p><p>The tags were generated with <a target="_blank" rel="ugc" href="https://github.com/toriato/stable-diffusion-webui-wd14-tagger">WD14 tagger</a> for the dataset.</p><p>The model has also been fine tuned to be better at handling shorter prompts.</p><p></p><h2><strong>Recommended Settings</strong></h2><p>This model performs best with the following settings:</p><ul><li><p><strong>Image Size</strong></p><p><strong>1024x576</strong> for wide 16:9, <strong>768x768</strong> for square, and <strong>640x1024</strong> for portrait</p><p><em>Feel free to experiment with higher resolutions, Juusoz made all the examples at higher than recommended resolutions</em></p></li><li><p><strong>Vae</strong></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt">vae-ft-mse-840000-ema-pruned.ckpt</a></p></li><li><p><strong>Sampler</strong></p><p><strong>DPM++ SDE Karras</strong> (preferred)</p><p><strong>2S Karras</strong></p><p><em>Karras samplers tend to create more dynamic and interesting generations</em></p><p><strong>Euler A</strong></p><p><em>Results tends to look smoother and more Airbrushed</em></p></li><li><p><strong>Steps</strong></p><p><strong>30</strong> minimum and <strong>+70</strong> can give nice results</p></li><li><p><strong>Skip Clip:</strong></p><p><strong>Clip 1</strong></p><p><em>Clip 2 and 4 are valid for experimentation and we recommend trying it for more variation.</em></p></li><li><p><strong>CFG</strong></p><p><strong>9-12</strong></p></li><li><p>Not required, but these tags improve the quality of the image:</p><p><strong>Prompt:</strong> <code>best quality, masterpiece</code></p><p><strong>Negative Prompt:</strong> <code>lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry</code></p></li></ul><p></p><h2><strong>Socials</strong></h2><p><a target="_blank" rel="ugc" href="https://mynefactory.ai">Website</a> | <a target="_blank" rel="ugc" href="https://discord.gg/GdJBzaTSCF">Discord</a> | <a target="_blank" rel="ugc" href="https://www.patreon.com/user?u=36154428">Patreon</a></p>