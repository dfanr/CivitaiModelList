## Deep Dream
### 一、模型概述

- 标签：`depth2img`, `img2img`
- 下载数：379
- 收藏人数：59
- 评论人数：1
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v0.75

- 统计数据
  - 发布时间：2023-02-11T08:08:49.652Z
  - 原始模型：SD 2.0 768
  - 下载数：379
  - 评分人数：0
  - 评分：0
- 下载地址
  - [deepDream_v075.ckpt](https://civitai.com/api/download/models/7073)
  - [deepDream_v075.yaml](https://civitai.com/api/download/models/7073?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7b9c63e3-f829-49d4-5930-2a34e5ab6800/width=450/65330.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/49cf0ebf-acd5-4802-88d9-bf0f2a739500/width=450/65329.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/309477b5-d197-4979-718e-830f2100e300/width=450/65328.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/771d7081-aa43-4d89-eeaa-694900342500/width=450/65327.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Hello, everyone. Here is an attempt to merge WaifuDivision 1.4 SDv2 model with vanilla SDv2 depth-512 model in the noble pursuit of creating depth aware SDv2 <strong>img2img</strong> model that actually can depict nudity as well as other objects. It's the work in progress, but since i don't have much time on my hands, i decided to upload and let it fly like a bird into the sky for you to try.</p><p>Usage is simple, you put the image into <strong>img2img </strong>(or <strong>Inpaint </strong>for that matter) and put in prompt what you want final image to be, increase steps and it will try to render new image while keeping your subject pose intact. As you can see on examples the concept works pretty good, even with denoise set to 1.</p><p>It tends to output paintings, mainly because merge was heavily in favor of anime model that is WD.  Also needs to be mentioned that to avoid scary looking faces that all SDv2 models are famous to produce, creative usage of negative prompt is a must. I recommend using <a rel="ugc" href="https://civitai.com/models/2385/socalguitarists-magic-facelift-negative-embedding-for-model-2x-fix-yo-ugly-faces">Neg_Facelift768</a> embedding and all kinds of bad things that you can fit to Negative. </p><p>Have fun prompting, neuro friends.</p><p>TODO: increase quality</p>