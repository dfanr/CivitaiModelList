## WLOP Style LoRA
### 一、模型概述

- 标签：`anime`, `girl`, `portaits`, `sexy`, `female`, `digital art`, `character art`, `highly detailed`, `wlop`, `style`, `art style`, `woman`, `artist`, `artstyle`, `digital illustration`, `fantasy`, `girls`, `portraits`
- 下载数：17723
- 收藏人数：3342
- 评论人数：28
- 评分人数：23
- 评分：4.96

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] offset

- 统计数据
  - 发布时间：2023-05-12T09:00:22.717Z
  - 原始模型：SD 1.5
  - 下载数：3606
  - 评分人数：6
  - 评分：5
- 下载地址
  - [wlop_offset.safetensors](https://civitai.com/api/download/models/68639)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f9ae154c-8b8c-4f62-b8b1-0f957f8a4d45/width=450/765072.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f88dec2f-2597-4875-af7c-e7be1c043813/width=450/765083.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b1037a57-e426-4f90-bae0-b76d990c6dbb/width=450/765073.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f9d4d978-b032-4ad2-a804-701968ea1342/width=450/765170.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1

- 统计数据
  - 发布时间：2023-05-12T08:44:49.642Z
  - 原始模型：SD 1.5
  - 下载数：14117
  - 评分人数：17
  - 评分：4.94
- 下载地址
  - [wlop-000030.safetensors](https://civitai.com/api/download/models/5835)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b1e40d0f-2aa2-4b42-ae1f-ee75f0e42c00/width=450/48752.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/950bed00-cba8-4c0a-736a-39c2f3c75600/width=450/48756.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ce545948-70db-4f54-e5c5-48ecad089d00/width=450/48778.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/79d6ba86-4869-4f65-06af-3ae009453c00/width=450/48755.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2>WLOP style LoRA</h2><p><strong>Making models can be expensive. Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong></p><p><br />There is already a <a target="_blank" rel="ugc" href="https://civitai.com/models/2968/wlop">model checkpoint for wlop</a> that you should definitely check out. However LoRA's are becoming the new way to basically mix models on the go and add artstyle and characters also combining multiple ones with many different pre-existing models. Wlop style is already used a lot in prompts, especially on Midjourney, so I made this. <br /><br />For the preview pics I used AnyLoRA and Abyss Orange Mix V2 and a <strong>weight of 1 for the offset version (0.6 for the old one)</strong>. Trigger word is of course <code>wlop</code>. Works well with <a target="_blank" rel="ugc" href="https://civitai.com/models/4384/dreamshaper">DreamShaper</a> too but you won't get the perfect style on it (it's trained on anime models). I also used CLIP skip 2. <br /><br /><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight</strong> (by default it's <code>:1</code> which is usually too high)</p></li></ul>