## Aayla Secura | Star Wars
### 一、模型概述

- 标签：`character`, `star wars`, `twi'lek`, `jedi`, `aayla secura`
- 下载数：856
- 收藏人数：122
- 评论人数：3
- 评分人数：4
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v.1

- 统计数据
  - 发布时间：2023-04-26T19:46:00.237Z
  - 原始模型：SD 1.5
  - 下载数：856
  - 评分人数：4
  - 评分：5
- 下载地址
  - [aaylaSecura_v01.safetensors](https://civitai.com/api/download/models/33954)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/036a8968-c26b-4224-7e1a-c43db224eb00/width=450/387227.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1f19d637-7d41-401d-6dfe-b9e679a83000/width=450/387233.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/500b3333-7f7c-4887-76c7-b8e52dc38300/width=450/387232.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/13fbd73e-a3af-41a6-874b-701276f76200/width=450/387231.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>Aayla Secura | Star Wars</h1><p>This is my first LoRA. Feel free to leave some feedback and ideas for improvement.</p><h3>Genereal training information</h3><p>Based on 30 images cropped to 768 x 768.</p><p>Manually refined the captions from BLIP afterwards.</p><p>Run with 100 steps per image totals in 3000 steps.</p><p>Trained on SD1.5</p><p>GTX1080 ~ 4h</p><p></p><p>I did some basic testing, the following settings can be tried out as a baseline:</p><ul><li><p>Model: SD1.5, however, other models are working well too (Mostly tested with <a rel="ugc" href="https://civitai.com/models/10752/the-allys-mix-iii-revolutions">The Ally's Mix</a>) </p></li><li><p>CFG: 6-9, mostly used <strong>7</strong></p></li><li><p>Steps: <strong>22</strong>, 30, 35 worked well with 2M Karras and DDIM</p></li><li><p>768 by 768 will probably yield best results as it was trained on this dimensions</p></li><li><p>LoRA weight: 0.3 [very far away from real Aayla but works sometimes]; <strong>0.6</strong> [very nice middleground for getting some batches for testing]; 0.8 [also worked very nice]; 0.9 [wouldn't go higher as the results turn out weirdly]</p></li></ul><p></p><h3>Styles</h3><ul><li><p>Realistic: (ultra realistic:1.1) [<strong>example image 1 and 2</strong>]</p></li><li><p>Cartoon: (cartoon:1.2) [weight 1.5 really exaggerates the cartoon look, therfore face details have to be sacrificed; <strong>example image 3, 4 with latent upscaling</strong>]</p></li><li><p>Drawing: drawing:1.1 of [pretty similar to cartoon, I personally facor cartoon]</p></li></ul><p></p><h3>Promts that should trigger additional training data:</h3><ul><li><p>wearing star wars costume </p></li><li><p>wearing star wars outfit</p></li><li><p>leather headpiece</p></li><li><p>blue light saber (<strong>put this on the negative promts if you don't want blue lights everywhere</strong>)</p></li></ul><p></p><p><em>*most example images where upscaled with denoising around 0.55 (2 times, latent)</em></p>