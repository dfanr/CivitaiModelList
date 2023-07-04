## Lawlas's Yiffymix 2.0 (furry model)
### 一、模型概述

- 标签：`anime`, `character`, `furry`, `illustration`, `nsfw`, `sfw`
- 下载数：12353
- 收藏人数：1566
- 评论人数：59
- 评分人数：44
- 评分：4.73

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] Lawlasmix with baked-in VAE

- 统计数据
  - 发布时间：2023-03-30T16:56:56.566Z
  - 原始模型：SD 1.5
  - 下载数：11179
  - 评分人数：36
  - 评分：4.69
- 下载地址
  - [lawlassYiffymix20Furry_lawlasmixWithBakedIn.safetensors](https://civitai.com/api/download/models/15460)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dea20b13-3bfe-4a36-ef40-898712884a00/width=450/154061.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a0812810-8277-450d-ce47-36186033d900/width=450/154059.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9d322223-0254-4388-ebdf-d08b3f80af00/width=450/154060.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1108200c-299d-427e-5215-98913fa43300/width=450/154058.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] Lawlasmix2.0

- 统计数据
  - 发布时间：2023-03-30T16:56:56.566Z
  - 原始模型：SD 1.5
  - 下载数：1174
  - 评分人数：8
  - 评分：4.88
- 下载地址
  - [lawlassYiffymix20Furry_lawlasmix20.safetensors](https://civitai.com/api/download/models/15288)
  - [orangemix.vae.pt](https://civitai.com/api/download/models/15288?type=VAE&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dea20b13-3bfe-4a36-ef40-898712884a00/width=450/151117.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a0812810-8277-450d-ce47-36186033d900/width=450/151129.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9d322223-0254-4388-ebdf-d08b3f80af00/width=450/151128.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/55a1a7d2-a739-4816-57d8-95db21e57d00/width=450/151125.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><em><u>Disclaimer: Despite having "Yiffymix" in the name, the model itself has nothing to do with Yiffymix.</u></em></p><p></p><p><strong>▼About</strong></p><p>Hello and welcome. This model is an upgrade from my previous model <a target="_blank" rel="ugc" href="https://civitai.com/models/4698/lawlass-yiffymix-furry-model">Lawlasmix</a>. I used <a target="_blank" rel="ugc" href="https://civitai.com/models/9942/abyssorangemix3-aom3">AOM3</a> and miscellaneous models during the making of the model, so don't forget to check that out.</p><p>It's capable of generating sfw/nsfw furry artworks in general with consistent quality, while having decent details in hands, clothing, background, etc. Compared with the old Lawlasmix, it's overall more <em><u>anime style oriented</u></em>, and<u> </u><em><u>doesn't need artist tags all the time </u></em>(It can still change the styles if you use them anyways).<strong><em> It can be tricky to write prompts for the model if you're new to it, so make sure you read the tips carefully!</em></strong></p><p></p><p><strong>▼Tips</strong></p><ul><li><p><strong>Personally I use it with these settings:</strong></p><p>Batch count: 6</p><p>Clip skip: 1 or 2 (for different styles)</p><p>CFG: 6-8</p><p>steps: 40-150</p><p>Size: 512 x 704 or 512 x 780 .etc (then use hiresfix, or SD upscale in img2img )</p><p>Sampler: DPM++ 2M Karras or Euler a</p><p></p></li><li><p><strong>Prompting</strong></p><p>The model can make amazing results with very simple prompts so long as you use it right. It uses both danbooru and e621 tags, like 1boy, 1girl, solo_focus.<em><u> It's recommended to start the positive prompt with "(furry art, uploaded on e621:1.4)" and negative prompt with "(worst quality, low quality:1.4)"</u></em><u>.</u> Since the merge has significant amont of anime models in it, you need to give more weight to furry related tags. Use tags like (anthro furry:1.6) in the positive prompts and (human:1.6) in order to get it to make furry art.<u> </u><em><u>The model performs rather well when you specify the color of the fur. For instance, (detailed red scales:1.5), (detailed blue fluffy fur:1.5)</u></em><u>. </u>Feel free to check out the example images for their prompts to help you write your own.</p><p></p></li><li><p><strong>VAE</strong></p><p>If you don't use any vae with <strong>the original version</strong>, the outputs of the model may suffer from loss of colors. As a result, consider using anythingv3 vae or orangemix vae. I provide the download of orangemix vae here. <em><u>However, if you don't want to use any VAEs or can't get them to load, you can now choose the versions with a VAE baked in the model.</u></em></p><p></p></li><li><p><strong>Embedding</strong></p><p>Feel free to use other textual inversions, but I strongly recommend <a target="_blank" rel="ugc" href="https://huggingface.co/FoodDesert/boring_e621">boring_e621</a>. It's trained specifically on furry artwork and works great in this case. Try <a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative">EasyNegative</a> as well</p></li></ul><p></p><p><strong>Known problem(s)</strong>:</p><ol><li><p>Since the has AOM3 mixed in it, it's very common for it to generate results in which characters have "M" shaped hair. <em><u>Consider using tags like (unique hairstyle, unique fringe, unique bangs:1.6) or using img2img to generate alternative images to help you get to the desired results.</u></em></p></li><li><p>The model has reported to be temperamental so to speak. <em><u>I suggest setting batch count to more than 2 so you have more results to choose from.</u></em></p><p></p></li></ol><p><strong>▼Credits:</strong></p><p>Here are models used as far as I can remember:</p><ol><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/9942/abyssorangemix3-aom3">AOM3</a></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/6174/divineelegancemix">DivineEleganceMix</a></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/4698/lawlass-yiffymix-furry-model">My previous model</a></p></li></ol><p>I apologize for not keeping a record of the models I used. Without their amazing work, this model wouldn't have even existed. Kudos to every creator on this site!</p>