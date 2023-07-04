## ControlNet QR Code
### 一、模型概述

- 标签：`tool`
- 下载数：2214
- 收藏人数：257
- 评论人数：15
- 评分人数：6
- 评分：4.67

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] SD2.1 v1

- 统计数据
  - 发布时间：2023-06-15T07:25:04.314Z
  - 原始模型：SD 2.1
  - 下载数：1103
  - 评分人数：2
  - 评分：4.5
- 下载地址
  - [controlnetQRCode_sd21V1.yaml](https://civitai.com/api/download/models/96366?type=Config&format=Other)
  - [controlnetQRCode_sd21V1.safetensors](https://civitai.com/api/download/models/96366)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a29b45ea-f548-4482-8674-9701a8db93fd/width=450/1150212.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4bac4ece-c5c8-452e-858d-78c5873ec697/width=450/1150211.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e86ea6c8-bf71-44db-a2b1-c19efae03999/width=450/1150229.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da1a2646-ca32-4b1b-bce6-312cbbaa4547/width=450/1150230.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] SD1.5 v1

- 统计数据
  - 发布时间：2023-06-15T07:25:04.314Z
  - 原始模型：SD 1.5
  - 下载数：1111
  - 评分人数：4
  - 评分：4.75
- 下载地址
  - [controlnetQRCode_sd15V1.yaml](https://civitai.com/api/download/models/96367?type=Config&format=Other)
  - [controlnetQRCode_sd15V1.safetensors](https://civitai.com/api/download/models/96367)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/473142b5-8854-42be-a9e6-0aa1b38e7350/width=450/1150292.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/18a3936e-bf52-4ef1-a0cb-dedd95b3e41b/width=450/1150316.jpeg" /> |
| ---- | ---- |


### 三、详情
<h1 id="heading-12">QR Code Conditioned ControlNet Models for Stable Diffusion 1.5 and 2.1</h1><p></p><h2 id="heading-13">Model Description</h2><p>These ControlNet models have been trained on a large dataset of 150,000 QR code + QR code artwork couples. They provide a solid foundation for generating QR code-based artwork that is aesthetically pleasing, while still maintaining the integral QR code shape.</p><p>The Stable Diffusion 2.1 version is marginally more effective, as it was developed to address my specific needs. However, a 1.5 version model was also trained on the same dataset for those who are using the older version.</p><h2 id="heading-14">Performance and Limitations</h2><p>These models perform quite well in most cases, but please note that they are not 100% accurate. In some instances, the QR code shape might not come through as expected. You can increase the ControlNet weight to emphasize the QR code shape. However, be cautious as this might negatively impact the style of your output.**To optimize for scanning, please generate your QR codes with correction mode 'H' (30%).**</p><p>To balance between style and shape, a gentle fine-tuning of the control weight might be required based on the individual input and the desired output, aswell as the correct prompt. Some prompts do not work until you increase the weight by a lot. The process of finding the right balance between these factors is part art and part science. For the best results, it is recommended to generate your artwork at a resolution of 768. This allows for a higher level of detail in the final product, enhancing the quality and effectiveness of the QR code-based artwork.</p><h2 id="heading-1239">Installation</h2><p>The simplest way to use this is to place the .safetensors model and its .yaml config file in the folder where your other controlnet models are installed, which varies per application.</p><p>For usage in auto1111 they can be placed in the webui/models/ControlNet folder. They can be loaded using the controlnet webui extension which you can install through the extensions tab in the webui (<a target="_blank" rel="ugc" href="https://github.com/Mikubill/sd-webui-controlnet">https://github.com/Mikubill/sd-webui-controlnet</a>). Make sure to <strong>enable</strong> your controlnet unit and set your input image as the QR code. Set the model to either the SD2.1 or 1.5 version depending on your base stable diffusion model, or it will error. No pre-processor is needed, though you can use the <strong>invert</strong> pre-processor for a different variation of results. 768 is the preferred resolution for generation since it allows for more detail.</p><p>Make sure to look up additional info on how to use controlnet if you get stuck, once you have the webui up and running its really easy to install the controlnet extension aswell.</p><p></p>