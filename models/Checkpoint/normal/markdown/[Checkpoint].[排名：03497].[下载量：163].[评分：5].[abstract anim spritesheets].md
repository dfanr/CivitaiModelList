## abstract anim spritesheets
### 一、模型概述

- 标签：`sprites`, `abstract`, `animation`
- 下载数：163
- 收藏人数：74
- 评论人数：0
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] V1

- 统计数据
  - 发布时间：2022-11-25T16:55:57.728Z
  - 原始模型：SD 1.5
  - 下载数：163
  - 评分人数：1
  - 评分：5
- 下载地址
  - [abstractAnim_v1.ckpt](https://civitai.com/api/download/models/1074)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cfcce96a-8846-4c9c-f50b-0f6feefc0f00/width=450/8695.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6b33cbec-07f8-45c7-f0e7-b855c8b24300/width=450/8696.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9205c2fe-2581-42a5-6587-d4dd085ab500/width=450/8697.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<p>Originally posted to <a href="https://huggingface.co/Avrik/abstract-anim-spritesheets" rel="ugc" target="_blank">HuggingFace by Avrik</a></p><p>An experimental Dreambooth model trained on individual frames of looping 3D animations that were then laid out on a 4x4 grid. Generates sprite sheets that can create very interesting abstract animations.</p><p>Use the token <strong>AbstrAnm spritesheet</strong>. Size must be set at 512x512 or your outputs may not work properly.</p><p><strong>Example prompt:</strong> AbstrAnm spritesheet, animation of a red glowing orb in the sky, highly detailed, fog, atmosphere, glow, sprites, animated, abstract <strong>Negative prompt:</strong> high contrast, text, overlay Steps: 30, Sampler: DPM++ 2M Karras, CFG scale: 8</p><p>Feel free to experiment with other types of prompts and/or model merges.</p><p>You can also upscale it 4x to produce 512x512 animations. Used SD Upscale from AUTOMATIC1111's web UI to add more sharpness and detail.</p><p>Discovered it's actually quite flexible and could even animate less abstract concepts.</p><p><strong>Prompt 1:</strong> AbstrAnm spritesheet, animation of magical swirling clouds in the clear blue sky, floating in crystal clear water, circular, sunny, timelapse, lens flare, nature, 35mm lens shot, photorealistic, sprites, animated, art by Greg Rutkowski <strong>Negative prompt:</strong> text, overlay, abstract, boring, empty, barren, simple background Steps: 25, Sampler: DPM++ 2S a, CFG scale: 10</p><p><strong>Prompt 2:</strong> AbstrAnm spritesheet, animation of a beautiful flower blowing in the wind, serene, pink, sunny, timelapse, lens flare, nature, 35mm lens shot, photorealistic, sprites, animated, art by Greg Rutkowski <strong>Negative prompt:</strong> text, overlay, abstract, boring, empty, barren, simple background Steps: 25, Sampler: DPM++ 2S a, CFG scale: 10</p><p>Some issues with this model:</p><ul><li>May not loop seamlessly</li><li>Tends to be too noisy</li><li>Sprites aren't usually perfect squares</li><li>Small size and short animation (could experiment with training on larger resolutions in the future)</li></ul>