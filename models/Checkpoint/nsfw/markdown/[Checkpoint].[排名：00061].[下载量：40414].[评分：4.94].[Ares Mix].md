## Ares Mix
### 一、模型概述

- 标签：`character`, `photorealistic`, `sexy`, `female`, `porn`, `nudes`, `woman`, `photography`, `photorealism`, `women`
- 下载数：40414
- 收藏人数：5175
- 评论人数：72
- 评分人数：70
- 评分：4.94

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v0.2

- 统计数据
  - 发布时间：2023-04-28T12:35:38.631Z
  - 原始模型：SD 1.5
  - 下载数：9300
  - 评分人数：24
  - 评分：4.83
- 下载地址
  - [aresMix_v02.safetensors](https://civitai.com/api/download/models/57295)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9ed9ec26-b48a-49c1-f679-eea456c19600/width=450/622547.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9b7efc64-57c9-4ce4-ccc3-0dccd3005600/width=450/622514.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0506feb7-f4d7-4991-ef46-41fb6c438400/width=450/622516.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0bd55556-3ff1-4953-d861-3aebf0f81900/width=450/622521.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v0.1

- 统计数据
  - 发布时间：2023-04-28T10:31:19.269Z
  - 原始模型：SD 1.5
  - 下载数：31114
  - 评分人数：46
  - 评分：5
- 下载地址
  - [aresMix_v01.safetensors](https://civitai.com/api/download/models/8145)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e5094812-9aa8-4809-7429-6b79cab25d00/width=450/76977.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6385feb7-285d-47d9-7325-19691cf7a600/width=450/76989.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b0259723-18fc-4149-1e09-23d3f80dc700/width=450/76988.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f4f03cb5-4cf9-4ea9-1443-95ac7dffc200/width=450/76987.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Attention: You need to get your own VAE to use this model to the fullest. While it does work without a VAE, it works much better with one. I recommend you try <a rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/tree/main">this one</a> out.</p><p></p><p>Hey everyone. After GrapeLikeDreamFruit hit, I started missing having a more general purpose model for the mundane kind of pictures - nude photographs on different backgrounds and some light hardcore capabilities. This model here is my response to that need. It handles the female nude superbly, and while it's less of an artistic model than GrapeLike, it's still quite capable in that regard. It's quite good at hardcore, even if that is just a secondary goal for this model, and can be prompted for a variety of acts. Model has a good response to Danbooru tags.</p><p></p><p>This model involves dreamlike photoreal, so here is the <a target="_blank" rel="ugc" href="https://huggingface.co/dreamlike-art/dreamlike-photoreal-2.0/blob/main/LICENSE.md">license</a> that you must abide by.</p><p></p><p>See examples for some ideas.</p><p></p><p>Deeper explanation:</p><p>This model merge was done following a similar phylosophy to GrapeLike: a Block merge between a realistic anatomy + skin core and a posing anime core. The block merge is done in such a way as to emphasize the anime core in the center of the Unet, while rapidly decaying back to the realistic core at the edges. This has the effect of bringing a lot of posing and composition ideas from hentai models inside the photorealistic core we have available without touching textures and photorealism. Full recipe follows:<br /><br />Anatomy core:</p><p>izumi, F222, dreamlike photoreal, realistic vision 1.2, sxd, all at the same intensity. ie, the merge chain was:<br />(((izumi + F222 0.5) + dreamlike photoreal 0.33) + realistic vision 0.25) + sxd 0.2</p><p></p><p>Anime core:</p><p>Anything v4.5 merged with Basil Mix using the same block merge coefficients used in mixing <a target="_blank" rel="ugc" href="https://civitai.com/models/4451/abyssorangemix2-nsfw-hardcore">Abyss Orange Mix</a>, then merged 40% with grapefruit, the result was merged 30% with gape60 and finally 15% with RPG v4.</p><p></p><p>Bringing both together:</p><p>The block merge for both was done using a formula. I kept the bottleneck Model A was anatomy, model B was anime. I kept the center lalyer at 0.7, as well as base alpha, then followed <code>0.8/(n**1.1)</code>as a merge rule, with n being distance from the center. Full numbers were "0.05199847612695355,0.05722134125067434,0.06354625877794251,0.07135480548979826,0.08122523963562354,0.09407671474206218,0.11146117361039158,0.13621438760332552,0.17411011265922482,0.23892225595753655,0.373213196614723,0.8,0.7,0.8,0.373213196614723,0.23892225595753655,0.17411011265922482,0.13621438760332552,0.11146117361039158,0.09407671474206218,0.08122523963562354,0.07135480548979826,0.06354625877794251,0.05722134125067434,0.05199847612695355".</p>