## RanburuMix
### 一、模型概述

- 标签：`clothes`, `clothing`
- 下载数：685
- 收藏人数：121
- 评论人数：1
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] A0

- 统计数据
  - 发布时间：2023-06-25T04:40:46.755Z
  - 原始模型：SD 1.5
  - 下载数：685
  - 评分人数：0
  - 评分：0
- 下载地址
  - [ranburumix_a0.safetensors](https://civitai.com/api/download/models/103465)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a0604a0a-235d-4cd0-b486-7dd4fcd448aa/width=450/1279709.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cffe2ea1-3877-4ca8-81b2-3b1a20e4c7e3/width=450/1279713.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0552886d-4f70-499d-9a63-e01d6087e1c1/width=450/1279714.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<p>Originally created Randoseru Buruma LoRA was difficult to control with t2i prompt.</p><p>I directly merged Randoseru Buruma to checkpoint for easier control with prompt.</p><p></p><p>Recommended Prompt</p><p>RAW photo, best quality, high res, 1girl solo wearing randoseru backpack and buruma and gym uniform with colored hem</p><p>Recommended Negative prompt</p><p>EasyNegative, bad-hands-5, bad_prompt_version2, ng_deepnegative_v1_75t, (gym, treadmill, weights, training machine, cardio, wokrout:2)</p><p></p><p>Refer to <a target="_blank" rel="ugc" href="https://civitai.com/models/43331?modelVersionId=94640">https://civitai.com/models/43331?modelVersionId=94640</a> and <a target="_blank" rel="ugc" href="https://civitai.com/models/6424?modelVersionId=11745">https://civitai.com/models/6424?modelVersionId=11745</a> and <a target="_blank" rel="ugc" href="https://civitai.com/models/6424?modelVersionId=11745">https://civitai.com/models/6424?modelVersionId=11745</a> for other usages.</p><p></p><p>Merge Steps</p><p>Step 1</p><p>Model A: majicmixRealistic_v6 e4a30e4607</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/43331?modelVersionId=94640">https://civitai.com/models/43331?modelVersionId=94640</a></p><p>Model B: chilloutmix_NiPrunedFp32Fix fc2511737a</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/6424?modelVersionId=11745">https://civitai.com/models/6424?modelVersionId=11745</a></p><p>Weight sum:A*(1-alpha)+B*alpha with use MBW normal alpha=0,0,0,0,0,0,0,0,0,0,0,0,0,1,1,1,1,1,1,1,1,1,1,1,1,1</p><p>Step 2</p><p>randoseruburuma_v1.0 163574cc28ff</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/90129?modelVersionId=95980">https://civitai.com/models/90129?modelVersionId=95980</a></p><p>Block Weight 0,0,1,1,1,1,0,1,1,1,0,0,0,1,1,1,0,1,1,1,1,0,0,0,0,0</p><p></p><p></p><p>ランドセルブルマLoRAの使い勝手が悪いのでモデルにマージしました。</p>