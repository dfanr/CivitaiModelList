## DGPD
### 一、模型概述

- 标签：`concept`, `dd`, `gif`, `frames`, `grids`
- 下载数：2144
- 收藏人数：464
- 评论人数：10
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] DGPD

- 统计数据
  - 发布时间：2023-05-16T09:40:24.478Z
  - 原始模型：SD 1.5
  - 下载数：2144
  - 评分人数：1
  - 评分：5
- 下载地址
  - [dgpd_.safetensors](https://civitai.com/api/download/models/72080)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dcde9cbf-953e-472c-9055-5a13403b4f7a/width=450/805656.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/51f20756-05f5-4e3c-aba0-de89ac4794fc/width=450/805669.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/23f0d698-27ad-432d-adc0-5d8328355ef5/width=450/805670.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e5e7e5c3-e626-4fe5-b090-127b6a10ad7e/width=450/805674.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>!!!THIS IS NOT A MODEL FOR CASUAL USE!!!</h1><p>I made a disclamer, so download it and use only if you struggle with my frames Loras (or any other, that use <strong>2x2frames </strong>or <strong>3x3frames </strong>tags). In short - it's a model that knows a basic concept of frames as a composition class, if that makes sense. Supposedly it gives more control of grids Loras, and at the first glimpse it really does.</p><p>This model was made like this:</p><ol><li><p>Firstly I trained a model on about 500 images of frames;</p></li><li><p>Then I clean it from any traces of the model I trained it on through merging;</p></li><li><p>Then I merged it with <a rel="ugc" href="https://civitai.com/models/24350/perfectdeliberate">perfectDeliberate </a>model a couple of times to get this result.</p></li></ol><p>Basicaly it's a perfectDeliberate model with frames, but I found a couple of downgrades in quality on my model when generated casual (not frames) pictures. So if you want to use as a standalone model - just use perfectDeliberate instead, it's just better.</p><h2>How to use it:</h2><ol><li><p>Download any of the grids Loras;</p></li><li><p>Use this model as "guide" in txt2img (just generate a couple of pictures in 512x512 (2x2frames tag) or 768x768 (3x3frames tag), till you are satisfied with the results, there will be artifacts, because images are small);</p></li><li><p>Then change the model to your liking, set denoising str 0.5-0.6 and lower the Lora weight to 0.4-0.6, and upscale it as much as you can;</p></li></ol><p>Also you can make gifs whith this model alone, the best results I get was with hiers fix on 0.5 str. </p><p><a rel="ugc" href="https://civitai.com/models/60211/dd-how-to-make-gifs-from-my-loras">Guide </a>on how to use my grid Loras.</p><h2>Know issues</h2><p>Sometimes here and there appears strange "glowing" artifacts. I guess it's because of the baked in perfectDeliberate VAE, or maybe I did something wrong when merging models. I'm trying to get rid of it. </p><h2>P.S.</h2><p>Feel free to ask any questions here in comments, or in <a target="_blank" rel="ugc" href="https://discord.gg/9My32sKEAK">my discord channel</a>.</p><p>Also I am making games with AI arts. They will be free in the future, but if you want to participate in making or have an early access - you can <a target="_blank" rel="ugc" href="https://www.patreon.com/aDDont">support me on patreon</a>)</p><p>Also my wet hair Lora was banned here, I dunno why. You can <a target="_blank" rel="ugc" href="https://www.patreon.com/posts/wet-hair-model-82413226">download </a>the last version of it from my patreon for free.</p>