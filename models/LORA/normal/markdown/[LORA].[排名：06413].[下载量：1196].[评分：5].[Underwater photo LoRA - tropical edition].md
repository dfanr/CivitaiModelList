## Underwater photo LoRA - tropical edition
### 一、模型概述

- 标签：`photorealistic`, `nature`, `photo`, `photography`, `fish`, `photos`, `animal`
- 下载数：1196
- 收藏人数：250
- 评论人数：1
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-10T19:26:52.554Z
  - 原始模型：SD 1.5
  - 下载数：1196
  - 评分人数：1
  - 评分：5
- 下载地址
  - [underwater-photos.safetensors](https://civitai.com/api/download/models/42122)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f4cd66fa-d6aa-4679-98cb-7d681295b600/width=450/462556.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/99bd96aa-25c5-47d9-43b1-852d01bbc300/width=450/462559.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/98169057-c729-43f9-4e72-6cd77edd3000/width=450/462555.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/83cd559f-0be6-4318-ffcc-72bf09d17300/width=450/462558.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This model was finetuned on top of <a target="_blank" rel="ugc" href="https://huggingface.co/SG161222/Realistic_Vision_V2.0"><u>Realistic Vision 2.0</u></a> to depict underwater photography. Rather than capturing photos from all types of ocean environments (e.g. deep waters with odd looking fish), wanted to focus only on well-lit photos from shallow waters. <br /></p><p>Training images were selected for high resolution, good lighting, and colorful subjects (like fish and coral). Was particularly interested in photos that showed A) light reflecting on the surface of the water, B) light rays coming into the water or C) light reflecting on the ocean floor. <br /></p><p>For training - used a relatively higher learning rate (3e-4), a larger LoRA (128 rank / 64 alpha) and most importantly, high noise offset (0.3) for high contrast and vivid colors. <br /></p><p>Join our <a target="_blank" rel="ugc" href="https://discord.gg/BuEEtKnfUK"><u>Discord</u></a><a target="_blank" rel="ugc" href="https://discord.com/invite/tDsAykmcff"> </a>for any questions or feedback!<br /></p><p><strong>Prompting</strong></p><p>Use “underwater photo” to trigger the style of the trained LoRA. Append the recommended positive prompt terms from Realistic Vision, but skip the recommended negative prompts unless you are depicting human subjects underwater (which I have not tried).</p><p></p><p>Recommend using LoRA at around 0.8. <br /></p><p>Example prompts</p><ul><li><p>Underwater photo of colorful fish and coral &lt;lora-underwater-000390-0.8&gt;, 8k uhd, dslr, soft lighting, high quality, film grain, Fujifilm XT3 2</p></li><li><p>Underwater photo of fish &lt;lora-underwater-000390-0.8&gt;, 8k uhd, dslr, soft lighting, high quality, film grain, Fujifilm XT3<br /></p></li></ul><p>Coral can kind of float sometimes, as the LoRA hasn’t fully learned that coral is supposed to be attached to rocks and stuff. This LoRA also oddly struggles with dolphins. <br /></p><p><strong>Settings</strong></p><p>Resolution <strong><u>must be 768 x 768</u></strong> for best results.</p><p>Sampler = DPM++ SDE Karras</p><p>Sample images were using CFG = 7 and 25 inference steps. </p>