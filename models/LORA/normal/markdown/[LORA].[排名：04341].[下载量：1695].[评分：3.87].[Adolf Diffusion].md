## Adolf Diffusion
### 一、模型概述

- 标签：`character`, `photorealistic`, `political`, `man`, `realistic`, `real person`
- 下载数：1695
- 收藏人数：313
- 评论人数：74
- 评分人数：23
- 评分：3.87

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Adolf-Diffusion

- 统计数据
  - 发布时间：2023-03-20T15:52:35.260Z
  - 原始模型：SD 1.5
  - 下载数：1695
  - 评分人数：23
  - 评分：3.87
- 下载地址
  - [Adolf-Diffusion.safetensors](https://civitai.com/api/download/models/26263)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/78eb538b-accb-40de-b39f-aa9b48bd4000/width=450/288990.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c99720bf-c8a3-42b9-18db-b6ca4a5e5f00/width=450/288993.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e9248c5b-63bf-47f1-1af5-d9c5870c2600/width=450/288992.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/de599ee4-73d1-4fbe-094a-e04b53264a00/width=450/288991.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>Adolf Diffusion</strong></p><p><u>IMPORTANT NOTES:</u></p><p>&gt;This model is NOT meant to share or glorify any political view.</p><p>&gt;Trigger word: "AdolfHitler". Recommended weight: 0.7 and higher</p><p>&gt;Trained on b&amp;w pictures, in order to get good results appropriate prompting and model is required.</p><p>&gt;The best results achieved with realistic models (<a target="_blank" rel="ugc" href="https://civitai.com/models/4201/realistic-vision-v13-fantasyai">Realistic Vision</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/4823/deliberate">Deliberate</a>).</p><p>&gt;Probably the easiest way is to just use inpaint.</p><p><strong>Prompting</strong></p><p>&gt;<u>To get images in color use these:</u></p><ul><li><p>Positive: in color</p></li><li><p>Negative: monochrome, black and white, b&amp;w, greyscale</p></li></ul><p>&gt;To get rid of blurry background:</p><ul><li><p>Negative: simple background, blurry background</p></li></ul><p>&gt;Trained mostly on upper body pictures, might be hard to get full body.</p><p>&gt;If you have problems with getting Adolf's mustache, try setting the LoRa weight higher (or first generate image with low weight and then inpaint face with high weight).</p><p>&gt;Eyes might sometimes be a problem, try experimenting with these:</p><ul><li><p>Positive: looking at viewer, detailed eyes etc.</p></li></ul><p><strong>How to make similar model</strong></p><p>I know this model is far from being great, but if someone wants to know the workflow, here you go:</p><p>1. Find good image and crop it (in my case 44 images). 2. Upscale it x2~x4 (in my case mostly R-ESRGAN). 3. Remove noise using any graphic software. 4. Scale down 5. Train LoRa (using Google Colab).</p><p>Also:</p><p>&gt;Some of example images were created using ControlNet and img2img</p><p>&gt;If you want to use my model anywhere feel free to do so, but it would be nice to put me in credits.</p><p>&gt;For any questions you can contact me rafikxd123#7133</p><p> </p>