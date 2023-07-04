## SCMix
### 一、模型概述

- 标签：`anime`, `style`
- 下载数：1547
- 收藏人数：392
- 评论人数：1
- 评分人数：4
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] SCMix

- 统计数据
  - 发布时间：2023-03-28T04:50:26.552Z
  - 原始模型：SD 1.5
  - 下载数：1181
  - 评分人数：3
  - 评分：5
- 下载地址
  - [scmix_.ckpt](https://civitai.com/api/download/models/23515)
  - [pastel-waifu-diffusion.vae.pt](https://civitai.com/api/download/models/23515?type=VAE&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/17e56132-4c00-4368-b9e4-f483d9b37300/width=450/255056.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6af8573a-cbd8-4163-8628-3ee56b1c8d00/width=450/254966.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f68b3f9f-8873-4c84-4ffd-261d2136a000/width=450/254976.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c764a464-608e-4ade-4e97-10c0da286100/width=450/254975.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] SCMIX_NSM

- 统计数据
  - 发布时间：2023-03-28T04:50:26.552Z
  - 原始模型：SD 1.5
  - 下载数：366
  - 评分人数：1
  - 评分：5
- 下载地址
  - [scmix_NSM.ckpt](https://civitai.com/api/download/models/23539)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/adb870a0-6b12-4893-eb0f-1f25a0207d00/width=450/255303.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/72f6ab4f-427e-4076-034b-a791525a2900/width=450/255249.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/70a288e6-182a-427c-fc74-c821bb679b00/width=450/255248.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/34d56b25-592e-4401-9fca-aed5be460900/width=450/255247.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>Best practice: Resolution=768*960, hires=2x, clip=2, sampler DMP++2M karras, 40 steps, for more parameters please refer to my diagram.</strong></p><h1><strong>SCMIX -</strong></h1><h3><strong>Mixed from pastel and abyssorangemix3AOM3_aom3a3</strong></h3><p>I really love detailed and chaotic images, as well as intense lighting and shadows. Therefore, I extracted the weight layers related to lighting and shadows from aom3 and mixed them with pastel through layer weighting. After a lot of filtering and iteration, I chose this version that is most suitable for me!</p><p>This is my favorite version, containing everything I love perfectly!</p><h1><strong>SCMIX_NSM -</strong></h1><h3><strong>Mixed from pastel and abyssorangemix3AOM3_aom3a3, as well as subtle nightSkyYOZORAStyle and meinamix_meinaV8,</strong></h3><p>I hope to achieve stronger contrast and complex backgrounds with this version, which is more suitable for long-range and full-body shots, of course, depending on your preferences~</p><p>You will notice that my sample images contain a lot of <strong>out border</strong> and tarot-style elements, thanks to two <strong>lora</strong>, one is the trained <strong>gsr</strong>, which makes the character's decorations more complex and gorgeous, and additional related items appear in the scene.</p><p>The second is <strong>tam</strong>, which adjusts the fusion from <strong>tachi-e</strong>, and I deleted the parts that would greatly change the composition and destroy the lighting.</p><p>As well as the fusion of the two, you can download it at the following link.</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/19825/scmixgrctam">SCMix_grc_tam | Stable Diffusion LORA | Civitai</a></p><p></p><p><strong>• 最佳实践：分辨率=768*960，hires=2倍，clip=2，采样器DMP ++2M karras，40step，更多参数可以参考我的示意图</strong></p><h1><strong>SCMIX—</strong></h1><p><strong>—混合自pastel and abyssorangemix3AOM3_aom3a3</strong></p><p>我超级喜欢细节丰富，杂乱的画面，以及浓度强烈的光影，故我将aom3中的涉及光影的权重层提取出于pastel进行分层权重混合，在通过大量的筛选迭代中选出了这个最合适的版本！</p><p>这是我最喜欢的版本，包含完美的我喜爱的一切！</p><h1><strong>SCMIX_NSM—</strong></h1><p><strong>—混合自pastel and abyssorangemix3AOM3_aom3a3，以及细微的nightSkyYOZORAStyle和meinamix_meinaV8，</strong></p><p>希望从中获得更强的对比度和复杂的背景，这个版本更适合远景，全身，当然看你喜好~</p><p>你会注意到，我的示例图片中包含了大量的<strong>out border</strong>，塔罗牌等风格的元素，这得益于两个<strong>lora</strong>，一个是训练的<strong>gsr</strong>，它更会让人物的装饰更加复杂和华丽，并在场景中出现额外的相关物品</p><p>第二个是<strong>tam</strong>，他调整融合自<strong>tachi-e</strong>，我删除了其中会大幅度改变构图，并破坏掉光影的部分</p><p>以及两者的融合版，你可以在以下链接中去下载</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/19825/scmixgrctam">SCMix_grc_tam | Stable Diffusion LORA | Civitai</a></p>