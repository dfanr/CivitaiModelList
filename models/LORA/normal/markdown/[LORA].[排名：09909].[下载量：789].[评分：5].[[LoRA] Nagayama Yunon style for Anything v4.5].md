## [LoRA] Nagayama Yunon style for Anything v4.5
### 一、模型概述

- 标签：`anime`, `girl`, `style`, `lora`
- 下载数：789
- 收藏人数：153
- 评论人数：0
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] lora-v1.0

- 统计数据
  - 发布时间：2023-03-28T14:36:07.319Z
  - 原始模型：SD 1.5
  - 下载数：789
  - 评分人数：2
  - 评分：5
- 下载地址
  - [nagayama_yunon-lora-v1.0.safetensors](https://civitai.com/api/download/models/30117)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d5a72c0f-3b83-46f7-4ddf-80e679c6f400/width=450/341789.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cfa863a6-a536-4562-48a8-675d54ebb000/width=450/341788.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/67954ed1-9ea5-4d7c-f461-97cfdb7f3700/width=450/341565.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8b83095b-47a1-4239-79fe-075c2726c800/width=450/341787.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<ul><li><p>checkpoint: <a target="_blank" rel="ugc" href="https://huggingface.co/andite/anything-v4.0">Anything v4.5</a> (<strong>DO NOT Forget VAE</strong>)</p></li><li><p>no trigger words required</p></li><li><p>recommond <strong>CFG Scale = 7.0</strong></p></li><li><p>recommond weight:<strong> 0.6</strong></p></li><li><p>recommond use hires.fix</p></li></ul><p></p><h2>Training params</h2><pre><code>$resolution = "768,1024"
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
$use_lion = 1</code></pre><p></p>