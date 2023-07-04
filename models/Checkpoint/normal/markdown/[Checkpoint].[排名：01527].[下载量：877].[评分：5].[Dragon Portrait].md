## Dragon Portrait
### 一、模型概述

- 标签：`animals`, `portaits`, `dragons`, `medieval`, `digital painting`, `fantasy art`, `fantasy`, `portraits`
- 下载数：877
- 收藏人数：270
- 评论人数：4
- 评分人数：2
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2

- 统计数据
  - 发布时间：2023-03-08T22:24:51.256Z
  - 原始模型：SD 2.1 768
  - 下载数：833
  - 评分人数：2
  - 评分：5
- 下载地址
  - [dragonPortrait_v2.safetensors](https://civitai.com/api/download/models/18201)
  - [dragonPortrait_v2.yaml](https://civitai.com/api/download/models/18201?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b2c82b3f-a7c4-4791-54e3-dd1b67846b00/width=450/187490.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/08400966-bb34-4326-3047-983b6df79300/width=450/187337.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7ebf8a13-51c4-4751-c11f-828e6cbbd400/width=450/187489.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0e366c82-d7e7-4194-8bc3-72e571a22c00/width=450/187488.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1

- 统计数据
  - 发布时间：2023-03-08T22:24:51.256Z
  - 原始模型：SD 2.1 768
  - 下载数：44
  - 评分人数：0
  - 评分：0
- 下载地址
  - [dragonPortrait_v1.safetensors](https://civitai.com/api/download/models/18202)
  - [dragonPortrait_v1.yaml](https://civitai.com/api/download/models/18202?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ccad6395-61f6-422f-3587-48e727172000/width=450/187343.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/394e75e8-3f3b-4263-057b-8c5b6b3ec500/width=450/187342.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/038299ad-df9c-49f0-f1c8-31e967764e00/width=450/187341.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ae567a3-55b0-407c-e401-614ab40ca200/width=450/187340.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><em>"You see, most places have waifus or lightly dressed girls. We have... dragons!"</em></p><p>A model trained specifically on modern portrait paintings of European dragons, based on around 80 hand-picked high quality digital art paintings from various communities. Artist names are not included in the caption to enforce a more generic art style.</p><p></p><p>The model is more or less an accident created from a failed attempt to train a more generic dragon model to improve the goofy default look of Stable Diffusion dragons, which still gave pretty bad results... except for portraits!</p><p></p><p>Since the model was trained using a slightly modified version of EveryDream2trainer, there's no real key word. The closest equivalent would be "dragon portrait", though the caption template also includes "head (shot) painting of a dragon" for better generalization.</p><p></p><p>The typical prompt roughly has a pattern like this:</p><p><strong>&lt;art style&gt; </strong>portrait <strong>&lt;art style&gt; </strong>of a <strong>&lt;mood&gt; &lt;color&gt;<em> </em></strong>dragon, <strong>&lt;feature 1 description&gt;</strong>, <strong>&lt;feature 2 description&gt;, &lt;feature n description&gt;,</strong> <strong>&lt;backround description&gt;</strong></p><p></p><p>Example prompts:</p><ul><li><p>digital portrait painting of an elegant cave dragon, open mouth, detailed bio-luminescent scales, emitting magic glow, in a dark gem cave</p></li><li><p>watercolor portrait of a cute colorful rainbow dragon, rain drops in the background</p></li><li><p>portrait statue of a dragon goddess from ancient egypt, ornate gold, egyptian ruins in the background</p></li><li><p>ancient roman mosaic portrait of an elegant dragon</p></li><li><p>head painting of a raging red dragon engulfed in flames, a burned village covered in ashes in the background</p></li></ul><p></p><p>For better consistency, all faces are facing to the right, since this is the direction that most of the training images use. You may want to flip the results manually if you want them to face the other direction.</p><p></p><p>TIs like <a target="_blank" rel="ugc" href="https://civitai.com/models/3093/midjourney-general-style">Midjourney style</a> seem to work fairly well and can enhance the results, but more experimentation is needed.</p>