## Graf Zeppelin (KanColle)
### 一、模型概述

- 标签：`anime`, `character`, `female`, `kantai collection`, `kancolle`
- 下载数：964
- 收藏人数：226
- 评论人数：0
- 评分人数：4
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-03-13T17:30:49.620Z
  - 原始模型：SD 1.5
  - 下载数：964
  - 评分人数：4
  - 评分：5
- 下载地址
  - [KC_Graf-000013.safetensors](https://civitai.com/api/download/models/15688)
  - [KCGraf.zip](https://civitai.com/api/download/models/15688?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c442379b-8098-49d3-0aa6-cfeb9f454700/width=450/156733.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/539b4ad6-baae-4441-fef2-11b3ff3c8d00/width=450/156744.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8b0ec8da-e335-4e1f-cca9-28d38da14d00/width=450/156743.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3c9a5c00-aaf6-4b36-ce96-535fb0ff6f00/width=450/156742.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This has more image to train, so it looks much better.</p><p>More preview on my Pixiv: <a target="_blank" rel="ugc" href="https://www.pixiv.net/users/18763851">4BEraser - pixiv</a></p><p>I use Colab to run it, so it didn't finish and stopped on epoch13.</p><p>How to use:</p><p>You can input nothing to generate the character any way, but I do recommend you to use following prompts to generate the outfit:</p><ul><li><p>Base: Graf Zeppelin /(Kancolle/), grey eyes, (large breasts:1.3)</p></li><li><p>Outfit: black gloves, black pantyhose, sidelocks, peaked cap, pleated skirt, black skirt, necktie, miniskirt, military uniform, iron cross, white capelet, long sleeves, white headwear, military hat, white jacket,</p></li><li><p>Try other tags by your own, this has a wide variety of possible clothings, <strong>since this model is bit overfitted, don't forget to put those official outfit element into negative prompts, and lower the model weight. I have updated some examples for reference.</strong></p><ul><li><p>NSFW compatible.</p></li><li><p>I'm not a fan of realistic model, but it seems being capable with ChilloutMix.</p></li><li><p>If you find out that it's focusing on chara's feet, you can try to use Controlnet to limit it.</p><p></p></li></ul></li></ul><p>Settings are what I am using, you can change by your own.</p><ul><li><p>DPM++ Series(SDE Karras, 2M Karras, etc.)</p></li><li><p>about 20 steps, CFG scale 5~7</p></li><li><p>LoRA Weight: maybe above 0.6, try it by your own</p></li><li><p>If using highres</p><ul><li><p>ESRGAN_4X</p></li><li><p>Denoising 0.4-0.6.</p></li></ul></li></ul><p></p><p>LoRA Train Info</p><ul><li><p>based on Animefull-pruned</p><ul><li><p>8x low quality 48 images</p></li><li><p>16x medium quality 51 images</p></li><li><p>32x high quality 33 images</p></li><li><p>=&gt; 1 epoch = 1128 images</p></li></ul></li></ul>