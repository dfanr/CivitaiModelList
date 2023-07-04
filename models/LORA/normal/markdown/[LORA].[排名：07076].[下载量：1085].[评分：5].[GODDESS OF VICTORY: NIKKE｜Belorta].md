## GODDESS OF VICTORY: NIKKE｜Belorta
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `sexy`, `female`, `woman`, `nikke`, `goddess of victory: nikke`
- 下载数：1085
- 收藏人数：239
- 评论人数：3
- 评分人数：4
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1

- 统计数据
  - 发布时间：2023-03-15T17:44:20.322Z
  - 原始模型：SD 1.5
  - 下载数：1085
  - 评分人数：4
  - 评分：5
- 下载地址
  - [NIKKE_TetraLine_belorta_v1_epoch-000004_1.0_NP_fp16.safetensors](https://civitai.com/api/download/models/23730)
  - [40_belorta 1girl.zip](https://civitai.com/api/download/models/23730?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/af324c53-01ce-4515-c6dd-9ca6f1c1d500/width=450/257437.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c25da254-8982-4049-8d0a-75494a4ffe00/width=450/257438.jpeg" /> |
| ---- | ---- |


### 三、详情
<h2>Word</h2><p>belorta</p><p></p><h2>Train data</h2><p>4 images</p><p></p><h2>Train</h2><pre><code>accelerate launch --num_cpu_threads_per_process 24 train_network.py --pretrained_model_name_or_path=C:\ProgramTools\__GenerativeAI\StableDiffusionModels\AOM3_orangemixs.safetensors --train_data_dir="H:\Resources\Resources_AI\forLeaningImages\NIKKE\__ByCompany\v3\TetraLine\40_belorta 1girl" --output_dir=H:\Resources\Resources_AI\__Models\__Lola\__MyLoRAs --train_batch_size=2 --network_module=networks.lora --xformers --mixed_precision=fp16 --save_model_as=safetensors --seed=42 --enable_bucket --clip_skip=2 --use_8bit_adam --save_every_n_epochs=1 --learning_rate=1e-04 --text_encoder_lr=5e-05 --network_dim=64 --network_alpha=64 --max_train_steps=560 --resolution=768,768 --caption_extension=.txt --shuffle_caption --keep_tokens=1 --logging_dir=logs --log_prefix=NIKKE_TetraLine_40_belorta_v1</code></pre><p></p><h2>Sample</h2><p>&lt;lora:NIKKE_TetraLine_belorta_v1_epoch-000004_1.0_NP_fp16:1&gt; best quality, ultra-detailed, 1girl, solo, belorta, breasts, looking_at_viewer, blush, smile, short_hair, bangs, skirt, d, thighhighs, gloves, bare_shoulders, twintails, closed_mouth, ,yellow_eyes, pleated_skirt, boots, tongue, black_gloves, belt, black_thighhighs, miniskirt, tongue_out, fingerless_gloves, black_skirt, black_footwear, zettai_ryouiki, tattoo, (wariza:1.4) room, indoors,</p><p></p>