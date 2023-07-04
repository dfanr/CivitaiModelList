## ControlNet for SD2.1
### 一、模型概述

- 标签：
- 下载数：311
- 收藏人数：59
- 评论人数：2
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-15T12:26:32.117Z
  - 原始模型：SD 2.1
  - 下载数：311
  - 评分人数：0
  - 评分：0
- 下载地址
  - [controlnetForSD21_v10.yaml](https://civitai.com/api/download/models/46355)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5d0d38cf-3a75-4b0f-1ec7-5001ef7c8300/width=450/501711.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2f65214d-8a3b-4517-d54e-e15ecd478200/width=450/501715.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e1dbecc1-df97-4757-b507-3ad8232b4200/width=450/501716.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/21a5b67e-f513-4873-1421-e6ab4b682000/width=450/501714.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3>Download them on HF:</h3><p><a target="_blank" rel="ugc" href="https://huggingface.co/thibaud/controlnet-sd21">https://huggingface.co/thibaud/controlnet-sd21</a></p><p></p><h3>To use with Automatic1111:</h3><ul><li><p>Download the ckpt files or safetensors ones</p></li><li><p>Put it in extensions/sd-webui-controlnet/models</p></li><li><p>in settings/controlnet, change cldm_v15.yaml by cldm_v21.yaml</p></li><li><p>Enjoy</p></li></ul><p></p><h3><strong>Canny:</strong></h3><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/48af285f-a859-4540-1d7c-f9870feaef00/width=525/48af285f-a859-4540-1d7c-f9870feaef00.jpeg" /><h3>Depth:</h3><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/37d2a3a3-1f89-4ce0-ad6c-671076cd2400/width=525/37d2a3a3-1f89-4ce0-ad6c-671076cd2400.jpeg" /><h3>ZoeDepth:</h3><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4597803c-c5b7-4cf0-3665-c090ce66df00/width=525/4597803c-c5b7-4cf0-3665-c090ce66df00.jpeg" /><h3>Scribble:</h3><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/64d4caaf-1c47-4716-176d-9a57aaf92000/width=525/64d4caaf-1c47-4716-176d-9a57aaf92000.jpeg" /><h3>OpenPose:</h3><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/36072eeb-5591-4bca-4a5b-75dfbaddb100/width=525/36072eeb-5591-4bca-4a5b-75dfbaddb100.jpeg" /><h3>Color:</h3><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b8d41cba-51f5-4ea9-e2a4-925f945b3000/width=525/b8d41cba-51f5-4ea9-e2a4-925f945b3000.jpeg" /><h3>OpenPoseV2:</h3><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b7870191-a0ef-464c-9f04-b633c3b33000/width=525/b7870191-a0ef-464c-9f04-b633c3b33000.jpeg" /><h3>LineArt:</h3><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/65a550b3-4e41-483a-4feb-62c9f7821c00/width=525/65a550b3-4e41-483a-4feb-62c9f7821c00.jpeg" /><h3>Ade20K:</h3><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fad8be5a-0e86-4d5a-4304-3751560a0e00/width=525/fad8be5a-0e86-4d5a-4304-3751560a0e00.jpeg" /><h3>Normal BAE:</h3><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9f3734ba-5095-4a49-9e31-d1b314297500/width=525/9f3734ba-5095-4a49-9e31-d1b314297500.jpeg" /><h3></h3><h3>To use ZoeDepth:</h3><p>You can use it with annotator depth/le_res but it works better with ZoeDepth Annotator. My PR is not accepted yet but you can use my fork. My fork: <a target="_blank" rel="ugc" href="https://github.com/thibaudart/sd-webui-controlnet"><strong><u>https://github.com/thibaudart/sd-webui-controlnet</u></strong></a> The PR: <a target="_blank" rel="ugc" href="https://github.com/Mikubill/sd-webui-controlnet/pull/655#issuecomment-1481724024"><strong><u>https://github.com/Mikubill/sd-webui-controlnet/pull/655#issuecomment-1481724024</u></strong></a></p><h3>Misuse, Malicious Use, and Out-of-Scope Use</h3><p>The model should not be used to intentionally create or disseminate images that create hostile or alienating environments for people. This includes generating images that people would foreseeably find disturbing, distressing, or offensive; or content that propagates historical or current stereotypes.</p><p>Thanks <a target="_blank" rel="ugc" href="https://huggingface.co/lllyasviel/"><strong><u>https://huggingface.co/lllyasviel/</u></strong></a> for the implementation and the release of 1.5 models. Thanks <a target="_blank" rel="ugc" href="https://huggingface.co/p1atdev/"><strong><u>https://huggingface.co/p1atdev/</u></strong></a> for the conversion script from ckpt to safetensors pruned &amp; fp16</p>