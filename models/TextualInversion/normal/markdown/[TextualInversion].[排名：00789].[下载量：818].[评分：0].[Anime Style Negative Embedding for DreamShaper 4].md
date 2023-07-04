## Anime Style Negative Embedding for DreamShaper 4
### 一、模型概述

- 标签：`anime`, `negative`, `negative embedding`, `textual inversion`, `embedding`, `tool`
- 下载数：818
- 收藏人数：104
- 评论人数：1
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] First Release

- 统计数据
  - 发布时间：2023-03-21T08:44:10.270Z
  - 原始模型：SD 1.5
  - 下载数：765
  - 评分人数：0
  - 评分：0
- 下载地址
  - [anime-style-negative-embedding.pt](https://civitai.com/api/download/models/26608)
  - [animeStyleNegative_firstRelease_trainingData.zip](https://civitai.com/api/download/models/26608?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/42c1ab12-6d09-4414-65ab-d498457bed00/width=450/293220.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1ce0eaba-4a76-4b61-d859-0f01b8b1cb00/width=450/293231.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/68b15f8d-4b88-4af5-6239-8d4099a20a00/width=450/293230.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5332cee5-0f49-4c7f-037f-7fda4f45da00/width=450/293229.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] Actual Training Images

- 统计数据
  - 发布时间：2023-03-21T08:44:10.270Z
  - 原始模型：SD 1.5
  - 下载数：53
  - 评分人数：0
  - 评分：0
- 下载地址
  - [animeStyleNegative_actualTrainingImages_trainingData.zip](https://civitai.com/api/download/models/26609)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2fb47195-b681-4827-6e81-d0e3a9b5da00/width=450/293250.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6a014898-428d-405d-55c9-b6646f66b500/width=450/293249.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3c5205c0-14f5-456a-1790-0357d7d35f00/width=450/293248.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d8c2b356-f3b1-4fa2-3cf0-9c745356ee00/width=450/293247.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>When activating this five vector negative embedding in your negative prompt it should help you attain an anime style more easily when using the checkpoint <a rel="ugc" href="https://civitai.com/models/4384/dreamshaper">DreamShaper</a> 4. The activation word by default is "anime-style-negative-embedding", but I recommend you change the file name to whatever word you want, as the filename is the activation word.</p><p></p><p>The embedding is probably fine to use on a variety of checkpoints, but the training images were generated on the DreamShaper 4 checkpoint and the embedding was also trained on it, so that is where to expect the best results.</p><p></p><p>The training images were generated with the use of the bad-artist and bad-artist-anime negative embeddings- they are good negative embeddings.  They are at <a rel="ugc" href="https://huggingface.co/nick-x-hacker/bad-artist">this hugging face repository</a> if you want to download them. </p><p></p>