## Simple - prompt with a single word
### 一、模型概述

- 标签：`girl`, `female`, `concept`, `highly detailed`, `art style`, `woman`, `artstyle`, `beautiful`, `portraits`
- 下载数：111
- 收藏人数：23
- 评论人数：0
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v0.1

- 统计数据
  - 发布时间：2023-03-29T01:32:41.525Z
  - 原始模型：SD 1.5
  - 下载数：111
  - 评分人数：1
  - 评分：5
- 下载地址
  - [simplePromptWithA_v01.safetensors](https://civitai.com/api/download/models/28273)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5186236e-a248-41d0-3a79-503f60881300/width=450/318133.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/563a7421-95aa-4407-1400-ab92efa83300/width=450/318129.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0e3eb18c-e6b5-42f6-8c1b-1c50fefe6e00/width=450/318131.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/aede5047-3291-4d8f-b78f-01a5b0c90f00/width=450/318135.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong><em>Trained so the word '1woman' is tied to a complex phrase. See the first example, prompt 'woman'</em></strong><br /><br /><strong>Trained using:</strong><br /><a target="_blank" rel="ugc" href="https://github.com/ntc-ai/conceptmod"><u>https://github.com/ntc-ai/conceptmod</u></a><br /><em>Training does not require a dataset, only words.</em><br /></p><p><strong>This model is heavily fine tuned and is not general purpose</strong>. It does not do males very well, for instance. This might not be good to add to merges as it heavily favors the word '1woman'<br /><br />Each loaded and continued training with new words:</p><ul><li><p>"high contrast++:0.2|vivid colors++:0.15|complex patterns++:0.1|motion++:0.05|action++:0.05|leading lines++:0.1|visual cues++:0.1|rule of thirds++:0.15|focal points++:0.1|@#|=high contrast, vivid colors, complex patterns, motion, action, leading lines, visual cues, rule of thirds, focal points:0.05"</p></li><li><p>'@#:0.1|=focal points on attractive face, 1woman, vivid colors, complex patterns, motion, action, leading lines, visual cues, rule of thirds:0.2|black and white--:0.05|text--:0.05|written--:0.05|focal points on attractive face, 1woman++:0.1'</p></li><li><p>'@#:0.2|=focal points on attractive face, sly grin that reaches eyes, eyes gleaming with joy, 1woman, vivid colors, complex patterns, motion, action, leading lines, visual cues, rule of thirds:0.2|black and white--:0.05|text--:0.05|written--:0.05|focal points on attractive face, 1woman++:0.1|sly grin that reaches eyes++:0.1|eyes gleaming with joy++:0.1'</p></li><li><p>"exposed pussy--:0.2|exposed tits--:0.05|1woman nipples--:0.2|1girl nipples--:0.25|excessive cleavage--:0.03|huge tits--:0.02|bare ass--:0.05|@#focal points on attractive face, sly grin that reaches eyes, eyes gleaming with joy, 1woman, vivid colors, complex patterns, motion, action, leading lines, visual cues, rule of thirds"</p></li><li><p>"@#|1woman#focal points on attractive face, sly grin that reaches eyes, eyes gleaming with joy, 1woman, vivid colors, complex patterns, motion, action, leading lines, visual cues, rule of thirds:0.1"</p></li><li><p>"@#|focal points on attractive face, sly grin that reaches eyes, eyes gleaming with joy, 1woman, vivid colors, complex patterns, motion, action, leading lines, visual cues, rule of thirds%1woman:-0.03|1woman=focal points on attractive face, sly grin that reaches eyes, eyes gleaming with joy, 1woman, vivid colors, complex patterns, motion, action, leading lines, visual cues, rule of thirds:0.1"<br /></p></li></ul><p>Technique based on <a target="_blank" rel="ugc" href="https://github.com/rohitgandikota/erasing">https://github.com/rohitgandikota/erasing</a><br />Model based on <a target="_blank" rel="ugc" href="https://civitai.com/models/13565/criarcys-fantasy-to-experience">https://civitai.com/models/13565/criarcys-fantasy-to-experience</a></p>