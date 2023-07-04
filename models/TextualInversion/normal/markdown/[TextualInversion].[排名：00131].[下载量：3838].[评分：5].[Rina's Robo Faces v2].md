## Rina's Robo Faces v2
### 一、模型概述

- 标签：`cyborg`, `cyberpunk`, `scifi`, `robots`, `style`
- 下载数：3838
- 收藏人数：617
- 评论人数：20
- 评分人数：11
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2

- 统计数据
  - 发布时间：2023-02-02T05:23:45.659Z
  - 原始模型：SD 1.5
  - 下载数：3052
  - 评分人数：8
  - 评分：5
- 下载地址
  - [emb-rrf2.pt](https://civitai.com/api/download/models/6271)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da897277-5ebf-4e15-0601-afc3c74bb700/width=450/55174.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bc3f5ba2-60fb-49ae-a0df-6b56811aa000/width=450/55173.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c5a326c5-850d-4683-05d2-95d3f172f900/width=450/55172.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/066efb3f-3b2b-47fd-a4f7-67ade62f8300/width=450/55171.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] 1.0

- 统计数据
  - 发布时间：2023-02-02T05:23:45.659Z
  - 原始模型：SD 1.5
  - 下载数：786
  - 评分人数：3
  - 评分：5
- 下载地址
  - [emb-rrf-low.pt](https://civitai.com/api/download/models/4052)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5bfd9436-700e-4c7a-725d-ff83b9619000/width=450/25412.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/714961ab-bd4a-423d-36c0-6e3fdc269500/width=450/25411.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/69bd7d8f-25a4-4dfa-88aa-0d3159db9f00/width=450/25410.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a7907135-2b6a-4aa5-3ed9-ab33af813d00/width=450/25409.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Updated with v2! The first version had some shortcomings, namely the strong asian predilection of facial features, and being tricky to trigger. The new embedding works better, and also produces crisper lines in many cases. The original training data included a couple of movie stills that weren't great quality, as well as a several images of makeup effects, which were amazing makeup effects, but I believe it was limiting the quality of the embedding. The movie stills were scrapped, and the training data was padded with images generated using the v1 embedding. The makeup images were run through an img2img prompt with the embedding, making images that still imparted the effect I wanted, but with cleaner source images. I did the same with the digital paintings that were in the training data. I have had the best luck with the new embedding just having (cybernetics by emb-rrf1:1.0) as the first tag with a low CFG (6-8), and playing with the weight as needed depending on how big the rest of the prompt is. 1.0 seems to work fine with small prompts, but if you are the type to over-engineer the prompt, or just want a more pronounced effect, feel free to fiddle with it. Most of the sample images were made with RinaMix2 (the pruned copy here on CivitAI, check my profile.) I have also tested in several other models, and it works pretty well there, but I didn't spend as much time experimenting with other models. This was, after all, designed for my use, so the vast majority of testing was done in my mix. I've included a few samples from other models, as well as a couple "bikini" shots to show what it does in prompts with no other mention of robots or sci-fi. Other folks models are the last images. A few fro  Elldreth's lucid, one from Protogen 5.8, and one striking image from aEros.</p><p></p><p>I hope you enjoy it!</p><p></p><p>Original Description:</p><p>This TI was trained on several images found online, some from digital artists, some from make-up artists, and a few from the TV show Westworld and the movie version of Ghost in the Shell. It's purpose was to create segmentation of faces and bodies into artificial looking plates. I couldn't get the effect I was looking for with prompts alone in the checkpoints available to me, so I decided to test my recent video card purchase with my first embedding.</p><p></p><p>Anyway, details. I've found after a bit of experimentation that tattoos work really well to trigger the embedding. They are not absolutely necessary, and I invite you to experiment to your heart's content, because the embedding will create segmentation on it's own, but not 100% of the time. However, if it sees a black tattoo, the embedding will latch onto that and do it's best to turn it into a seam, or if it's a solid black patch, it will show robotics underneath. As you will see in the first few sample images, the embedding skews toward asian features. In later images, I have added (asian:1.1) to the negative prompt to balance this out a bit. The early samples are of a "beautiful cyborg", later samples are of a "beautiful fantasy warrior in gold and steel armor". It also tends VERY strongly toward close-up portraits. You can change this with positives such as wide shot, full body and negatives like close shot, but you may need to weight them pretty heavily to break away from portraits.</p><p></p><p></p><p>EDIT: Added an image (#20) that was the prompt from image #7 (and a few others) and ran it through RatnikaMix (also here at CivitAI <a target="_blank" rel="ugc" href="https://civitai.com/models/2670/ratnikamix">https://civitai.com/models/2670/ratnikamix</a> ) with a random seed. I lowered the weight on the tattoo tag to 1.1 for that image.</p>