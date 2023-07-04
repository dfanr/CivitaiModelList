## Formidable (Azur Lane) | 可畏（碧蓝航线）
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `azur lane`, `game character`, `video game`, `formidable`, `碧蓝航线`, `可畏`
- 下载数：5521
- 收藏人数：1176
- 评论人数：11
- 评分人数：13
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] Default v3

- 统计数据
  - 发布时间：2023-05-30T15:29:47.847Z
  - 原始模型：SD 1.5
  - 下载数：1975
  - 评分人数：3
  - 评分：5
- 下载地址
  - [formidable_AzurLane_v3.safetensors](https://civitai.com/api/download/models/85580)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bfa73e6e-dc9c-4093-abea-a2e62708430d/width=450/969811.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/99503144-add6-40ac-acad-7639f024c7ad/width=450/969833.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d0388b57-787d-49eb-9549-938b7a5a1761/width=450/969841.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/497e4515-26ab-472f-b915-457688ecba3b/width=450/969846.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] Default v2

- 统计数据
  - 发布时间：2023-05-30T15:14:45.676Z
  - 原始模型：SD 1.5
  - 下载数：2391
  - 评分人数：6
  - 评分：5
- 下载地址
  - [formidable_AzurLane_v2.safetensors](https://civitai.com/api/download/models/52332)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fb8b8bdd-07b4-4bb3-1776-3e0e3e985500/width=450/564105.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/33374a45-8e51-4279-1eb0-c53734411500/width=450/564126.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f61c083e-b27b-49f1-2703-6d45bd572b00/width=450/564129.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/91586f90-1ad3-4cef-71c0-ffc9345c1900/width=450/564134.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] Default v1

- 统计数据
  - 发布时间：2023-05-30T15:14:45.676Z
  - 原始模型：SD 1.5
  - 下载数：1155
  - 评分人数：4
  - 评分：5
- 下载地址
  - [formidable_default v1.0.safetensors](https://civitai.com/api/download/models/44591)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7cf4c54e-a051-4d4e-324c-a7db550fb600/width=450/485679.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c5063213-62d1-4633-190b-085ba7e6a000/width=450/485682.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/617b2a38-9411-42f8-30bd-2f56f448a400/width=450/485677.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/be5579a2-73fb-4391-8f9a-697ebac29000/width=450/485686.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3 id="heading-226">2023.05.30：</h3><ul><li><p>使用金字塔噪声，增加图像质量。</p></li><li><p>Applying "Diffusion With Offset Noise" to enhance image quality.</p></li><li><p>尝试加强腰部附着物的拟合程度，代价是没有头部的图像出现概率变大。</p></li><li><p>Attempting to improve the fit of waist attachments, at the cost of increased probability of images without heads.</p></li><li><p>如果出现没有头部的图像，请尝试在负面提示词添加<code>lower body</code>。</p></li><li><p>If images without heads occur, please try adding 'lower body' to the negative prompt.</p></li></ul><p></p><h3 id="heading-227">2023.04.22：</h3><ul><li><p>重新校对文本集，提示词的准确有所上升。</p></li><li><p>Reviewed the text dataset again, and the accuracy of prompt words has improved.</p></li><li><p>增加训练步数，提升拟合程度。</p></li><li><p>Increased the number of training steps to improve the fitting level.</p></li></ul><p></p><h3 id="heading-228">2023.04.13：</h3><p>这是我第一次进行LoRA训练，出现问题的地方我未必知道如何解决。</p><p>This is my first time training with LoRA, and there may be issues that I am not sure how to solve.</p><p></p><h3 id="heading-229"><s>大就是好。</s></h3><p><s>bigger is better.</s></p><p></p><h3 id="heading-230">🥵</h3><p></p><h3 id="heading-231">Training Set：</h3><ul><li><p>number of repeats = 2</p><ul><li><p>close-up = 10</p></li><li><p>portrait = 10</p></li><li><p>upper body = 10</p></li><li><p>lower_body=10</p></li><li><p>cowboy shot = 10</p></li><li><p>full body = 10</p></li><li><p>pose = 15</p></li><li><p>other clothing = 10</p></li><li><p>ornament_waist = 10</p></li></ul></li><li><p>number of repeats = 4</p><ul><li><p>nsfw = 30</p></li><li><p>chibi = 5</p></li></ul></li><li><p>number of images = 130</p></li><li><p>number of epochs = 19</p></li></ul><pre><code>#!/bin/bash
# LoRA train script by @Akegarasu

# Train data path | 设置训练用模型、图片
pretrained_model="./sd-models/model.ckpt"     # base model path | 底模路径
is_v2_model=0                                 # SD2.0 model | SD2.0模型 2.0模型下 clip_skip 默认无效
parameterization=0                            # parameterization | 参数化 本参数需要和 V2 参数同步使用 实验性功能
train_data_dir="./train/1.formidable-default" # train dataset path | 训练数据集路径
reg_data_dir=""                               # directory for regularization images | 正则化数据集路径，默认不使用正则化图像。

# Network settings | 网络设置
network_module="networks.lora" # 在这里将会设置训练的网络种类，默认为 networks.lora 也就是 LoRA 训练。如果你想训练 LyCORIS（LoCon、LoHa） 等，则修改这个值为 lycoris.kohya
network_weights=""             # pretrained weights for LoRA network | 若需要从已有的 LoRA 模型上继续训练，请填写 LoRA 模型路径。
network_dim=32                 # network dim | 常用 4~128，不是越大越好
network_alpha=16               # network alpha | 常用与 network_dim 相同的值或者采用较小的值，如 network_dim的一半 防止下溢。默认值为 1，使用较小的 alpha 需要提升学习率。

# Train related params | 训练相关参数
resolution="768,768"  # image resolution w,h. 图片分辨率，宽,高。支持非正方形，但必须是 64 倍数。
batch_size=2          # batch size
max_train_epoches=20  # max train epoches | 最大训练 epoch
save_every_n_epochs=1 # save every n epochs | 每 N 个 epoch 保存一次

train_unet_only=0            # train U-Net only | 仅训练 U-Net，开启这个会牺牲效果大幅减少显存使用。6G显存可以开启
train_text_encoder_only=0    # train Text Encoder only | 仅训练 文本编码器
stop_text_encoder_training=0 # stop text encoder training | 在第N步时停止训练文本编码器

# 噪音
noise_offset="0" # noise offset | 在训练中添加噪声偏移来改良生成非常暗或者非常亮的图像，如果启用，推荐参数为0.1
keep_tokens=2    # keep heading N tokens when shuffling caption tokens | 在随机打乱 tokens 时，保留前 N 个不变。
min_snr_gamma=0  # minimum signal-to-noise ratio (SNR) value for gamma-ray | 伽马射线事件的最小信噪比（SNR）值  默认为 0

# 金字塔噪声
multires_noise_iterations=6 # 多分辨率（金字塔）噪声迭代次数 推荐 6-10。无法与 noise_offset 一同启用。
multires_noise_discount=0.3 # 多分辨率（金字塔）衰减率 推荐 0.3，须同时与上方参数 multires_noise_iterations 一同启用。

# Learning rate | 学习率
lr="3.5e-5"            # 3.5e-5=3.5*10^(-5)=0.000035
unet_lr="3.5e-5"       # 3.5e-5=3.5*10^(-5)=0.000035
text_encoder_lr="3e-6" #   3e-6=3.0*10^(-6)=0.000003
lr_scheduler="cosine_with_restarts" # "linear", "cosine", "cosine_with_restarts", "polynomial", "constant", "constant_with_warmup", "adafactor"
lr_warmup_steps=0                   # warmup steps | 学习率预热步数，lr_scheduler 为 constant 或 adafactor 时该值需要设为0。
lr_restart_cycles=1                 # cosine_with_restarts restart cycles | 余弦退火重启次数，仅在 lr_scheduler 为 cosine_with_restarts 时起效。

# Output settings | 输出设置
output_name="1.formidable-default" # output model name | 模型保存名称
save_model_as="safetensors"        # model save ext | 模型保存格式 ckpt, pt, safetensors

# Resume training state | 恢复训练设置
save_state=0 # save state | 保存训练状态 名称类似于 &lt;output_name&gt;-??????-state ?????? 表示 epoch 数
resume=""    # resume from state | 从某个状态文件夹中恢复训练 需配合上方参数同时使用 由于规范文件限制 epoch 数和全局步数不会保存 即使恢复时它们也从 1 开始 与 network_weights 的具体实现操作并不一致

# 其他设置
min_bucket_reso=256              # arb min resolution | arb 最小分辨率
max_bucket_reso=1024             # arb max resolution | arb 最大分辨率
persistent_data_loader_workers=0 # persistent dataloader workers | 容易爆内存，保留加载训练集的worker，减少每个 epoch 之间的停顿
clip_skip=2                      # clip skip | 玄学 一般用 2

# 优化器设置
optimizer_type="Lion" # Optimizer type | 优化器类型 默认为 AdamW8bit，可选：AdamW AdamW8bit Lion SGDNesterov SGDNesterov8bit DAdaptation AdaFactor

# LyCORIS 训练设置
algo="lora"  # LyCORIS network algo | LyCORIS 网络算法 可选 lora、loha、lokr、ia3、dylora。lora即为locon
conv_dim=4   # conv dim | 类似于 network_dim，推荐为 4
conv_alpha=4 # conv alpha | 类似于 network_alpha，可以采用与 conv_dim 一致或者更小的值
dropout="0"  # dropout | dropout 概率, 0 为不使用 dropout, 越大则 dropout 越多，推荐 0~0.5， LoHa/LoKr/(IA)^3暂时不支持</code></pre>