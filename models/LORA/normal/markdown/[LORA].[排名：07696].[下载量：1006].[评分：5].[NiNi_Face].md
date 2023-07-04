## NiNi_Face
### 一、模型概述

- 标签：`character`, `girl`, `woman`
- 下载数：1006
- 收藏人数：211
- 评论人数：1
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] V4

- 统计数据
  - 发布时间：2023-05-30T10:53:58.336Z
  - 原始模型：SD 1.5
  - 下载数：1006
  - 评分人数：1
  - 评分：5
- 下载地址
  - [NiNi_V4.safetensors](https://civitai.com/api/download/models/85402)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/17405f7d-1aa5-496c-9921-4db95a46d3ac/width=450/993895.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dea6b36a-7d33-490d-ae48-9263143a8804/width=450/979108.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/874de720-7b7f-4658-ba52-1196eb6efb92/width=450/968577.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/36a3e8b2-58df-43f7-be4f-bfa9db74d1ba/width=450/968364.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>自己训练的一个人脸 Lora 模型，基于 SD1.5，算是失败品，因为生成的人脸并不像用来训练的人脸，但是生成的人脸看起来也不错，于是分享出来给大家试试效果。</p><p>与 majicMIX realistic 或 majicMIX sombre 搭配使用，推荐参数：</p><p>模型权重: 0.5~0.9</p><p>提示词引导系数 CFG Scale: 5~7</p><p>采样步数 Sampling steps: 15~25</p><p>可以通过分层控制减少污染，例如：1,0,0,0,0,0,0,0,1,1,1,0,0,0,0,0,0，分层控制可以尝试更高的模型权重。</p><p>The Lora model of a person's face that I trained myself, based on SD1.5, is considered a failure because the generated face does not look like the one used for training, but the generated face also looks good. So I shared it with everyone to try the effect.</p><p>Used in conjunction with majicMIX realistic or majicMIX symbol.</p><p>Pollution can be reduced through hierarchical control, such as 1,0,0,0,0,0,0,0,1,1,1,0,0,0,0,0,0, Hierarchical control can attempt higher model weights.</p>