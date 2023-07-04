## Nixeu Style LoRA
### 一、模型概述

- 标签：`anime`, `girl`, `sexy`, `female`, `character art`, `highly detailed`, `nixeu`, `splatoon`, `style`, `art style`, `woman`, `illustration`, `artstyle`, `beautiful`, `girls`, `portraits`
- 下载数：4641
- 收藏人数：1037
- 评论人数：10
- 评分人数：6
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] offset

- 统计数据
  - 发布时间：2023-05-17T12:01:13.527Z
  - 原始模型：SD 1.5
  - 下载数：4382
  - 评分人数：4
  - 评分：5
- 下载地址
  - [nixeu_offset.safetensors](https://civitai.com/api/download/models/5890)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/95e49bd1-3026-4489-0d6d-b3f8657b3f00/width=450/49598.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/732fef72-7b0f-4a39-b2c4-5dd4b04e3885/width=450/816647.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9e1e2661-1772-4d9c-f31d-4ecf03240400/width=450/49614.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/aa6120a9-1f5c-4b90-b665-6d08d6fb9800/width=450/49600.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] offset 64 dim

- 统计数据
  - 发布时间：2023-05-17T12:01:13.527Z
  - 原始模型：SD 1.5
  - 下载数：143
  - 评分人数：2
  - 评分：5
- 下载地址
  - [nixeu_offset64dim.safetensors](https://civitai.com/api/download/models/73181)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/017f1e82-0377-4350-8c10-6b4a2a456b59/width=450/816668.jpeg" /> |
| ---- |

#### [版本1/共3个版本] original

- 统计数据
  - 发布时间：2023-05-17T12:01:13.527Z
  - 原始模型：SD 1.5
  - 下载数：116
  - 评分人数：0
  - 评分：0
- 下载地址
  - [nixeu-epoch-000100.safetensors](https://civitai.com/api/download/models/73160)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/40780eef-f657-4300-8236-9bdc82b77cdf/width=450/816629.jpeg" /> |
| ---- |


### 三、详情
<h2>Nixeu style LoRA</h2><p><strong>Making models can be expensive. Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong></p><p><br />I made this a while ago to fulfill a request on the Project AI discord. It doesn't imitate Nixeu's stile perfectly, so I think it's transformative enough. Still it's an interesting LoRA. <br /><br />Activation is simply <code>nixeu</code>. I suggest weight 1 for the offset version (0.6 for the old one).<br />If you add tags like <code>artist name</code> you can also have it add the signature (with funny spelling usually). If you don't want that, just put it in the negative prompt. LoRA's are kind of made to overfit, so it's kind of expected as this author puts the signature everywhere.</p><p></p><p><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight</strong> (by default it's <code>:1</code> which is usually too high)</p></li></ul>