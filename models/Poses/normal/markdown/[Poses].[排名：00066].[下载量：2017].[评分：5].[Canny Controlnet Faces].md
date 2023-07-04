## Canny Controlnet Faces
### 一、模型概述

- 标签：`sexy`, `female`, `poses`, `woman`, `girls`
- 下载数：2017
- 收藏人数：306
- 评论人数：2
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-08T16:40:25.371Z
  - 原始模型：SD 1.5
  - 下载数：2017
  - 评分人数：1
  - 评分：5
- 下载地址
  - [cannyControlnetFaces_v10.zip](https://civitai.com/api/download/models/65776)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/66f7301d-410f-4e58-a0a4-5cd29c5ff07b/width=450/729103.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e49da7c7-e4ab-460e-86ae-448fd6676893/width=450/729100.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/583d6a55-c5c5-4953-a468-0ca692adacb8/width=450/729099.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/76a54164-419b-472d-a843-acdd4e8981d8/width=450/729101.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Get early access to build and test build, be able to try all epochs and test them by yourself on <a target="_blank" rel="ugc" href="https://www.patreon.com/betterCuteAsians"><strong>Patreon </strong></a>or contact me for support on Discord</p><p>To support me you can buy me a coffe at <a target="_blank" rel="ugc" href="https://ko-fi.com/antonioriolo">https://ko-fi.com/antonioriolo</a></p><p></p><p>Those are canny controlnet poses, i usually upload openpose controlnet, but this time i wanted to try canny since faces are not saved with openpose and i wanted to do a set of face poses. let me know in the comments what do you think and if you want me to post more canny poses, and about what?</p><p></p><p><strong>Install Instructions:</strong></p><p></p><p>open stable diffusion -&gt; extensions -&gt; install from URL -&gt; <a target="_blank" rel="ugc" href="https://github.com/Mikubill/sd-webui-controlnet.git">https://github.com/Mikubill/sd-webui-controlnet.git</a></p><p>click Apply and restart UI</p><p>Then download from <a target="_blank" rel="ugc" href="https://huggingface.co/webui/ControlNet-modules-safetensors/tree/main">https://huggingface.co/webui/ControlNet-modules-safetensors/tree/main</a> the file control_canny-fp16.safetensor</p><p>place it inside extensions/sd-webui-controlnet/models</p><p></p><p>After all of this, you will have a ControlNet v1.1.112 just above Script in txt2image tab</p><p>Open it, place the pose you want to replicate by selecting it from your computer and place it in the image selection square box. You can also drag and drop.</p><p>Select preprocessor NONE, check Enable Checkbox, select control_canny-fp16 in Model list, check Controlnet is more important in Control Mode.</p><p></p><p>Then generate your image, don't forget to write a proper prompt for the image.</p><p>I uploaded the pose images and 1 example generated image with that pose using the same prompt for all of them and my model betterCuteAsian. But you can modify the prompt to fit what you want.</p><p></p><p>Enjoy!<br /><br /><strong><u>If you'd like to support my efforts and have access to early and bleeding edge builds</u></strong>, please think about joining my Patreon: <a target="_blank" rel="ugc" href="https://www.patreon.com/betterCuteAsians"><strong>https://www.patreon.com/betterCuteAsians</strong></a></p>