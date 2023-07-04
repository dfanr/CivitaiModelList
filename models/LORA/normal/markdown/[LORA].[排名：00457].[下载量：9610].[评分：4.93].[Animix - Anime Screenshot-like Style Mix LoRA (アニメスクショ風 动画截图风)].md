## Animix - Anime Screenshot-like Style Mix LoRA (アニメスクショ風/动画截图风)
### 一、模型概述

- 标签：`anime`, `girl`, `boy`, `female`, `screenshot`, `anime screencap`, `style`, `art style`, `woman`, `illustration`, `artstyle`, `beautiful`, `digital illustration`, `male`, `men`, `anime style`
- 下载数：9610
- 收藏人数：1804
- 评论人数：7
- 评分人数：14
- 评分：4.93

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-03-30T12:06:58.976Z
  - 原始模型：SD 1.5
  - 下载数：8778
  - 评分人数：6
  - 评分：5
- 下载地址
  - [animemix_16.safetensors](https://civitai.com/api/download/models/28340)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b1241d27-c822-4b83-b2c0-e9cdc9bd5100/width=450/318954.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2e6f1ca9-1ce8-4afd-62b4-1bce90a76600/width=450/319108.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8816791d-dd0b-4937-ef7f-49d018b19800/width=450/318968.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/49d20a77-a369-4461-98a6-297c981a7700/width=450/318955.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0 full model

- 统计数据
  - 发布时间：2023-03-30T12:06:58.976Z
  - 原始模型：SD 1.5
  - 下载数：832
  - 评分人数：8
  - 评分：4.88
- 下载地址
  - [animeScreenshotlikeMix_fp16.safetensors](https://civitai.com/api/download/models/28555)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/426df619-c900-4e8f-4b6a-29c2f5599000/width=450/321585.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/aaeeb61b-25c8-4ff5-9685-51aa0cee1700/width=450/321584.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f7d027a8-e9b6-4e2c-c8f9-ebbde7079e00/width=450/321583.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f0775b27-044e-4bd5-61f5-40d0f5bd2a00/width=450/321582.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>You can also download a full-merged model here (just in case you don't have Anything V4.5 or want to train a LoRA based on this style): <a target="_blank" rel="ugc" href="https://huggingface.co/OedoSoldier/animix">https://huggingface.co/OedoSoldier/animix</a></p><p>你可以在这里下载大模型（以防你没有Anything V4.5或者想要以此画风训练LoRA）：<a target="_blank" rel="ugc" href="https://huggingface.co/OedoSoldier/animix">https://huggingface.co/OedoSoldier/animix</a></p><p></p><h3>Check the new variant: <a rel="ugc" href="https://civitai.com/models/26622">Ambientmix</a>!</h3><p></p><p>Recommend settings:</p><p>Model: Anything V4.5</p><p>VAE: Orangemix (the same with NAI)</p><p>LoRA Strength: 1</p><p>Sampler: DPM++ 2M Karras</p><p>Sampling steps: 20</p><p>CFG: 7</p><p>Negative embedding: <a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative">EasyNegative</a>、<a target="_blank" rel="ugc" href="https://civitai.com/models/16993/badhandv4-animeillustdiffusion">badhandv4</a></p><p>Highres fix is also recommended.</p><p>Note: all the LoRA names used in sample images are my local name, you need to change them to your saved LoRA filename!</p><p></p><p>推荐设置：</p><p>基模：Anything V4.5</p><p>VAE：Orangemix（同NAI）</p><p>LoRA强度：1</p><p>采样器：DPM++ 2M Karras</p><p>采样步数：20</p><p>CFG：7</p><p>负面embedding：<a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative">EasyNegative</a>、<a target="_blank" rel="ugc" href="https://civitai.com/models/16993/badhandv4-animeillustdiffusion">badhandv4</a></p><p>推荐使用高清修复。</p><p>注意：样图中的LoRA名称是我本地文件名，要改成你保存的文件名！</p><p></p><p>This model is suitable for reproducing images similar to anime screenshots, and it is recommended to use <a target="_blank" rel="ugc" href="https://github.com/hako-mikan/sd-webui-lora-block-weight">LoRA block weight</a> expansion when using LoRA and character LoRA together. Setting the block weights of the character LoRA to presetting <code>MIDD</code> will reduce the distortion caused by the influence of the character LoRA on the style.</p><p></p><p>本模型适合复现类似于动漫截图的图像，建议在此LoRA与角色LoRA一起使用时使用<a target="_blank" rel="ugc" href="https://github.com/hako-mikan/sd-webui-lora-block-weight">LoRA块权重扩展</a>。将角色LoRA的输出权重设置为<code>MIDD</code>预设将减少角色LoRA影响对风格产生的影响。 <br /></p><p>This is a LoRA mix of:</p><ul><li><p>2020s Anime Magazine Illustration Style</p></li></ul><ul><li><p>Anime-like 2D (extracted LoRA)</p></li><li><p>Anime Lineart Style</p></li><li><p>Anime Screencap Style</p></li><li><p>Avas Anime Hamster</p></li><li><p>Epi Noise Offset</p></li><li><p>Hipoly 3D Model Lora</p></li><li><p>Makoto Shinkai Substyles</p></li></ul><p>Merged with special tweaks to make full use of the strengths of each LoRA.</p><p></p><p>本LoRA由以下LoRA混合而成：</p><ul><li><p>2020s Anime Magazine Illustration Style</p></li></ul><ul><li><p>Anime-like 2D (extracted LoRA)</p></li><li><p>Anime Lineart Style</p></li><li><p>Anime Screencap Style</p></li><li><p>Avas Anime Hamster</p></li><li><p>Epi Noise Offset</p></li><li><p>Hipoly 3D Model Lora</p></li><li><p>Makoto Shinkai Substyles</p></li></ul><p>经过特别调教，得以发挥各LoRA的长处。</p>