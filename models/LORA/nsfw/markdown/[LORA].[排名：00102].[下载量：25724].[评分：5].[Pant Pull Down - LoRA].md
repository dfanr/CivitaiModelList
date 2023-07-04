## Pant Pull Down - LoRA
### 一、模型概述

- 标签：`photorealistic`, `panties`, `booty`, `woman`
- 下载数：25724
- 收藏人数：4366
- 评论人数：6
- 评分人数：18
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] pantpulldown v1

- 统计数据
  - 发布时间：2023-02-20T17:01:26.487Z
  - 原始模型：SD 1.5
  - 下载数：25724
  - 评分人数：18
  - 评分：5
- 下载地址
  - [pantpulldown.safetensors](https://civitai.com/api/download/models/13184)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8184f9be-450c-46ee-841e-dc696d7d6700/width=450/127424.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3afe8b67-3077-4333-1c00-631a93203700/width=450/127433.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a3f86d27-fc2f-4ce7-6ab7-331b35c12100/width=450/127432.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/97b03189-726d-4c9b-2c15-419742751000/width=450/127431.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>Important</strong>: Having multiple models uploaded here on civitai has made it difficult for me to respond to each and every comment. One of the ways I plan on addressing this is via the creation of a pdf guide for each and every model (think of it as the models documentation). This will take a while though. So in the meantime, if you have any questions or feedback -</p><p><a target="_blank" rel="ugc" href="https://discord.com/channels/1010980909568245801/1073440375336882186"><strong>visit my thread of the Unstable Diffusion Discord</strong></a></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8adf0eaf-79a9-45f1-cf0b-ef122b125000/width=525/8adf0eaf-79a9-45f1-cf0b-ef122b125000.jpeg" /><p></p><p>Similar to shirtlift <em>butt</em> for booty lovers.</p><p></p><p>Admittedly, this was just made for fun. It's not as versatile as shirtlift, as trying find good data was quite difficult. In the end, the model was trained on roughly 100 pictures. Manual tagging + BLIP were used for captions.</p><p></p><p><strong>General Prompt Guide</strong></p><ul><li><p>Simply add <code>pantpulldown</code> towards the end of your prompt, followed by <code>&lt;lora:pantpulldown:1&gt;</code></p></li><li><p>Add "rear view" angles towards the beginning of the prompt: <code>rear angle</code>, <code>from behind</code>, <code>viewed from behind</code>, <code>back towards viewer</code>, ect..</p></li><li><p>Noting the butt size somewhere in the prompt can also help: <code>big butt</code> seems to work well, but can sometimes force closeup shots.</p></li><li><p>Adding <code>full body</code> towards the beginning is useful for full body shots. (note, this may be different depending on what SD model you use).</p></li><li><p><strong>For short length prompts</strong> setting the weight between <code>0.5</code> and <code>0.8</code> seems be optimal: <code>&lt;lora:pantpulldown:0.6&gt;</code></p></li><li><p>Conversely, <strong>For longer length prompts</strong> setting the weight to <code>0.8</code> and <code>1</code> seems to optimal: <code>&lt;lora:pantpulldown:1&gt;</code></p></li><li><p>Describing whether or not genitals are exposed can help elevate issues where genitals are not generated properly, or are visible when you prefer they not be.</p></li><li><p>Interestingly, I've had the best results by adding the LoRA at the end of full length prompts; as show in most of the sample images.</p></li></ul><p></p><p><strong>Issues</strong></p><ul><li><p>Bad faces</p><ul><li><p>Try adding "pretty face" to your positive prompt.</p></li></ul></li><li><p>Bad hands</p><ul><li><p>Hands are the devil for Diffusion models; try adding "perfect hands" to your positive prompt, and "mutated hands, distorted hands", ect.. to your negative prompt.</p></li></ul></li><li><p>Bare bottom with no pants</p><ul><li><p>Increase the LoRA weight in your prompt.</p></li></ul></li></ul><p></p><p>Realistically, A hypernetwork + still frames of people undressing their pants would likely be ideal. This is something I'll consider after I finish training my upcoming "Enhanced skin texture" hypernetwork.</p><p></p>