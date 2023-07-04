## coloring-book
### 一、模型概述

- 标签：`lineart`, `vector`, `draw style`, `coloringbook`, `coloring book`
- 下载数：3418
- 收藏人数：667
- 评论人数：12
- 评分人数：6
- 评分：4.67

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] coloring-book

- 统计数据
  - 发布时间：2023-01-24T14:25:17.949Z
  - 原始模型：SD 2.1 768
  - 下载数：3418
  - 评分人数：6
  - 评分：4.67
- 下载地址
  - [coloringBook_coloringBook.ckpt](https://civitai.com/api/download/models/5978)
  - [coloringBook_coloringBook.yaml](https://civitai.com/api/download/models/5978?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a9a5b5f4-6fb5-43b7-bb60-111bef44b200/width=450/50959.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2a116adc-40b5-4893-94b5-09d101455c00/width=450/50970.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f3fa5457-9bbe-4685-99d4-515003963000/width=450/50969.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5a80db51-49dd-428a-be9a-5712033dc200/width=450/50968.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>About model</strong><br />A simple model trained on a custom dataset containing over 100 coloring book type images.</p><p>If you enjoy this model and would like me to improve on it, <a target="_blank" rel="ugc" href="https://www.buymeacoffee.com/mrhup">buy me a coffe </a>☕</p><p><br /><strong>Installation:</strong></p><p>Download both the ckpt and yaml files. Ensure that the same naming pattern is used and copy them under models/Stable-Diffusion path in your local/cloud SD installation. Stable Diffusion 2.1 is required for the model to work correctly.<br /></p><p><strong>Black images issue:</strong></p><p>2.1 models need to have a web-ui config modified - if you are getting <strong>black images </strong>- go to your config file and add to COMMANDLINE_ARGS= <code>--no-half</code> - potentially it could work with <code>--xformers</code> instead (if supported). This line might slow your generations a bit but will not affect negatively your output.</p><p></p><p><strong>Prompt suggestion:</strong></p><p><code>bichon havanese wearing sunglasses COLR_001, (((white background))), coloring book, line art, high resolution, black and white, colorless</code></p><p>Negative: <code>((watermark)), (text), color, shading, gradient, shadows, transparency, noisy, blurred</code></p>