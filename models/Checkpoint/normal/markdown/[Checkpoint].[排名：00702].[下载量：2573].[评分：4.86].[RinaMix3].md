## RinaMix3
### 一、模型概述

- 标签：`scifi`, `base model`, `fantasy`, `portraits`
- 下载数：2573
- 收藏人数：707
- 评论人数：16
- 评分人数：7
- 评分：4.86

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] RinaMix3

- 统计数据
  - 发布时间：2023-04-03T04:08:28.145Z
  - 原始模型：SD 1.5
  - 下载数：835
  - 评分人数：0
  - 评分：0
- 下载地址
  - [rinamix3_.safetensors](https://civitai.com/api/download/models/34169)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5eab779b-2d58-4d7b-8bb3-3ff1e7c79a00/width=450/390414.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d7512239-389a-4cc3-0ef1-40e2be50b600/width=450/390413.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2aab379f-e817-4da3-12a0-dc6f0b36a100/width=450/390412.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/963e58d6-060d-41a9-8bc9-9356e375b400/width=450/390411.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] RinaMix2-fp16-no_ema

- 统计数据
  - 发布时间：2023-04-03T04:08:28.145Z
  - 原始模型：SD 1.5
  - 下载数：1738
  - 评分人数：7
  - 评分：4.86
- 下载地址
  - [rinamix3_rinamix2Fp16NoEma.safetensors](https://civitai.com/api/download/models/5264)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/27aae1fb-6396-4df4-5684-83cccb4fb400/width=450/41136.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d5d9790e-9df6-46a3-cd2a-f5f41fd57a00/width=450/41135.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/53877f36-f5ce-442c-cc5c-17684d468b00/width=450/41134.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ae15cd0-b7ae-4865-2fc2-c8ea9e69da00/width=450/41133.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>EDIT: Updated with v3. RinaMix3 is my daily driver. RinaMix2 was a merge of 8 other models, this one is a merge of 16. Most of the originals are there, but some were either updated or replaced with newer stuff closer to what I wanted. ATSB, Float's and Anything and Everything were replaced with AOM, Rev Animated, RealDosMix and others. RPGv2 was replaced with RPGv4, etc.</p><p>If the sample image has a tag that starts with "emb-", it's one of the embeddings listed on my profile, in case you're trying to get an exact replica. Also used bad_prompt_version2 and easynegative negative TIs in some cases. I know I used emb-rrf2 and emb-rrf-low (Rina's Robo Faces) and emb-anada (Ana de Armas embedding) and emb-babs (Barbara Palvin embedding), maybe others but I think that's it.</p><p> Here's the full list:</p><p>Rev Animated</p><p>AOM3A1B</p><p>RPGv4</p><p>RealEldenApocalypse</p><p>Hassan1512</p><p>RealDosMix</p><p>Dreamlike Diffusion</p><p>Sci-fi Diffusion</p><p>Chilloutmix_NI</p><p>Deliberate</p><p>Epic Diffusion</p><p>epi_hyperphotogoddess</p><p>KotosMix</p><p>Slimy Supermodel 2</p><p>MoistMix</p><p>Rev3</p><p>Noise Offset checkpoint at .6, because a full strength 1 was too dark for my tastes.</p><p>The point of this mix was the same as the last one, to get nearly (but not quite) photorealistic portraits and decent fantasy and sci-fi stuff out of a general purpose mix. while testing and generating samples, I picked some prompts from <a target="_blank" rel="ugc" href="http://krea.ai">krea.ai</a> to test this merge with, and it's much more colorful than RinaMix2, and is capable of better 2.5D anime-inspired stuff. The Noise Offset allows for some good contrast, too. Anyway, I'm happy with it, so I'm throwing it up for you guys. Like the last one, this is a pruned fp16 copy, though I think this one is EMA-only, whereas the last one was no EMA. Don't know the difference, just passing it on. The very large image in the cavern with goofy escher-esque geometry doesn't have a prompt, because it was just the result of goofing off in the OpenOutpaint extension with an -inpainting version of this mix. I've included the original image next to it, which does have a prompt. Have fun, and post images if you make something.  :)</p><p></p><p>EDIT: My upload kept timing out on the full merge, so I'm uploading the pruned fp16-noEMA version.</p><p>EDIT2: sorry, I left up the pics from the unpruned model, so they were not reproduceable. They have all been replaced by images genned in the pruned copy, in some cases from the same seed. Others I just did random batches with the existing prompts. Please note that some will require my robo faces embed or the Ana hypernetwork to reproduce exactly (available here on CivitAI). They are intended to show image quality. I haven't uploaded the Nuke embed yet, used toward the end of the sample set.</p><p>This is my model for personal use, but I thought others may want to try it out. It was mostly merged for detail and image quality, but I haven't done a whole lot of testing on its versatility. It does pretty decent portrait work, not quite as clean as Protogen, but good enough for my purposes. It does well with the scenarios I've fed it. I had to mix my own model, though, because my favorite embedding (<a target="_blank" rel="ugc" href="https://civitai.com/models/3670/rinas-robo-faces">Rina's Robo Faces</a>, see samples above and at link) doesn't always work reliably on some newer merges. I still have to weight the tattoos heavily to get them to work on this mix, but the output is better than the merge I had previously been using. This merge includes the following models, so whatever tags work with them MIGHT work with this merge. I haven't tested. I was using Add Difference most of the way through the merge, so as not to overtune it with repeated weights.</p><p>ATitanStrawBerry</p><p>RPGv2</p><p>Float's Mix</p><p>RealEldenApocalypse</p><p>Hassan1512</p><p>Anything and Everything</p><p>Dreamlike Diffusion</p><p>Sci-fi Diffusion</p><p></p><p>All of the samples are raw gens, but some of them use embeddings (my Robo Face embedding available here:<a target="_blank" rel="ugc" href="https://civitai.com/models/3670/rinas-robo-faces">https://civitai.com/models/3670/rinas-robo-faces</a>, and a nuke embed that I haven't published, because I see there's already one here) and celeb hypernetworks. Ana available here:<a target="_blank" rel="ugc" href="https://civitai.com/models/4072/anadearmaspt">https://civitai.com/models/4072/anadearmaspt</a>, and a Barbara Palvin HN which hasn't been published yet because it isn't really all that great. Referring to the quality of the training, not the appearance of the human being.</p><p></p><p>I'm not sure if this model is really needed, as the community is becoming crowded with quality merges, but I'd love to see what you make with it if you download it!</p>