## AkkaiMix
### 一、模型概述

- 标签：`anime`, `base model`
- 下载数：1002
- 收藏人数：180
- 评论人数：3
- 评分人数：4
- 评分：4.75

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-28T02:05:41.849Z
  - 原始模型：SD 1.5
  - 下载数：1002
  - 评分人数：4
  - 评分：4.75
- 下载地址
  - [akkaimix_v10.safetensors](https://civitai.com/api/download/models/83232)
  - [akkaimix_v10_trainingData.zip](https://civitai.com/api/download/models/83232?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6d8a2b4b-8153-4a9d-8cbb-211562ebcf53/width=450/995598.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1d962b03-2c2d-4d41-b8e2-b779ca52cb6d/width=450/980259.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/df34ccb1-76c9-46d9-a61b-a0d96eee9955/width=450/953468.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6efa50a9-695a-45a3-978c-26c8ced744b0/width=450/946421.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This model is a result of multiple mixes and lora merges to get cute faces with big round eyes, high contrast, thick black lines with a high level of detail.<br /><br />The pros :<br />- Lora stacking without too much mess<br />- Good with both SFW and NSFW<br />- Very little prompting required<br />- Highly detailed skin &amp; clothing textures<br />- More than decent hands from base gen<br /><br />The cons :<br />- Might give some unwanted animal ears<br />- Do no mix well with certain style lora<br /><br />Recommended parameters :<br /><br /><span style="color:rgb(255, 255, 255)">VAE : kl-f8-anime2.pt</span></p><p><span style="color:rgb(64, 192, 87)">Masterpiece, best quality</span></p><p><span style="color:rgb(250, 82, 82)">(worst quality, low quality:1.4)</span></p><p><span style="color:rgb(34, 139, 230)">Sampler : Dpm++ 2M Karras Steps : 30</span></p><p><span style="color:rgb(34, 139, 230)">Sampler : Dpm++ SDE Karras Steps : 25</span></p><p><span style="color:rgb(34, 139, 230)">Sampler : UniPC Steps : 30</span></p><p><span style="color:rgb(253, 126, 20)">CFG scale : 6.5-7.5</span></p><p><span style="color:rgb(250, 242, 0)">Clip Skip : 2</span></p><p><span style="color:rgb(247, 89, 144)">Hires.fix: Ultra_Remacri (See Training data) or SwinIR_4X Denoising strength : 0.45</span></p><p></p><p>I'd highly recommend to also use Adetailer at default parameters with the "face_yolov8s" model.</p><p><br />Tips :<br />- For better quality eyes and iris, simply specify eye colors<br />- Keep the negative simple, stacking negative TI will have the opposite effect</p>