## SamDoesArts (Sam Yang) Style LoRA 
### 一、模型概述

- 标签：`anime`, `girl`, `samdoesarts`, `sam yang`, `style`, `art style`, `woman`, `artstyle`, `digital illustration`, `girls`, `women`
- 下载数：43150
- 收藏人数：7842
- 评论人数：75
- 评分人数：71
- 评分：4.97

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] offset

- 统计数据
  - 发布时间：2023-05-06T17:30:48.853Z
  - 原始模型：SD 1.5
  - 下载数：41552
  - 评分人数：58
  - 评分：4.97
- 下载地址
  - [sam_yang_offset_right_filesize.safetensors](https://civitai.com/api/download/models/7804)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/676532a0-04ad-41c0-cac4-d6d1fa595400/width=450/73354.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e7b21e65-258f-4aa0-ebae-12adbc05dd00/width=450/73379.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e41b5d6b-2052-4684-6024-8d9ba70c0f00/width=450/126879.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/92dd6c56-2fd2-470c-1e31-747772f46900/width=450/126881.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] offset 32dim

- 统计数据
  - 发布时间：2023-05-06T17:30:48.853Z
  - 原始模型：SD 1.5
  - 下载数：556
  - 评分人数：0
  - 评分：0
- 下载地址
  - [sam_yang_offset32dim.safetensors](https://civitai.com/api/download/models/64140)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fed5855f-3ad2-44a9-8352-1ef4d359bd59/width=450/708163.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/01f5269c-5c67-44d3-9748-1e84c64c7c54/width=450/708205.jpeg" /> |
| ---- | ---- |

#### [版本1/共3个版本] original

- 统计数据
  - 发布时间：2023-05-06T17:30:48.853Z
  - 原始模型：SD 1.5
  - 下载数：1042
  - 评分人数：13
  - 评分：5
- 下载地址
  - [sam_yang.safetensors](https://civitai.com/api/download/models/10864)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bcf75f7c-df0a-424a-36ec-80ecc4eaf700/width=450/105008.jpeg" /> |
| ---- |


### 三、详情
<h2>SamDoesArts (Sam Yang) style LoRA</h2><p><strong>Making models can be expensive. Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong></p><p>There are already countless models for this artstyle, but I still wanted to test out how LoRA's can handle it. I also wanted to experiment with <a target="_blank" rel="ugc" href="https://huggingface.co/m4gnett/any-pastel"><strong>AnyPastel</strong></a> (or <a rel="ugc" href="https://civitai.com/models/23521?modelVersionId=28100">Anime Pastel Dream - Soft</a>). This LoRA didn't come out super strong, so it has the right flexibility to get a style that's closer to Sam Yang's on AnyPastel, while still reminding of him on other models. Check the examples (mainly the model hash) to get what I mean. Triggers with <code>sam yang</code> and I suggest AnyPastel as base model (or, if you don't care about having a more matching artstyle, AnyLoRA or AbyssOrangeMix2). <strong>Use weight=1 for the offset version or 0.65 for the original (check "original" tab for a comparison)</strong>.</p><p>The pic of Melina is also using my Melina LoRA.</p><p>Pic 3 and last 4 ones (all the realistic ones) have been made by <a target="_blank" rel="ugc" href="https://civitai.com/models/10028/neverending-dream-ned?reviewId=16388&amp;modal=reviewThread">kaynite</a> using <a target="_blank" rel="ugc" href="https://civitai.com/models/10028/neverending-dream-ned">NED</a>.</p><p><br /><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight according to the instructions</strong> (by default it's <code>:1</code>)</p></li></ul><p></p>