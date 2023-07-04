## ProtogEmb 2 (for SD 2.x 768)
### 一、模型概述

- 标签：`digital art`, `protogen`, `digital painting`, `style`, `digital illustration`, `embedding`
- 下载数：1373
- 收藏人数：178
- 评论人数：1
- 评分人数：3
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] ProtogEmb 2.0

- 统计数据
  - 发布时间：2023-01-19T07:16:43.321Z
  - 原始模型：SD 2.1 768
  - 下载数：1373
  - 评分人数：3
  - 评分：5
- 下载地址
  - [protogemb2.pt](https://civitai.com/api/download/models/5510)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a7b7051a-767c-4a11-7f3e-7433b6cff600/width=450/43920.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2b729db9-b567-4bc4-264d-4185f8470600/width=450/43930.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c780218e-8802-4adb-7329-5f2d4662f500/width=450/43929.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/83d167b0-bd27-44f8-2a04-d2c4ebb23c00/width=450/43928.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Same idea as the original ProtogEmb but retrained from scratch on <strong>SD 2.1 768</strong> version.</p><p>Since the training images were higher quality it can output much more detailed pictures, I also expanded the base images for training from 67 to 92, all generated using <strong>Protogen 2.2/3.4 by Darkstorm2150 </strong></p><p></p><p><strong>HOW TO USE</strong></p><p>just drop it into your "embeddings" folder and type the name of the file in your prompt, you can also rename it to whatever you want and use that as the trigger.</p><p>Unlike most of SD 2.x <strong>you don't need a ton of negative prompts for it to look nice</strong>, I personally like to add "cartoon, 3d" to the negatives as the results end up looking higher fidelity.</p><p></p><p><strong>HOW WAS IT MADE?</strong></p><p>The images used to train it were from Protogen 2.2 and 3.4 using the base prompt darkstorm2150<strong> </strong>used for the showcase images of the original models.</p><p>For this updated embedding I started by training a base in 1500 steps, then further bursts of 100 steps switching the datasets to focus and enhance any part I felt was lacking.</p><p></p><p><strong>SPECS</strong></p><p>8 vectors per token, 4000 steps, 92 base images (which were switched around for focused training), batch size of 4, prompt template being either style_filewords or a custom one which I edited according to what was the focus of the training, shuffle tags enabled, learning rate from 0.005 for general training to 0.0001 to focused training.</p>