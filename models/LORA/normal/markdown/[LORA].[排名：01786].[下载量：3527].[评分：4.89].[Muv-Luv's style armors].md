## Muv-Luv's style armors
### 一、模型概述

- 标签：`female`, `highly detailed`, `scifi`, `robots`, `armor`, `clothing`
- 下载数：3527
- 收藏人数：771
- 评论人数：2
- 评分人数：9
- 评分：4.89

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2.0

- 统计数据
  - 发布时间：2023-04-12T00:55:24.445Z
  - 原始模型：SD 1.5
  - 下载数：2143
  - 评分人数：5
  - 评分：4.8
- 下载地址
  - [fortifiedsuitV2.safetensors](https://civitai.com/api/download/models/43118)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/70a04e7f-665b-476b-65f9-3c5f1eeb3100/width=450/473014.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/632e1384-ea07-43de-346d-484594685500/width=450/473015.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/73c05177-2857-4af8-f228-17ec3eb77500/width=450/473104.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5d44106f-9aa2-4464-1cbe-a5602ab51900/width=450/473591.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] 1.0

- 统计数据
  - 发布时间：2023-04-11T22:11:02.744Z
  - 原始模型：SD 1.5
  - 下载数：1384
  - 评分人数：4
  - 评分：5
- 下载地址
  - [fortifiedsuit.safetensors](https://civitai.com/api/download/models/13238)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b1588b53-fdbf-4730-66fa-bc502aedb400/width=450/127967.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8aa1818d-4310-44fa-a1d6-0849bb19fd00/width=450/127970.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d6696bca-3e55-4dc8-b405-15d71858c000/width=450/127969.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e41e0792-76bd-42e8-c751-9e335c1e2100/width=450/127968.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3>=== V2 ===</h3><p>The trigger is still <strong>fortified suit</strong>, BUT the second recommended tag isn't <u>bodysuit</u> anymore, it's <strong>plugsuit</strong> with the color you want. For example: <strong>((blue:1.5) plugsuit)</strong></p><p>The sweet-spot is still between 0.6 and 0.7. "Animal ears" issue in the previous version is fixed but not heterochromia (unfortunately I don't even know how to fix that) so keep "heterochromia" in your negative.</p><p><strong>Males are way easier to generate</strong>, it's not perfect but you don't need to go crazy with the weights anymore. The armor as a whole is also more consistent and you shouldn't find missing parts on your gens.</p><p>The dataset was a bit too contaminated by the pink colored armor from Sumika. So you still need to add more weight to all your colors (unless you like pink). I'll try to fix that in the next version.</p><p>This version should work well with realistic models and any artstyle (feel free to test and report here if you encounter an issue).</p><p>=============================</p><p><strong>Not made for realism! It only works for anime style.</strong></p><p>It's my first LoRA so I think it's not up to the standard yet. Anyway, it produces muv-luv armors which I couldn't get with any model or prompt (that's how niche it is).</p><p>You use it by adding "<strong>fortified suit</strong>" tag in your prompt and I recommand adding "<strong>bodysuit</strong>" tag as well. The sweet-spot for this LoRA seems to be <u>between 0.6 and 0.7</u> for the weight.</p><p>It has been trained on 126 images (official arts and fanarts), it's <strong>very biaised against males </strong>since males are only 20% at most of the dataset! Although, if you put a very high weight like (1boy:1.9) and (1girl:1.3) in negative you still can get some guys.</p><p>There are a few issues with <strong>heterochromia</strong> and <strong>animal ears</strong>, so put these in negative if you don't want that in your art.</p><p>To change the color of the armor you can write something like (blue:1.5 and fortified suit), (black:1.5 and bodysuit).</p><p>Other related Muv-luv stuff (robots): <a target="_blank" rel="ugc" href="https://civitai.com/models/8584/muv-luv-tsf-concept-lora">https://civitai.com/models/8584/muv-luv-tsf-concept-lora</a></p>