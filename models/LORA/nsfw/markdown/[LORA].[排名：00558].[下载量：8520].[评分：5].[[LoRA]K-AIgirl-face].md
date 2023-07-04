## [LoRA]K-AIgirl-face
### 一、模型概述

- 标签：`{1girl}`
- 下载数：8520
- 收藏人数：1555
- 评论人数：9
- 评分人数：4
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] K-AIgirl-face2

- 统计数据
  - 发布时间：2023-03-31T10:54:57.362Z
  - 原始模型：SD 1.5
  - 下载数：7278
  - 评分人数：3
  - 评分：5
- 下载地址
  - [K-AIgirl-face2.safetensors](https://civitai.com/api/download/models/31715)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5e58d8e6-1fd3-4024-3a70-3088b612e000/width=450/360998.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9be619c3-c3f9-4b54-6a7e-2df5fc701e00/width=450/361004.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/257b3f17-2d42-4ef0-6ed7-c03d9e372c00/width=450/361003.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f9bf0bb2-82eb-4085-28dc-259b64a35d00/width=450/361002.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] K-AIgirl-face-re

- 统计数据
  - 发布时间：2023-03-31T10:54:57.362Z
  - 原始模型：SD 1.5
  - 下载数：609
  - 评分人数：0
  - 评分：0
- 下载地址
  - [K-AIgirl-face-re.safetensors](https://civitai.com/api/download/models/31716)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6efc90a1-ae54-4931-ce77-5e866c7ff300/width=450/361005.jpeg" /> |
| ---- |

#### [版本1/共3个版本] NEVON

- 统计数据
  - 发布时间：2023-03-31T10:54:57.362Z
  - 原始模型：SD 1.5
  - 下载数：633
  - 评分人数：1
  - 评分：5
- 下载地址
  - [nevon.safetensors](https://civitai.com/api/download/models/32435)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7327a0f4-1d30-42b6-2345-03abe176a400/width=450/369600.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0b138cbf-384f-4b77-6ccc-ff661580fa00/width=450/369599.jpeg" /> |
| ---- | ---- |


### 三、详情
<p>也算兑现承诺了吧，把我早期训练并使用的lora分享给大家。</p><p></p><p>基于schoolmax 2.5d训练，后来我对比了一下这个模型和0.5chillout+0.5AOM2的完美世界基本上区别很小，</p><p>所以可以认为是基于chill训练的，但是schoolmax 2.5d颜色比较舒服一点。</p><p></p><p>这个模型对于脸部权重的修正比较中性（但拉高权重还是改变挺大的，所以不是欠拟合），因为我不是拿特定脸训练的，而是从生成结果里选择了一些自己觉得好看的图片进行二次训练。</p><p></p><p>样本数量从70到1300都有，但是1300的大样本（K-AIgirl-face）训练不是很成功，反而是低分辨率小样本的K-AIgirl-face2效果比较好，K-AIgirl-face3则有比较大的偏色问题，过拟合情况比较严重。</p><p></p><p>推荐用法：</p><p>0.2 K-AIgirl-face-re/K-AIgirl-face2</p><p>+</p><p>0.2 koreanDollLikeness_v15</p><p>作为基底，配合chilloutmix，可以大大改善生成人物的脸型和脸部背光的问题，对于其他lora的兼容也很好。</p><p>甚至可以把这两个lora融到大模型里面，毕竟lora用多了速度损失实在太大。</p><p></p><p></p><p></p><p></p><p></p><p></p>