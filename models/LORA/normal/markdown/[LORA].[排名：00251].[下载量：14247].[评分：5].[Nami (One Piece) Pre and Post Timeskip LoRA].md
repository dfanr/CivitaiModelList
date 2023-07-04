## Nami (One Piece) Pre and Post Timeskip LoRA
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `photorealistic`, `sexy`, `female`, `one piece`, `woman`, `beautiful`, `cute`, `girls`, `portraits`, `realistic`, `women`, `nami`
- 下载数：14247
- 收藏人数：2127
- 评论人数：13
- 评分人数：30
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] post timeskip

- 统计数据
  - 发布时间：2023-04-29T17:39:44.002Z
  - 原始模型：SD 1.5
  - 下载数：12857
  - 评分人数：25
  - 评分：5
- 下载地址
  - [nami_final_offset.safetensors](https://civitai.com/api/download/models/18189)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/08dafdeb-e171-4e2a-534d-a194c6b48000/width=450/366074.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/afb0ff27-2bb5-491d-6f16-8632f7061000/width=450/187077.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e147d008-06cb-4f3b-52c7-995b67d6cc00/width=450/187076.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1dd3fd2f-b45d-447a-34b0-80419528db00/width=450/187075.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] pre timeskip

- 统计数据
  - 发布时间：2023-04-29T17:39:44.002Z
  - 原始模型：SD 1.5
  - 下载数：1390
  - 评分人数：5
  - 评分：5
- 下载地址
  - [nami_pre_timeskip_offset.safetensors](https://civitai.com/api/download/models/18188)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f289ceb1-c156-46a2-192d-394fddeff800/width=450/366077.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d68d3e0a-647a-445e-ba61-40a1b41ee100/width=450/187055.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/241f67c9-6cdb-435f-945a-5fd8fa1a8b00/width=450/187058.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0ba67f15-ece5-4539-49fa-894204708b00/width=450/187057.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2>Nami (One Piece) LoRA (pre and post timeskip)</h2><h3><u>CHECK BOTH VERSIONS</u></h3><p><strong>Pre Timeskip: </strong><a target="_blank" rel="ugc" href="https://civitai.com/models/15431?modelVersionId=18188">https://civitai.com/models/15431?modelVersionId=18188</a><br /><strong>Post Timeskip:</strong> <a target="_blank" rel="ugc" href="https://civitai.com/models/15431?modelVersionId=18189">https://civitai.com/models/15431?modelVersionId=18189</a></p><p><strong><u>Also check your filters to see all the examples</u></strong></p><p><strong>Making models can be expensive. Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong></p><p>Well, this wasn't easy to get right. One version of Nami alone is already pretty hard to make: she has a very specific tattoo, asymmetrical, she has exactly 2 rings per side on her jeans (or on her skirt before timeskip) and she wears tons and tons of different official outfits. Plus her artworks tend to be inconsistent, so I had to clean the dataset a lot. Not to mention the timeskip problem: she is basically 2 different characters, both very hard.</p><p>At the end of the day I had to accept some compromise. First of all I had to make TWO LoRA's and not one. Second I needed to focus on getting her main outfit right and, most importantly, the tattoo. Everything else came second.</p><p>I think I managed somehow. I made 2 LoRA's, one for pre timeskip Nami and one for post timeskip Nami, both of them can do both versions, but they focus on their respective ones.</p><p>Main outfits are always kind of right, but exactly right about 1/4th of the time. Tattoo is almost always right. Secondary outfits are almost right about 1/4th of the time, depending on how rare they are in artworks.</p><p>The model is not overfitted and can be used on most booru based models. I mostly tried it with AnyLoRA and NeverEnding Dream for realistic shots. <strong>Weight should be around 1 for post timeskip and around 1.2 for pre timeskip for better accuracy</strong>. I suggest using weight 1 if you need just her face and tattoo on non-official outfits.</p><p>Triggers with <code>nami \(one piece\)</code> for better accuracy. Also use <code>short hair</code> in pre timeskip version. One of the examples is also using my Wano Style LoRA.</p><p>Please enjoy.</p><p></p><p><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight according to the instructions</strong> (by default it's <code>:1</code>)</p></li></ul><p></p>