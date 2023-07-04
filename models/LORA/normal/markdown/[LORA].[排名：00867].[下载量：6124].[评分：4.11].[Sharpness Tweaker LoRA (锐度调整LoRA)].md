## Sharpness Tweaker LoRA (锐度调整LoRA)
### 一、模型概述

- 标签：`style`
- 下载数：6124
- 收藏人数：923
- 评论人数：5
- 评分人数：9
- 评分：4.11

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v3.0

- 统计数据
  - 发布时间：2023-05-20T17:21:23.231Z
  - 原始模型：SD 1.5
  - 下载数：4274
  - 评分人数：4
  - 评分：4.75
- 下载地址
  - [add_sharpness.safetensors](https://civitai.com/api/download/models/76092)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8299cfa5-2121-482e-9c82-0d6bee29abe3/width=450/851665.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/feb31bd4-6df9-44fb-9b32-1652736560d3/width=450/851628.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b6127d88-c80d-41ed-9d4d-0edc04d547b0/width=450/851626.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0107b32d-2ba7-4f2d-916c-4306b8c98f1f/width=450/851635.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v2.0

- 统计数据
  - 发布时间：2023-05-20T17:18:09.370Z
  - 原始模型：SD 1.5
  - 下载数：867
  - 评分人数：3
  - 评分：3
- 下载地址
  - [sharpness.safetensors](https://civitai.com/api/download/models/74273)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/06a0e00e-1b4b-44d1-b1e4-2b3b1361290a/width=450/830082.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/866148dd-8de1-4642-9c2c-1f5a77a07d2a/width=450/830083.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d38a584b-3c1e-40ee-9b04-13b4a6d21d7e/width=450/833231.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e61f53b7-5168-4d65-a450-d618e879342b/width=450/833216.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v1.0

- 统计数据
  - 发布时间：2023-05-20T17:18:09.370Z
  - 原始模型：SD 1.5
  - 下载数：983
  - 评分人数：2
  - 评分：4.5
- 下载地址
  - [sharpening_tool.safetensors](https://civitai.com/api/download/models/73944)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7680cf9e-fbab-4cd4-9671-cf46a0b9fcc3/width=450/825922.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cce9ea00-fd56-46a2-a8d8-4c001259170a/width=450/826174.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e5cf67ee-f6f6-49df-bb8c-99d359764589/width=450/826253.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<p>特殊用法：</p><p><strong><u>1. 你可以试着把权重设为负数（降锐化），然后拉高CFG Scale。这样效果可能要略好于直接锐化</u></strong></p><p>2. 二次元模型一般不需要锐化，但可能会用到降锐化</p><p></p><p>【中文】</p><p>完全自由的锐度调节工具！</p><p>有3个版本，不过最推荐v3.0，因为它可以胜任的权重范围最广，但可能只有在高权重下才有明显效果</p><p>v3.0推荐权重：-2.0~2.0，权重越高，锐化就越强。负数则是使图像变平滑</p><p></p><p>【English】</p><p>A powerful sharpness tweaker!</p><p>There are 3 verisons for you to choose, but I suggest the v3.0 most since it is suitable for wide weight ranges (It may only work at high weights, however)</p><p>The recommend weight for v3.0 is -2.0~2.0. The higher the weight is, the sharper the images will be. If you set the weight to a negative number, it can make images smooth.</p><p><strong><u>You can try to use negative weight and increase the CFG Scale, which may better than common way.</u></strong></p>