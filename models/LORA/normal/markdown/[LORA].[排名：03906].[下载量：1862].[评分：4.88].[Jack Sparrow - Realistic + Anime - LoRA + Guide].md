## Jack Sparrow - Realistic + Anime - LoRA + Guide
### 一、模型概述

- 标签：`anime`, `3d`, `person`, `photorealistic`, `digital art`, `manga`, `guide`, `2d`, `male`, `man`, `photography`, `photorealism`, `real person`, `semi-realistic`, `3d-to-2d`, `pirates of the caribbean`, `jack sparrow`
- 下载数：1862
- 收藏人数：482
- 评论人数：28
- 评分人数：8
- 评分：4.88

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] offset

- 统计数据
  - 发布时间：2023-04-28T21:29:56.554Z
  - 原始模型：SD 1.5
  - 下载数：1862
  - 评分人数：8
  - 评分：4.88
- 下载地址
  - [jack_sparrow_offset.safetensors](https://civitai.com/api/download/models/14395)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2ffa8ab5-734f-437c-3f6d-cbb42df89400/width=450/626538.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9501499c-6b38-4a34-b993-8f865ec2f700/width=450/140365.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0a6dfc86-bb26-477e-48c2-58de77d17700/width=450/140370.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ae850ee5-e982-4bd2-c33e-612544bdad00/width=450/140751.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2>Jack Sparrow - Realistic + Anime - LoRA</h2><p><strong>Making models can be expensive. Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong></p><p><strong>Consider leaving a ❤️ to receive future updates. </strong></p><p>This is a successful experiment I made for testing out my theory on how to make an anime character from a photorealistic dataset. The answer was simply to use <a target="_blank" rel="ugc" href="https://civitai.com/models/10028"><strong>NeverEnding Dream (NED)</strong></a>. NED was made basically to bridge the gap between photorealistic models and anime ones, so the theory was to use a dataset made of movie screencaps of Jack Sparrow (about 80), tag them with booru style tags (using a combination of WD Tagger + manual) and train a LoRA on NED. <br />If you then make the inference on NED it gives a perfectly photorealistic model, but if you use it on AnyLoRA or anime models in general it gives you an anime version of Jack Sparrow with <em>little </em>to no style transfer.</p><p>You can probably use this technique to turn any real person into an anime counterpart and vice versa (see: my <a target="_blank" rel="ugc" href="https://civitai.com/models/11814/ganyu-genshin-impact-realistic-anime-lora">Ganyu LoRA</a>).</p><p>You can use at weight 1 generally, but tune it based on the model. Trigger is <code>jack sparrow</code>.</p><p>As most of my LoRA's, this can be customized a lot. In the examples I provided a blonde anime girl Jack Sparrow. Examples 6 and 7 are of course using my <a target="_blank" rel="ugc" href="https://civitai.com/models/4219/one-piece-wano-saga-style-lora">One Piece style LoRA</a>. Third image by <a target="_blank" rel="ugc" href="https://civitai.com/user/bloodsplash09">bloodsplash09</a>.</p><p></p><p><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight according to the instructions </strong>(by default it's <code>:1</code>)</p></li></ul>