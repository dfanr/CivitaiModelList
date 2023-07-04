## Egg Fusion - LoRa Merge
### 一、模型概述

- 标签：`style`
- 下载数：205
- 收藏人数：113
- 评论人数：2
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-18T00:18:39.690Z
  - 原始模型：SD 1.5
  - 下载数：205
  - 评分人数：1
  - 评分：5
- 下载地址
  - [eggFusionLoraMerge_v10.ckpt](https://civitai.com/api/download/models/48510?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [eggFusionLoraMerge_v10.safetensors](https://civitai.com/api/download/models/48510)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7046a3ca-6b49-4290-bc04-2f9ee4139500/width=450/521069.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f42886a6-d723-4cee-3635-74c200ce7100/width=450/521061.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/49bd75fb-c33f-4cf7-d512-d841a9b2da00/width=450/521067.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b7be5585-429d-4f6a-3ca6-f568feceb200/width=450/521063.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>A fully revamped checkpoint based on the 512dim lora and chilloutmix_NiPrunedFp32Fix + deliberate_v2.<br /><br />Training data: 512 DIM LORA<br /><a target="_blank" rel="ugc" href="https://civitai.com/models/41893/lora-eggeaster-fusion">https://civitai.com/models/41893/lora-eggeaster-fusion</a><br /><br />Here is how it looks using the lora on top of models:</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ea3da144-d1ea-4f46-90f4-86d4e0af8a00/width=525/ea3da144-d1ea-4f46-90f4-86d4e0af8a00.jpeg" /><p>lora weights: TEnc Weight 0.2 UNet Weight 1<br /><br />Merged the 512dim lora to chillout and deliberate / --ratios 0.99 toward my fusion lora<br /></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9a3a1f66-5db8-4fbc-bedb-510946276500/width=525/9a3a1f66-5db8-4fbc-bedb-510946276500.jpeg" /><p></p><p>C is CHillout / d is deliberate <br /><br /><br />Merged C and D with:</p><p><br />Base_alpha=0.53<br />Weight_values=0,0.157576195987654,0.28491512345679,0.384765625,0.459876543209877,0.512996720679012,0.546875,0.564260223765432,0.567901234567901,0.560546875,0.544945987654321,0.523847415123457,0.5,0.476152584876543,0.455054012345679,0.439453125,0.432098765432099,0.435739776234568,0.453125,0.487003279320987,0.540123456790124,0.615234375,0.71508487654321,0.842423804012347,1</p><p>and <br />1,0.842423804012346,0.71508487654321,0.615234375,0.540123456790123,0.487003279320988,0.453125,0.435739776234568,0.432098765432099,0.439453125,0.455054012345679,0.476152584876543,0.5,0.523847415123457,0.544945987654321,0.560546875,0.567901234567901,0.564260223765432,0.546875,0.512996720679013,0.459876543209876,0.384765625,0.28491512345679,0.157576195987653,0<br /><br />both results merged </p><p>Weight_values=<br />1,0.842423804012346,0.71508487654321,0.615234375,0.540123456790123,0.487003279320988,0.453125,0.435739776234568,0.432098765432099,0.439453125,0.455054012345679,0.476152584876543,0.5,0.523847415123457,0.544945987654321,0.560546875,0.567901234567901,0.564260223765432,0.546875,0.512996720679013,0.459876543209876,0.384765625,0.28491512345679,0.157576195987653,0</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a2ef463b-c07f-423b-f530-be13cc66d400/width=525/a2ef463b-c07f-423b-f530-be13cc66d400.jpeg" /><p></p><p>And voila..<br />here is Egg_fusion checkpoint with the 512 dim-trained lora<br /></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/778d66b3-4e07-40de-6c13-22ba9f0c1300/width=525/778d66b3-4e07-40de-6c13-22ba9f0c1300.jpeg" /><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/be88a286-35ec-4756-13d6-0774d7bef900/width=525/be88a286-35ec-4756-13d6-0774d7bef900.jpeg" /><p><br />Enjoy your eggs  🤟 🥃<br /></p>