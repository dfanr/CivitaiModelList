## Reference Sheet for Head | Concept LoRA
### 一、模型概述

- 标签：`concept`, `multi`, `controlnet`, `control`, `viewer`, `head`, `reference`, `sheet`, `reference sheet`, `multiview`
- 下载数：870
- 收藏人数：257
- 评论人数：0
- 评分人数：6
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-25T15:42:32.517Z
  - 原始模型：Other
  - 下载数：870
  - 评分人数：6
  - 评分：5
- 下载地址
  - [Headviews.safetensors](https://civitai.com/api/download/models/103792)
  - [Headviews.zip](https://civitai.com/api/download/models/103792?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/638d7a2b-05f0-4c46-92b9-42d4f04a2bf1/width=450/1285397.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4be0ee79-0a52-4976-b815-d2a1d419c114/width=450/1284806.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ce6d5c76-a774-44ba-b026-1088f9104919/width=450/1284856.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ca6e002a-82e4-42c5-be69-e35dfb4d0962/width=450/1284863.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><span style="color:rgb(219, 222, 225)">Reference Sheet for Head | Concept LoRA</span></p><p></p><p><span style="color:rgb(193, 194, 197)">Big thanks to</span> <span data-type="mention" class="mantine-1yiar0p" data-id="mention:1875206" data-label="YuruSama">@YuruSama</span> <span style="color:rgb(209, 213, 219)">for assisting me with the dataset. Much appreciated!</span></p><p></p><p>Weight can go from 0.5 up to 1. I recommend 0.7. Works with almost every Character. All previews are done without any additional help, except the tags and helping tags. Hairstyle can be messy somtimes. Use of 3D Checkpoint recommended.</p><p><span style="color:rgb(209, 213, 219)">ControlNet can also be helpful in this case, and I have included the depth map for it in the </span><strong><em><span style="color:rgb(209, 213, 219)">Training Images tab</span></em></strong><span style="color:rgb(209, 213, 219)">.</span></p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1f998bae-ca9d-43e7-a36b-c3d5dc863a9d/width=525/1f998bae-ca9d-43e7-a36b-c3d5dc863a9d.jpeg" /></p><p><span style="color:rgb(209, 213, 219)">How to use it? Install </span><a target="_blank" rel="ugc" href="https://github.com/Mikubill/sd-webui-controlnet"><strong><em><span style="color:rgb(76, 110, 245)">ControlNet</span></em></strong></a><span style="color:rgb(76, 110, 245)"> </span><span style="color:rgb(209, 213, 219)">in your WebUI and include your image with the following settings:</span></p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f798f5e8-e5bf-4153-8e5d-0c391c2c4656/width=525/f798f5e8-e5bf-4153-8e5d-0c391c2c4656.jpeg" /></p><h2 id="heading-111"><span style="color:rgb(250, 82, 82)">KEEP IN MIND TO REMOVE ALL FACIAL FEATURES, IF YOU ARE DOING A BACKVIEW.</span></h2><p></p><p>Trigger Words:</p><ul><li><p>FIFront</p></li><li><p>FIFrontBelow</p></li><li><p>FIFrontLittleAbove</p></li><li><p>FIFrontLittleLeft</p></li><li><p>FIFrontLittleRight</p></li><li><p>FIFrontSideLeft</p></li><li><p>FIFrontSideRight</p></li><li><p>FISideLeft</p></li><li><p>FISideRight</p></li><li><p>FIBackAboveRight</p></li><li><p>FIBackAboveLeft</p></li><li><p>FIBackRight</p></li><li><p>FIBackLeft</p></li></ul><p></p><p>Currently in Process:</p><ul><li><p>Back (working, but character is misspresented)</p></li><li><p>BackAbove</p></li><li><p>FrontAbove</p></li></ul><p></p><p>Use of additional helping Prompt recommended:</p><ul><li><p>from above</p></li><li><p>from side</p></li><li><p>from below</p></li><li><p>from behind</p><p></p></li></ul><p></p><p><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Download LoRA</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA and use the triggerword</p></li><li><p><strong>Make sure to change the weight if needed</strong> (by default it's <code>:1</code>)</p></li><li><p>Have Fun!</p></li></ul>