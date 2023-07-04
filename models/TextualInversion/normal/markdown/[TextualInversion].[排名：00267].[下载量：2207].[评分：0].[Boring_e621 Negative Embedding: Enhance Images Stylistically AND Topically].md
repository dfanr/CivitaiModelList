## Boring_e621 Negative Embedding: Enhance Images Stylistically AND Topically
### 一、模型概述

- 标签：`negative`, `negative embedding`, `textual inversion`, `furry`, `embedding`, `tool`
- 下载数：2207
- 收藏人数：214
- 评论人数：7
- 评分人数：0
- 评分：0

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v4.0

- 统计数据
  - 发布时间：2023-07-03T13:06:52.654Z
  - 原始模型：SD 1.4
  - 下载数：1719
  - 评分人数：0
  - 评分：0
- 下载地址
  - [boring_e621_v4.pt](https://civitai.com/api/download/models/94126)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f7feae94-dbc0-46c4-8861-68938b56c676/width=450/1114352.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/44feaf23-361c-4583-b61d-54790ccae4aa/width=450/1188006.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/49e2f73c-4cbe-47fb-a369-b2f12e3d8edf/width=450/1253450.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/aeb23349-893a-4107-a585-42cceadb44ff/width=450/1114571.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v1.0

- 统计数据
  - 发布时间：2023-06-18T14:46:58.201Z
  - 原始模型：SD 1.4
  - 下载数：221
  - 评分人数：0
  - 评分：0
- 下载地址
  - [by boring_e621.pt](https://civitai.com/api/download/models/93426)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/afe88a88-9a62-47ec-b602-c191c471c290/width=450/1220197.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9c7eb66a-7bda-409d-8bf4-8fdc1bfc26d2/width=450/1188223.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fbaf0399-8b2b-4ea5-8909-4a5b799066fc/width=450/1102591.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d5e942e7-2025-45d2-beb8-745720502642/width=450/1102522.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] fluffyrock v4.0

- 统计数据
  - 发布时间：2023-07-03T12:59:23.462Z
  - 原始模型：Other
  - 下载数：267
  - 评分人数：0
  - 评分：0
- 下载地址
  - [boring_e621_fluffyrock_v4.pt](https://civitai.com/api/download/models/98798)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ae54c3cf-246b-445f-aefb-549d607c0863/width=450/1194419.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b5f6477f-665f-414c-8767-0ce8f4a19232/width=450/1250772.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/93a8c106-b565-4c55-a888-56306610c4b9/width=450/1250877.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<p>This is a download site for the negative embedding boring_e621. Its original huggingface repository, which goes into more detail about how it was trained and what it does, can be found <a target="_blank" rel="ugc" href="https://huggingface.co/FoodDesert/boring_e621">here</a>.</p><p></p><p>Briefly, This embedding attempts to capture what it means for an image to be uninteresting. So if you're using the <a target="_blank" rel="ugc" href="https://github.com/AUTOMATIC1111/stable-diffusion-webui">Automatic1111 Stable Diffusion WebUI</a>, you can place this file in stable-diffusion-webui\embeddings and add the trigger word to your NEGATIVE prompt, and your results should become more interesting, both stylistically and topically.</p><p></p><p>The title image for this model illustrates the quality improvements it can make to four simple prompts in the base SD 1.5 model. In the first column, for example, boring_e621_v4 makes the hamburger more photorealistic, places it on a cocobolo table, freshens the vegetables, and adds a slice of cheese and an order of fries.</p><p></p><p>As this embedding is known for its ability to improve furry art specifically, the second image illustrates the improvements it yields on four simple prompts on <a target="_blank" rel="ugc" href="https://huggingface.co/Doubleyobro/yiffy-e18/tree/main">YE-18</a>, a model appearing in many furry mix models.</p><p></p><p>Which version should I get?</p><ul><li><p><strong>boring_e621_v4</strong> (newest and works best with most models)</p></li><li><p>boring_e621 (works well with most models, but is less intense than v4)</p></li><li><p>boring_e621_fluffyrock_v4 (should only be used with a <a target="_blank" rel="ugc" href="https://civitai.com/models/92450">Fluffyrock</a> model WITHOUT "vpred" in the name)</p></li></ul><p></p><p>Each of the Suggested Resource models below has specifically been reported to produce great results with boring_e621 (except for Fluffyrock, which has been reported to work well with boring_e621_fluffyrock_v4 instead).</p>