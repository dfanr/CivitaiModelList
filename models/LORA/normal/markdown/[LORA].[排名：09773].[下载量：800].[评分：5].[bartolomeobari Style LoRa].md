## bartolomeobari Style LoRa
### 一、模型概述

- 标签：`style`, `bartolomeobari`
- 下载数：800
- 收藏人数：186
- 评论人数：4
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-02T08:46:10.341Z
  - 原始模型：SD 1.5
  - 下载数：800
  - 评分人数：2
  - 评分：5
- 下载地址
  - [bartolomeobari_stylev1.safetensors](https://civitai.com/api/download/models/32982)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/372fd5dd-b448-4f36-2fd8-c608c242e200/width=450/375708.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5daa2b25-3884-4b64-b1ea-512445e6b100/width=450/375715.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ea692451-70db-46b9-d653-ad46e3cfd900/width=450/375714.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f1c06be3-0a5b-42a2-21b3-8a2203b01d00/width=450/375713.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is my first model trained for LoRa. It turned out pretty good (especially highres), considering the time spent on making the dataset.</p><p></p><p>I recommend using <em>0.6-0.8 </em>for weights, although 1 still looks decent. No trigger words are required, however you can also include <code>bartolomeobari</code> in your prompt. Trained on <a target="_blank" rel="ugc" href="https://civitai.com/models/14305/heavenorangemix">HeavenOrangeMix</a>, but other anime models should also work. It plays well with other LoRas, but weights need to be lowered otherwise the image gets fried.</p><p></p><p></p><p><em>Notes</em></p><p>The model tends to produce close-ups, so I recommend adding <code>close-up</code> to negatives. Additionally, the default face expression isn't neutral and tends towards tokens like <code>:3</code> or <code>wavy mouth</code>. Adding face expressions to your prompts or adding the above to your negative prompt should improve your generations. After I get some time to clean up the dataset and retrain the model, these problems should go away.</p>