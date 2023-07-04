## Akira Toriyama Style LoRA
### 一、模型概述

- 标签：`anime`, `digital art`, `manga`, `dragon quest`, `chrono trigger`, `dragon ball`, `akira toriyama`, `style`, `art style`, `illustration`
- 下载数：8084
- 收藏人数：1502
- 评论人数：27
- 评分人数：13
- 评分：4.92

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] toriyama_akira_3

- 统计数据
  - 发布时间：2023-03-17T08:02:07.194Z
  - 原始模型：SD 1.5
  - 下载数：7402
  - 评分人数：11
  - 评分：4.91
- 下载地址
  - [toriyama_akira_3.safetensors](https://civitai.com/api/download/models/5737)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d92cc8d6-edf6-4612-ea42-719ccec65800/width=450/47117.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3b3a19ab-7a1b-483e-3aa1-f850422ebb00/width=450/47116.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d60bb60e-05d6-4a9c-7204-480160612a00/width=450/47115.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1855d5e4-7fee-4d62-01be-6e25e9c54f00/width=450/47113.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] toriyama_akira_1

- 统计数据
  - 发布时间：2023-03-17T08:02:07.194Z
  - 原始模型：SD 1.5
  - 下载数：452
  - 评分人数：2
  - 评分：5
- 下载地址
  - [toriyama_akira-000040.safetensors](https://civitai.com/api/download/models/5585)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b98573d0-28f9-4795-dd47-50d49ce9f600/width=450/44812.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c76c987b-e9b7-45fd-7241-dc8b5fb08900/width=450/44809.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a02ffc55-f7a1-4274-f096-55f2743aca00/width=450/44810.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8e3b78ab-b639-411b-fdfa-ae486eb6fb00/width=450/44811.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] toriyama_akira_2

- 统计数据
  - 发布时间：2023-03-17T08:02:07.194Z
  - 原始模型：SD 1.5
  - 下载数：230
  - 评分人数：0
  - 评分：0
- 下载地址
  - [toriyama_akira_2.safetensors](https://civitai.com/api/download/models/5623)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2de5fc85-043d-4750-2d33-5593e06baa00/width=450/45374.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1d540d22-cbe4-4c22-4f00-418795b6d400/width=450/45340.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c56d94be-b942-4dba-dd36-7bf4ece09400/width=450/45336.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/885fa760-ca4f-4ea0-1524-1ad3d6eb6400/width=450/45335.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2><strong>Akira Toriyama style LoRA</strong></h2><p><strong>Making models can be expensive. Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong></p><p>Triggers with <code>toriyama akira</code>. I suggest weight above 0.5. <br />I've uploaded the 60 epoch and 40 epoch version. Both can work depending on the model and the desired strength.</p><p>Also I've found it gives usually better results with CLIP skip 2 (except the first image, maybe that was lucky).</p><p>This is trained on Anything v4.5, so use that or AbyssOrangeMix2 if you want accurate results. Other models may still work. <br /><br />A big difference from my other LoRA's is that this one basically requires highres fix at least at 1.5-2x size.</p><p>Keep in mind <strong>this is LoRA</strong>, so you need to use it as such. It's not a standalone model and it's not a TI. <br /><br /><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight</strong> (by default it's <code>:1</code> which is usually too high)</p></li></ul><p></p>