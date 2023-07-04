## Fakemon (Pokémon LORA) Beta
### 一、模型概述

- 标签：`anime`, `pokémon`, `style`, `pokemon`, `video game`
- 下载数：1719
- 收藏人数：360
- 评论人数：5
- 评分人数：4
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0 beta

- 统计数据
  - 发布时间：2023-03-10T17:42:11.128Z
  - 原始模型：SD 1.5
  - 下载数：1719
  - 评分人数：4
  - 评分：5
- 下载地址
  - [pokemon.safetensors](https://civitai.com/api/download/models/20503)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/db9ccc2b-1c8f-41a1-f1cf-9f75ae5b7800/width=450/216947.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/95df0c6b-b3df-4276-e8c7-363e07d21f00/width=450/216953.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/aa17c85b-e1f9-45f5-9e47-eafa188a3500/width=450/220526.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/acad3727-11d0-4aae-e5c8-cdf455693e00/width=450/216952.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3>A LORA trained on official artworks of all the 1008 Pokémon, along with their types and BLIP generated captions.</h3><p></p><p>This is my first fully trained LORA model and I have no idea what I'm doing.</p><p><strong>Any feedback or tips on how to improve this would be really helpful :)</strong></p><p></p><p><strong>Fell free to experiment with it and share!</strong></p><p></p><h3>Recommended Configs:</h3><p>My default prompt is:</p><p>pokemon, [type1] and [type2], [characteristics], masterpiece, high quality, best quality, high-definition, ultra-detailed, black background,&lt;lora:pokemon:0.5&gt;</p><p></p><p>Negative prompt:</p><p>nsfw, human, 1boy, 1girl, (worst quality, low quality:1.4), ( jpeg artifacts:1.4), (depth of field, bokeh, blurry, film grain, chromatic aberration, lens flare:1.0), greyscale, monochrome, dusty sunbeams, trembling, motion lines, motion blur, emphasis lines, text, title, logo, signature</p><p></p><ul><li><p>The weights could be between <u>0.5-0.7</u> for <strong>animal </strong>like and <u>0.2-0.5</u> for <strong>humanoid </strong>like Pokémon.</p></li><li><p>Clip Skip: 2 and ENSD: 31337.</p></li><li><p>768x768 works better than 512x512.</p></li><li><p>For sampler <strong>Euler a </strong>works fine, but I prefer <strong>DPM++ SDE Karras</strong>.</p></li><li><p>Use "<strong>black background"</strong> tag to keep the Pokémon isolated, more complex backgrounds are better with <strong>negative embeddings</strong>.</p></li><li><p>You can use either one or two types.</p></li><li><p>Describe your Pokémon along with vibe characteristics (Ex: edgy, cute, strong, etc).</p></li><li><p>I tested it on both <a target="_blank" rel="ugc" href="https://civitai.com/models/9942/abyssorangemix3-aom3"><strong>AbyssOrangeMix3</strong></a>, and <a target="_blank" rel="ugc" href="https://civitai.com/models/7371/rev-animated"><strong>ReV Animated</strong></a><strong> </strong>and get good results, realistic models such as <a target="_blank" rel="ugc" href="https://civitai.com/models/4201/realistic-vision-v13-fantasyai"><strong>Realistic Vision</strong></a><strong> </strong>seems to not work at all, but further tests are welcomed.</p></li><li><p>Abyss has more <strong>official artwork</strong> style and ReV is more <strong>stylized</strong>.</p></li><li><p>You can get deformed creatures some times, so a <strong>negative embedding</strong> should help.</p></li></ul><p></p><p>Examples of negative embeddings:</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8ed99c80-b2d1-476d-4021-a9dd2b39df00/width=525/8ed99c80-b2d1-476d-4021-a9dd2b39df00" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fed242f2-a623-48b3-ec2a-db449f1a2900/width=525/fed242f2-a623-48b3-ec2a-db449f1a2900" /><p></p><p>Here is a image with every type applied in the same prompt: <a target="_blank" rel="ugc" href="https://imgur.com/a/pkqj5ST">https://imgur.com/a/pkqj5ST</a></p><p></p><p>The base model used for the training is the <a target="_blank" rel="ugc" href="https://civitai.com/models/9942/abyssorangemix3-aom3"><strong>AbyssOrangeMix3</strong></a>, therefore the <a target="_blank" rel="ugc" href="https://huggingface.co/WarriorMama777/OrangeMixs#licence">licenses </a>of this LORA are the same.</p>