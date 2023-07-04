## Reflections on water
### 一、模型概述

- 标签：`photorealistic`, `nature`, `photo`, `style`, `photorealism`, `photoshoot`, `landscape`
- 下载数：785
- 收藏人数：199
- 评论人数：2
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-17T17:53:02.097Z
  - 原始模型：SD 1.5
  - 下载数：785
  - 评分人数：2
  - 评分：5
- 下载地址
  - [Reflections.safetensors](https://civitai.com/api/download/models/48310)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6024036b-a588-4fca-15ac-9b7bcd2f0700/width=450/518895.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cc2aebbb-c362-4ad7-1975-f0257f662b00/width=450/518873.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/048e921a-19c5-4917-df3f-aff4cc5b7900/width=450/518880.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ba6d1050-1041-43b0-ad52-88b3613d3700/width=450/518883.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This model was finetuned on top of <a target="_blank" rel="ugc" href="https://huggingface.co/SG161222/Realistic_Vision_V2.0"><u>Realistic Vision 2.0</u></a> to depict light reflecting on water. <br /></p><p>After seeing how lighting and water could work together in a <a target="_blank" rel="ugc" href="https://civitai.com/models/35940/underwater-photo-lora-tropical-edition"><u>previous model</u></a>, was inspired to do a version above water. Water can be difficult to depict because ripples and waves on the surface change the way light reflects, and capturing this effect can be important for realism. Though the base models can show this to some degree, after experimentation I thought this could be improved.<br /></p><p>Around 20 HD images were used for training, selected for high resolution, as well as a variety of lighting conditions (daytime, night, dawn/sunset) and water conditions (still vs. moving water). Used a relatively higher learning rate (5e-3), and a very high contrast noise (0.30) to improve the contrast especially for night scenes. LoRA is 128 / 64 (dim / alpha).</p><p></p><p>Notably also tried to experiment with the reflections of different things (e.g. people, animals, buildings, nature). Unfortunately people and animals are quite difficult - the real instances are hard to get right, without even considering their reflections. It’s possible that the amount of detail necessary in depicting water somehow affects their realism, more experimentation may tell.<br /></p><p>Join our <a target="_blank" rel="ugc" href="https://discord.gg/BuEEtKnfUK"><u>Discord</u></a><a target="_blank" rel="ugc" href="https://discord.gg/ubpkxuzt"> </a>for any questions or feedback!<br /></p><p><strong>Prompting</strong></p><p>Use “reflections” to trigger the LoRA. Append the recommended positive prompt terms from Realistic Vision. Have not tried the suggested negative prompts, but do make sure to modify them appropriately if not depicting human subjects.</p><p></p><p>The basic prompt pattern is “reflection of [object] on [body of water]”. You can add a clause to control lighting conditions (e.g. “bright lighting”) or time of day (e.g. “at dusk”) at the end. </p><p></p><p>Example prompts:</p><ul><li><p>Reflections of cliffs over an ocean, at dawn, 8k uhd, dslr, soft lighting, high quality, film grain, Fujifilm XT3 </p></li><li><p>Reflections of an iceberg, 8k uhd, dslr, soft lighting, high quality, film grain, Fujifilm XT3  &lt;lora-Reflections-0.8&gt; 2</p></li><li><p>Blurry reflection of bridge on water, medium lighting, 8k uhd, dslr, soft lighting, high quality, film grain, Fujifilm XT3 &lt;lora-Reflections-000400-0.8&gt;<br /></p></li></ul><p>Recommend using LoRA at around 0.8. <br /></p><p><strong>Settings</strong></p><p>Resolution <strong><u>must be 768 x 768</u></strong> for best results.</p><p>Sampler = DPM++ 2M Karras</p><p>Sample images were using CFG = 7 and 25-50 inference steps. </p>