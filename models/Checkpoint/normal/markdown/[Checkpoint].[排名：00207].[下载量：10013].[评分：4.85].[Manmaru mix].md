## Manmaru mix
### 一、模型概述

- 标签：`style`
- 下载数：10013
- 收藏人数：2586
- 评论人数：8
- 评分人数：27
- 评分：4.85

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-08T15:19:57.416Z
  - 原始模型：SD 1.5
  - 下载数：10013
  - 评分人数：27
  - 评分：4.85
- 下载地址
  - [manmaruMix_v10.safetensors](https://civitai.com/api/download/models/91735)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3979e187-2604-4bd5-abcf-c791d9e8712c/width=450/1072657.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bef3c984-5ac6-42c1-a775-0451fcd0d233/width=450/1072845.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/29910488-84fd-4b81-8ccb-93e214b1e323/width=450/1086942.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b5463d02-0f2f-4361-b0d0-3210cc412d72/width=450/1100125.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><span style="color:rgb(193, 194, 197)">I don't speak English so I'm translating at DeepL. Let me know if the English is weird.</span></p><p></p><p>This model was adjusted so that the hand-drawn look would fade and the background<br />would come out clearly, while keeping the characterization of the Thumbelina Model.</p><p></p><p>このモデルはThumbelina Modelのキャラデをそのままに、<br />手描き感を薄くし、背景がくっきり出るように調整しました。</p><p></p><p><strong>Tips / 参考</strong></p><p>This model works well with LoRA, which enlarges the eyes. (e.g.<strong> </strong><a target="_blank" rel="ugc" href="https://huggingface.co/2vXpSwA7/iroiro-lora">bigeye</a>)<br />目を大きくするLoRAと相性がいいです。(例：<a target="_blank" rel="ugc" href="https://huggingface.co/2vXpSwA7/iroiro-lora">bigeye</a>)</p><p></p><p><strong>Merging Method / マージ方法</strong></p><ol><li><p>A:Thumbelina_v20.safetensors<br />B:nostalgiaMix_nostalgia.safetensors<br />Sum Merge : -0.6 (THIS IS "minus"!! マイナスです！！)<br />　-&gt;tmp.safetensors</p></li><li><p>A:flat2DAnimerge_v20.safetensors<br />B:tmp.safetensors<br />C:featurelessMix_v10.safetensors<br />MBW:<br />　alpha:0.25,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5<br />　beta:0.5,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0</p></li></ol><p></p><p><strong>Origin of the model name / モデル名の由来</strong></p><p>"manmaru" = "まん丸", means "perfectly round".<br />Because the eye shape output by this model is round.</p><p>このモデルで出力される目の形がまん丸なので、"manmaru"。</p>