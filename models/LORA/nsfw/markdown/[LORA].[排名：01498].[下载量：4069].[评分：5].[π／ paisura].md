## π／ paisura
### 一、模型概述

- 标签：`photorealistic`, `concept`, `illustration`, `realistic`
- 下载数：4069
- 收藏人数：774
- 评论人数：4
- 评分人数：3
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v1.0_OUT34

- 统计数据
  - 发布时间：2023-06-02T14:17:01.415Z
  - 原始模型：SD 1.5
  - 下载数：969
  - 评分人数：0
  - 评分：0
- 下载地址
  - [paisura_1.0_OUT34.safetensors](https://civitai.com/api/download/models/87696)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/29a38304-a02c-4765-99ab-24a0617f2c42/width=450/1005663.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fec704d3-e975-4752-b1a8-ae4424f8980e/width=450/1005596.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8e13b94f-ecb4-472b-95d9-3bff1d2f7283/width=450/1005630.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d7099d9f-44da-4f34-8ab9-8a534385c6d1/width=450/1005660.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v1.0_OUT34_DIM32

- 统计数据
  - 发布时间：2023-06-02T14:17:21.317Z
  - 原始模型：SD 1.5
  - 下载数：144
  - 评分人数：0
  - 评分：0
- 下载地址
  - [paisura_1.0_OUT34_DIM32.safetensors](https://civitai.com/api/download/models/87679)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c6c000f2-9039-42d9-b536-22bb48f57815/width=450/1005249.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/15cb27eb-5877-4b1e-936c-de985475e5ea/width=450/1005483.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/939cfb35-7bf5-400f-99cd-a1e470feb887/width=450/1005262.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2ffc92b9-fc07-44b8-bc7e-12293f7e2be2/width=450/1005266.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] paisura_test1

- 统计数据
  - 发布时间：2023-06-02T14:17:01.415Z
  - 原始模型：SD 1.5
  - 下载数：2956
  - 评分人数：3
  - 评分：5
- 下载地址
  - [paisura.safetensors](https://civitai.com/api/download/models/22640)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6dd6c9ee-4e6e-4c24-12e6-bea9a3019200/width=450/243869.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7716a320-fa5c-452f-188a-fa999c92b400/width=450/243886.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ef1da848-01b7-456a-6d0a-9fbadd598600/width=450/243885.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/01cc41e7-0dbb-4acf-489c-f58eed20e500/width=450/243884.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>隣接した円(P1,P2)の内を移動する点(b1,b2)の間を通る接線S</p><p>接点の画像生成を求めるLoRA</p><p>Tangent line S passing between points (b1, b2) moving within adjacent circles (P1, P2)</p><p>LoRA, which seeks to generate an image of the tangent point</p><p></p><p>prompt1:<br />masterpiece, best quality, ultra-detailed, illustration,<br /><strong>paisura</strong>, 1girl, glasses, small breasts, shirt, wristwatch, jewelry, strap between breasts, earrings, long hair, white shirt, striped, short sleeves, black hair, striped shirt, bag, skirt, solo focus, blurry, t-shirt, between breasts, necklace, handbag<br />&lt;lora:paisura:0.6:NP&gt;<br /><br />prompt2:<br />masterpiece, best quality, ultra-detailed, illustration,<br /><strong>paisura</strong>, 1girl, glasses, small breasts, necktie, skirt, bag, school uniform, black hair, outdoors, road, between breasts, street, school bag, ground vehicle<br />&lt;lora:paisura:0.6:NP&gt;</p><p></p><p>Prompt3…？</p><p>masterpiece, best quality, ultra-detailed, illustration,</p><p>(paisura:1.4), (older man), silver hair , short cut, (mascular male:1.5), (sunglasses), laughing,messenger bag, black shirt, long sleeves, jeans, thumbs up, street,</p><p>&lt;lora:paisura:0.8:NP&gt;</p><p></p><p>LoRA Block Weightを使用して設定</p><p>NP:1,1,1,1,1,0,0,0,1,1,1,1,1,1,1,0,0<br />NP=disable_IN07-08_MID00_OUY10-11:1,1,1,1,1,0,0,0,1,1,1,1,1,1,1,0,0</p><p>で適用すると画風や塗りへの影響を少し軽減できるかもしれません</p><p>他に良い設定があるかもしれません。</p><p></p><p>お手数ですがファイル名はpaisura.safetensorsにリネームしてお使いください。</p><p>Please rename the file to paisura.safetensors.</p><p></p>