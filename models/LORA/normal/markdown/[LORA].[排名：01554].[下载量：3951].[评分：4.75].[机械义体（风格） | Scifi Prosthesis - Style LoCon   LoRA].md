## 机械义体（风格） | Scifi Prosthesis - Style LoCon / LoRA
### 一、模型概述

- 标签：`3d`, `style`, `beautiful`, `portraits`
- 下载数：3951
- 收藏人数：1081
- 评论人数：8
- 评分人数：8
- 评分：4.75

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] epoch000006

- 统计数据
  - 发布时间：2023-03-22T18:02:33.842Z
  - 原始模型：SD 1.5
  - 下载数：3487
  - 评分人数：7
  - 评分：4.71
- 下载地址
  - [dylanKowalski-000006.safetensors](https://civitai.com/api/download/models/26674)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3e50fddc-c14a-4c28-80c1-f5c2e9a0ca00/width=450/293964.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c1a9939d-cdc7-4a45-fe5c-f47b9747e900/width=450/293963.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/381a3c57-55ee-428a-79fb-a2b3e14cdb00/width=450/293962.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/673a18da-46fa-4943-c119-ef1e715e1600/width=450/293961.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] 1

- 统计数据
  - 发布时间：2023-03-22T18:02:33.842Z
  - 原始模型：SD 1.5
  - 下载数：464
  - 评分人数：1
  - 评分：5
- 下载地址
  - [dylanKowalski.safetensors](https://civitai.com/api/download/models/25122)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/658d40a1-4436-402b-742e-8f1e45328b00/width=450/293966.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/82b34e23-0207-4343-80e1-4f8bf8056200/width=450/293965.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ccc1010c-e748-4a60-d55c-a4cd2cc76100/width=450/274933.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bf5fe5e8-a1f5-432a-8759-5b2a96163600/width=450/274932.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2>ℹ️What is this | 这是什么</h2><p>这是一个风格LoCon / LoRA，可以画出具有繁复结构的类蒸汽朋克/赛博朋克/... 反正就是机械风格的角色，取决于你填什么提示词。风格来源于Dylan Kowalski。</p><p>This is a style LoCon / LoRA which generate highly detailed, complex and steampunk-alike character. The artstyle is from 3D artist Dylan Kowalski.</p><p>训练素材包含10张图片，分辨率512*768。训练基础模型为Chillout</p><p>Dataset contains 10 pictures with resolution at 512*768, trained on chillout.</p><p>预览图片生成使用<a target="_blank" rel="ugc" href="https://civitai.com/models/21952/eris">Eris</a>，它和这个LoCon 配合的很好。</p><p>Previews are generated with <a target="_blank" rel="ugc" href="https://civitai.com/models/21952/eris">Eris</a>, which works very well for this LoCon.</p><p></p><p>更新了一些图片示例 / Updated some images.</p><p>添加了Epoch-06，对画风影响较弱。可自行尝试 / Added Epoch-06, these have lesser effect on style, for those who wish to reduce the artifacts.</p><p></p><h2>💦Known Issues | 已知问题</h2><p>🫱在部分Checkpoint下手画的非常答辩，建议在负面提示词中加入hand。</p><p>Hands are really bad (at least on some checkpoints), avoid generating hands by adding "hand" into the negative prompts, or use "portrait, upper body, close up," in the positives.</p><p>⚖️权重高于0.5会导致画面迅速崩坏，LoRA加载过多可能导致最终图片模糊。建议最高0.5，少加载LoRA。<a target="_blank" rel="ugc" href="https://github.com/klimaleksus/stable-diffusion-webui-anti-burn.git">这个插件</a>有可能缓解。</p><p>Weight above 0.5 tends to destroy image. Loading too many LoRA will produce blurry images. <a target="_blank" rel="ugc" href="https://github.com/klimaleksus/stable-diffusion-webui-anti-burn.git">This </a>might help.</p><p>👦有时候会拒绝画男性，在负面中添加“1girl, female”可以解决这个问题。</p><p>Sometimes it refuses to generate male character, add "1girl, female" in the negative to solve this.</p><p></p><h2>❓How to use | 使用方法</h2><p>✅必须提示词 / Mandatory trigger：</p><p>🔸byDylanKowalski,&lt;lora:dylanKowalski:0.5&gt;,</p><p></p><p>✳️可以搭配以下提示词 / Works well with：</p><p>🔸steampunk（for steampunk aesthetic）</p><p>🔸cyberpunk（for cyberpunk aesthetic）</p><p>🔸intricate details</p><p>🔸ornaments</p><p>🔸prosthesis</p><p>🔸clockwork</p><p>✳️其他和材质相关的提示词 / OTHER PROMTS INDICATE MATERIALS, BE CREATIVE. (EXAMPLE)</p><p>🔸porcelain</p><p>🔸titanium</p><p>🔸gemstones</p><p>🔸holographic</p><p>🔸...</p><p></p><p></p><h2>📝其他信息与参数:</h2><p>🔸Model: Eris / Darelites Fantasy Mix</p><p>🔸Image Resolution / 分辨率: 512*768</p><p>🔸Sampler / 采样器: DPM++ 2M Karras,</p><p>🔸Sampling Steps / 采样步数: 20-40,</p><p>🔸Hires fix / 高分辨率修复算法: R-ESRGAN 4+.</p><p></p><p>🧡 希望你喜欢这个模型。I hope you enjoy it as much as I do. 🧡</p>