## Zelda CDI Style LoRA
### 一、模型概述

- 标签：`nintendo`, `the legend of zelda`, `philips`, `style`, `video game`
- 下载数：1524
- 收藏人数：289
- 评论人数：10
- 评分人数：22
- 评分：4.91

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] 256 dim

- 统计数据
  - 发布时间：2023-02-05T22:33:50.008Z
  - 原始模型：SD 1.4
  - 下载数：1524
  - 评分人数：22
  - 评分：4.91
- 下载地址
  - [ZeldaCDI256NAI.safetensors](https://civitai.com/api/download/models/7018)
  - [ZeldaCDI.zip](https://civitai.com/api/download/models/7018?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/223cb61e-835e-4c56-777e-ae3ee68dea00/width=450/64500.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dc35bd92-6426-4620-99e1-a070afa56d00/width=450/64493.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1cc9b3e3-f1c1-49be-aa3e-c6f18a6d9500/width=450/64499.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/78e4607e-0c18-40ad-a97e-74c322eff700/width=450/64498.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3>Zelda CDI style LoRA</h3><p></p><p>This is a LoRA, this mean that you need to update Voldy/AUTOMATIC1111's webui to use it (use <code>git pull</code>) .</p><p></p><p>That LoRA does not have a particular trigger (except the default <code>&lt;lora:LoRaName:1&gt;</code>).</p><p></p><p>You can use it at weight <code>1.0</code> but since it's a 256 dim model, there is a possibility that it overfit in some situation and if it happens to overfit you can lower the weight to <code>0.9</code> or <code>0.8</code> .</p><p></p><pre><code>121 images, 8 repeats,5 epoch,4840 steps
Learning rate: 1e-4
Text encoder learning rate: 5e-5 
Unet learning rate: 1e-4 
max bucket resolution: 512 
clip skip: 2 
dim/alpha: 256 
batch size=1 
Base model: a Notorious AnythingV3 Important ancestor (you get it?) this mean that this LoRA work on any model derived from that particular model like AnythingV3/4/4.5, AOM 1/2,etc...</code></pre><p></p><p></p><p>All characters are owned by Nintendo even if they pretend that this game never existed.</p>