## KPC-R Mix
### 一、模型概述

- 标签：`anime`, `portrait`, `style`, `woman`, `girls`, `realistic`, `style art`, `painting`
- 下载数：320
- 收藏人数：74
- 评论人数：0
- 评分人数：1
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.1

- 统计数据
  - 发布时间：2023-06-19T01:37:36.762Z
  - 原始模型：SD 1.5
  - 下载数：8
  - 评分人数：0
  - 评分：0
- 下载地址
  - [kpcRMix_v11.safetensors](https://civitai.com/api/download/models/99133)
- 样例图像：
#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-06-19T01:37:36.762Z
  - 原始模型：SD 1.5
  - 下载数：312
  - 评分人数：1
  - 评分：5
- 下载地址
  - [kpcRMix_v10.safetensors](https://civitai.com/api/download/models/87485)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f3ce743d-cd83-4598-900b-ae1aa673c041/width=450/1001556.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f22c81cf-19f8-403d-a27c-78a1c028fbc2/width=450/1001560.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da7fcdd6-7368-4231-a209-bdd1c6842a60/width=450/1001561.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7d576179-2188-4f2e-937f-85c540fc4d71/width=450/1001580.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-2"><strong>KPC-R</strong></h1><p></p><p>This model is well trained to make 2.5d anime-like images right out of the box with minimal prompting. I've been working on this model for a few months now, and it's the result of crafting my own "style". Heavily inspired by artists like incase, and the styles of spiderverse/arcane. KPC-R makes what appears to be photoreal images, with a serious sense of artistic style to faces and people. The model is both SFW and NSFW capable.</p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/48e5c776-126d-4a37-b359-e8f41df8df92/width=525/48e5c776-126d-4a37-b359-e8f41df8df92.jpeg" /><p>girl with ginger hair sitting by pool outside hotel.</p><p></p><p><strong>NEGATIVE PROMPTING:</strong></p><p>Negative prompting will produce far better results. For the image above, I used the following negative prompt:</p><p><em>(ng_deepnegative_v1_75t, easynegative, bad quality, low quality, bad artist, (deformed), cropped, out of frame, (bad hands, badhandv4:1.2),gray skin:1.4), blurry, amputee, monochrome, fat, cold, thick thighs, long thighs, short shins, [high contrast], (!text:1.2!), watermark, bad-picture-chill-75v</em></p><p></p><p>Definitely use easynegative all the time, and bad-picture-chill-75v for more photorealistic results.</p><p>Furthermore, the prompt tends to generate younger looking people, which I'm not a huge fan of, so prompting against it is advised</p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/391c704e-9a73-4d5e-b8b0-ad900174b984/width=525/391c704e-9a73-4d5e-b8b0-ad900174b984.jpeg" /><p>woman with gray hair in business attire</p><p></p><p><strong>RECOMMENDED GENERATION SETTINGS:</strong></p><p>Personally, I prefer Euler a, at around 35 steps, at a CFG scale of 8. You can use other samplers of course, but this will be the fastest, and the quality difference is negligible.</p><p></p><p>For upscaling, latent models will give you a more soft/stylish look, but R-ESRGAN 4x+ is best overall, as it provides more consistency. For models other than those provided by A1111, 4x-Ultrasharp is my favorite.</p><p></p><p><strong>VAE:</strong></p><p>The model comes with a prebaked VAE, being orangemix.</p>