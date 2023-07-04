## Mina Ashido (my hero academia) 
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `woman`
- 下载数：1526
- 收藏人数：266
- 评论人数：6
- 评分人数：5
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-03-14T21:55:44.292Z
  - 原始模型：Other
  - 下载数：1526
  - 评分人数：5
  - 评分：5
- 下载地址
  - [minaashido.safetensors](https://civitai.com/api/download/models/12773)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/36502b0f-a320-46b5-bb71-d19f6197c300/width=450/123467.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/99ed2d9e-34ae-46c0-5a2d-5397a8395300/width=450/123469.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/80cd70ef-c9e7-4604-ebc7-0e4039183d00/width=450/123466.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e8cc1506-1ae5-41b4-ad3b-9d41be307500/width=450/123468.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Use mina ashido on your prompt, this was trained on this collab: <a target="_blank" rel="ugc" href="https://colab.research.google.com/drive/1bFX0pZczeApeFadrz1AdOb5TDdet2U0Z?usp=sharing">https://colab.research.google.com/drive/1bFX0pZczeApeFadrz1AdOb5TDdet2U0Z?usp=sharing</a></p><p>!accelerate launch \</p><p>    --num_cpu_threads_per_process 8 train_network.py \</p><p>    --network_module=networks.lora \</p><p>    --pretrained_model_name_or_path="/content/model/nai.ckpt" \</p><p>    --train_data_dir="/content/drive/MyDrive/sd/dataset/sincos" \</p><p>    --reg_data_dir="/content/drive/MyDrive/sd/dataset/sincos_reg" \</p><p>    --output_dir="/content/drive/MyDrive/sd/stable-diffusion-webui/models/lora/" \</p><p>    --caption_extension=".txt" \</p><p>    --prior_loss_weight=1 \</p><p>    --resolution=768 \</p><p>    --enable_bucket \</p><p>    --min_bucket_reso=512 \</p><p>    --max_bucket_reso=1152 \</p><p>    --train_batch_size=3 \</p><p>    --learning_rate=1e-4 \</p><p>    --unet_lr=1.5e-4 \</p><p>    --text_encoder_lr=1.5e-5 \</p><p>    # --max_train_steps=8010 \</p><p>    --mixed_precision="fp16" \</p><p>    --save_precision="fp16" \</p><p>    --use_8bit_adam \</p><p>    --xformers \</p><p>    --max_train_epochs=8\</p><p>    --save_every_n_epochs=1\</p><p>    --save_model_as=safetensors \</p><p>    --clip_skip=2 \</p><p>    --seed=23 \</p><p>    --network_dim=128 \</p><p>    --network_apha=128 \</p><p>    --max_token_length=225 \</p><p>    --cache_latents \</p><p>    --lr_scheduler="cosine_with_restarts" \</p><p>    --output_name="minaashido" \</p><p>    --shuffle_caption \</p><p>    # --keep_tokens=1 \</p><p>    # --lr_warmup_steps=$lr_warmup_steps \</p>