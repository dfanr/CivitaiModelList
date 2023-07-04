## Based66
### 一、模型概述

- 标签：`anime`, `female`, `style`, `girls`
- 下载数：1600
- 收藏人数：231
- 评论人数：1
- 评分人数：5
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v3.0

- 统计数据
  - 发布时间：2023-05-11T18:02:11.630Z
  - 原始模型：SD 1.5
  - 下载数：1399
  - 评分人数：5
  - 评分：5
- 下载地址
  - [based66_v30.safetensors](https://civitai.com/api/download/models/67841)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f6561701-6df9-4c1b-b55d-67e87255a88d/width=450/759689.jpeg" /> |
| ---- |

#### [版本1/共2个版本] v2.0

- 统计数据
  - 发布时间：2023-05-11T08:47:37.811Z
  - 原始模型：SD 1.5
  - 下载数：201
  - 评分人数：0
  - 评分：0
- 下载地址
  - [based66_v20.safetensors](https://civitai.com/api/download/models/66140)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6607c827-3964-4631-b2ad-66c1ec1a2293/width=450/738180.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1dd96146-47e2-4dfa-bcbf-09212ba2237e/width=450/738181.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9aa57450-ad95-4562-a8ff-8ef5582cf858/width=450/738182.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fb6b4cb8-eabc-45fd-9e84-2c3f8d3bf023/width=450/738251.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3><a target="_blank" rel="ugc" href="https://mega.nz/file/qExmQBQA#9eyI78TMEJu8V4c84UWitrlDAjyqxrxSVc1D5ktb87k">CC License</a></h3><p></p><p>The next installment in my Based mixes, Based66 aims to have better LORA compatibility while maintaining the more sharper lines/softer color Anime appearance I wanted with the future installment of my models. This model was mostly made with the desire to circumvent the troubles Based65 had with LORA compatibility due to too many finetuned models which I was unaware of in the mix, so in Based66 the only finetuned model I made sure to use in the mix was HLL4, the 4th installment of the Vtuber finetuned model which I was using the 3rd version in Based64 and Based65. <a target="_blank" rel="ugc" href="https://huggingface.co/CluelessC/hll-test/tree/main">The 4th version of the Vtuber finetune is here like always</a>. (B66 was also made to get into the current rise of mixes being posted online, despite B64 and B65 being uploaded to my Civitai page not too long ago those models were made way long before so B66 is the actual "new player" I decided to introduce into the current meta for more recent model mixes)</p><p></p><p>Based66 was made with a bigger focus on MBW and presets, I made sure to focus on specific seeds and the x/y grid option provided by the Supermerger to ensure specific issues were solved and avoided with earlier iterations of the model which were lost to the void (aside from the official first version of the model that I uploaded to huggingface, the only issue with that model was anatomy and some weird lighting issues but it was fixed with version 2) however those fixes lead to some good and some bad of the model which I will try fixing in the future for version 3, which currently they aren't as big of an issue like the issues with version 1 but I'll explain the good quirks and bad quirks about this model</p><p></p><h3>Usage</h3><p>I was testing the max steps I'm fine with 40 with CFG scale 10 with some example outputs and it works fine but you can just keep to the trusty 7 CFG scale and 20-25 steps I usually use but otherwise the most important thing to know about this model is that it's not VAE baked, so there's no VAE in this model because I prefer all models make me pick my own VAE in the stable diffusion settings so use <a target="_blank" rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt">kl-f8-anime2</a> by <a target="_blank" rel="ugc" href="https://huggingface.co/hakurei">Hakurei</a>, it looks a lot nicer in B66 avoided that super orange tint that I didn't like with B64, otherwise that's all you have to know about using this model, it works like any other Anime mix so just use it as you please, but now we get into the specific issues I saw with V2 I saw with some earlier testers</p><p></p><p><strong>V2 needs stronger weights (1.x) with specific prompts to have the model listen to it</strong></p><p><strong>V2 is too faithful to LORAs leading to the need for stronger weights with specific prompts to have the model output it correctly</strong></p><p><strong>V2 has trouble with multiple LORAs (eg: concept/character/style) I will be working on V3 right away to fix this issue</strong></p><p></p><p>these are all issues I will fix in V3 however V2 being too faithful to LORAs is something I desired but at a cost, B65 had trouble with LORAs so my goal with B66 was to have it listen/understand LORAs for outputs a lot more better which it did however this issue is not as huge as the issues I saw testers have with V1, so I'm fine with this issue for now until I put effort into seeing what can fix that for version 3.</p><p></p><p><strong><em>Which all major issues with V2 have been fixed with the V3 upload so you can use up to 3 LORAs and there's no need for stronger weights to get the desired output especially when using LORAs compared to V2</em></strong></p><p></p><h3>Future Notes</h3><p>V3 may be the final version of this model before I proceed to Based67, for now I'm satisfied with the major issues I have fixed but if you're looking for the unpruned versions of Based66 just go onto my <a target="_blank" rel="ugc" href="https://huggingface.co/AnonymousM/Based-mixes/tree/main">huggingface page</a> to find them all</p><p></p><h3>Support</h3><p>Pretty sure a lot of model mixers have wrote that they would love it if you support them in anyway to links that they provide given that model mixing does take a long time (not as long thanks to supermerger but still does take a lot of time out of the day to get the right outputs) and you can do that for me, I would just be happy if you support me by looking at my <a target="_blank" rel="ugc" href="https://www.pixiv.net/en/users/90601160">Pixiv</a> or <a target="_blank" rel="ugc" href="https://twitter.com/AnonymousM_667">Twitter</a> for any outputs I make with my mixes and LORAs I train (which I will be going back to since I need to get back into the LORA meta) but if you wish to support me financially which would help me out in a lot of ways please do, I have the basic sites that most people use for donations like <a target="_blank" rel="ugc" href="https://ko-fi.com/anonymousm">Ko-Fi</a><a target="_blank" rel="ugc" href="ko-fi.com/anonymousm"> </a>and whatever but I also have services available for anyone that has stuff they want me to do work on, you can see all of them on my <a target="_blank" rel="ugc" href="https://linktr.ee/anonymousm">Linktree!</a> Most of all just have a great time with B66 and ensure you have fun while using it (because at this rate I feel like I'm done with B66 and will move onto B67) that's the biggest support you can do for me! Until then, I'll go back to LORA baking and focus my efforts on there until I have time to pour into making version 3 of this model that fixes the need for stronger weights on prompts.</p>