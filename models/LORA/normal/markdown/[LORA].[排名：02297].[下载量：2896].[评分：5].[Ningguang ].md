## Ningguang 
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `girls`
- 下载数：2896
- 收藏人数：687
- 评论人数：6
- 评分人数：8
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] V1.0

- 统计数据
  - 发布时间：2023-02-27T15:32:15.231Z
  - 原始模型：Other
  - 下载数：2896
  - 评分人数：8
  - 评分：5
- 下载地址
  - [Ningguang.safetensors](https://civitai.com/api/download/models/10075)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9573a553-c456-4c36-c029-f2955fe52800/width=450/98179.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c0c93618-a75c-4378-dd99-62cfe9934800/width=450/98186.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7cb5ca29-7d7e-4b1c-6354-ed207320c000/width=450/98185.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c7709515-4537-4501-fe87-296734995700/width=450/98184.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3>Brief</h3><p>This is a LoRa model of the lovely character Ningguang from Genshin Impact. It was trained basing on anything V3, and works on both anime checkpoints such as OrangeMixs, 9527, counterfeit, and realistic checkpoints such as ChillOutMix. But it is still in development stage and I will continuously upgrading it. Hope you enjoy using my model.</p><p>For more info: <a target="_blank" rel="ugc" href="https://huggingface.co/okingjo/Multi-identifier_LORA_Model">https://huggingface.co/okingjo/Multi-identifier_LORA_Model</a></p><p></p><h3>Changing costume</h3><p>The two costumes in game (the original one and the orchid's evening gown) are included in this model. and you can switch them by prompt:</p><p>"ningguang\(genshin impact\)" will give you the original costume.</p><p>"ningguang \(orchid's evening gown\) \(genshin impact\)" will give you the orchid's evening gown costume.</p><p>And, if you want, add "headonly" to the prompt to remove her clothes.</p><p></p><h3>About training</h3><p>I`m using Kohya_ss to train the model with handpicked ningguang images from danbooru. I am painter myself so I paid extra attention to make sure that the faces on each of the images match to my impression to the character. Beside, I have also included 360 snapshots from 3D model of Ningguang on both costumes to further improve accuracy. the total quantity is 115.</p><p>The training was divided into two phases, first with default learning rate, 20 repeats, and 7 epochs, then another 6 epochs with 1/10 the learning rate.</p><p>It looks there is still room for more epochs, but I am afraid of over-training so that`s it. I`ll do more test in the future.</p><p></p><p>Please feel free to comment and let me know if there are anything you think could improve the training! I`m still learning!</p>