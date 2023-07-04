## Muppet
### 一、模型概述

- 标签：`character`, `muppets`
- 下载数：364
- 收藏人数：24
- 评论人数：0
- 评分人数：2
- 评分：4

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] 1.0

- 统计数据
  - 发布时间：2022-12-16T02:09:26.155Z
  - 原始模型：SD 1.5
  - 下载数：364
  - 评分人数：2
  - 评分：4
- 下载地址
  - [muppet_10.pt](https://civitai.com/api/download/models/1495)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2e0a5fb1-faa3-40b2-c495-02a463a1e300/width=450/13086.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/235b3f8d-37af-4332-915c-5c9b2f217000/width=450/13085.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/26f59542-4737-4ebe-2609-8ea6cd59e700/width=450/13091.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b2dfffb4-a8c8-408b-39f8-13287989d300/width=450/13090.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><br /></p><p>https://huggingface.co/doctorderp/muppet/tree/main</p><p>IMPORTANT INSTRUCTIONS!!!</p><p>This model was trained on SD base 1.5 version BUT It does also work for 1.4 as they both share the same Clip encoder.</p><p>Install instructions.</p><p>Simply place the muppet.pt file inside the \stable-diffusion-webui\models\hypernetworks folder. Load the model inside the Automatic1111 interface under settings hypernetwork.</p><p>Use instructions.</p><p>Make sure and use 0.7 hypernetwork strength for best results. Using strength of 1.0 will lead to background distortion.</p><p>Use DPM++ SDE Karras sampler with 15 steps and CFG of 7.0.</p><p>Make sure and always include the word muppet somewhere in the prompt. For people always preface the subject with muppet, example "muppet man walking", "muppet girl playing in the backyard", etc... For animals put the word muppet at the end of the prompt, example "a cow in a green field muppet". With longer prompts you will want to put the word muppet closer to the beginning of the prompt for better effect. Sometimes putting the word muppet smack dab in the middle of the prompt is best, play around with it for optimal effect for your prompt.</p><p>VERY IMPORTANT! Always describe the background in some detail or you WILL get artifacts when generating an image that has no info on the background. So for example DON'T just say "an old muppet man". DO say "an old muppet man inside a rustic hut".</p><p>Some fun info. People have been sleeping on hypernetworks and I plan to change that. Hopefully the flexibility of this hypernetwok will show everyone their true potential. Because this model is a hypernetwork it can be used in conjunction with ANY model based on the 1.4 CLIP architecture. That means this model will work on any custom 1.4 or 1.5 model, like the modern disney model, or classic disney, etc… for example, let's say you want to load classic disney as base. Well simply load the classic disney model, make sure and preface every prompt with classic disney. As per instructions of the model. Then follow up with my “muppet” tag as instructed once you have loaded the hypernetwork. So the prompt should look something like this “classic disney. muppet girl playing in the backyard.” Make sure and adjust the hypernetwork strength to .5 for a more cartoon look or .7 for a realistic muppet look. Also you can muppify your own face! Simply prompt muppet in image to image at .6-.7 denoise strength and watch out, HAHA! Have fun folks!</p>