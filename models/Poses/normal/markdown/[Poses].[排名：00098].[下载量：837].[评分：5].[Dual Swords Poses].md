## Dual Swords Poses
### 一、模型概述

- 标签：`photorealistic`, `sexy`, `poses`, `controlnet`, `realistic`, `pose`
- 下载数：837
- 收藏人数：170
- 评论人数：0
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-22T15:44:25.239Z
  - 原始模型：SD 1.5
  - 下载数：837
  - 评分人数：2
  - 评分：5
- 下载地址
  - [dualSwordsPoses_v10.zip](https://civitai.com/api/download/models/77961)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/12cc3312-4a8e-4d58-a2f7-8e7ecee05673/width=450/874159.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fbdd4244-573f-466a-85ba-04b0220dcd3f/width=450/874158.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2b90f412-398f-491a-a1dc-ed376a1008b8/width=450/874161.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3c1a2041-e4a2-467b-bab3-27892de1c86d/width=450/874160.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Get early access to build and test build, be able to try all epochs and test them by yourself on <a target="_blank" rel="ugc" href="https://www.patreon.com/betterCuteAsians"><strong>Patreon </strong></a>or contact me for support on Discord</p><p></p><p><strong>Install Instructions:</strong></p><p></p><p>open stable diffusion -&gt; extensions -&gt; install from URL -&gt; <a target="_blank" rel="ugc" href="https://github.com/Mikubill/sd-webui-controlnet.git">https://github.com/Mikubill/sd-webui-controlnet.git</a></p><p>click Apply and restart UI</p><p>Then download from <a target="_blank" rel="ugc" href="https://huggingface.co/webui/ControlNet-modules-safetensors/tree/main">https://huggingface.co/webui/ControlNet-modules-safetensors/tree/main</a> the file <a target="_blank" rel="ugc" href="https://huggingface.co/webui/ControlNet-modules-safetensors/blob/main/control_openpose-fp16.safetensors">control_depth-fp16.safetensor</a></p><p>place it inside extensions/sd-webui-controlnet/models</p><p></p><p>After all of this, you will have a ControlNet v1.1.112 just above Script in txt2image tab</p><p>Open it, place the pose (black and white image, not the example one) you want to replicate by selecting it from your computer and place it in the image selection square box. You can also drag and drop.</p><p>Select preprocessor NONE, check Enable Checkbox, select control_depth-fp16 in Model list, check Controlnet is more important in Control Mode (or leave balanced).</p><p></p><p>Then generate your image, don't forget to write a proper prompt for the image and to preserve the proportions of the controlnet image (you can just check proportions in the example images for example).</p><p>I uploaded the pose images and 1 example generated image with that pose using the same prompt for all of them. But you can modify the prompt to fit what you want.</p><p></p><p>Enjoy!<br /><br /><strong><u>If you'd like to support my efforts and have access to early and bleeding edge builds</u></strong>, please think about joining my Patreon: <a target="_blank" rel="ugc" href="https://www.patreon.com/betterCuteAsians"><strong>https://www.patreon.com/betterCuteAsians</strong></a></p>