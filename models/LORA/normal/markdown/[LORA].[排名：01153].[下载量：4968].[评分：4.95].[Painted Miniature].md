## Painted Miniature
### 一、模型概述

- 标签：`d&d`, `miniatures`, `figurines`, `handpainted`, `warhammer`, `style`
- 下载数：4968
- 收藏人数：1113
- 评论人数：6
- 评分人数：21
- 评分：4.95

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v3.5

- 统计数据
  - 发布时间：2023-02-26T09:10:35.524Z
  - 原始模型：SD 1.5
  - 下载数：3814
  - 评分人数：10
  - 评分：5
- 下载地址
  - [Pmini_v3.5.18.safetensors](https://civitai.com/api/download/models/15606)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4ca44835-2f34-4c5b-69b7-6dc843c32500/width=450/155781.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6d8fbb0a-92e1-434a-6677-16e582fef600/width=450/155780.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2c965ae0-4c13-4eff-f7b0-914171ea1400/width=450/155779.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7cb72320-1dc9-4afd-6152-376e2c11c300/width=450/155778.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v3.0

- 统计数据
  - 发布时间：2023-02-26T09:10:35.524Z
  - 原始模型：SD 1.5
  - 下载数：1154
  - 评分人数：11
  - 评分：4.91
- 下载地址
  - [Painted_Miniature_i_v3.0.safetensors](https://civitai.com/api/download/models/9072)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2edb878d-5c0e-4334-0589-d30fe33a8700/width=450/86967.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/65712634-99a0-4f56-4206-b51009262300/width=450/89058.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cd5231e9-09c4-4ed0-eeb5-7ddc9d063a00/width=450/86961.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/540acdf7-7f34-47e7-2b93-628f9231db00/width=450/86984.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>A lora model dedicates to generate painted miniature figurine. The lora model is trained with SD1.5 base model. The example images are generated with <a target="_blank" rel="ugc" href="https://civitai.com/models/5062/clarity"><strong>Clarity </strong></a>and <a target="_blank" rel="ugc" href="https://civitai.com/models/3816/protogen-x53-photorealism-official-release"><strong>Protogen x5.3 (Photorealism)</strong></a><strong> </strong>ckpt models. It should work fine with other fine tune SD1.5 originated ckpt models.</p><h3>User suggestions:</h3><p>The following setup gives me satisfied outputs.</p><p>trigger words: painted miniature, pmini style, on a base (optional: to add a plate under miniatures' feet)</p><p>lora weight: 0.6-0.8</p><p>Sampler: Euler a for 100 steps</p><p>W*H: 768*1024</p><p>CFG scale: 5-7</p><p>Negative emb. (optional): <a target="_blank" rel="ugc" href="https://huggingface.co/datasets/Nerfgun3/bad_prompt"><strong>bad_prompt</strong></a></p><p>Hires. fix: R-ESRGAN General WDN 4xV3, steps 20, denoising strength 0.4</p><h3>Prompt example 1: miniatures in themed background</h3><p><u>positive prompt</u>: a <strong>painted miniature</strong> of a male human thief <strong>on a base</strong>, in a lost ruin, <strong>pmini style</strong>, character design, studio lighting, (extremely detailed 8k wallpaper), Intricate, High Detail figurine, Sharp focus, dramatic, photorealistic art &lt;<strong>lora:Painted_Miniature_i_v3.0:0.6</strong>&gt;</p><p><u>negative prompt</u>: headpiece, (bad_prompt:0.8), cartoon, (bad art:1.2), (deformed:1.2),(close up:1.2),(b&amp;w:1.2),blurry, (duplicate:1.3), (mutilated:1.2), (out of frame:1.2),blurry, (disfigured:1.3), closed eyes</p><p></p><h3>Prompt example 2: high detailed miniatures in plain background</h3><p><u>positive prompt</u>: <strong>pmini style</strong>, <strong>painted miniature</strong> of male human thief, character design, Intricate, High Detail, Sharp focus, dramatic, photorealistic art <strong>&lt;lora:Painted_Miniature_i_v3.0:0.6&gt;</strong></p><p><u>negative prompt</u>: headpieces, cartoon, (bad art:1.2), (b&amp;w:1.2),blurry, closed eyes, nsfw</p>