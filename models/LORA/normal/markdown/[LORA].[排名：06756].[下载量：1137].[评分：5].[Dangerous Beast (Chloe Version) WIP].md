## Dangerous Beast (Chloe Version) WIP
### 一、模型概述

- 标签：`anime`, `clothing`, `fate \(series\)`
- 下载数：1137
- 收藏人数：312
- 评论人数：3
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v0.6

- 统计数据
  - 发布时间：2023-05-02T16:19:13.817Z
  - 原始模型：Other
  - 下载数：1137
  - 评分人数：1
  - 评分：5
- 下载地址
  - [dangerous_beast_chloe_v0.6.safetensors](https://civitai.com/api/download/models/58899)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7063a703-cc57-4d85-526d-e3395e6a8c00/width=450/664066.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b86a95a8-2031-422b-b176-d746bb0f1700/width=450/664008.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e1d4f64c-319f-44c6-73fd-d549d569af00/width=450/664178.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<p><strong>This LoRA is still a work in progress, your mileage may vary! Detailed explanation below.</strong></p><p>A variation of the "dangerous beast" outfit from Fate/Grand Order originally worn by Chloe von Einzbern in Fate/Kaleid Liner Prisma Illya.</p><p>This is a costume LoRA.</p><p>This LoRA is part of a series I'm working on, check out the others here:</p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/53083/dangerous-beast-miyu-version">Miyu version</a></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/53875/dangerous-beast-illya-version">Illya version</a></p><p></p></li></ul><h2>About the v0.6 Release</h2><p>This one gave me a lot of trouble (and still is continuing to do so). <strong>tl;dr: Messes up the belly button a lot and is somewhat overfit to the training data!</strong></p><p><br />I still wanted to publish this preliminary version however, since I have no idea when I'll be able to produce a better version than this. Adding something like "tattoo", "piercing" and/or "navel piercing" to the negative prompt may help.<br />Common issues are the o-ring turning into a piercing, the bellybutton turning out weird or multiple bellybuttons appearing (usually each having their own o-ring).</p><p>One of the most persistent issues is that the model <strong>really </strong>struggles specifically with the area framed by the o-ring (usually the bellybutton), this was worse initially but it got a lot better after I manually removed the stomach tattoo that is usually present in this area in most of the training images (which was a pain to do).</p><p>This variation (despite not being trained all that much) seems to be somewhat overfitted to the dataset, meaning that a lot of the properties that shouldn't be learned (especially style and color of the hair and eyes) may pollute your generated images. This model (and some of the ones I trained on this data afterwards) all trade between consistency of the outfit and generalization of the character features, which is annoying and made selection pretty hard. I've yet to find a "best of both worlds" model for this, so this one skews more on the consistency side.</p><p></p><p>My hunch is that this problem requires more samples and more variation among the samples to derive a more generalized and flexible model, so going forward my plan will be to take whatever images I can generate with this that look decent enough and extend my dataset using those. That might however take some time (and motivation), so I don't know how long it'll be until I manage to improve on this.</p>