## 晖映 Enhanced Backlighting
### 一、模型概述

- 标签：`lighting`, `background`, `backlighting`
- 下载数：5107
- 收藏人数：1117
- 评论人数：15
- 评分人数：12
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-07T14:21:09.807Z
  - 原始模型：SD 1.5
  - 下载数：5107
  - 评分人数：12
  - 评分：5
- 下载地址
  - [backlighting.safetensors](https://civitai.com/api/download/models/39164)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7e30c8d2-8800-4d80-69f6-0b18033f2900/width=450/434169.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9bfbfb9a-6c51-474b-130d-cc231be56b00/width=450/434170.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7782350c-0f74-42ed-9b97-6c4712be9400/width=450/433624.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9d6bc412-d372-4026-342e-4c7ad2af3d00/width=450/433596.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>晖映 Enhanced Backlighting</h1><p>[Eng ver below]</p><p>这是一个用来改善逆光侧光环境光照效果的Lora，许多模型的noise_offset未经调整，会导致画面整体亮度过于均衡，显得没有暗区重点或者摄影反光效果，尤其是二次元类model，即使是给出了backlighting的prompt，人物依然会显得亮度和环境保持一致，缺乏重点的突出，显得画面色调很”平“，这个LORA特意加深了对比度来改善这个问题，对于二三次元的模型都有自然光的照射改善效果。</p><ul><li><p><strong>特别提示</strong>：由于trigger word忘记区分，使用backlighting这个prompt会比较重的加深对比和自然光效，如果你不喜欢这种风格，可以尝试去掉它并改变Lora的权重，可以得到一些较轻的效果。计划在后续版本里通过特殊关键字解决这个问题。</p></li><li><p><strong>特别提示2</strong>：这个Lora针对丁达尔现象也有不错的效果，甚至可以在二次元模型中搭配另外一个尚在完善中的Lora模拟出来。即Komorebi 日语(<em>木漏</em>れ日)，效果请见例图。待测试完善后会择机发布的。</p></li><li><p><strong>特别提示3</strong>：Lora的权重和CFG高低都会影响阳光的效果，如果不希望画面出现太多夕阳余晖的感觉，可以通过提示词改善或者降低权重或CFG</p></li></ul><p>对比效果如下：</p><p></p><p>提示词均为1girl,backlighting</p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9fd066fa-982f-43dd-37a3-490d32da9500/width=525/9fd066fa-982f-43dd-37a3-490d32da9500.jpeg" /><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/faf9c2e2-4920-46fd-6386-de7795d5ea00/width=525/faf9c2e2-4920-46fd-6386-de7795d5ea00.jpeg" /><p>Enhanced Backlighting is a Lora used to improve the backlighting and sidelighting effects in environments with strong lighting contrast. Many models have not adjusted their noise_offset, which can result in an overly balanced overall brightness and a lack of emphasis on dark areas or photographic reflection effects, especially for 2D models. Even when the prompt for backlighting is given, the character still appears to have the same brightness as the environment, lacking a prominent highlight and making the image appear very "flat" in tone. This LORA intentionally deepens the contrast to improve this problem and has a natural light illumination improvement effect for both 2D and 3D models.</p><ul><li><p><strong>Special Note</strong>: Due to forgetting to distinguish the trigger word, using the prompt 'backlighting' will heavily increase the contrast and natural light effect. If you don't like this style, you can try removing it and changing the weight of Lora to achieve a lighter effect. We plan to solve this problem through special keywords in future versions.</p></li><li><p><strong>Special Note 2</strong>: This Lora has a good effect on the Ding Darr phenomenon, and can even be combined with another Lora, which is still under development, to simulate the effect of 'Komorebi' in Japanese (sunlight filtering through trees) for 2D models. Please refer to the example image for the effect. It will be released after testing and improvement.</p></li><li><p><strong>Special Note 3</strong>: The weight and CFG of Lora will affect the effect of sunshine. If you don't want the screen to have too much sunset glow, you can improve or lower the weight or CFG through prompt words.</p></li></ul><p>The comparison effect is as upside img.</p><p>The prompt words are '1girl' and 'backlighting'.</p>