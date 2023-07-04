## Bad artist Negative embedding 
### 一、模型概述

- 标签：`bad artist`
- 下载数：41060
- 收藏人数：3365
- 评论人数：10
- 评分人数：82
- 评分：4.91

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] Bad artist 

- 统计数据
  - 发布时间：2023-01-25T06:22:39.427Z
  - 原始模型：SD 1.5
  - 下载数：29926
  - 评分人数：53
  - 评分：4.92
- 下载地址
  - [By bad artist -neg.pt](https://civitai.com/api/download/models/6056)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cb4bd554-c7ed-4837-3803-8f24fa8fc900/width=450/52078.jpeg" /> |
| ---- |

#### [版本1/共2个版本] Bad artist anime 

- 统计数据
  - 发布时间：2023-01-25T06:22:39.427Z
  - 原始模型：SD 1.5
  - 下载数：11134
  - 评分人数：29
  - 评分：4.9
- 下载地址
  - [By bad artist -neg.pt](https://civitai.com/api/download/models/6057)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b1ebed82-d4e3-4213-d4dd-8b2b7696ba00/width=450/52079.jpeg" /> |
| ---- |


### 三、详情
<h3><strong>I AM NOT THE ORIGINAL CREATOR OF THIS EMBEDDING</strong></h3><p>HE IS -</p><p><a target="_blank" rel="ugc" href="https://huggingface.co/nick-x-hacker/bad-artist">https://huggingface.co/nick-x-hacker/bad-artist</a></p><p>The images above were generated with <strong>only "solo"</strong> in the positive prompt, and "sketch by bad-artist" (this embedding) in the negative.<br />The embedding uses only <strong>2 tokens</strong>.</p><p>Textual-inversion embedding for use in unconditional (negative) prompt.<br />Inspired partly by <a target="_blank" rel="ugc" href="https://huggingface.co/datasets/Nerfgun3/bad_prompt"><strong><u>https://huggingface.co/datasets/Nerfgun3/bad_prompt</u></strong></a>.</p><p>There are currently 2 version:</p><ul><li><p>'bad-artist': Not as strong, but produces pretty unique images (recommended)</p></li><li><p>'bad-artist-anime': More generic anime style (this was the first version uploaded)</p></li></ul><p>I recommend using with 'by', so for example "sketch <strong>by bad-artist</strong>", or "painting <strong>by bad-artist</strong>", or "photograph <strong>by bad-artist</strong>", etc.</p><p>Trained with 2 vectors per token for 15000 (1850x8) steps, at 500x500, on an Anything-v3-based model.</p><p>Full generation parameters for images above (using the 'bad-artist' version, not the 'bad-artist-anime' version):</p><pre><code>solo
Negative prompt: sketch by bad-artist
Steps: 15, Sampler: DPM++ 2M Karras, CFG scale: 4, Seed: 1476197242, Size: 512x640, Clip skip: 2</code></pre>