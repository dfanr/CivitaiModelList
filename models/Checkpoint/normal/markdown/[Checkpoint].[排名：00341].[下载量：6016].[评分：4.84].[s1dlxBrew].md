## s1dlxBrew
### 一、模型概述

- 标签：`photorealistic`
- 下载数：6016
- 收藏人数：972
- 评论人数：54
- 评分人数：19
- 评分：4.84

### 二、下载地址（共4个版本）

#### [版本4/共4个版本] 0.4

- 统计数据
  - 发布时间：2023-06-15T12:18:09.296Z
  - 原始模型：SD 1.5
  - 下载数：1613
  - 评分人数：1
  - 评分：3
- 下载地址
  - [s1dlxbrew_04.ckpt](https://civitai.com/api/download/models/13166?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [s1dlxbrew_04.safetensors](https://civitai.com/api/download/models/13166?type=Model&format=SafeTensor&size=full&fp=fp16)
  - [s1dlxbrew_04.safetensors](https://civitai.com/api/download/models/13166)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fbe0e028-f449-4f0e-4879-c1cf06a8b600/width=450/127297.jpeg" /> |
| ---- |

#### [版本3/共4个版本] 0.3

- 统计数据
  - 发布时间：2023-03-30T12:02:09.211Z
  - 原始模型：SD 1.5
  - 下载数：1925
  - 评分人数：7
  - 评分：5
- 下载地址
  - [s1dlxbrew_03.safetensors](https://civitai.com/api/download/models/6980)
  - [s1dlxbrew_03.ckpt](https://civitai.com/api/download/models/6980?type=Model&format=PickleTensor&size=full&fp=fp16)
- 样例图像：
#### [版本2/共4个版本] 0.2

- 统计数据
  - 发布时间：2023-03-30T12:02:09.211Z
  - 原始模型：SD 1.5
  - 下载数：2026
  - 评分人数：7
  - 评分：4.86
- 下载地址
  - [s1dlxbrew_02.ckpt](https://civitai.com/api/download/models/6074?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [s1dlxbrew_02.safetensors](https://civitai.com/api/download/models/6074)
- 样例图像：
#### [版本1/共4个版本] 0.1-LOL

- 统计数据
  - 发布时间：2023-05-02T09:06:41.762Z
  - 原始模型：SD 1.5
  - 下载数：452
  - 评分人数：4
  - 评分：5
- 下载地址
  - [s1dlxbrew_01LOL.pt](https://civitai.com/api/download/models/5395?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [s1dlxbrew_01LOL.safetensors](https://civitai.com/api/download/models/5395)
- 样例图像：

### 三、详情
<p>Note: this mix needs a VAE model on the side. The usual <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/tree/main">vae-ft-mse-840000-ema-pruned</a> would do</p><p></p><h2>Mix recipes</h2><h3>v0.1</h3><p><code>(hassan*0.7 + vivid*0.3)*0.3 + dreamlike*0.7</code></p><p></p><h3>v0.2</h3><p><code>(hassan*0.6 + (vivid - sd1.5)*0.4)*0.4 + (dreamlike - sd1.5)*0.6</code></p><p></p><h3>v0.3</h3><p>same as v0.2</p><p></p><h3>v0.4</h3><p><code>grad_v(v0.3, analog diffusion - sd1.5)</code></p>