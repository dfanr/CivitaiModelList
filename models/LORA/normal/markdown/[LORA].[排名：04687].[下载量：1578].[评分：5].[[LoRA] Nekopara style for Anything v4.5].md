## [LoRA] Nekopara style for Anything v4.5
### 一、模型概述

- 标签：`anime`, `girl`, `style`, `lora`
- 下载数：1578
- 收藏人数：298
- 评论人数：2
- 评分人数：5
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] lora-v1.0

- 统计数据
  - 发布时间：2023-03-28T14:47:56.146Z
  - 原始模型：SD 1.5
  - 下载数：1578
  - 评分人数：5
  - 评分：5
- 下载地址
  - [nekopara-lora-v1.0.safetensors](https://civitai.com/api/download/models/30723)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/05c9ba8c-7796-4a64-f3cc-79a29e436c00/width=450/348923.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ee97c5e3-62a8-4e6b-5068-ff39b752e600/width=450/348930.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ff942d45-01f1-48e9-d21d-6ee33dc36000/width=450/348929.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7838abaa-d28c-4e87-9df0-65a72437c200/width=450/348928.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<ul><li><p>checkpoint: <a target="_blank" rel="ugc" href="https://huggingface.co/andite/anything-v4.0">Anything v4.5</a> (<strong>DO NOT Forget VAE</strong>)</p></li><li><p>no trigger words required</p></li><li><p>recommond <strong>CFG Scale = 7.0</strong></p></li><li><p>recommond weight:<strong> 0.7</strong></p></li><li><p>recommond use hires.fix</p></li></ul><p></p><h2>Training params</h2><pre><code>$resolution = "768,1024"
$batch_size = 3
$max_train_epoches = 8
$save_every_n_epochs = 1
$network_dim = 128 
$network_alpha = 128 
$clip_skip = 2 
$lr = "1e-4"
$unet_lr = "1e-4"
$text_encoder_lr = "1e-5"
$lr_scheduler = "cosine_with_restarts" 
$lr_warmup_steps = 0 
$lr_restart_cycles = 1
$noise_offset = 0.05 
$keep_tokens = 3
$min_bucket_reso = 256
$max_bucket_reso = 1024
$use_lion = 1</code></pre>