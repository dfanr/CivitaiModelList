## Giger's Alien Factory
### 一、模型概述

- 标签：`character`, `movie`, `horror`, `alien`, `monsters`, `giger`
- 下载数：1059
- 收藏人数：277
- 评论人数：19
- 评分人数：7
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] 1.1 (768)

- 统计数据
  - 发布时间：2023-03-05T22:31:33.230Z
  - 原始模型：SD 1.5
  - 下载数：812
  - 评分人数：2
  - 评分：5
- 下载地址
  - [gigersAlienFactory_11768.ckpt](https://civitai.com/api/download/models/19091?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [gigersAlienFactory_11768.safetensors](https://civitai.com/api/download/models/19091)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e84deda6-bba7-4587-4aad-d15189a33f00/width=450/199861.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2786ce00-666a-4123-d1da-a9d465af5300/width=450/199860.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/983ba53e-2a78-408f-3cc2-4f55d70a1500/width=450/199858.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/23265a0d-cc6e-4e24-8127-9dd62a0f4b00/width=450/199857.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] 1.0

- 统计数据
  - 发布时间：2023-03-05T22:31:33.230Z
  - 原始模型：SD 1.5
  - 下载数：247
  - 评分人数：5
  - 评分：5
- 下载地址
  - [gigersAlienFactory_10.ckpt](https://civitai.com/api/download/models/4722?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [gigersAlienFactory_10.safetensors](https://civitai.com/api/download/models/4722)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d6f22751-f365-4be1-48fa-01e7cfd3d600/width=450/33589.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4a97d0ae-6752-4821-9f5f-c09fa489c100/width=450/33588.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/21fcbd55-5556-4476-5085-5ebacd15a200/width=450/33587.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3483d69c-4877-4434-2180-dd8d9cd2aa00/width=450/33586.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>A gift to all my fellow Alien fans, far and wide. A tribute to a genius visionary who inspired an entire generation of artists. Giger you were a true master. I offer my humble contribution towards your great legacy.</p><p><br />Allow me to present, Giger’s Alien Factory</p><p></p><p>Over 350 hours of work, including 60 hours of image manipulation/clean up, 15 dreambooth trainings and tens of thousands of image generations. Resulting in a model capable of producing a detailed likeness of Gigers classic Xenomorph. Compatible with decently high CFG on most seeds before deteriorating. Optimised for close portraits and full body shots and built to be the most consistent, accurate and faithful Giger's Xeno model I could manage.</p><p><br />The data set is built from photos of six startlingly accurate, fully detailed models. A life-size cast from moulds used for the original costume, four extremely detailed 1/3rd scale models based on the original casting and a life-size head. All selected models are frighteningly faithful to the original down to the finest detail, while differing slightly in colour and texture for improved variety. Complete with the translucent dome skull detailing, sadly never used in the movie. Strictly no upscaled images and only the cleanest data, completely free from noise and grain.</p><p><br />On the updated model I do full body generations @ 1024x704 with “walking” or “standing” specified in the prompt to ensure the whole body is in frame. You can also add “close portrait” and “headshot” to the negative prompt to help with this. Close portraits and torso shots can be made at this ratio and size but the duplications become a problem.</p><p><br />I do close portraits @ 704x1024, this ratio also results in a lot of duplications but does result in better composed close portrait shots. Start the prompt with “8k close portrait headshot photo” for decent close ups.</p><p></p><p>For most generations outside the native 512x, the tail is hit and miss and a real nightmare. It can manifest randomly, ruining otherwise perfect outputs with floating tails, sticking out of random places of the Xenos body, throughout the scenes and anywhere but the Xeno’s butt. I have tried my best to mitigate this with specific regularisation images and the selection, framing and editing of the reference images. This didn’t work too well and I think I need to use captions which I plan to add to the model soon.</p><p><br />To avoid duplications and guarantee consistency, render with a square ratio. Don’t worry about going small though, we can easily render as big as 768x768 before duplications and distortions start to creep into the outputs.</p><p><br />Hires fix doesn't like this model and I discourage anyone from hoping for consistent results using it. The anatomy is just too wild to present a clear framework for img2img to work with.</p><p><br />The models CFG sweet spot is around 9-12 and most details are complete by 30 steps but I take mine much higher to at least 150 on most outputs to tighten up the likeness.</p><p><br />The concept can be quite heavy in this model and if the Xeno elements are bleeding into your environment, enter the token after the scene description of the prompt. This usually requires a higher CFG than usual by about 2-3 to complete the likeness of the Xeno.</p><p><br />eg: “8k photo of a picturesque edo japanese village, bigbadejo alien_monster, brandishing a samurai sword, global illumination, depth of field, ray tracing, subsurface scattering,”</p><p><br />I have completed a full week of extensive testing on the final model. Prompting in different locations/environments to get a feel of the limitations and a sense of what it's capable of. I’m pleased to say the model is very capable, far more flexible than I ever hoped for and has become quite a powerful tool. Blend it with animals, mix it with popular models or even apply it as a style. I can’t wait to see what the community creates with it. (strictly no tutu’s)</p><p><br /></p>