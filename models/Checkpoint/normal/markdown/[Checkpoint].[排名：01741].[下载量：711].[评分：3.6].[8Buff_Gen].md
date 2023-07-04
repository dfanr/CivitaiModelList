## 8Buff_Gen
### 一、模型概述

- 标签：`anime`, `generic`, `base model`, `realistic`, `nsfw`
- 下载数：711
- 收藏人数：114
- 评论人数：3
- 评分人数：5
- 评分：3.6

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0_NoEmaPruned

- 统计数据
  - 发布时间：2023-05-28T22:23:22.526Z
  - 原始模型：SD 1.5
  - 下载数：410
  - 评分人数：3
  - 评分：3
- 下载地址
  - [8buffGen_v10Noemapruned.safetensors](https://civitai.com/api/download/models/84090)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/aeaeef02-5c72-48cd-98b8-71aa22e4c0ac/width=450/949077.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/368529ce-dfd8-4ea1-a451-0d9c3a1661d0/width=450/949080.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/841cb36e-9952-4d04-a0cd-7edcb9f39b6a/width=450/949081.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b2b1f2a4-032b-42b2-865e-c466bb9adf39/width=450/949082.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-05-28T21:55:21.705Z
  - 原始模型：SD 2.1
  - 下载数：301
  - 评分人数：2
  - 评分：4.5
- 下载地址
  - [8buffGen_v10.safetensors](https://civitai.com/api/download/models/46665)
  - [8buffGen_v10.ckpt](https://civitai.com/api/download/models/46665?type=Model&format=PickleTensor&size=full&fp=fp16)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a016e763-ba3b-48ed-1050-5a487d30e700/width=450/505206.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a1969fb1-4e15-4e03-45fc-36082cde7f00/width=450/505204.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5c84a441-7d70-4b96-1bae-5ad86e28e400/width=450/505207.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2d4879a6-c6d8-4a51-e4a8-79c5332eb500/width=450/505201.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>NEW! No_EMA Pruned version now available! </p><p>We are proud to announce that Eight Buffalo Media Group has shared our first text-to-image model!</p><p><br />Note that Version 1 of this model still has a few issues, so please be patient as we improve. Constructive feedback is always welcome.</p><p></p><p>This freely available model is a combination of many different models that have been mixed,  merged, and specifically trained on a couple things like people in glass jars. The goal is a strong general model that allows control similar to many anime models, with a more realistic look and feel.</p><p></p><p>See images for prompt matrix testing.</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/952dcfd7-214d-49f1-9f7a-ffaa9ca22900/width=525/952dcfd7-214d-49f1-9f7a-ffaa9ca22900.jpeg" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/89e04397-c8ca-4a13-bed5-06766b7a6c00/width=525/89e04397-c8ca-4a13-bed5-06766b7a6c00.jpeg" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a4631a26-8727-4a83-d815-9a8be784da00/width=525/a4631a26-8727-4a83-d815-9a8be784da00.jpeg" /><p>This model does require a good deal of prompt crafting, the trade off is you have a lot of control on the images you create. I would recommend finding a prompt that generates the style and quality to your liking and saving it as a style.<br /><br />Current known issues/limitations:</p><ul><li><p>More people you add, the more likely you will get blurry/distorted faces</p></li><li><p>Tends to make women young looking. Add negative prompts to help this.</p></li><li><p>Tends to make men old looking. Add negative prompts to help this.</p></li><li><p>When putting people in jars, faces tend to be blurry/distorted. The more jars and more people, the more blurry/distorted. Prompts and and restore faces can help this a little. </p></li><li><p>DPM++SDE Karras sampling method tends to get the best consistent results, but experiment.</p></li></ul><p><br />Going for a general purpose model with a fine level of control. Merged with a lot of different models, but don’t remember all of them. Links below to those that were remembered or provided inspiration for direct training.</p><ul><li><p>Level4 - <a target="_blank" rel="ugc" href="https://civitai.com/models/17449/level4"><u>https://civitai.com/models/17449/level4</u></a></p></li><li><p>Meinahentia - <a target="_blank" rel="ugc" href="https://civitai.com/models/12606/meinahentai"><u>https://civitai.com/models/12606/meinahentai</u></a></p></li><li><p>Girls in Glass Jars (inspiration) - <a target="_blank" rel="ugc" href="https://civitai.com/models/10453/girls-in-glass-jars"><u>https://civitai.com/models/10453/girls-in-glass-jars</u></a> </p></li><li><p>Shampoo-mix - <a target="_blank" rel="ugc" href="https://civitai.com/models/33918/shampoo-mix"><u>https://civitai.com/models/33918/shampoo-mix</u></a></p></li><li><p>Stable Diffusion - <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/stable-diffusion-2-1"><u>https://huggingface.co/stabilityai/stable-diffusion-2-1</u></a></p></li></ul><p>Please review and respect any related licenses. See <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/stable-diffusion-2-1"><u>https://huggingface.co/stabilityai/stable-diffusion-2-1</u></a> for the post know license related to known used models.</p><p></p><p>Common Negative Prompts Used:</p><p>(((worst quality, low quality, bar censor, distorted face))), (((jpeg artifacts, signature, watermark, text, username))), blurry, bad faces, blurry faces, bad eyes, bad anatomy, bad hands, error, extra limbs, missing fingers, extra digit, fewer digits, cropped, normal quality, missing fingers, extra digit, fewer digits, censor, black and white, monochrome, NSFW,</p><p></p><p>See our page on huggingface: <a target="_blank" rel="ugc" href="https://huggingface.co/EightBuff/8Buff_Gen">https://huggingface.co/EightBuff/8Buff_Gen</a></p><p><a target="_blank" rel="ugc" href="https://eightbuff.blogspot.com/"><u>Our Blog</u></a> is now live! Check it out for the latest news and articles: <a target="_blank" rel="ugc" href="https://eightbuff.blogspot.com/">https://eightbuff.blogspot.com/</a></p><p>Shop our<a target="_blank" rel="ugc" href="https://www.redbubble.com/people/EightBuffalo"> <u>RedBubble page</u></a> and help our artists.</p><p>Subscribe to our<a target="_blank" rel="ugc" href="http://patreon.com/EightBuffaloMediaGroup"> <u>Patreon Site</u></a> for News and updates! </p><p>Buy us a Coffee! <a target="_blank" rel="ugc" href="https://www.buymeacoffee.com/eightbuffalo">https://www.buymeacoffee.com/eightbuffalo</a></p><p><a target="_blank" rel="ugc" href="http://eightbuff.com">http://eightbuff.com</a></p><p>Enjoy!</p>