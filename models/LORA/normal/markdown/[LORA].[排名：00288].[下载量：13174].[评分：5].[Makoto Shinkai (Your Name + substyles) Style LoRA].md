## Makoto Shinkai (Your Name + substyles) Style LoRA
### 一、模型概述

- 标签：`anime`, `girl`, `movie`, `female`, `highly detailed`, `makoto shinkai`, `style`, `art style`, `woman`, `illustration`, `artist`, `artstyle`, `cute`, `digital illustration`, `girls`, `male`
- 下载数：13174
- 收藏人数：2896
- 评论人数：23
- 评分人数：19
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] offset

- 统计数据
  - 发布时间：2023-04-03T22:31:14.524Z
  - 原始模型：SD 1.5
  - 下载数：13174
  - 评分人数：19
  - 评分：5
- 下载地址
  - [shinkai_makoto_offset.safetensors](https://civitai.com/api/download/models/12610)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8a74bbda-3a1b-49f4-86e3-b9ff52334a00/width=450/122175.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9ac7d408-a700-4419-cf5a-868778784300/width=450/122173.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3d371d90-f250-4469-4683-d383620f1100/width=450/122216.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/80e9b7b0-2268-480c-01ed-999e921a8b00/width=450/122513.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2>Makoto Shinkai style LoRA</h2><h3>Includes substyles for Your Name, Weathering With You and The Garden of Words.</h3><p><strong>Making models can be expensive. Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong></p><p>Requested on Discord, this was trained on my hand selected and tagged dataset of anime screencaps. Trigger word is <code>shinkai makoto</code> and contains substyles that are each triggered with <code>kimi no na wa.</code> (mind the dot), <code>tenki no ko</code>, and <code>kotonoha no niwa</code> respectively. See the example images and final comparison. Keep in mind this is not a character lora. While it obviously overfitted on the main cast, it won't get characters accurately 100% of the time without a character specific LoRA/TI.</p><p>It works most accurately on AnyLoRA and I've offset it so that it works at 1 weight. Should actually work on most anime models and on <a target="_blank" rel="ugc" href="https://civitai.com/models/10028/neverending-dream">NeverEnding Dream</a>.</p><p>Clip skip 2 should be better, but careful as some of the examples are using Clip skip 1 because I forgot the setting from another test I was making. Pic 3 and 10 are generated with clip skip 1 and upscaled with clip skip 2.</p><p><br /></p><p><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight according to the instructions </strong>(by default it's <code>:1</code>)</p></li></ul>