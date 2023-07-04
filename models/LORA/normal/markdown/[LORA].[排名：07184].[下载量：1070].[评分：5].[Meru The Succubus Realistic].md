## Meru The Succubus Realistic
### 一、模型概述

- 标签：`anime`, `character`, `person`, `photorealistic`, `sexy`, `female`, `woman`, `game character`, `girls`, `realistic`
- 下载数：1070
- 收藏人数：277
- 评论人数：0
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-06T01:55:55.005Z
  - 原始模型：SD 1.5
  - 下载数：1070
  - 评分人数：2
  - 评分：5
- 下载地址
  - [MeruSuccubus.safetensors](https://civitai.com/api/download/models/90085)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d32b24c0-f89b-40fa-b1e9-3c0f61a13dfc/width=450/1044607.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3383a6d4-f5f7-4ea3-96ef-a56bd5ffc1f1/width=450/1044604.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d696785b-381e-4c44-ad79-a0094255ac25/width=450/1044605.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dc1cd305-bf72-44ae-9ad7-fb47a0508ce2/width=450/1044603.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This was my attempt at creating Meru the succubus but centered around being more realistic. I think the results turned out pretty great, and you will be able to re-create my results if you follow my workflow. Please read it first, before asking me, why you are not able to make the same images. Copying the generation data from example images wont yield the same results because they are not directly from txt2img.</p><p></p><h2 id="heading-3278">Settings</h2><p>First of all the settings. Don't use a <strong>CFG</strong> scale over <strong>7</strong> or else you will be getting artifacts. I found <strong>6</strong> to be pretty good. Use this <strong><em>prompt</em></strong> for the best results:</p><p></p><p><strong>&lt;lora:MeruSuccubus:0.8&gt;, merusuccubus, (red skin), colored skin, (yellow eyes, glowing eyes), horns, (demon tail), choker, bangs,</strong></p><p></p><p>Very important to also include this in the <strong><em>negative</em></strong> or else you will be getting extra nipples and a lot of moles:</p><p></p><p><strong>(multiple mole:1.2), (multiple nipples:1.2),</strong></p><p></p><p><strong>Steps</strong>: 32-37</p><p><strong>CFG</strong>: 5-7</p><p><strong>Resolution</strong>: 512x768</p><p></p><p></p><p><em>My full prompt:</em></p><p></p><p><strong>photorealistic, (hyperrealistic:1.2), beautiful, masterpiece, best quality, extremely detailed face, perfect lighting</strong> <strong>, &lt;lora:MeruSuccubus:0.8&gt;, merusuccubus, (red skin), colored skin, (yellow eyes, glowing eyes), horns, (demon tail), choker, bangs,</strong></p><p><em>negative:</em></p><p></p><p><strong>(worst quality, low quality:1.4), (monochrome), zombie, watermark, username,patreon username, patreon logo, (extra fingers, deformed hands, polydactyl:1.5),(multiple mole:1.2), (multiple nipples:1.2),</strong></p><p></p><p></p><h1 id="heading-3279">Workflow</h1><p>All the example images were created with this workflow:</p><h3 id="heading-3280">1:</h3><p>First generate a txt2img which you like (The quality wont be sharp ofc). You can do a hiresfix if you want to.</p><h3 id="heading-3281">2:</h3><p>Send the image to img2img. Here i set the resolution as 936x1400 (Width x Height) because that is what my pc can handle. Set the denoise strength between 0.35-0.5</p><h3 id="heading-3282">3:</h3><p>Send the image you like to inpainting. Start inpainting all the features like the face, body, clothes, hands etc..</p><h3 id="heading-3283">4:</h3><p>Send to extra and upscale the image with your favorite upscaler. I used 4x_fatal_anime</p><p></p><p>Here are the progress after completing each step:</p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c688dcf3-68ae-482e-a11e-33336637f20c/width=525/c688dcf3-68ae-482e-a11e-33336637f20c.jpeg" /></p><p></p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ea22a61b-e86c-491b-ae4b-55d2292b239b/width=525/ea22a61b-e86c-491b-ae4b-55d2292b239b.jpeg" /></p>