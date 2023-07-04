## Art of Magic the Gathering
### 一、模型概述

- 标签：`style`, `fantasy`
- 下载数：489
- 收藏人数：118
- 评论人数：1
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] 32

- 统计数据
  - 发布时间：2022-11-21T23:45:39.877Z
  - 原始模型：SD 1.5
  - 下载数：454
  - 评分人数：0
  - 评分：0
- 下载地址
  - [artOfMagicThe_32.ckpt](https://civitai.com/api/download/models/1016)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da1fbae6-26e7-4b55-4b3c-82e73534c400/width=450/36343.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d770bf8b-2c4a-4e1f-455f-979ab34da200/width=450/36342.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dd665ad2-34d1-4aaa-ffa0-9e85dafe7900/width=450/36344.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8d8e3144-98c9-47af-ea42-b6298fc42b00/width=450/36345.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] 16

- 统计数据
  - 发布时间：2022-11-21T23:45:39.877Z
  - 原始模型：SD 1.5
  - 下载数：35
  - 评分人数：0
  - 评分：0
- 下载地址
  - [artOfMagicThe_16.ckpt](https://civitai.com/api/download/models/1015)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da1fbae6-26e7-4b55-4b3c-82e73534c400/width=450/8469.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d770bf8b-2c4a-4e1f-455f-979ab34da200/width=450/8468.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dd665ad2-34d1-4aaa-ffa0-9e85dafe7900/width=450/8470.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8d8e3144-98c9-47af-ea42-b6298fc42b00/width=450/8471.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Originally posted to <a href="https://huggingface.co/TopdeckingLands/ArtOfMtg_V1" rel="ugc" target="_blank">HuggingFace by TopdeckingLands</a></p><p><br /></p><p>Art of MtG v1</p><p>Experimenal model, based on ~5000 arts for cards from Magic: the Gathering game on top of SD1.5 model. Large variety of cards from 2014 to 2022 was used. Logos, guild/clan icons and mana symbols were not part of training set as Fan Content Policy explicitly prohibits their use. Each art was captioned with card name, artist, colors and name of color combination, type line, set name and BLIP description.</p><p>You can try it out on <a href="https://huggingface.co/spaces/TopdeckingLands/Diffusion_Space" rel="ugc" target="_blank">Huggingface Space</a> (probably slow) and <a href="https://colab.research.google.com/drive/109CvcHvmfTv3hlS8DSetiky9kH1WVKFf" rel="ugc" target="_blank">Google Colab</a></p><p><br /></p><p>Usage</p><p><strong><em>mtg art</em></strong> is the main prompt to use, and adding <strong><em>card frame</em></strong> negative prompt is recommended.</p><p>Model has understanding of some planes, terms and characters to different degree. Previews below use negative prompt <em>lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry</em>, Euler sampler, 20 steps and CFG 7.</p><p><br /></p><p>Planes</p><p>Planes that did not have sets named after them are unknown to model.</p><p>Characters</p><p>Even main cast of planeswalkers that appear often does not work consistently, even if it's often possible to recognize character - the styles are wildly different between specific original arts.</p><p>Species</p><p>Model has good understanding of <strong><em>phyrexian</em></strong> and Emrakul(tentacle) type of <strong><em>eldrazi</em></strong> among others</p><p>Artists</p><p>A total of 200 artists had at least 5 images included, 50 of them had more than 30 each. It's safe to expect every major modern MtG artist style to be represented and reproducible to some degree. Styles are not supposed to be representative of artist's real style and are biased by types and colors of cards illustrated by them.</p><p><br /></p><p><br /></p><p>Color combination names used</p><ul><li>0-color: colorless</li><li>1-color: monowhite, monoblue, monoblack, monored, monogreen</li><li>2-color: guilds of Ravnica</li><li>3-color: shards of Alara, clans of Tarkir, triomes of Ikoria, families of New Capenna (relevant two)</li><li>4-color: no special names</li><li>5-color: WUBRG</li></ul><p>Different color combinations have different aesthetic attached. X room for example:</p><p><br /></p><p><br /></p><p>Improvements considered for V2</p><ul><li>Filter out highly off-style Secret Lar card / Variations</li><li>Use scryfall art tags for descriptions in addition to BLIP, dropping use of color combination names</li><li>Add more character-centric data or refine on their art after main training</li><li>Fix BLIP hiccups hiccups hiccups hiccups hiccups hiccups hiccups hiccups</li></ul><p>Fine-tuning data was provided by Wizards of the Coast under their <a href="https://company.wizards.com/en/legal/fancontentpolicy" rel="ugc" target="_blank">Fan Content Policy</a>. Note you can't use this model for commercial purposes, as it's strongly against given policy.</p>