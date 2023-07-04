## Snow White
### 一、模型概述

- 标签：`character`, `disney`, `woman`, `cartoon`, `disney princess`
- 下载数：1100
- 收藏人数：224
- 评论人数：0
- 评分人数：7
- 评分：4.29

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-19T18:54:54.864Z
  - 原始模型：SD 1.5
  - 下载数：1100
  - 评分人数：7
  - 评分：4.29
- 下载地址
  - [SnowWhite_v1.safetensors](https://civitai.com/api/download/models/50026)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2f310f67-d245-42aa-b233-642754d9e4bc/width=450/1222112.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3afdccbd-28dd-4343-bf63-e555e5410d00/width=450/539380.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5236610d-828f-4c93-a5d5-d469b8b9bd00/width=450/539658.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/70d9980f-483e-43a6-16ab-e8a45abdeb00/width=450/538259.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><span style="color:rgb(34, 139, 230)">Please contact me here on civitAi or on Twitter if you want to provide the LoRa in a generation service.</span></p><p></p><h3 id="heading-19">TLDR (Because I don't care)</h3><p>Use <code>snow white &lt;lora:snowWhite_v10:1&gt;</code> in positiv promt.</p><p><em>If you like the LoRa, please feel free to share your generated images here and leave a review (</em><strong><em>or at least a rating</em></strong><em>) ;D</em></p><p></p><h2 id="heading-20">About</h2><p>I still enjoy making models for animated stuff, especially this old stuff is challenging.</p><p>The last time I watched Snow White was ages ago (back when VHS was still a thing) and I never realised how "badly" made it was compared to more modern films, but it's actually from 1937 so I give them a bit of slack (it's actually quite good when you think about it, it was the first "long" animated film ever as far as I know).</p><p>I never noticed that Snow White had her eyes closed for most of the film (and to be honest, when she did open her eyes, she had some really crazy eyes, at the time, drawing eyes wasn't their forte, but they definitely got better. About 13 years later, with the release of Cinderella, they actually learned how to make eyes that were not scary :D (Which is another LoRa in the making, by the way ^^)</p><p></p><h2 id="heading-21">Training</h2><p>Well, like I said, I tried to only use frames where she had her eyes open, so I worked with 36 images for training.</p><p>This approach increased a small problem: there are not many pictures where her skirt is involved, so look in the next section how to prevent her from going full comando on your pictures (or at least without a skirt xD). And this time I calculated the learning rate properly instead of eyeballing the values.</p><p></p><h2 id="heading-22">Usage</h2><p>There is no need to adjust the weight - it's as simple as that:</p><p><code>snow white &lt;lora:snowWhite_v10:1&gt;</code></p><p>I suggest adding <code>long skirt</code> f you want to have her completely in her famous dress, otherwise she will be bottomless most of the time...</p>