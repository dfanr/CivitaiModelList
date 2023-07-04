## PastelMix-dpep4
### 一、模型概述

- 标签：`anime`, `colorful`, `pastel`, `style`, `paintings`, `anything`, `vivid colors`, `dpep`
- 下载数：764
- 收藏人数：224
- 评论人数：4
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] PastelMix-dpep4

- 统计数据
  - 发布时间：2023-05-03T02:35:51.136Z
  - 原始模型：Other
  - 下载数：664
  - 评分人数：0
  - 评分：0
- 下载地址
  - [pastelmixDpep4_pastelmixDpep4.safetensors](https://civitai.com/api/download/models/26356)
  - [pastelmixDpep4_pastelmixDpep4.ckpt](https://civitai.com/api/download/models/26356?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [blessed2.vae.safetensors](https://civitai.com/api/download/models/26356?type=VAE&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/49a2f97e-7f45-4169-38b3-315570cdb700/width=450/290221.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7bd81f67-b74d-4bd1-8e45-f9efad41d600/width=450/290228.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3689f227-2a7d-479a-0c91-5c4c14378800/width=450/290227.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/44846aa5-e09e-40af-5c2b-549996100300/width=450/290226.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] PastelMix-hell5dpep

- 统计数据
  - 发布时间：2023-05-03T02:35:51.136Z
  - 原始模型：Other
  - 下载数：100
  - 评分人数：0
  - 评分：0
- 下载地址
  - [pastelmixDpep4_pastelmixHell5dpep.safetensors](https://civitai.com/api/download/models/61033)
  - [pastelmixDpep4_pastelmixHell5dpep.safetensors](https://civitai.com/api/download/models/61033?type=Model&format=SafeTensor&size=full&fp=fp16)
  - [kl-f8-anime2.ckpt](https://civitai.com/api/download/models/61033?type=VAE&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/042720c9-b56d-4c33-97ee-0b2e7db59ad4/width=450/668857.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/14c74ece-a32f-41e0-8c4f-22cda58aab50/width=450/668856.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/37616aaf-6b28-4c9f-8569-6afb8b293885/width=450/668858.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ebb54b70-27ad-4a31-b336-2dddc623ac2c/width=450/668862.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is just a recreation of <a rel="ugc" href="https://civitai.com/models/5414/pastel-mix-stylized-anime-model">pastelmix </a>except it uses the new version of closertodeath's detailprojectmodel, akak dpep4 to make dpep4mkmp as a base (as opposed to dpep3mkmp) and swaps out basil-mix for ChilloutMix. The big difference between dpep3 and dpep4 is that dpep4 is a lot less fried. This affects input and output layers 1-5, of the Unet, making large alterations to the common output layers and the detail input layers, as indicated by this Unet merging guide below.</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4a5cf2e4-53d5-4ee5-0ea9-d1c561f27e00/width=525/4a5cf2e4-53d5-4ee5-0ea9-d1c561f27e00" /><p>In theory we're using "dpep4mkmp's understanding of things like bodyparts and feet, hair, clothes" and using sampling them using "tea's understanding", whereas we're using "tea's understanding of things like background and picture composition" and letting dpep handle upsampling them, except for super granular inputs where it's all ChilloutMix handling the show. As dpep's strength is primarily in super highly detailed backgrounds and chilloutmix's strengths are in making the most realistic textures, this plays to both their strengths.</p><p></p><p>In practice these changes mostly make a different in body parts and other high level blocks related to anatomy. We get the same pastel-like style but with big changes to the face and body parts which are more distinct and less blended together (because dpep4 is less fried). This primarily manifests in the skin and eyes but also a less squished facial shape. </p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c1f592fd-4501-4dfe-a214-d9d070927100/width=525/c1f592fd-4501-4dfe-a214-d9d070927100" /><p>You can check andite's <a rel="ugc" href="https://huggingface.co/andite/pastel-mix">huggingface repo</a> for the recipe.</p>