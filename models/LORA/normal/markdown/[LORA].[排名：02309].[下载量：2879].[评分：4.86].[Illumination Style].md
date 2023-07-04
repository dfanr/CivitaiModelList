## Illumination Style
### 一、模型概述

- 标签：`nintendo`, `style`, `illumination`
- 下载数：2879
- 收藏人数：691
- 评论人数：7
- 评分人数：7
- 评分：4.86

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v2_epoch3

- 统计数据
  - 发布时间：2023-06-08T01:33:30.334Z
  - 原始模型：SD 1.5
  - 下载数：2879
  - 评分人数：7
  - 评分：4.86
- 下载地址
  - [style_illumination_v2_epoch3.safetensors](https://civitai.com/api/download/models/42981)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a4cffd91-00e7-438b-61fa-9e71d97b9000/width=450/470990.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4b6c5cb1-716b-4d88-76d3-fd9327ef2200/width=450/471245.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0aa8df4b-a8dd-4ebe-0fc7-27dc66c06300/width=450/470953.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d6af6c11-13fb-42ea-580d-052bbdfc8c00/width=450/470934.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3 id="heading-7">An attempt to reproduce Illumination's style, particularly the latest iteration of which as seen in The Super Mario Bros. Movie.</h3><p></p><p>Training was performed using <a target="_blank" rel="ugc" href="https://civitai.com/models/24149">Mistoon</a> as the base checkpoint, with the preview images using the same plus <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt">vae-ft-mse-840000-ema-pruned</a> as the VAE. The training dataset consists of a mere 6 crops of Mario and 8 crops of Peach from 4K trailer encodes provided by <a target="_blank" rel="ugc" href="http://www.digital-digest.com/">Digital Digest</a>. Because of this the LORA is expected to be stiff and will require cherry picking to get good results. Once the full movie has released it's possible I may return to this LORA with the additional data.</p><p></p><p>0.8 strength is my personal recommendation if generating Mario or Peach, followed by 0.6 or lower for other characters or if trying to get Mario and Peach to wear other outfits. You'll likely also want to err on caution with sampling steps and CFG. Less relevant tags that may help with guiding the style include <strong>filmic</strong>, <strong>film grain</strong>, <strong>depth of field</strong>, <strong>blurry background</strong>, and <strong>3d</strong>. I would also recommend adding youth-adjacent tags to your negative prompt if they aren't already present, such as <strong>child</strong> and <strong>chibi</strong>.</p><p></p><p>Recommended LORAs to pair this with include any of <a target="_blank" rel="ugc" href="https://civitai.com/user/Numeratic">Numeratic</a> or <a target="_blank" rel="ugc" href="https://civitai.com/user/thesauceer">thesauceer</a>'s fantastic Nintendo training.</p>