## Pulp-diffusion
### 一、模型概述

- 标签：`vintage`, `pulp art`
- 下载数：272
- 收藏人数：78
- 评论人数：1
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] pulp-diffusion-alpha

- 统计数据
  - 发布时间：2023-02-10T20:35:46.851Z
  - 原始模型：SD 2.1 768
  - 下载数：272
  - 评分人数：1
  - 评分：5
- 下载地址
  - [pulpDiffusion_pulpDiffusionAlpha.ckpt](https://civitai.com/api/download/models/8783)
  - [pulpDiffusion_pulpDiffusionAlpha.yaml](https://civitai.com/api/download/models/8783?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b88efb98-7133-4ce6-91d8-0a2d59185800/width=450/83842.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dff32237-9b09-4204-06fa-eda57f2fa600/width=450/84542.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bb364945-726e-4706-14d7-a200cfb34800/width=450/84541.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0ae5e0b8-9a8a-4a84-925d-fc754aceb500/width=450/83919.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>About model:</strong><br />Style model for Stable Diffusion mimicking pulp illustration/old magazine covers. It has one trigger word but doesn't need it to work. It works out-of-the-box. </p><p></p><p><strong>License and support:</strong></p><p>This model is open source so you can share, merge or use for monetization as you like (that will apply to other versions as well)</p><p>If you like what I am doing and you want to support my current and upcoming projects: here is my <a target="_blank" rel="ugc" href="https://www.buymeacoffee.com/pmejna">coffee jar</a></p><p><br /><strong>Installation:</strong><br />As it is model based on 2.1 to make it work you need to use .yaml file with name of a model (vector-art.yaml). The yaml file is included here as well to download. Simply copy paste to the same folder as selected model file. Usually this is the <code>models/Stable-diffusion</code> one.</p><p></p><p><strong>Versions:</strong></p><p>Currently, there is only one version of this model. Next training will be based on resources I have used previously, but all captioned + new images.<br /><br /><strong>Black images issue:</strong></p><p>2.1 models need to have a web-ui config modified - if you are getting <strong>black images </strong>- go to your config file and add to COMMANDLINE_ARGS= <code>--no-half</code> - potentially it could work with <code>--xformers</code> instead (if supported). This line might slow your generations a bit but will not affect negatively your output.</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ef662aec-6a48-4acc-3bca-574a9f3f2e00/width=525" /><p><br /><strong>Purpose:</strong><br />For Prompts reference check the tooltip on the sample images.</p><p><br />I am working on a guide website for all my models. My goal is to create models useful for the design world. I personally don't see a lot of benefit in using models to "just create a beautiful image". <br /><br />This model is a good starting point for poster elements/backgrounds or elements you can use in the process of T-shirt design (using photoshop and going with threshold method or other) <br /><br />I find it also a good choice for book covers. Especially if you want to achieve result of book covers from 1930-70 style (horror, sci-fi, thriller and similar)</p>