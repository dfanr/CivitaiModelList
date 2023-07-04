## bad_pictures
### 一、模型概述

- 标签：`negative embedding`, `bad hands`, `style`
- 下载数：15760
- 收藏人数：1634
- 评论人数：13
- 评分人数：40
- 评分：4.95

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v3.0

- 统计数据
  - 发布时间：2023-05-09T04:02:12.683Z
  - 原始模型：SD 1.5
  - 下载数：13503
  - 评分人数：34
  - 评分：4.94
- 下载地址
  - [bad_pictures.pt](https://civitai.com/api/download/models/66043)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bdd749c7-39f8-4e09-8b32-e4f74ef1b753/width=450/732452.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c5239791-d677-487d-b71e-304f0044db6a/width=450/732454.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/972f2836-8699-40e7-9642-2624866ce30a/width=450/732455.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f3a057c9-86bc-4019-9d8c-22c68d587337/width=450/732456.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v2

- 统计数据
  - 发布时间：2023-05-09T03:12:37.061Z
  - 原始模型：SD 1.5
  - 下载数：1581
  - 评分人数：4
  - 评分：5
- 下载地址
  - [bad_pictures.pt](https://civitai.com/api/download/models/36636)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bc418aa0-9d85-42ab-58ab-1d50f0948d00/width=450/437969.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/eb0b0625-c46b-4a80-3bf5-c9d87e183300/width=450/416961.jpeg" /> |
| ---- | ---- |

#### [版本1/共3个版本] untrained

- 统计数据
  - 发布时间：2023-05-09T03:12:37.061Z
  - 原始模型：SD 1.5
  - 下载数：676
  - 评分人数：2
  - 评分：5
- 下载地址
  - [np_simple_negatives.pt](https://civitai.com/api/download/models/27684)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/73e097d0-e881-4244-5862-6a9050a6b800/width=450/353561.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d55d31a3-3b22-4b08-9b11-17b0b590ef00/width=450/314562.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f6e0b6ad-ef1a-4bc0-14b0-d5ffc17bf800/width=450/305130.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/977b5429-af8b-4085-1edc-d5254247f400/width=450/305129.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>A very versatile negative embedding that helps generate high quality images. Higher chances of producing normal looking hands in realistic images.</p><p></p><h3>Best Practices:</h3><p>Keep your token usage to below 75 for best effect. Most of the time, you don't need to add other quality specifiers to your prompts (e.g. worst quality, bad quality).</p><p></p><h3>Usage:</h3><p>Negative prompt: bad_pictures</p><p>If you notice any artifacts, you can try increasing or decreasing the weighting like this: (bad_pictures:1.1) or (bad_pictures:0.8).</p><p>Values between 0.8 and 1.2 seems to work best (clip size 2):</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/95a6d2cb-6e6b-49b8-019c-567a8a4a9000/width=525/95a6d2cb-6e6b-49b8-019c-567a8a4a9000" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8406e4d8-5964-454f-674e-3a72a621fe00/width=525/8406e4d8-5964-454f-674e-3a72a621fe00" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f8d5c7e4-8e2e-4ca7-04f0-5e35eb1b1300/width=525/f8d5c7e4-8e2e-4ca7-04f0-5e35eb1b1300" /><p></p><h3>Tested on:</h3><ul><li><p>VersaMix (<a target="_blank" rel="ugc" href="https://civitai.com/models/20865/versamix">https://civitai.com/models/20865/versamix</a>)</p></li><li><p>Lyriel (<a target="_blank" rel="ugc" href="https://civitai.com/models/22922/lyriel">https://civitai.com/models/22922/lyriel</a>)</p></li><li><p>Anything V5 (<a target="_blank" rel="ugc" href="https://civitai.com/models/9409?modelVersionId=30163">https://civitai.com/models/9409?modelVersionId=30163</a>)</p></li></ul>