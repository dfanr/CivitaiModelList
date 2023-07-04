## LowRA
### 一、模型概述

- 标签：`dark`, `masterpiece`, `style`, `epic`, `cinematic`, `low key`, `filmic`
- 下载数：73294
- 收藏人数：5243
- 评论人数：110
- 评分人数：353
- 评分：4.85

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2.0

- 统计数据
  - 发布时间：2023-05-05T11:29:46.765Z
  - 原始模型：SD 1.5
  - 下载数：64132
  - 评分人数：223
  - 评分：4.97
- 下载地址
  - [LowRA.safetensors](https://civitai.com/api/download/models/63006)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fa545fa5-10ca-4b41-8ca0-f91dab227816/width=450/693804.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4f29cc2c-d1de-48ee-a31e-7858a823635b/width=450/693802.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/82e73369-a723-456c-869f-07e9abd48a19/width=450/693803.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/33e89d0c-2fee-4a34-9ff7-eea8f9f0e1a9/width=450/693801.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-05-05T11:12:15.112Z
  - 原始模型：SD 1.5
  - 下载数：9162
  - 评分人数：130
  - 评分：4.65
- 下载地址
  - [LowRa.safetensors](https://civitai.com/api/download/models/52753)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2a5c8ec7-515d-4e93-9c56-6f07ad58cb00/width=450/569206.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/315d8c2a-cff8-4205-45e9-739d4b4ee600/width=450/569212.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e0c1bc89-a456-4a8b-c18d-7c112065ed00/width=450/569205.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2a34aa31-ca8b-4d23-e161-ffb6320b3000/width=450/596638.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>LowRA</h1><h2>The Real Game Changer</h2><p>Now you can get as much <code>low key</code> as you need with just one LowRA</p><h3><u>Quick tips</u>:</h3><ul><li><p>Your start point (weight) is 0.6 ➜ <code>&lt;lora:LowRA:0.6&gt;</code></p></li><li><p>Looking for more darkness? Just add <code>dark theme</code> to your prompt</p></li><li><p>The best weight range is about 0.6 ≈ 0.8</p></li></ul><h3><u>Technical information</u>:</h3><p>Dreambooth training (creation) models process is designed to turn each of your images into noise at each stage of training. This is done, so that later, during the image generation phase, Stable Diffusion could turn any random noise back into an image. The more you Train your model in Dreambooth (the more often you turn the same image into random noise), the easier it will be for Stable Diffusion to recreate the image you need from random noise (which Stable Diffusion creates itself). For example, If you turn 1 image into random noise 10 times (10 steps Dreambooth Training), then during generation, Stable Diffusion has 10 times more chance to recreate the image from noise. That's why we making thousands of training steps – to increase the probability of recreating an image.<br /><br />However, by turning any image into noise we get ≈45 to ≈55 percent of <em>Brightness</em> (HSB). Always. You can check this on python with <code>numpy random</code> or in Photoshop, just take a completely white square and a completely black square and then turn both into noise. Then Filter ➜ Blur ➜ Average. You will always get ≈45 to ≈55 percent of <em>Brightness</em>. That's why you always fail, when you trying to generate <code>completely black square</code> or <code>completely white square</code>. You just can't.<br /><br />LowRA solves this problem, when it embeds itself in the image generation process. At the beginning of the image generation process, LowRA gives you another noise, that allows you to get the image in the key you want. The higher the weight of LowRA, the more Stable Diffusion will be forced to use samples from LowRA. The samples used to train LowRA were strictly selected images that had an overall average <em>Brightness</em> of less than 25%. This made it possible to make the use of LowRA with less weight, so that when you use LowRA in parallel with other LoRAs, you don't get mess. So if you are using something else to get <em>low key</em> images in Stable Diffusion, you should forget the old techniques and just use LowRA.<br /><br />The careful selection of images in LowRA training proceeded as follows: a few thousand low key images were selected to begin with, each getting one noise pattern in Photoshop and a strict color palette for each individual subject. Warm and bright tones received no more than 25% of the space in the entire image. Next, each processed image was sent to img2img to create 10 similar generations. After that, a sample of the 10 images was tested for proper color reproduction in Photoshop. If the test passed, and the bright and warm tones did not exceed 25% of the <em>Brightness</em>, the image that was sampled was sent to dataset. If not, the image was simply deleted and the next image was taken. This rigorous and careful selection made it possible to obtain the ideal dataset for training. And now you can see the result of my work on this page.</p>