## SingleLineArt Style LoRA
### 一、模型概述

- 标签：`drawing`, `lineart`, `style`, `art style`
- 下载数：1263
- 收藏人数：281
- 评论人数：10
- 评分人数：4
- 评分：4.75

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-03-16T08:42:44.741Z
  - 原始模型：SD 1.5
  - 下载数：1263
  - 评分人数：4
  - 评分：4.75
- 下载地址
  - [SingleLineArt-LORA.safetensors](https://civitai.com/api/download/models/24020)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0edec80b-137d-4ad2-f711-52fdc71cb800/width=450/260984.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/40ecf901-23c8-48b8-aab0-20a8810fa500/width=450/260990.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/48cb6b1a-9cfb-4f21-7082-d9f65ee77600/width=450/260989.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5bffcb3d-054c-493b-ae31-8be2e3c83500/width=450/260988.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This model is best suited for generating portraits of faces, though it can do full body renders as well albeit with less accuracy as far as the single line art style is concerned. </p><p>It also works well with ControlNet using depth and openpose.</p><p>When you use this LoRA in Txt2IMG, it will attempt to inject some colour and shading into your image. If you don't want colour or shading in your images, you can either :</p><ul><li><p>Use negative prompts and add terms like "colour", "shading" to try to reduce or remove those effects from your images.</p></li><li><p>Use positive prompts such as "monochrome", "B&amp;W", "flat colour", "simple", "minimalistic"</p></li></ul><p>As an alternative workflow for simpler B&amp;W images, use the LoRA in the <u>IMG2IMG</u> using the following steps :</p><ol><li><p>Load a plain white 512x512 square as your base image</p></li><li><p>Set the denoising to 0.9</p></li><li><p>Invoke your prompt and ensure to call the LoRA, eg. <strong>SingleLineArt style B&amp;W line drawing of a yoga instructor in a pose&lt;lora:SingleLineArt-LORA:1&gt;</strong></p></li><li><p>For a hand-drawn on paper look, substitute the blank white image from step 1 for a scanned paper texture and set your denoising to 0.7 - 0.9 </p></li></ol>