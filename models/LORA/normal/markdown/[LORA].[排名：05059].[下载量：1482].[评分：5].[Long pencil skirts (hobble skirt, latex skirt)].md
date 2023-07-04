## Long pencil skirts (hobble skirt, latex skirt)
### 一、模型概述

- 标签：`sexy`, `bdsm`, `latex`, `clothing`, `skirt`, `pencil skirt`
- 下载数：1482
- 收藏人数：348
- 评论人数：5
- 评分人数：4
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-11T00:05:39.116Z
  - 原始模型：SD 1.5
  - 下载数：1482
  - 评分人数：4
  - 评分：5
- 下载地址
  - [lpskirtV1.safetensors](https://civitai.com/api/download/models/67514)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5546a22a-09bd-4fca-8189-47af37e0dd2e/width=450/750492.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/61f406b8-76fe-4a4c-9ff6-51cca00c834c/width=450/757856.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e34b7a1c-3f2c-4053-ba9f-ece6d75d5b08/width=450/751857.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/55e84782-8b60-490c-9fe0-85beddd6e25c/width=450/750490.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is my first experimental LoRA, I'm not fully satisfied with the raw results but with some work it can generate workable images. I noticed that most models are incapable of producing sexy characters that still wear long skirts. This LoRA is an attempt to combat that problem. I intended for it to be highly configurable through different tags which did not turn out as well as i had hoped. But the tags are:</p><ul><li><p>lpskirt: the base tag to generate long pencil skirts (always use this one)</p></li><li><p>short_lpskirt: for "short" long pencil skirts (ends right above the knee)</p></li><li><p>medium_lpskirt: for medium long pencil skirts (below knee)</p></li><li><p>long_lpskirt: ends between knee and ankle</p></li><li><p>longest_lpskirt: ankle length</p></li><li><p>latex_lpskirt: latex material</p></li><li><p>leather_lpskirt: leather material</p></li><li><p>cotton_lpskirt: cotton material</p></li><li><p>high_waist_lpskirt: for high waisted skirts</p></li><li><p>hobble_lpskirt: for very tight skirts that look like they are impossible to walk in (the primary reason for me to make this model was to be able to produce these)</p></li></ul><p>some additional tags that were used during training but I haven't properly tried for generation (no guarantee to have an effect):</p><ul><li><p>zipper_lpskirt: for skirt with a zipper</p></li><li><p>laced_lpskirt: for skirt with laces</p></li><li><p>flared_lpskirt: for a long pencil skirt that ends in a flared section</p></li><li><p>side_slit_lpskirt: for skirts with a slit on the side</p></li><li><p>front_slit_lpskirt: for skirts with a slit on the front</p></li><li><p>back_slit_lpskirt: for skirts with a slit on the back</p></li></ul><p>RECOMMENDED SETTINGS:</p><ul><li><p>use weight 0.5-0.75</p></li><li><p>always use "lp_skirt"</p></li><li><p>define a length (it still struggles with longest so if you want to force it anyway you can try something like "(hobble_lpskirt, longest_lpskirt, long_lpskirt:1.7)", you can also try adding the smaller sizes to the negative prompt)</p></li><li><p>define a material like "latex_lpskirt", additionally you can add a description like "a woman wearing a long black latex pencil skirt"</p></li><li><p>define extras like "high_waist_lpskirt"</p></li><li><p>optionally add something like "(leggings,pants:1.1)" to negative prompt if it does not properly wrap legs in a skirt in the produced images</p></li><li><p>CLICK GENERATE AND HOPE FOR THE BEST (use highresfix or multidiffusion for best results)</p></li></ul><p>The sample images are definitely cherry picked and some of them had extensive fixes done to them through img2img/inpainting</p><p></p><p>If you want to fix a slit in the skirt that you do not want i recommend opening the image in your preferred image editing software and painting roughly over the slit with the color of the skirt. Then put the image through img2img with denoising:0.5-0.7</p>