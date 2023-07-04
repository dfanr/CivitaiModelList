## AAM - AnyLoRA Anime Mix - Anime Screencap Style Model
### 一、模型概述

- 标签：`anime`, `landscapes`, `base model`, `anime screencap`, `hentai`
- 下载数：4895
- 收藏人数：941
- 评论人数：23
- 评分人数：30
- 评分：4.93

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1

- 统计数据
  - 发布时间：2023-06-09T09:57:50.324Z
  - 原始模型：SD 1.5
  - 下载数：4895
  - 评分人数：30
  - 评分：4.93
- 下载地址
  - [aamAnyloraAnimeMixAnime_v1.safetensors](https://civitai.com/api/download/models/89927)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/30b5829a-64d2-4020-bde5-878643fe2a49/width=450/1051395.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/70c824ca-ca76-427e-9441-2f332984decf/width=450/1052447.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5a60ead0-057f-4072-8c45-d45aef9b448e/width=450/1043191.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d9ea3d05-81bb-4557-8c08-ae7896556c7e/width=450/1043147.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-2586">AnyLoRA Anime Mix (AAM)</h1><h2 id="heading-2587">Anime Screencap Style Model<br /></h2><p><strong>Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕. </strong><br /><strong>A ❤️, a kind comment or a review is greatly appreciated.</strong><br /></p><h3 id="heading-650">Purpose of this model</h3><ul><li><p>Train character loras where the dataset is mostly made of anime screencaps, allowing less anime style transfer and less overfitting.</p></li><li><p>Use anime styles if the lora is "weak" and doesn't give enough flat coloring.</p></li></ul><p></p><h3 id="heading-236">Suggested settings</h3><ul><li><p><strong>Set the ETA Noise Seed Delta (ENSD) to 31337</strong></p></li><li><p><strong>Set CLIP Skip to 2</strong></p></li><li><p><strong>DISABLE face restore. It's terrible, never use it</strong></p></li><li><p><strong>Use negative prompts and embeddings that don't ruin the style</strong></p></li><li><p><strong>Use AnimeVideo or Foolhardy as upscalers. If you know what to do, Latent makes an interesting effect (see the first example and the Miku one)</strong></p></li><li><p><strong>(optional to reproduce some results) Set "Do not make DPM++ SDE deterministic across different batch sizes."</strong><br /><strong>(this setting is not actually good, so I'm gonna disable it, but might be the reason some results are different)</strong></p></li></ul><p></p><h3 id="heading-651">Brief history</h3><p>Chatting on Discord, I noticed my Mushoku Tensei style LoRA, while trained on AnyLoRA, was performing a bit better on CyberAlchemist's AnimeMix base model. I read on his HF that the model was a supermerge of AnythingElse, his AnimeMix lora and various other style loras. Since AnimeMix was already including many of my old anime style loras, I wanted to experiment and try to make a model that could maximize the result of my Mushoku Tensei style, going beyond what AnyLoRA and AnimeMix could do.</p><p>After testing many different versions, adjusting the settings and receiving feedback from the Discord channel, I ended up with a version that works very well on anime loras trained on AnyLoRA (base). Especially my Mushoku Tensei one which felt very weak on AnyLoRA.</p><p>I don't advise using this for anime style training (limit to generation after training it on AnyLoRA or NAI), but it might actually be fairly good for character loras where your dataset is made mostly of anime screencaps. It should technically reduce the anime style impact making the character lora less overfitted. I'll definitely experiment with it in the following weeks.</p>