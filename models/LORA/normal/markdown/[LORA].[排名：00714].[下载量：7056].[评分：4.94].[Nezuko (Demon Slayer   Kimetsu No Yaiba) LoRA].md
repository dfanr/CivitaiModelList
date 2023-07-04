## Nezuko (Demon Slayer / Kimetsu No Yaiba) LoRA
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `photorealistic`, `female`, `asian`, `demon slayer`, `woman`, `cute`, `girls`, `portraits`, `nezuko kamado`, `kimetsu no yaiba`
- 下载数：7056
- 收藏人数：1192
- 评论人数：17
- 评分人数：16
- 评分：4.94

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] offset

- 统计数据
  - 发布时间：2023-03-24T14:37:04.494Z
  - 原始模型：SD 1.5
  - 下载数：7056
  - 评分人数：16
  - 评分：4.94
- 下载地址
  - [kamado_nezuko_offset.safetensors](https://civitai.com/api/download/models/24191)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/021ff234-e11d-4884-81e7-cb822338f600/width=450/262965.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/195b0396-50dc-4dc2-bc29-2c0708583500/width=450/262932.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2673397c-49c3-40e8-9295-aa69b6a16f00/width=450/262931.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5a7a490a-139c-465f-6d36-e6d90484db00/width=450/262962.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2>Nezuko (Demon Slayer / Kimetsu No Yaiba) LoRA</h2><p><strong>Making models can be expensive. Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong></p><p>I've always loved this character and I wanted to give it a try. The bamboo gag is a bit tricky, as most base models have that overfit on the tag "kamado nezuko", which is also the one I wanted to use as trigger. However I managed to separate it from the character. Most of the time it should appear with no gag unless you prompt for it using <code>bit gag</code> and <code>gagged</code>, and instead prompt for <code>open mouth</code> or similar tags. If that doesn't work I noticed it's easy to just put <code>bit gag</code> and <code>gagged</code> in the negative prompts, as shown in one of the examples. Of course the trigger is <code>kamado nezuko</code>, which is required. Weight is around 1.</p><p>Realistic examples are made using <a target="_blank" rel="ugc" href="https://civitai.com/models/10028/neverending-dream-ned">NED</a>, the anime ones are made with AnyLoRA, Counterfeit or AnyPastel.</p><p>Pics 6 and 7 are also using my <a target="_blank" rel="ugc" href="https://civitai.com/models/21272/demon-slayer-kimetsu-no-yaiba-anime-style-lora">Demon Slayer Anime Style LoRA</a>.</p><p><br /><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight according to the instructions</strong> (by default it's <code>:1</code>)</p></li></ul><p></p>