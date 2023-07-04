## CopperMix_γ
### 一、模型概述

- 标签：`anime`, `girl`, `style`, `cute`
- 下载数：882
- 收藏人数：321
- 评论人数：4
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] CopperMix_γ

- 统计数据
  - 发布时间：2023-03-03T09:23:38.224Z
  - 原始模型：Other
  - 下载数：882
  - 评分人数：2
  - 评分：5
- 下载地址
  - [coppermix_.safetensors](https://civitai.com/api/download/models/17916)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/141d2df3-882b-475d-e896-b2a7d61f9100/width=450/183383.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/32f0fd65-6acb-4b29-41da-d3ba9b6ab000/width=450/183388.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5a60091c-1c03-46fe-f581-3165597f4700/width=450/183387.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d2523c8d-6fc2-422d-1c0d-8f435b208800/width=450/183386.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>CopperMix是一个模型混合计划</p><p>这个计划最初的想法就是想要做出一个不需要很复杂的prompt就能能让角色看起来更加娇小模型</p><p>本模型基于CopperMixβ调整后发布</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/13362/coppermixb">https://civitai.com/models/13362/coppermixb</a></p><p>虽然是排在β后面的γ,但是我觉得这个不能算是迭代关系,更像是一个分支版本</p><p>这个版本的特点是保留了一部分β画风同时改善了β部分场景过曝的问题,并且改良了背景细节(大概)</p><h2>融合配方</h2><p>块权重融合MBW:</p><p>A:Night Sky YOZORA|<a target="_blank" rel="ugc" href="https://civitai.com/models/12262/night-sky-yozora-style-model">https://civitai.com/models/12262/night-sky-yozora-style-model</a></p><p>B:CopperMixβ|<a target="_blank" rel="ugc" href="https://civitai.com/models/13362/coppermixb">https://civitai.com/models/13362/coppermixb</a></p><p>1,0.9,0.7,0.5,0.3,0.1,1,1,1,1,1,1,0,1,1,1,1,1,1,0.1,0.3,0.5,0.7,0.9,1</p><p>alpha:0.75</p><h2>使用推荐</h2><p>用橙子系的(worst quality, low quality :1.4)来抑制效果也不错<br />同时也推荐试试用EasyNegative放在抑制中使用<a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative">https://</a><a target="_blank" rel="ugc" href="http://civitai.com/models/7808/easynegative">civitai.com/models/7808/easynegative</a></p><p>VAE推荐挂载通用VAE(即Animate.vae)</p>