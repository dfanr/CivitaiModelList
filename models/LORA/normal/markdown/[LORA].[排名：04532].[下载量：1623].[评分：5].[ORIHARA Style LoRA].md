## ORIHARA Style LoRA
### 一、模型概述

- 标签：`anime`, `girl`, `style`, `artist`, `artstyle`, `embedding`, `girls`
- 下载数：1623
- 收藏人数：393
- 评论人数：6
- 评分人数：4
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-03-20T01:17:50.139Z
  - 原始模型：SD 1.5
  - 下载数：1623
  - 评分人数：4
  - 评分：5
- 下载地址
  - [ORIHARA.safetensors](https://civitai.com/api/download/models/8070)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/81c807cb-5f51-4b14-bca9-b04e5e70da00/width=450/76061.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/59f9b51f-ec5e-4b39-5a79-8ab3271e1a00/width=450/76070.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/05ebae12-157b-4a2b-70c1-8b28e140f500/width=450/76069.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0f494a23-9489-4300-f8c9-5725e34afe00/width=450/76068.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>ORIHARA Style LoRA</h1><h3><em>If you enjoy my models and want to support me you could </em><a rel="ugc" href="https://www.buymeacoffee.com/Pixel422"><em>buy me a coffee</em></a><em>!</em></h3><p>This is my first time training an embedding so it might not be at the highest quality but I'm quite satisfied with the results. It mimics the artstyle of the artist ORIHARA, the artist responsible for most of the vocalist Ado's artwork. Keep in mind when using it that it was trained on 6GB VRAM so the embedding might not be as good as other ones on this website but you can still get satisfactory results.</p><p></p><p>The example images were created with AbyssOrangeMix2 (hard) and I was using 0.75 weight but feel free to experiment with other weights and models. This might be model-specific but it is much better at making women than men. For the NSFW images i have also been using a couple of Corneo's textual inversion embeddings as well as JustNeutral's ShyLily embedding and it seems to be merging pretty well.</p><p></p><p>To change the weight just change the '1' in this prompt: &lt;lora:ORIHARA:1&gt;.</p><p></p><p><strong><u>I'd love to see the art you guys make with it so feel free to add them in comments.</u></strong></p><p></p><p><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight</strong> (by default it's <code>:1</code> which is usually too high)</p></li></ul>