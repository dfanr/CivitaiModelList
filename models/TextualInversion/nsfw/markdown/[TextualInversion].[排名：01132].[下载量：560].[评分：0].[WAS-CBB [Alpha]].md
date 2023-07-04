## WAS-CBB [Alpha]
### 一、模型概述

- 标签：`nude`, `mixed race`, `body`, `vae-ft-mse-840000`, `erotic photography`, `body style`, `body look`
- 下载数：560
- 收藏人数：99
- 评论人数：8
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v0.1

- 统计数据
  - 发布时间：2023-04-18T07:26:28.987Z
  - 原始模型：SD 1.5
  - 下载数：560
  - 评分人数：0
  - 评分：0
- 下载地址
  - [WAS-CBB.pt](https://civitai.com/api/download/models/48721)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2b7d001c-9905-4cba-1a58-80fbcc9d3a00/width=450/523815.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2693eed1-995a-4156-0322-4c242f9dc700/width=450/523739.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4af4c3bd-f935-4d87-c170-ac5c71ab7200/width=450/523816.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9b7f4166-f044-4d16-281a-ef9631791400/width=450/523814.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<img src="https://i.postimg.cc/3rqMy81s/Cultured-Beautiful-Bodies.png" /><p>🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑</p><p></p><p>First of all I would like to start off by saying this is a experiment in tricking Stable Diffusion. I have longed for mixed race bodies that more resemble what I am fond of, bodies like my significant other. SD didn't seem to do it right, and was had to control to get the effect I wanted.</p><p></p><p>I also didn't want to release a model that would reproduce identifiable faces for privacy and respect, and just wanted the artistic form of the generalized body type.<br /><br /><strong>To defeat this I put together an idea to experiment with:</strong></p><ol><li><p>Gather images that represent the dataset I wanted</p></li><li><p>Specifically crop images so that only the body is in the frame.</p></li><li><p>Upscale the images with 4x-UltraSharp.pth, downsize to 512x512<br />3.a For images that the face could not be cropped out, I masked and filled with latent noise (using ComfyUI and my <a target="_blank" rel="ugc" href="https://github.com/WASasquatch/was-node-suite-comfyui">WAS Node Suite</a>)</p></li><li><p>Train with prompts that focus on the body type I am going for<br />4.a Add specific emphasis on faces, which don't exist, again in the style I am going for<br /></p></li></ol><p>The idea here is that while training, and using my prompts, Stable Diffusion is going to be force to make up unique faces on it's own. To me the frequency of cut-off faces seems very low, and so far, my theory seems to have panned out.</p><p></p><p>🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑🤎🍑</p><h2><br />Notes:</h2><ul><li><p><em>Best used with VAE vae-ft-mse-840000</em></p></li><li><p><em>Best used with good ol' negative embeds for composition, and bad hands</em></p></li><li><p><em>Best used with models like Dreamlike, Protogen, TheAlly's Mix's, etc.</em></p></li><li><p><em>Due to the nature of the TI, if you want clothed models, you'll have to play with weighting to taste.</em></p></li></ul>