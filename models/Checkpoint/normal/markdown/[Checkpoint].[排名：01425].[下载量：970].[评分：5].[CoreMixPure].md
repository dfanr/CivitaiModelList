## CoreMixPure
### 一、模型概述

- 标签：`anime`, `character`, `kawaii`, `woman`, `girls`
- 下载数：970
- 收藏人数：312
- 评论人数：0
- 评分人数：4
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-21T15:09:22.784Z
  - 原始模型：SD 1.5
  - 下载数：970
  - 评分人数：4
  - 评分：5
- 下载地址
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f253097a-dd45-4e29-22d7-12005c24a700/width=450/500296.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/79796134-972a-4775-2c82-cf7f6613df00/width=450/500297.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9a9148d5-19ec-4d8f-87c6-6a9dc8998e00/width=450/500361.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<p><a target="_blank" rel="ugc" href="https://huggingface.co/coretan/CoreMix">More info → Hugging Face</a></p><p>高い汎用性と表現力を目指した2Dイラスト向けの階層マージモデルです。<br />Openjourney-v4とCounterfeit-V2.5が土台。VAEはお好みでどうぞ。<br /><br />A MBW model created around Openjourney-v4 and Counterfeit-V2.5.<br />A series of merged model for 2D illustrations developed for versatility and expressiveness.</p><p>VAE is your choice.</p><p></p><p><strong>IMPORTANT:</strong><br /><strong>(masterpiece, best quality)などのクオリティタグは非推奨です。</strong><br />出力の強度が強すぎて、結果に悪影響を与えます(線がガビガビになったりします）<br />下記の推奨テンプレートを参照してください。</p><p><strong>(masterpiece, best quality) etc. quality tags are NOT RECOMMEND.</strong><br />The output parameters are too strong and adversely affect the results.<br />Please refer to the recommended templates below.</p><p></p><p>1: HDRのような色彩感と精細な背景描写がウリ。<br />2: Latentとプロンプトを書くのが好きな人向け💕<br />3: AOMシリーズとAnythingシリーズは不使用。</p><p></p><p>1: HDR-like colors and detailed background depiction.<br />2: For people who like to write prompts and latent upscaler:)<br />3: AOM and Anything series are not used.</p><p></p><p><strong>Recommended Setting:</strong><br />Resolution: 512x512 ~ 768x768<br />Steps: 30 ~<br />Sampler: DPM++ 2M Karras or DPM++ SDE Karras<br />CFG scale: 7 ~ 11<br />Denoising strength: 0.55 ~ 0.6 (Latent) / 0.32 ~ 0.45 (SwinIR 4x)<br />Hires steps: 20 ~<br />Hires upscaler: Latent(nearest-exact) / SwinIR 4x for close-up shot<br />Hires upscale: 2<br /><br /><strong>Recommended Starter Template:</strong><br />absurdres, highres, reflection, refraction:1.4, ultra detailed:1.0, BREAK</p><p><strong>Negative Starter Template:</strong><br /><a target="_blank" rel="ugc" href="https://huggingface.co/datasets/gsdf/EasyNegative">EasyNegative </a>(worst quality, low quality:1.4) [:(<a target="_blank" rel="ugc" href="https://civitai.com/models/16993/badhandv4-animeillustdiffusion">badhandv4</a>:1.5):27] simple background:1.0,</p>