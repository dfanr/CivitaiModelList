## Dragon's Crown Style [Happy Little Accident Edition]
### 一、模型概述

- 标签：`style`, `fantasy`
- 下载数：1795
- 收藏人数：383
- 评论人数：5
- 评分人数：6
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] DragonsCrown-768

- 统计数据
  - 发布时间：2023-03-12T06:09:19.331Z
  - 原始模型：Other
  - 下载数：1435
  - 评分人数：4
  - 评分：5
- 下载地址
  - [DragonsCrown-768.safetensors](https://civitai.com/api/download/models/15827)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ac0c5a93-e10b-42f6-781a-10655fed4d00/width=450/158989.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a95db7f7-a023-4d32-bbd3-a23020882700/width=450/170869.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/99612c44-11db-4879-965d-da2f4044de00/width=450/159008.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/51f9d5e3-bea9-4071-6097-4f353aa29700/width=450/159007.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] Dragons Crown Artbook Style

- 统计数据
  - 发布时间：2023-03-12T06:09:19.331Z
  - 原始模型：Other
  - 下载数：223
  - 评分人数：2
  - 评分：5
- 下载地址
  - [DragonsCrownArtbook.safetensors](https://civitai.com/api/download/models/21413)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/79466952-fa0c-4af0-fd18-60b0b0445900/width=450/227537.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cc330bfe-7c10-45dd-2b0d-d5109c7b0000/width=450/227536.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0c01765e-1262-4071-fe75-4ff6f4551500/width=450/227535.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/34acd886-9264-43ba-71bd-0c9605f6b700/width=450/227534.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] DragonsCrown-768-Mix

- 统计数据
  - 发布时间：2023-03-12T06:09:19.331Z
  - 原始模型：Other
  - 下载数：137
  - 评分人数：0
  - 评分：0
- 下载地址
  - [DragonsCrown-768-Mix.safetensors](https://civitai.com/api/download/models/15828)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ac0c5a93-e10b-42f6-781a-10655fed4d00/width=450/159029.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/99612c44-11db-4879-965d-da2f4044de00/width=450/159028.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/51f9d5e3-bea9-4071-6097-4f353aa29700/width=450/159027.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/efd2d6ea-7569-43c6-a6f0-ed491deae200/width=450/159026.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This LoRA was made on six images only of official character art from the game Dragon's Crown by Vanillaware as an experiment with dataset sizes and new training options. It was not intended to be a fully fledged style LoRA let alone something to be shared but I had a bit too much fun with it to keep it to myself.</p><p>If you're willing to keep this in mind and is prepared to do a little wrangling to get results here's how it works.</p><p><strong><u>What this LoRA likes generating</u></strong><br />Fantasy races<br />Fantasy settings<br />Armor, boy does it love heavy armor stuff<br />Big ladies<br />Big boys<br />Helmets<br />Tattoos<br />Swords,staves,arrows and so on</p><p><strong><u>What this LoRA doesn't like generating</u></strong><br />Anything outside the above list. See "Dataset tag occurance" below for things to add to negatives if they're persistent.<br />Faces. Not much of them in the dataset as you can see but they inpaint nicely at full resolution.</p><p>Beyond that it seems to work decently at low weights to stabilize txt2img outputs. Including a bit of it's style in the process of course.</p><p></p><p><strong><u>How to use</u></strong><br />As for how well it works for you is heavily down to your model and how well the LoRA weights matches up with it. I recommend AOM2 users to stay within the recommended 5 - 6 CFG range and lower the default negative (worst quality, low quality:1.4) prompt down to 1.0.</p><p>For samplers I just tested Euler A and DPM++ 2M Karras at 20 steps, both work fine, the latter might be slightly more on style.</p><p>LoRA weight can be anything from 0.1 to 1.0 depending on prompt and model.</p><p><strong><u>Prompting specific characters</u></strong><br />Sorceress, dwarf,knight,amazon,elf and wizard can all be prompted simply by describing them. Due to only having one image each you may have to tweak LoRA strength find the optimal balance between versatility and character accuracy. <br />I've included a grid image containing a wildcard prompt for those who want to see how.</p><p><strong><u>Versions</u></strong><br />DragonsCrown-768 - Last epoch. Might be slightly more strict in its style.<br />DragonsCrown-768-Mix - Epoch mix. Might be slightly more versatile at the cost of style.<br />DragonsCrownArtbook - A completely new LoRA trained on the official art book, a larger dataset with a darker gritter oil painting like style.<br /><br /><strong><u>Misc</u></strong><br />768 resolution trained on NAI. Tested on NAI + AOM2. All sample images are raw untouched txt2img unless otherwise specified.<br />Dataset images can be seen <a target="_blank" rel="ugc" href="https://imgur.com/a/eDL0f7c">here</a>.</p><p><br />Don't forget to review and upload your own images, it's always fun to see what you're creating! <br />Like my LoRAs and want more? Please consider a small tip towards my electricity bill and further training &gt;.&lt;</p><p><strong><u>Dataset tag occurance</u></strong><br />solo 100%<br />weapon 67%<br />long hair 67%<br />boots 67%<br />1boy 50%<br />male focus 50%<br />1girl 50%<br />gloves 50%<br />armor 33%<br />sword 33%<br />helmet 33%<br />breasts 33%<br />staff 33%<br />brown eyes 33%<br />large breasts 33%<br />thighs 33%<br />muscular 33%<br />hood 33%<br />belt 33%<br />shield 12%</p>