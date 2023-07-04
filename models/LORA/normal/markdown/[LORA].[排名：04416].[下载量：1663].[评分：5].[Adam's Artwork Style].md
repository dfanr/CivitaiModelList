## Adam's Artwork Style
### 一、模型概述

- 标签：`general purpose`, `art`, `digital art`, `digital painting`, `paintstyle`, `style`, `art style`, `digital colors`, `paintings`, `illustration`, `artstyle`, `beautiful`, `digital illustration`
- 下载数：1663
- 收藏人数：591
- 评论人数：1
- 评分人数：6
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v0.1

- 统计数据
  - 发布时间：2023-03-10T15:54:49.545Z
  - 原始模型：SD 1.5
  - 下载数：1663
  - 评分人数：6
  - 评分：5
- 下载地址
  - [15_AJAWS.safetensors](https://civitai.com/api/download/models/20376)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6de2559e-ac5e-432f-3bd1-2c663e7f7400/width=450/215733.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5b743cad-dcbb-4ef2-4466-4e5b12180c00/width=450/215740.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1521bc71-bd9a-418e-e026-4de189074900/width=450/215741.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/54ec5837-9af9-4bbd-8363-d42c924fbd00/width=450/215742.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>A LoRA trained on images in my preferred artwork style. It should work with most 1.5 models, but I've found that it works best with the Dungeons N Waifu's model with a <strong>LoRA weight</strong> between <strong>0.25</strong> and <strong>0.5</strong>, and a <strong>CFG Scale</strong> of <strong>4.5</strong></p><p></p><p>Smaller faces and hands generated in this style tend to be a little scrungy and might require inpainting, since the GFPGAN style conflicts with the painterly style (see the dancing bohemian woman for example)</p><p></p><p>Upscaling by x1.5 using Lanczos for 10 steps with a denoising strength of 0.3 usually fixes up the image nicely, though YMMV</p><p></p><p>All example pictures are done in Dungeons N Waifu's without negative prompting except where necessary</p><p></p><p>Some examples of prompts to try:</p><ul><li><p>AJAWS, character concept art of a beautiful person downloading the most beautiful lora &lt;lora:15_AJAWS:0.5&gt; Steps: 30, Sampler: DDIM, CFG scale: 4.5, Seed: 145, Size: 512x768, Model hash: cb79fb0155</p></li><li><p>AJAWS, a man at an art gallery crying tears of joy at art made by the most beautiful lora &lt;lora:15_AJAWS:0.5&gt;<br />Steps: 30, Sampler: DDIM, CFG scale: 4.5, Seed: 145, Size: 768x512, Model hash: cb79fb0155</p></li></ul>