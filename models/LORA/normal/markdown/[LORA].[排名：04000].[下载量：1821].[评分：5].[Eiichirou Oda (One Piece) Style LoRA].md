## Eiichirou Oda (One Piece) Style LoRA
### 一、模型概述

- 标签：`anime`, `one piece`, `watercolor`, `manga`, `mangaka`, `oda eiichirou`, `style`, `art style`, `illustration`, `artstyle`, `beautiful`, `traditional art`
- 下载数：1821
- 收藏人数：376
- 评论人数：4
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1

- 统计数据
  - 发布时间：2023-03-23T22:19:46.223Z
  - 原始模型：SD 1.5
  - 下载数：1821
  - 评分人数：2
  - 评分：5
- 下载地址
  - [oda_eiichirou.safetensors](https://civitai.com/api/download/models/5866)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9cb1c9a4-4dd7-412b-3b17-08aa63f2e600/width=450/49251.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fe724a37-bca8-4854-186a-9b325928a100/width=450/49249.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9565d49e-e6c7-400a-f751-63670c793b00/width=450/49248.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/edd13f07-7f1e-4bfe-f0c2-1fe79d856f00/width=450/49250.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2>Eiichirou Oda (One Piece) style LoRA</h2><p><strong>Making models can be expensive. Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong></p><p>LoRA net for the style of my favourite mangaka. Oda's style has changed a lot during the years, so it was hard to capture his character design. This model mostly got his way of drawing lines and his coloring, plus certain details. It didn't really grasp character concept completely as much as my previous LoRA's (probably because the dataset was full of pics with multiple characters, as Oda mostly makes those), but it's pretty good when combined with embeddings (like the first Nico Robin pic, which is using <a target="_blank" rel="ugc" href="https://civitai.com/models/4223/nico-robin-ti">my embedding</a>, and unlike the second one, which is not using embeddings and looks like a mix between Nami and Robin). <br /><br />Trigger word is <code>oda eiichirou</code>, suggested <strong>weight around 0.5 or 0.6</strong> depending on the base model (I used Anything V4.5 here).</p><p>For the <strong>One Piece anime style</strong> please use this other LoRA I made: <a target="_blank" rel="ugc" href="https://civitai.com/models/4219/one-piece-wano-style-lora">https://civitai.com/models/4219/one-piece-wano-style-lora</a> <br /><br /><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight</strong> (by default it's <code>:1</code> which is usually too high)</p></li></ul>