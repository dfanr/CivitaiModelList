## Perfect Sketchbook 完美草图
### 一、模型概述

- 标签：`anime`, `portrait`, `sketch art`, `style`, `illustration`
- 下载数：2027
- 收藏人数：831
- 评论人数：16
- 评分人数：6
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] SketchyAnimeStyle

- 统计数据
  - 发布时间：2023-06-12T03:09:52.269Z
  - 原始模型：Other
  - 下载数：1008
  - 评分人数：2
  - 评分：5
- 下载地址
  - [perfectSketchbook_sketchyanimestyle.safetensors](https://civitai.com/api/download/models/34584)
  - [perfectSketchbook_sketchyanimestyle.safetensors](https://civitai.com/api/download/models/34584?type=Pruned%20Model&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f8b4a15c-e079-4541-6236-82a495e4a100/width=450/395029.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a140b8ec-7d8c-4b7d-f5e1-7753f8513900/width=450/395028.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/87411105-1b56-45b8-dc42-746baa346900/width=450/395027.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6a7f40b8-3803-4127-c06b-54de3eaf1000/width=450/395026.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] SketchyStyle

- 统计数据
  - 发布时间：2023-06-12T03:09:52.269Z
  - 原始模型：Other
  - 下载数：1019
  - 评分人数：4
  - 评分：5
- 下载地址
  - [perfectSketchbook_sketchystyle.safetensors](https://civitai.com/api/download/models/33519?type=Model&format=Other&size=pruned&fp=fp16)
  - [perfectSketchbook_sketchystyle.safetensors](https://civitai.com/api/download/models/33519)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c9499c5e-e9b2-4d73-e1ec-263c6fba2700/width=450/382191.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6495065f-7357-455f-21eb-d20ad324e200/width=450/382199.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7393ff0f-6617-49af-6460-82986fd55a00/width=450/382198.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8538ca88-43ea-4f28-9c01-4c20a001d900/width=450/382197.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Made this on complete accident. I think this serves as a practical exercise in what applying a huge amount of lineart style LoRAs to a model until it's almost ruined and then replacing unet blocks IN06, IN07, IN08, OUT05, OUT4, and OUT3 with that of realistic model does.</p><p>This model creates a sort of sketchbook like effect to the model. You've got the bones of a semi-realistic model as far as anatomy goes but it looks like someone drew it in with pencil. I call it Perfect Sketch, because basically you can throw any prompt you'd use on Perfect World in here and it'll work.</p><p>I can do a more detailed explanation of why this works if anyone's interested but if you're only interested in prompting here are the usage recommendations.</p><h3>Usage</h3><p>Ideally you should prompt for realism for best effects. With SketchyAnimeStyle it doesn't really matter, but with SketchStyle it will help a lot. If you don't want to come up with your own prompt, just insert this before your prompt.</p><pre><code>(ultra high detail, realistic, best quality, 8k raw, masterpiece)

BREAK</code></pre><p>As far as negatives go, keep it simple. Once again, if you don't want to come up with your own prompt, I generally like to use this.</p><pre><code>easynegative, (worst quality, low quality:1.4), (monochrome:1.1), watermark</code></pre><p>Don't use latent upscaler and if you upscale at 2 or below keep the denoise at 0.4 or below.</p><p>With SketchyStyle you should use a upscaler otherwise the facial details will not resolve. With SketchyAnimeStyle it doesn't really matter that much though obviously upscaling is better.</p><h3>Process</h3><p><a target="_blank" rel="ugc" href="https://huggingface.co/Jemnite/SketchbookStyle">Huggingface</a></p><p>Generally speaking, anything between OU03toOUT5/IN8toIN6 is responsible for segmenting the face and body. I was trying to correct anatomy breakdown after fucking up the weights with loras so I replaced the parts of the unet responsible for compressing and uncompressing the body features with those of the functioning model I started with. This enforces the anatomy of that model into this one to some degree while leaving the fine details intact. I think this could be used as a generalized approach, where you can apply loras to change style and then revert certain blocks to restore anatomy or aesthetic composition. However, this technique is largely experimental and needs more research.</p>