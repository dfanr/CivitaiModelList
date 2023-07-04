## Object Taped To Wall
### 一、模型概述

- 标签：`style`, `artistic`
- 下载数：159
- 收藏人数：90
- 评论人数：1
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] V1

- 统计数据
  - 发布时间：2022-11-27T19:29:06.383Z
  - 原始模型：SD 1.5
  - 下载数：159
  - 评分人数：2
  - 评分：5
- 下载地址
  - [objectTapedToWall_v1.ckpt](https://civitai.com/api/download/models/1101)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/01175479-d4d2-4340-e53a-7255c5034b00/width=450/8957.jpeg" /> |
| ---- |


### 三、详情
<p>Originally posted to <a href="https://huggingface.co/ProGamerGov/Object-Taped-To-Wall-Diffusion-V1" rel="ugc" target="_blank">HuggingFace by ProGamerGov</a></p><p>This fine-tuned Stable Diffusion v1.5 model was trained for 2000 iterations with a batch size of 4, on a selection of photos of things taped to wall. Training was performed using <a href="https://github.com/ShivamShrirao/diffusers" rel="ugc" target="_blank">ShivamShrirao/diffusers</a> with full precision, prior-preservation loss, the train-text-encoder feature, and the new <a href="https://huggingface.co/stabilityai/sd-vae-ft-mse" rel="ugc" target="_blank">1.5 MSE VAE from Stability AI</a>. A total of 2100 regularization / class images were used from <a href="https://huggingface.co/datasets/ProGamerGov/StableDiffusion-v1-5-Regularization-Images" rel="ugc" target="_blank">here</a>. Regularization images were generated using the prompt "artwork style" with 50 DPM++ 2S a Karras steps and a CFG of 7, using the MSE VAE. A negative prompt of "text" was also used for this dataset.</p><p>Use the tokens <strong>ttw style</strong> in your prompts for the effect. Note that the effect also appears to occur at a much weaker strength on prompts that steer the output towards specific artistic styles.</p><p>This model will likely not perform well on taping objects that are not traditionally able to be taped to walls.</p><ul><li><a href="https://huggingface.co/ProGamerGov/Object-Taped-To-Wall-Diffusion-V1/resolve/main/v1_size_512x512_t4x8.png" rel="ugc" target="_blank">Full Image</a></li></ul><p>Example images were generated with the v1 2000 iteration model using DPM++ 2S a Karras:</p>ttw style, &lt;object&gt; taped to wall
