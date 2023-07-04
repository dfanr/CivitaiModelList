## Prinz Eugen (Kancolle)
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `kantai collection`, `kancolle`, `game character`
- 下载数：1805
- 收藏人数：401
- 评论人数：5
- 评分人数：8
- 评分：4.88

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-25T09:01:03.767Z
  - 原始模型：SD 1.5
  - 下载数：1805
  - 评分人数：8
  - 评分：4.88
- 下载地址
  - [PrinzEugenFullTag1-000007.safetensors](https://civitai.com/api/download/models/23308)
  - [Prinz.zip](https://civitai.com/api/download/models/23308?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/57d3f5de-5569-4c2e-5c26-2771f8eeb300/width=450/252782.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6d87e324-baf8-4f5c-a5c8-fb8dbb3b8c00/width=450/252863.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/689eba41-a9c7-45d8-bece-0ec527128700/width=450/252791.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f565b86a-f19f-4df7-fab2-c118c1e9cd00/width=450/252790.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>More preview on my Pixiv: <a target="_blank" rel="ugc" href="https://www.pixiv.net/users/18763851">4BEraser - pixiv</a></p><p><s>Feuer Feuer</s></p><p>Next is Iowa. Progress: solving the pic from 1000+images.</p><p>Maybe I should download Koikatsu again for <a target="_blank" rel="ugc" href="https://www.pixiv.net/artworks/78906403">this</a> to reference.</p><p>How to use:</p><p>Base: <code>Prinz Eugen/(Kancolle/),</code></p><ul><li><p>↑ Basically enough since I merged the characteristic prompt into it.</p></li><li><p>Still, if the generated hair is too long, add <code>long hair</code><u> to negative prompt</u>.</p></li><li><p>Her eye color is kinda blue and green, personally I will choose to add <code>green eyes</code> prompt.</p><p></p></li></ul><p>Official Outfit: <code>anchor hair ornament, peaked cap, hat ornament, military uniform, iron cross, long sleeves, white gloves, black skirt, pleated skirt, miniskirt, kneehighs, boots,</code></p><ul><li><p>This one is good enough for alternate clothings. If it didn't go well, <strong>add your prompt weight to over 1.2 will help, or consider switch to a more common model.</strong></p></li><li><p>I've put some test grid image to show you whether you should add weight or not. Those bad pics means the prompt need a higher weight to generate.</p></li><li><p>I didn't merge rigging dataset to this version, so mostly it will be fine in any situation.</p><ul><li><p>NSFW compatible I guess.</p></li><li><p>If you find out that it's focusing on chara's feet, you can try to use ControlNet to limit it, or delete the lower body related tags. I've solved the outfit tag from chara's head to feet, so it should be easy to sort out.</p></li><li><p>It's bit weird that this model doesn't look very well in Anime-latest, considering I trained it based on Anime-Full, but AOM3/Counterfeit v2.5/ANYV3 seems to be fine.</p><p></p></li></ul></li></ul><p>Settings are what I am using, you can change by your own.</p><ul><li><p>DPM++ Series(SDE Karras, 2M Karras, etc.)</p></li><li><p>about 20 steps, CFG scale 5~7</p></li><li><p>Base resolution ≤ 1024x1024 (Trained size)</p></li><li><p>LoRA Weight: above 0.6, try it by your own</p></li><li><p>If using highres</p><ul><li><p>ESRGAN series are all fine (personally, R-ESRGAN+Anime 6B)</p></li><li><p>Denoising 0.5-0.6.</p></li><li><p>LoRA Train Info</p><ul><li><p>based on Animefull-pruned</p></li><li><p>batch 2</p><ul><li><p>4x other outfits 132 images</p></li><li><p>3x official outfits 147 images</p></li><li><p>6x NSFW 13 images</p></li><li><p>=&gt; 1 epoch = 1047 images</p></li></ul></li></ul></li></ul></li></ul>