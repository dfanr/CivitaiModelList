## 舰娘电 / Inazuma(Kancolle) / いなづま / 電
### 一、模型概述

- 标签：`anime`, `character`, `kancolle`
- 下载数：845
- 收藏人数：174
- 评论人数：6
- 评分人数：3
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-06T07:31:37.047Z
  - 原始模型：SD 1.5
  - 下载数：845
  - 评分人数：3
  - 评分：5
- 下载地址
  - [inazuma5.safetensors](https://civitai.com/api/download/models/63702)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e432b917-8eb9-4496-a52a-84923141672d/width=450/703017.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/30c027b7-f0a6-4768-a554-448d9a4a485f/width=450/703026.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/066929db-db2c-4fd8-863a-c19f2ce0a580/width=450/703033.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0df4fe8e-988e-4b9d-9a68-d4d745751885/width=450/703019.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>问题原因找到了,是因为lora触发词会被ckpt识别成一个画面中的元素,目前解决办法就是<strong><em>不用触发词</em></strong>就能很大程度上减轻问题。触发词只替换了1girl,brown hair,brown hair，跑图的时候加上去就行</p><p></p><p>The reason for the problem has been found, which is that Lora's trigger word would be recognized as an element in the picture by the checkpoint. The current solution is<strong><em> to not use the trigger word</em></strong>, which can <strong><em>greatly alleviate the problem</em></strong>. The trigger word only replaces "1girl, brown hair, brown hair", so you can add it while running the image.</p><p></p><p>===========================================================</p><p>目前模型有一个问题,就是权重高了会出现和木桩子,并且有些模型海+人物就会出现炮或者火焰。原因我目前没有搞清楚,因为训练集里面本身就没有出现火焰或者木桩子,炮管我觉得可能是一些ckpt本身的原因.如果我之后找到更好的训练集了可能会更新训练。ckpt自带tag为：inazuma \(kancolle\)</p><p></p><p>The current model has an issue which is that if the weight is too high, it will produce pillars, and some models with sea+characters will produce cannon or fire. I have not figured out the reason yet because there is no fire or pillar in the original training set, and the reason for the cannon may be due to some aspects of the checkpoint itself. If I find a better training set in the future, I may update the training. The tag of the checkpoint is "inazuma (kancolle)".</p><p></p><p>Lora触发词是：electric \(kancolle\)</p><p>The lora trigger words is : electric \(kancolle\)</p>