## Atlanta (Kancolle)
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `kantai collection`, `kancolle`, `game character`, `video game`
- 下载数：1747
- 收藏人数：469
- 评论人数：1
- 评分人数：5
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0-7epch

- 统计数据
  - 发布时间：2023-04-25T09:04:02.559Z
  - 原始模型：SD 1.5
  - 下载数：1747
  - 评分人数：5
  - 评分：5
- 下载地址
  - [KCAtlanta.safetensors](https://civitai.com/api/download/models/20429)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/71a96ff5-f4a2-4473-372b-9e58d088ef00/width=450/216436.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fd1acc1f-4c9b-42a4-050b-bc2df8b99700/width=450/216438.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dedc42fd-ddfb-4c5f-5f45-c80264447d00/width=450/216437.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7f991b64-3c3d-41e6-d54b-68e1f2184300/width=450/216481.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This one is trained before Bismarck, so I lost the training detail of the file.</p><p>I kept the image set but bruh I didn't solve it very well so I won't put it on.</p><p>Next one is probably Pudding, and the next next one, maybe Iowa or Warspite.</p><p>How to use:</p><p>You can input nothing to generate the character any way, but I do recommend you to use following prompts to generate the outfit:</p><ul><li><p>Base: <code>Atlanta /(Kancolle/), pink hair, twin tails, grey eyes, large breasts</code></p></li><li><p>Original Outfit:</p><ul><li><p><code>suspender skirt, gloves, breasts, garrison cap, partially fingerless gloves, white gloves, long sleeves, high-waist skirt, black skirt, white shirt, earrings, jewelry, star earrings, thigh strap, black headwear, anchor hair ornament, garter straps, rigging, hair ornament, dress shirt, headgear, camouflage, boots, rudder footwear, black footwear,</code></p></li></ul></li><li><p>Mitsukoshi Alternate (Not good since lack of training data, but do work a little bit):</p><ul><li><p><code>jewelry, earrings, alternate costume, sweater, long sleeves, shopping bag, asymmetrical legwear, black sweater, coat, pantyhose, skirt, mismatched legwear, turtleneck, single earring, star earrings, breasts, turtleneck sweater, hair ornament, ribbed sweater, boots, scarf, white footwear, white coat</code></p></li></ul></li><li><p>Try other tags by your own, this has a wide variety of possible clothing's. If the official element keep popping up, put those in negative prompts.</p><ul><li><p>NSFW compatible, sort of.</p></li><li><p>If you find out that it's focusing on chara's feet, you can try to use Controlnet to limit it.</p></li><li><p>It seems that it will keep generate bad full body pose in wide mode if you don't give it any pose prompts, try to add other pose, <code>feet out of frame</code>, or use controlnet to solve it.</p></li><li><p>capable to most anime model &amp; lora but won't be good on Counterfeit. Suggest AOM3 for similar result.</p><p></p></li></ul></li></ul><p>Settings are what I am using, you can change by your own.</p><ul><li><p>DPM++ Series(SDE Karras, 2M Karras, etc.)</p></li><li><p>about 20 steps, CFG scale 5~7</p></li><li><p>LoRA Weight: above 0.6, try it by your own</p></li><li><p>If using highres</p><ul><li><p>ESRGAN_4X</p></li><li><p>Denoising 0.5-0.6.</p></li><li><p>LoRA Train Info</p><ul><li><p>based on Animefull-pruned</p></li><li><p>batch 2</p><ul><li><p>4x Low quality 148 images</p></li><li><p>8x Med quality 104 images</p></li><li><p>16x High quality with 61 images</p></li><li><p>=&gt; 1 epoch = 2400 images</p></li><li><p>yup I know it's way too much, but I'm not going to re-train it instantly.</p></li></ul></li></ul></li></ul></li></ul>