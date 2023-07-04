## Waifu Diffusion - Beta 03
### 一、模型概述

- 标签：`anime`, `base model`, `woman`
- 下载数：439
- 收藏人数：59
- 评论人数：6
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Beta 3

- 统计数据
  - 发布时间：2023-05-15T13:42:18.291Z
  - 原始模型：SD 2.1 768
  - 下载数：439
  - 评分人数：2
  - 评分：5
- 下载地址
  - [waifuDiffusionBeta03_beta3.yaml](https://civitai.com/api/download/models/71346?type=Config&format=Other)
  - [kl-f8-anime2.ckpt](https://civitai.com/api/download/models/71346?type=VAE&format=Other)
  - [waifuDiffusionBeta03_beta3.safetensors](https://civitai.com/api/download/models/71346)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4002de02-353a-4c8e-9898-91ce208d4aa3/width=450/797166.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fe6fb86a-d02b-4988-995c-9713f2655ff8/width=450/797168.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ead844d1-3d04-4115-8f27-2aaca38d618e/width=450/797167.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/19ce036b-bea8-4d03-9fe4-efe7733c2b2f/width=450/797165.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>Waifu Diffusion - Beta 03</h1><p>Reuploaded from Huggingface to civitai for enjoyment.</p><p><em>WD 1.5 Beta 3 is fine-tuned directly from stable-diffusion-2-1 (768), using v-prediction and variable aspect bucketing (maximum pixel area of 896x896) with real life and anime images. Given the broad range of concepts encompassed in WD 1.5, we expect it to serve as an ideal candidate for further fine-tuning, LoRA's, and other embedding applications. - [</em><a target="_blank" rel="ugc" href="https://saltacc.notion.site/saltacc/WD-1-5-Beta-3-Release-Notes-1e35a0ed1bb24c5b93ec79c45c217f63#7214d3ab-e297-4d1b-b5cc-0ae236a863f7"><em>Notion.site</em></a><em>]</em></p><h2>Author's Notes</h2><p><em>Model is good. Think of it like NAI when it first came out. It's a good way to kickstart a lot of finetuning right? Well you can just do that with WD 1.5 B3.</em> - KaraKaraWitch</p><h2>Aesthetic Models?</h2><p>To be uploaded.</p><h2>Installation</h2><ol><li><p>Download the 3 files.</p></li><li><p>Same deal how you install SD 2.1.</p></li><li><p>Use the magic sauce VAE </p></li></ol><p>If you can't do that well uhhh... I guess try and google and figure it out? <a target="_blank" rel="ugc" href="https://easywithai.com/guide/how-to-run-the-new-2-1-stable-diffusion-model/">I think this could help.</a></p><h2>Usage</h2><p>Use the following "mastering" prompts for improved looks:</p><p>Positive Prompt:</p><pre><code>(exceptional, best aesthetic, new, newest, best quality, masterpiece, extremely detailed, anime, waifu:1.2)</code></pre><p>Negative Prompt:</p><pre><code>lowres, ((bad anatomy)), ((bad hands)), missing finger, extra digits, fewer digits, blurry, ((mutated hands and fingers)), (poorly drawn face), ((mutation)), ((deformed face)), (ugly), ((bad proportions)), ((extra limbs)), extra face, (double head), (extra head), ((extra feet)), monster, logo, cropped, worst quality, jpeg, humpbacked, long body, long neck, ((jpeg artifacts)), deleted, old, oldest, ((censored)), ((bad aesthetic)), (mosaic censoring, bar censor, blur censor)</code></pre><h2>What can it do?</h2><p>Model can do the following:</p><p>- Realistic <code>(realistic, real life:1.2)</code> In positive.</p><p>- Horny (The typical stuff, probably better with finetunes lol)</p><p>- Whatever you want to tune it with lol.</p><p>- Tuning is rather easy too. LoRA works (Kohya ones) and LyCORS (Tested LoCon and it works sooo yeah.)</p><h2>What's new?</h2><ul><li><p>Fixed Text Encoder Training, so TE is actually trained now, give it a try if you're from Beta 2.</p></li></ul><h2>Loicense (License)</h2><p>It's... Complicated.</p><p>TLDR: Just follow the Fair AI Public License 1.0-SD (<a target="_blank" rel="ugc" href="https://freedevproject.org/faipl-1.0-sd/">https://freedevproject.org/faipl-1.0-sd/</a>). If any derivative of this model is made, please share your changes accordingly. Special thanks to ronsor/undeleted (<a target="_blank" rel="ugc" href="https://undeleted.ronsor.com/">https://undeleted.ronsor.com/</a>) for help with the license.</p><p>It does kinda go against the spirit of civitai but uhhh whatever lol.</p><h2>How 2 Train a <s>Drag-</s> Waifu Diffusion</h2><p>1. BLIP/BLIP2 and WD Tagger to provide booru tags and natural language captions to every image.</p><p>2. Apply Date gradient</p><p>3. Bucket <s>𝒜𝑒𝓈𝓉𝒽𝑒𝓉𝒾𝒸</s> Aesthetic into <em>Exceptional, Best, Normal &amp; bad.</em></p><p>4. Add stars to Booru images &amp; bucket em. (Masterpiece, Best, High, Medium, Normal, Low &amp; Worst)</p><p>5. Train</p><p>6. ???</p><p>7. Profit.</p><h2>How to Lycoris/Locon/LoRA train</h2><p><em>KaraKaraWitch here, okay so here are some of my comments from inital trial runs with WD 1.5 B3 and some common pitfalls.</em></p><p>1. Use the VAE provided. Do not use the builtin model VAE.</p><p>2. Enable <code>--v2</code> and <code>--v_parameterization</code></p><p>3. Train as per usual</p><p><em>"Wait what that's it?!"</em></p><p>Yes. The Do not however that your final loss should hover around 0.3. Any lower (like 0.29) might indicate overfitting issues.</p><p><em>"Amongus sus"</em></p><p>I meannn I only did a couple of styles and it did work out like that soo...</p><h2>Where the fp32 version?!</h2><p>According to devs, there is no perceivable difference in terms of quality when using either fp16 or fp32. (Unless you use memory opts like xformers. Those will cause more bigger issues than saving at fp32.)</p><h2>I want it to be Diffused! (Diffusers format)</h2><p><a rel="ugc" href="https://huggingface.co/waifu-diffusion/wd-1-5-beta3">See when salt uploads the thingy to HF lol</a></p><h2>Sooo what's the point is this model?!</h2><p>Like I said in the beginning:</p><p>&gt; <em>Think of it like NAI when it first came out. It's a good way to kickstart a lot of finetuning right? Well you can just do that with WD 1.5 B3.</em></p><p>It is <strong>recommended and encouraged</strong> to finetune and/or locon/lora it!</p>