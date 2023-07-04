## Belle Delphine
### 一、模型概述

- 标签：`person`, `female`, `woman`, `celebrity`, `real person`
- 下载数：7376
- 收藏人数：884
- 评论人数：5
- 评分人数：20
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-13T03:14:33.777Z
  - 原始模型：SD 1.5
  - 下载数：7376
  - 评分人数：20
  - 评分：5
- 下载地址
  - [DI_belle_delphine_v1.safetensors](https://civitai.com/api/download/models/44242)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ee38e2f-3a27-4a5d-28c0-414e372d3500/width=450/482694.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/379fe8d1-a2d6-46c6-97a4-dedfaa9bb100/width=450/482698.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6223542a-4aec-487a-2ae5-f8dd91949a00/width=450/482703.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5232b3ae-9fd7-4621-6ddb-ed2694b17e00/width=450/482706.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is a Lora of the internet celebrity Belle Delphine.</p><p>There already exist multiple LoRAs and checkpoints of her, like <a target="_blank" rel="ugc" href="https://civitai.com/models/16551">here</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/6650/bdelphine-lora-760x1024-v2">here</a> or <a target="_blank" rel="ugc" href="https://civitai.com/models/5109/luisapbelle-delphine-lora">here</a>.</p><p>But I wasn’t happy with their results, as they either do not look how I would want it to look, or they are very prone to cat ears or pink hair. But everyone has their own taste, so check them out if you are unhappy with this one.</p><p> </p><p>This LoRA does not use any trigger word, and I suggest a default weight of 1.</p><p></p><p>The preview images mainly use <a target="_blank" rel="ugc" href="https://civitai.com/models/6424?modelVersionId=11732">ChilloutMix</a>, additional images are from <a target="_blank" rel="ugc" href="https://civitai.com/models/4823?modelVersionId=15236">Deliberate</a> and <a target="_blank" rel="ugc" href="https://civitai.com/models/4201?modelVersionId=29460">Realistic Vision</a>. The Overwatch images are using <a target="_blank" rel="ugc" href="https://civitai.com/models/10028?modelVersionId=11925">NeverEnding Dream</a>.</p><p> </p><p>The results are good enough for me to upload it here, but it is not perfect, and you might encounter the following problems:</p><ul><li><p>It really likes generating the same lip shape, despite it not even being that frequent in the training images.</p></li><li><p>This also generates cat ears, especially if you have something with ear in your prompt or something on the head which could become ears, but it is less frequent than with other models in my experiments and opinion.</p></li><li><p>Depending on the prompt certain noise / “paint” on the face might appear.</p></li></ul><p> </p><p>Additionally, this LoRA is mostly doing its job only when the face is sufficiently big (also dependent on model). If it becomes too small, the quality decreases and I advise using the high resolution fix then. In the example images multiple images also make use of that.</p><p> </p><p>This Lora is trained on the 1.5 base model with ~140 images, 50 repeats per image, 1e-5 learning rate, 5e-05 for the text encoder, 0.00015 for the unet. All training images were cropped to 512x512 and no bucketing was used.</p>