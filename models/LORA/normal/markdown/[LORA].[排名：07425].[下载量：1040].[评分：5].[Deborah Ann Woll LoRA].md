## Deborah Ann Woll LoRA
### 一、模型概述

- 标签：`girl`, `person`, `photorealistic`, `female`, `woman`, `actress`, `celeb`, `celebrity`, `photorealism`, `realistic`, `real person`
- 下载数：1040
- 收藏人数：162
- 评论人数：1
- 评分人数：5
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-03-02T14:17:21.331Z
  - 原始模型：SD 1.5
  - 下载数：1040
  - 评分人数：5
  - 评分：5
- 下载地址
  - [debannwoll-os600.safetensors](https://civitai.com/api/download/models/17545)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c4d83943-f9b3-4693-6eef-b83aa1f2c400/width=450/178948.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/47e5ee0c-5d19-497d-1915-af048b519400/width=450/178953.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/52d7b8ae-d6f5-494e-1ea7-8f2e3e14c900/width=450/178952.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5adc2a16-4e43-4dc5-9e8f-ccc44ab41d00/width=450/178950.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Prompt trigger word is <code>debannwoll</code>, see the metadata info on the example images for examples of prompts and settings that work well</p><p></p><p><strong>Disclaimer:</strong> This model is intended solely to generate fan art and is for non-commercial use. By downloading and using this model, you agree to abide by local laws and regulations and to not to infringe on the rights of others, including their reputation, privacy, or likeness.</p><p></p><h2>Tips</h2><ul><li><p>LoRA weights between 0.8 and 1.2 seem to work well, start with 0.9 for base SD v1-5 and 1 for other models like realisticVision, etc.</p></li><li><p>The sampling method I like to start with is <code>Euler a</code> at 25 steps and use a CFG of 6</p></li><li><p>For experimenting and trying to get better results try a CFG of 5 or 8, adjusting LoRA weights (0.8, 1.0 or 1.2) and playing with Hires fix denoising strength, if your results still look bad go back to the recommended starting settings above.</p></li><li><p>Expect every 1 in 3 images to be good with close up prompts and 1 in 6 to be good with a torso / full body prompts</p></li><li><p>The secret to getting more accurate faces and adding more detail to the scene is to learn how to use Hires. fix, which has a bit of a learning curve.</p></li><li><p>You can apply Hires. fix on a specific seed or if you have a good GPU (or are willing to wait) figure out the prompt you like and then generate all your images in batches with Hires fix, playing with Denoising strength and LoRA weight to get back likeness.</p></li></ul><p></p><p>Tested for accuracy and prompt flexibility on: v1-5-pruned-emaonly [cc6cb27103], realisticVisionV13_v13 [c35782bad8], deliberate_v2</p><p></p><h2>How to use LoRA's in auto1111</h2><p>1. Copy the file to <code>../stable-diffusion-webui/models/lora</code></p><p>2. Select the LoRA using the <a target="_blank" rel="ugc" href="https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Features#extra-networks">Extra networks button</a></p><p>3. Adjust the multiplier/weight to 1 (between 0.8 and 1.2 generally works well)</p>