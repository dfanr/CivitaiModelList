## 大长腿 Very long legs
### 一、模型概述

- 标签：`sexy`, `concept`, `thighs`, `barefoot`, `thigh`, `beautiful girl`, `concept lora`, `legs`, `tall woman`, `tall girls`, `leg`, `stature`
- 下载数：1777
- 收藏人数：336
- 评论人数：3
- 评分人数：6
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v2.0

- 统计数据
  - 发布时间：2023-05-17T16:17:10.965Z
  - 原始模型：SD 1.5
  - 下载数：1777
  - 评分人数：6
  - 评分：5
- 下载地址
  - [VeryLongLegs_v2.safetensors](https://civitai.com/api/download/models/73341)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/92feb9f4-a62c-4e07-9557-3cf89c8c9e06/width=450/819096.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1c792612-b99b-42c2-bc49-fe9ee1a45144/width=450/819107.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4aa370fb-97ed-4e74-aac8-a6acb2d7faf0/width=450/819113.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9a65d4a4-4746-4e65-bec5-df3dc7ede389/width=450/819112.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>意外的发现没有额外大长腿的模型，这也算小众XP吗？（虽然我自己也是更重视胸= =）</p><p>主要效果就是拉长腿，以及稍微缩小了头部（也就是头身比缩小到1:8、1:9这样），对画风的影响我尽力了</p><p>训练图片我是生成大图缩小到640*960的，这样脸部会好一点，正常跑图最好也都是要hi-res的，不然有完整长腿的图片，部区域太小真的都是崩的</p><p></p><p>推荐权重0.5-0.7 + (very_long_legs:1.1), 权重0.8以上比较容易腿过长而且其他部位也容易过拟合</p><p></p><p>完整腿部动作还是挺难搞的，脚和脚趾也都特别容易崩，处理起来难度不亚于复杂手势，非常规姿势建议还是用controlNet配合生成（单用controlNet不用lora效果也不好，例如骨骼腿拉的很长，跑出来就变成从脚底的大仰角照片而非正面直拍了）</p><p></p><p>注：v1版本其实是随便生成50张图用美图秀秀修的，v1.1到v2就经历了各种测试，包括controlNet补充姿势（虽然结果还是不太好，但总算不是只有站立才拉长腿了），正则化图像减少对腿之外的部分以及画风的影响（影响是小了，但效果也变差了，最后还是放弃正则化了）</p>