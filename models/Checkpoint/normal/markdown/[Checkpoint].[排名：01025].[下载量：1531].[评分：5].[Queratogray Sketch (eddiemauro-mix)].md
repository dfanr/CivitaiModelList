## Queratogray Sketch (eddiemauro-mix)
### 一、模型概述

- 标签：`pencil`, `monochrome`, `style`, `sketching`, `illustration`, `sketch`, `pen`, `grayscale`
- 下载数：1531
- 收藏人数：318
- 评论人数：7
- 评分人数：4
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-30T04:15:07.429Z
  - 原始模型：SD 1.5
  - 下载数：1531
  - 评分人数：4
  - 评分：5
- 下载地址
  - [queratograySketch_v10.safetensors](https://civitai.com/api/download/models/85210)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/149afe79-321a-4d28-b186-564048a3a7e3/width=450/1086044.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f9cf478d-fac3-4684-9684-d788160124a8/width=450/1066189.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ab12e6db-581f-4c4a-8b74-d1160e2dcb8f/width=450/964375.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/68ce7690-4647-46f9-8977-3e41067b6536/width=450/964374.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Hi, I’m a product and car designer, and I’m so excited to test with AI. This tool is to enjoy and also to change/transform images style (sketch). If you want to support my work and help me to upload more models (with better quality), you can do it by entering here and donating, I would greatly appreciate it:</p><p><a target="_blank" rel="ugc" href="https://ko-fi.com/eddiemauro">https://ko-fi.com/eddiemauro</a></p><p></p><p>I decided to collaborate with a friend, called ‘Joell Martínez Tenjo’, who is a product designer, but focuses on animation and illustration. We took more than 50 sketch style of his grayscale/monochrome illustrations "Sketchbook" series, then I trained a model and mixed it with some other models to regularize training, obtaining aprox. 50% of his final style. You can check his profile here:</p><p><a target="_blank" rel="ugc" href="https://www.behance.net/queratoilustracion">https://www.behance.net/queratoilustracion</a></p><p></p><p>The style is centered just on generating people images, but you can combine it with other Lora's to extend the use with different kinds of things.</p><p></p><p>After a lot of training and testing images, I finally arrived at a stable model to generate this Sketch style, called "Queratogray". Recommendation to use this model:</p><ol><li><p><u>It is mandatory to use this caption in the prompt: “sketch artstyle”.</u></p></li><li><p><u>Please don't use Negative Embeddings. Try to have a simple Negative prompt (see image examples) because this will destroy the style. It is good in generating faces and eyes, so it is not so necessary "face restoration" or other embeddings.</u></p></li><li><p>Clip Skip 2. Go to settings-Stable Diffusion-Clip Skip, and put “2”. I trained model with this option.</p></li><li><p>Generate first some images by changing “Batch size”, select one, and go to img2img mode, duplicate or increase resolution (image size), with “denoise strength” of “0.3 to 0.5”. It is the same process of “hires.fix” in txt2img mode, but you can have more images generated to select. Try to preserve 512x512 (or just 512 on one side) because images are trained at this resolution, and when you change it the model-shapes start gets crazy, even that you can experiment.</p></li><li><p>Use new “extra tool” for enhancing image called "<strong>4xNMKD-SIAX_200k" or "4xUniscaleV2-Moderate"</strong>, to increase final resolution. You can use these in hires.fix. <strong>Then Increase size with ControlNet Tile and "Ultimate SD upscale" with 4x-UltraSharp, 4xNMKD-SIAX_200k or 4xUniscaleV2-Moderate with double of size and and denoise of 0.3-0.5.</strong></p></li><li><p>Use ControlNet to generate a more controlled shape of what you want, in case you are changing an image into this sketch style.</p></li><li><p>Use VAE 560000 or 840000 of SD model 1.5, to enhance the image created. Sometimes works. <span style="color:rgb(193, 194, 197)">It enhances mostly the contrast.</span></p><p></p></li></ol><p></p><p>The sample images here were created the model, and it has not any inpainting or post-production, just were upscaled with A111 models. You have to consider that you have to experiment so much to arrive at these results because it is hard to test just once and get an ideal result. I use Automatic1111 with most used extensions.</p><p></p><p>Example Prompt:</p><p></p><p><strong>Positive prompt: </strong>A young man, sketch artstyle, grayscale, monochrome, ((solo))</p><p><strong>Negative prompt:</strong> out of frame, multiple people, missing fingers, extra digit, fewer digits, (((many people))), blurry, color</p><ul><li><p>Steps, from 20-40 (For EulerA is enough 20, and you can also use DPM++SDE Karras, but EulerA is better mostly)</p></li></ul><ul><li><p>CFG scale: 7-8.</p></li></ul><p></p><p>You can follow me on my social networks. I will show my process and also design tips and tools:</p><p><a target="_blank" rel="ugc" href="https://www.facebook.com/eddiemauro.design"><u>https://www.facebook.com/eddiemauro.design</u></a></p><p><a target="_blank" rel="ugc" href="https://www.instagram.com/eddiemauro.design/"><u>https://www.instagram.com/eddiemauro.design/</u></a></p><p><a target="_blank" rel="ugc" href="https://www.linkedin.com/in/eddiemauro/"><u>https://www.linkedin.com/in/eddiemauro/</u></a></p><p><a target="_blank" rel="ugc" href="https://www.behance.net/eadesign1"><u>https://www.behance.net/eadesign1</u></a></p><p></p>