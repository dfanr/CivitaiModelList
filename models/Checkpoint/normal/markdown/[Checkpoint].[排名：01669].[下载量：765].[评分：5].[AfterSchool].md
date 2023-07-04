## AfterSchool
### 一、模型概述

- 标签：`anime`, `colorful`, `base model`, `hentai`, `glowing eyes`
- 下载数：765
- 收藏人数：164
- 评论人数：28
- 评分人数：1
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] VAE baked

- 统计数据
  - 发布时间：2023-03-18T10:04:48.033Z
  - 原始模型：SD 1.5
  - 下载数：676
  - 评分人数：1
  - 评分：5
- 下载地址
  - [afterschool_vaeBaked.ckpt](https://civitai.com/api/download/models/14838?type=Pruned%20Model&format=PickleTensor&size=pruned&fp=fp16)
  - [afterschool_vaeBaked.safetensors](https://civitai.com/api/download/models/14838)
  - [afterschool_vaeBaked.ckpt](https://civitai.com/api/download/models/14838?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [afterschool_vaeBaked.safetensors](https://civitai.com/api/download/models/14838?type=Model&format=SafeTensor&size=full&fp=fp16)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/135b9bc3-02cd-4e59-c612-7925611a8c00/width=450/273600.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b60a4404-f3f7-4ec8-8dcf-865d32267600/width=450/273599.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/13b5df9d-df4c-42c3-8a31-a236928dcf00/width=450/273598.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/44a6563e-454d-48f4-7d31-f31b62822700/width=450/273597.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] No VAE

- 统计数据
  - 发布时间：2023-03-18T10:04:48.033Z
  - 原始模型：SD 1.5
  - 下载数：89
  - 评分人数：0
  - 评分：0
- 下载地址
  - [afterschool_noVAE.ckpt](https://civitai.com/api/download/models/16866?type=Pruned%20Model&format=PickleTensor&size=pruned&fp=fp16)
  - [afterschool_noVAE.ckpt](https://civitai.com/api/download/models/16866?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [afterschool_noVAE.safetensors](https://civitai.com/api/download/models/16866?type=Model&format=SafeTensor&size=full&fp=fp16)
  - [afterschool_noVAE.safetensors](https://civitai.com/api/download/models/16866)
  - [AfterSchool.vae.pt](https://civitai.com/api/download/models/16866?type=VAE&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9e0be335-7a14-4d59-5443-92ed95556b00/width=450/273606.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/24c9e6db-a270-4c5c-5197-4ce835287800/width=450/273605.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c583e699-8d67-4a8b-4e96-6d78b08ecc00/width=450/273604.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7a93cbe3-6a3d-43c2-f867-49be59d31800/width=450/273603.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Hello everyone.</p><p>I decided to finally rename and reupload this model, and clean the gallery as well. This is the same model as before, the only difference is I unbaked the VAE file. My reasoning is maybe someone prefers raw looks. Or you already have this VAE file. Or you wish to attach a different one. The default VAE is the file from <a target="_blank" rel="ugc" href="https://civitai.com/models/4836/schoolmax-25d">schoolmax2.5d</a>, renamed for convenience. Baked VAE version is available as well.</p><p>I removed the previous wall of text cause nobody would want to read it. Basically, this model tries to make 2.5d images with painted eyebrows and pubic hair. Sometimes it works, sometimes doesn't. I think it's a decent first step. It can't do hands, it can't do background people (seriously, don't try that), and it's better in portrait mode than in landscape (unless you're doing a landscape, of course), but what's new? It is equally good for SFW and NSFW. Thanks to users <strong>lynx</strong> and <strong>ritcher1</strong>, I found this model is extremely sensitive to weights in prompts. So maybe it's not as niche as I thought.</p><p>The only drawbacks I found here is that the resulting merge doesn't like positive textual inversions or LORAs. Anything I tried to add, even <a target="_blank" rel="ugc" href="https://civitai.com/user/Master_Corneo">Master Corneo</a>'s POVs, cause it to lose 2.5d effect completely, reverting it into 2d model. What's weird as I never encountered this behavior even on fully photorealistic models. Negative inversions are fine, however.</p><p>Now, for settings.</p><p>In my tests, DPM++ 2M Karras was the best sampler. Steps from 20 to 32, scale about 10. As of recent, I started to heavily trim my prompts, eliminating useless buzzwords like masterpiece or unity 8k wallpaper  from positive part. For negative, I tend to use negative embeddings like <a target="_blank" rel="ugc" href="https://huggingface.co/datasets/Nerfgun3/bad_prompt">bad_prompt_version2</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative">Deep Negative</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative">EasyNegative</a>, and <a target="_blank" rel="ugc" href="https://civitai.com/models/4499/unspeakable-horrors-negative-prompt">Unspeakable Horrors</a>. on top of basic (worst quality:1.4, low quality:1.4). I increased clip skip to 2 and I like the results. Face restore seems to be not very compatible with this merge, it curses faces. Photo realism tag works extremely well. Eyes are still cursed sometimes, especially when steps are too high. Fingers are almost always cursed, nothing new here. I have xformers enabled so your results may vary a bit, mostly in colors.</p><p>Thanks to <a target="_blank" rel="ugc" href="https://civitai.com/user/DiaryOfSta"><strong>DiaryOfSta</strong></a> (<a target="_blank" rel="ugc" href="https://civitai.com/models/6437/anidosmix"><strong>AniDosMix</strong></a>) and <a target="_blank" rel="ugc" href="https://civitai.com/user/MJXXZ"><strong>MJXXZ</strong></a> (<a target="_blank" rel="ugc" href="https://civitai.com/models/4836/schoolmax-25d"><strong>schoolmax2.5d</strong></a>). Every rights and credits remain by their creators and/or owners. I take no credit beyond the basic mention. Both original authors disabled some kind of commercial use so I'll just disable it altogether. Speak with them, if you have to.</p>