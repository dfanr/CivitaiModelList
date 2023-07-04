## Controlnet QR Pattern (QR Codes)
### 一、模型概述

- 标签：`tool`
- 下载数：2674
- 收藏人数：465
- 评论人数：44
- 评分人数：12
- 评分：4.42

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-16T00:03:46.051Z
  - 原始模型：SD 1.5
  - 下载数：2674
  - 评分人数：12
  - 评分：4.42
- 下载地址
  - [controlnetQRPatternQR_v10.yaml](https://civitai.com/api/download/models/96917?type=Config&format=Other)
  - [controlnetQRPatternQR_v10.safetensors](https://civitai.com/api/download/models/96917)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d8d59b59-4bf9-4130-b8b2-896da0051364/width=450/1160663.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8c5d2811-8809-4acc-97d7-cbab8b15bb18/width=450/1199725.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c93ef576-0c9c-4bcb-91fc-04f748c91e75/width=450/1180167.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/64c0638f-c119-4cd4-ab24-4c699ea4a4e1/width=450/1160653.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-22">Controlnet model for use in qr codes</h1><p>Conditioning only 15% of the pixels closest to black, so as not to affect the luminance of the rest of the image. Also manteing the color to some degree.</p><p>Move the .yaml to extensions/sd-webui-controlnet/models</p><p><strong>Take a look at antfu blog posts for a detailed workflow:  </strong></p><p><a target="_blank" rel="ugc" href="https://antfu.me/posts/ai-qrcode">https://antfu.me/posts/ai-qrcode</a></p><p><a target="_blank" rel="ugc" href="https://antfu.me/posts/ai-qrcode-refine">https://antfu.me/posts/ai-qrcode-refine</a></p><pre><code>IMPORTANT:

Don't expect the images to be scannable at first, try to generate a lot of images and adjust the parameters. The recommended parameters are only recommendations, many images require different values.
</code></pre><pre><code>Recommended parameters:

Steps: +50, Size: 920x920,
ControlNet:
preprocessor: none,
weight: 1,
starting/ending: (0, 0.75),
control mode: Balanced

Play arround with the starting step, 0 to 0.25 its the sweetspot, if it start at 0 the qr has priority, the higher you raise them, the stronger the prompt gets

Hires fix is not recommended but if you want to use it anyway, ensure that your resolution is set to a minimum of 600x600. Additionally, set the denoising strength to a minimum of 0.7 and the hires steps to at least 20.

To ensure smooth generation of details within the QR code, it is recommended to use a shortened link or text. Utilizing a link shortener such as url.zip or bit.ly is advisable, as the complexity of the QR code increases with longer links or text.
</code></pre><pre><code>Suggested parameters by hello-docker on reddit:

Sampling steps - 22
Height and width - 920 &amp; 920
ControlWeight - 1.25
Starting control step - 0
Ending control step - 0.9
Control mode - Balanced
Resize Mode - Resize and fill</code></pre><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3a59da58-c729-4c88-bd4b-8005e35d7fdf/width=525/3a59da58-c729-4c88-bd4b-8005e35d7fdf.jpeg" /></p><p><strong><span style="color:rgb(242, 243, 245)">Fruit store by @.pos in discord</span></strong></p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3dcf57c3-79f5-4406-8fe4-541f7a392904/width=525/3dcf57c3-79f5-4406-8fe4-541f7a392904.jpeg" /></p><p>(Custom preprocessor still on development)</p>