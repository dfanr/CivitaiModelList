## GTA768 Art Style Embedding for version 2.X
### 一、模型概述

- 标签：
- 下载数：2025
- 收藏人数：254
- 评论人数：3
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] GTA768

- 统计数据
  - 发布时间：2022-12-30T20:02:48.389Z
  - 原始模型：SD 2.0 768
  - 下载数：2025
  - 评分人数：2
  - 评分：5
- 下载地址
  - [gta768ArtStyleEmbedding_gta768_trainingData.zip](https://civitai.com/api/download/models/1561?type=Training%20Data)
  - [GTA768.pt](https://civitai.com/api/download/models/1561)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c0dad763-6d87-495f-9bc1-25ff65b2b500/width=450/13799.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5fb84a04-0084-4b18-7462-ccccaf5bdb00/width=450/14126.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d287d72a-f453-432b-a2a2-f865dd53b400/width=450/13975.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a3a5157f-e2ec-4255-c269-b74b99e4d500/width=450/13974.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is another high quality textual inversion embedding that I am excited to release to the stable diffusion community! I have been really underwhelmed by the output of the existing GTA embeddings and checkpoints available currently and I wanted to be able to reliably apply that eye-catching Rockstar style to a variety of subjects and locations, without everybody looking like Michael or having a palm tree growing out of my snowy mountainside. So through a lot of trial and error, I feel I have finally achieved that goal, and I am so excited to share my extremely reliable and versatile Grand Theft Auto 5 style embedding for Stable Diffusion version 2.X models.</p><p>--------</p><p><strong>To use this embedding in AUTOMATIC1111, copy it to your embeddings folder in your stable-diffusion-webui directory. No need to restart, just invoke the embedding from your prompt. Make sure you are using a compatible model or you will get errors!</strong></p><p>--------</p><p><strong>GTA768</strong> is a general purpose embedding. It can easily reproduce GTA5 style imagery, i.e. "man holding gun in front of palm tree in Los Santos" type prompts all day, with very few duds (though "holding a gun" is still pretty tough ask for SD in general). <u>This is easy.</u></p><p><strong>🪄 It also has a trick up its sleeve!</strong> Because <strong>GTA768</strong> is so flexible and versatile, you can use it to produce magical nautical imagery, breathtaking heavy brush natural landscapes, gorgeous period pieces and adorable animals. It also mixes really well with other high quality embeddings such as my <a href="https://civitai.com/models/1305/sda768" rel="ugc" target="_blank">SDA768</a> and <a href="https://civitai.com/models/1288/inkpunk768" rel="ugc" target="_blank">Inkpunk768</a> embeddings.</p><p>💖💖I hope you enjoy using this embedding in your art as much as I enjoy creating them for the Stable Diffusion community. 🙏🏼🙏🏼If you do like it, can you pretty please <u>click the heart</u> at the top and leave a review? Many thanks! 💖💖</p><p><strong>Special Note - </strong>This is a gun happy embedding thanks to the original artwork training images. If you're getting overwhelmed with guns, <u>make sure to add "gun" to your negative prompt</u>, it works really well to get everybody to holster their weapons and get back to posing the way you want them to!</p><p><strong><u>Training Config:</u></strong></p><ul><li><strong>Learning Rate: </strong>0.005:60, 0.0005:1500, 0.00025:3000, 0.000075</li><li><strong>Vectors: </strong>12</li><li><strong>Training Model: </strong>768-v-ema.ckpt (2.0 version model)</li><li><strong>Training Steps: </strong>GTA768v3-2800</li><li><strong>Training Samples: </strong>75 high quality 768x768 training images, which are a selection of original GTA5 artwork mixed with a subset of hand picked GTA-style AI generated images using the GTA5 checkpoint model which matched my target style but offered a variety of subjects and landscapes to provide a more consistent, reliable and better quality training experience. My training images are included if you wish to download and inspect for yourself.</li></ul>