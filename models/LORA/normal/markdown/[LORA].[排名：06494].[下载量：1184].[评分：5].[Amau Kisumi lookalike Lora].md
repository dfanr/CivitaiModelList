## Amau Kisumi lookalike Lora
### 一、模型概述

- 标签：`female`, `idol`, `woman`, `cute`, `girls`, `japanese`, `girl，`
- 下载数：1184
- 收藏人数：250
- 评论人数：0
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-15T22:32:22.785Z
  - 原始模型：SD 1.5
  - 下载数：1184
  - 评分人数：2
  - 评分：5
- 下载地址
  - [amaukisumi-v4.safetensors](https://civitai.com/api/download/models/46741)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d3acedd1-51ff-4d21-1992-a89039562c00/width=450/505253.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d60bef5e-8c69-4615-6c5d-6e7d5fe75700/width=450/505260.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5dd531d5-85f9-4dcb-76dc-20f7842a8700/width=450/505294.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<p>This is my first upload of a Lora I trained after getting into SD and subsequently Lora training. So I am pretty new at this. Feedbacks welcome.</p><p></p><p>Some details on the Lora settings:</p><p>Trained with around 137 photos of Amau Kisumi, a popular Japanese idol. Photos are all publicly available on her Twitter site, please support and follow her -&gt; <a target="_blank" rel="ugc" href="https://twitter.com/amau_kisumi">https://twitter.com/amau_kisumi</a></p><p>Kohya Trainer</p><ul><li><p>Base Model: chilloutmix</p></li><li><p>Network dim/alpha: 32/16</p></li><li><p>learning_rate: 1e-4</p></li><li><p>text_encoder_lr: 5e-5</p></li><li><p>lr_scheduler: constant</p></li><li><p>train_batch: 6</p></li><li><p>num_epochs: 15 (but I took epochs #12 after several testing)</p></li><li><p>steps: 15</p></li></ul><p>Most of the parameters I just follow by reading a combination of a few guides. If you have any wisdom to share, please do.</p><p></p><p>To use please:</p><p>&lt;lora:amaukisumi-v4:0.8&gt; or &lt;lora:amaukisumi-v4:1&gt; amaukisumi</p><p>I found best results between 0.8 and 1.0, works best with chilloutmix.</p><p>But due to most of her photos being gravure, you may supress NSFW by putting in Negative prompts like "lingerie, nude, naked", and specify clothes style in Positive Prompts.</p><p>Also her chest might be a bit on big side, so put like (small perfectly shaped breast)</p><p></p>