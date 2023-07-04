## Kylie Minogue (90s)
### 一、模型概述

- 标签：`girl`, `person`, `singer`, `female`, `textual inversion`, `woman`, `90s`, `actress`, `celebrity`, `embedding`, `girls`, `real person`, `women`, `australian`, `princess of pop`, `pop`, `classic beauties`, `kylie minogue`
- 下载数：1373
- 收藏人数：128
- 评论人数：19
- 评分人数：3
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v2.0

- 统计数据
  - 发布时间：2023-06-16T15:06:58.356Z
  - 原始模型：SD 1.5
  - 下载数：793
  - 评分人数：2
  - 评分：5
- 下载地址
  - [t3stkyli3.pt](https://civitai.com/api/download/models/75347)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4e1f57b7-5f9f-4407-a408-ebfd5c272c11/width=450/842675.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/48edc2dc-a185-4d52-a7d0-3688304f804d/width=450/842694.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ccf7e1b-e872-47a1-af17-95e475d2f4b0/width=450/842687.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/02eec04d-618b-420f-aa1a-93bbac0281a5/width=450/842693.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v1.0

- 统计数据
  - 发布时间：2023-06-16T15:06:58.356Z
  - 原始模型：SD 1.5
  - 下载数：455
  - 评分人数：1
  - 评分：5
- 下载地址
  - [y0ungkyli3.pt](https://civitai.com/api/download/models/72687)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a7d49da1-c5a2-43a6-9868-b2ec49b2045b/width=450/811176.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3f926c96-effa-4ca8-ab15-8da0ab3afd0f/width=450/811177.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d363d29d-9977-4986-950e-a648283046c3/width=450/811178.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1f5f4d2f-d253-438a-8230-928b29f4f663/width=450/811179.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v0.1

- 统计数据
  - 发布时间：2023-06-16T15:06:58.356Z
  - 原始模型：SD 1.5
  - 下载数：125
  - 评分人数：0
  - 评分：0
- 下载地址
  - [y0ungkyli3.pt](https://civitai.com/api/download/models/72612)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9a5789f5-ab77-4610-b237-5391a8150ab8/width=450/810481.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0556a894-803d-4ec8-8744-0ce45fe72775/width=450/810482.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/608f52b3-cd25-475e-808c-4b928dfe2ebd/width=450/810483.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e46df7af-f1c2-479a-8d7f-eab9f3db8252/width=450/810490.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><a target="_blank" rel="ugc" href="https://www.instagram.com/kylieminogue/">Kylie Minogue</a> is an Australian singer and actress who rose to stardom already in the late 80s. She's often referred to as the <em>Princess of Pop</em> and is one of the best selling artists of all time. With this embedding I'm trying to capture her looks in the late 80s and <a target="_blank" rel="ugc" href="https://kylieforeverandever.tumblr.com/post/615643553436254208/kylie-minogue">early 90s</a> era.</p><p><strong>Updated</strong>: So... I was having a look at my <a target="_blank" rel="ugc" href="https://civitai.com/models/11054/tiffany-keller-instagram-model">Tiffany Keller </a>TI, one of the first I published on this site, and I was a bit amazed at how good it still looked. I ran a few tests and man, even if there are some issues (I still upscaled the pics for my dataset back then, and it shows in a little bit of saturation and some slight problems with the eyes)... almost every image I generated with that TI looked awesome, to be honest. I wondered why... What was the main difference compared to my current embeddings? The only possible answer was the vector strength, which in Tiffany's TI case was of 0.198. The perfect vector strength, basically. But how did I manage such vector strength with only 1500 steps, I asked myself... Well, again, there was only one possible answer: the learning rate was way different back then. It was a flexible one and, apparently, it quickly pushed the vector strength much higher than my most recent settings do.</p><p>So I decided to try to apply<a target="_blank" rel="ugc" href="https://imgur.com/a/gPQ1R5D"> that learning rate</a> to Kylie and stop the training process at 1500 steps. Vector strength is slightly over 0.2, but yeah... the results look great, in my opinion, so I'm probably sticking to this new process from now on. :)</p><p>Appreciate my work? My TIs are free, but you can always <a target="_blank" rel="ugc" href="https://www.buymeacoffee.com/jernaugurgeh">buy me a coffee</a>. :)</p><p>Curious about my work process? I have summarized it <a target="_blank" rel="ugc" href="https://civitai.com/models/56570/renata-valliulina?commentId=118383&amp;modal=commentThread">here</a>.</p><h2>How to create a good prompt using my TIs</h2><p>You're obviously free to experiment, but bear in mind that my TIs are trained with a more or less fixed phrasing, that normally starts with:</p><p>"photo of EMBEDDING_NAME, a woman"</p><p>So I recommend always starting your prompt like that and then building the rest of the prompt from there. For instance, "photo of (t3stkyli3:0.99), a woman, RAW, close portrait photo, long brown coat, (turtleneck sweater:1.2), trousers, curly hair, (high detailed skin:1.2), 8k uhd, dslr, soft lighting, high quality, film grain, Fujifilm XT3 sharp focus, f 5.6"</p>