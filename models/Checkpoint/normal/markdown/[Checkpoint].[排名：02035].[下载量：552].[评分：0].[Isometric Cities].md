## Isometric Cities
### 一、模型概述

- 标签：`landscapes`, `city`, `style`
- 下载数：552
- 收藏人数：222
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1

- 统计数据
  - 发布时间：2022-12-10T22:22:22.756Z
  - 原始模型：SD 1.5
  - 下载数：552
  - 评分人数：0
  - 评分：0
- 下载地址
  - [isometricCities_v1.ckpt](https://civitai.com/api/download/models/47)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d71dd460-bfdd-4782-2de0-ff0aea687800/width=450/246.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/60a14554-7827-43ea-790b-8bef28c96200/width=450/248.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/838448ae-3d32-493e-61d5-0c86598e5100/width=450/247.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<p>Created by Astroboy, originally uploaded to HuggingFace</p><p><br /></p><p>This model trained based on Stable Diffusion 1.5 model to create isometric cities, venues, etc more precisely. Trained isometric city model merged with SD 1.5 with Automatic1111's checkpoint merger tool (Couldn't remember exactly the merging ratio and the interpolation method)</p><p>Use "<strong>an illustration of an isometric city, digital art, highly detailed</strong>" in your prompts.</p><p><br /></p><p>Intended uses &amp; limitations</p><p>Do not use for commercial purposes.</p><p><br /></p><p>Training procedure</p><p>Trained on a WSL2 Ubuntu machine with DreamBooth.</p><p><br /></p><p>Training hyperparameters</p><p>The following hyperparameters were used during training: --with_prior_preservation --prior_loss_weight=1.0</p><p>--instance_prompt="an illustration of an isometric city, digital art, highly detailed"</p><p>--class_prompt="isometric city"</p><p>--resolution=512</p><p>--train_batch_size=1</p><p>--mixed_precision="fp16"</p><p>--gradient_accumulation_steps=1 --gradient_checkpointing</p><p>--use_8bit_adam</p><p>--learning_rate=5e-6</p><p>--lr_scheduler="constant"</p><p>--lr_warmup_steps=0</p><p>--num_class_images=50</p><p>--max_train_steps=1500</p>