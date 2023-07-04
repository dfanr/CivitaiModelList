## Fairy Knight Tristan/Baobahn Sith (FGO)
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `female`, `fate grand order`, `game character`
- 下载数：1492
- 收藏人数：344
- 评论人数：5
- 评分人数：2
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] FGOTrissithFinal

- 统计数据
  - 发布时间：2023-02-27T22:19:13.143Z
  - 原始模型：SD 1.5
  - 下载数：1341
  - 评分人数：1
  - 评分：5
- 下载地址
  - [FaeTristanV5.safetensors](https://civitai.com/api/download/models/16387)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d050e211-00d2-4759-e8ba-a2725cb66500/width=450/165291.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e4eb6f9a-8eb0-46d2-019b-0d6947b18800/width=450/165309.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/af9c15d2-629a-44a1-4081-79fa2c382900/width=450/165310.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ef0052fb-f462-464a-7f6f-dabc07265100/width=450/165308.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] FGOTrissithFreefit

- 统计数据
  - 发布时间：2023-02-27T22:19:13.143Z
  - 原始模型：SD 1.5
  - 下载数：151
  - 评分人数：1
  - 评分：5
- 下载地址
  - [FaeTristanV2.safetensors](https://civitai.com/api/download/models/16388)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/554841cd-9aba-4d66-982b-445dfb46e200/width=450/165325.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8c86c992-5913-4111-01b1-a441867a0900/width=450/165324.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/05ace272-7584-4a38-e325-1b605d409300/width=450/165323.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c2d38753-f8d1-408d-d9a0-daed223f8c00/width=450/165322.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Fae Knight Tristan from Fate Grand Order. There is a normal TI somewhere out there, but no LORA yet, so here you go. It includes all 3 of her ascensions plus a "freefit" mode for help with alternate costumes.</p><p></p><p>Be careful with the tags and tokens. There are a bunch, with two calling upon literally every image in the dataset (<strong><em>baosith</em></strong> and <strong><em>fktristan</em></strong>, testing suggests that you don't use them), 3 for each ascension (<strong><em>1asc, 2ndasc, 3rdasc</em></strong>), and 2 more for custom outfits (<strong><em>freefit</em></strong> and <strong><em>alternate costume</em></strong>). The asc tokens were meant to simply be used by themselves so they would generate the corresponding outfit without any specifics, but each time I trained this LORA that plan failed. So they more or less just guide the ai to what needs generating. Same with the freefit token, though it should have more effect on the second LORA. I should also stress that like the first two tokens, <em>DO NOT USE HER DANBOORU TAG</em>. I am uncertain if it really makes a difference, but it seems all three of those tags just confuse the AI and fuck up the clothes.</p><p></p><p>Tags aside, every outfit seems to come out pretty accurate for the most part. That said, below you'll find two LORAs to download, because strangely, while one of them failed mostly to grasp the clothing concept, it simultaneously generates REALLY neat images compared to the other. So if you want my advice, use that one specifically for alternate outfits, and the main one for Sith's ascensions.</p><p>Additionally, regarding the main LORA, I also advise you to exclude any unused outfit tokens in the negatives prompt, because sometimes just one tag (like grey skin) might cause it to jumble up the clothes and give you some kind of amalgamation.</p><p></p><p>Lastly, don't ever expect it to get the heels right. It never will.</p><p></p><h3>TLDR:</h3><ul><li><p>Don't use baosith, fktristan, OR HER TAG NAME. Just prompt the outfit tags and details (see previews).</p></li><li><p>Use the Freefit LORA to help with custom outfits, and the final version for her canonical ones.</p></li><li><p>It will always fuck up the heels, there ain't no way it's gonna be consistent with that.</p></li><li><p>When trying for one ascension outfit, make sure to exclude the tokens for the others in the negative pompt.</p></li><li><p>Beware of tags that apply to all her outfits, specifically grey skin or pale skin. Head specific tags should be fine.</p></li><li><p>Her first outfit sometimes gives her the headpiece from 2nd asc, just put "black headpiece" in the negs to fix that.</p></li><li><p>You'll notice this soon enough, but perhaps thanks to either me or all the artists that have drawn Sith, she will have her hand by her mouth in an ojousama-ish pose 85% of the time, unless prompted to do otherwise.</p><p></p><p></p></li></ul><p>Trained on NAI with 202 images (Freefit with 162), extensively tested across multiple models. NSFW capable and mostly style compatible (mainly in freefit mode).</p><p><strong>Images in preview may be from past versions! Do not expect full replication!</strong></p>