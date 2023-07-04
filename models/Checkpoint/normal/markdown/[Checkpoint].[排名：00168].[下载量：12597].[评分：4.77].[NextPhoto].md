## NextPhoto
### 一、模型概述

- 标签：`photorealistic`, `photo`, `style`, `easy`
- 下载数：12597
- 收藏人数：1451
- 评论人数：41
- 评分人数：62
- 评分：4.77

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2.0

- 统计数据
  - 发布时间：2023-06-21T03:23:52.193Z
  - 原始模型：SD 1.5
  - 下载数：6625
  - 评分人数：19
  - 评分：4.58
- 下载地址
  - [nextphoto_v20.safetensors](https://civitai.com/api/download/models/100637)
  - [nextphoto_v20.safetensors](https://civitai.com/api/download/models/100637?type=Model&format=SafeTensor&size=full&fp=fp16)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8d72c38a-1938-4a84-b7a2-88908d560283/width=450/1227084.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/788d28f9-52b8-46b3-ace2-fcf89a610b6e/width=450/1227087.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3d61a8a0-c9dd-4fb5-b9f4-fbfd8a38e5a7/width=450/1227090.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7190cf9c-3c04-41f1-b6fa-27f58ce66e7e/width=450/1227091.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-06-21T02:24:12.818Z
  - 原始模型：SD 1.5
  - 下载数：5972
  - 评分人数：43
  - 评分：4.86
- 下载地址
  - [nextphoto_v10.safetensors](https://civitai.com/api/download/models/89650)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5a7980b5-b90a-4aee-81e0-41ac6daec495/width=450/1037499.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d79054df-ce61-40a6-af9a-f3b80d975681/width=450/1037507.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1e8a02a4-2f22-486e-821f-4ca160ad6b0a/width=450/1037517.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a87709a0-d7e1-43c6-baba-71293327bb88/width=450/1050975.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>NOTE:</strong> For the best detail, use the Euler A sampler with hires fix enabled, using the ESRGAN_4X upscaler at 0.3 to 0.5 denoising. Other samplers can result in oversharpening, bluriness, or image artifacts - Euler A strikes the best balance and is consistent.</p><p></p><p>After tinkering with some block merging, I accidentally stumbled into an extremely realistic model. This model is remarkably easy to prompt, and generates very photorealistic images. The model works great for outdoors, landscapes, urban, indoors, you name it.</p><p>In version 2, I trained version 1 against a curated set of high resolution images to improve details. View the "about this version" on v2.0 for more details.</p><h2 id="heading-3155">Usage Guide</h2><ul><li><p><strong>(highly recommended) </strong>The negative prompt is quite important for the photorealism, but you don't really have to change it ever to get great results.<strong> </strong>I'd recommend the following negative prompt as a base: <em>(worst quality:0.8), cartoon, halftone print, (cinematic:1.2), verybadimagenegative_v1.3, easynegative, (surreal:0.8), (modernism:0.8), (art deco:0.8), (art nouveau:0.8)</em></p><ul><li><p>This prompt uses the verybadimagenegative_v1.3 and easynegative textual embeddings. You'll need</p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/11772/verybadimagenegative">https://civitai.com/models/11772/verybadimagenegative</a></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative">https://civitai.com/models/7808/easynegative</a></p></li></ul></li><li><p>Place the downloaded files into the "embeddings" folder of the SD WebUI root directory, then restart stable diffusion.</p></li><li><p><strong>(IMPORTANT) </strong>For v2, you should decrease the weights of the negative prompt. I would recommend <em>(verybadimagenegative_v1.3, easynegative:0.5)</em></p></li></ul></li><li><p><strong>Positive Prompts: </strong>You don't need to think about the positive a whole ton - the model works quite well with simple positive prompts.</p><ul><li><p>Examples:</p><ul><li><p>A medium photo of woman at the train station</p></li><li><p>A perfect photo of an old married couple sitting on their porch</p></li><li><p>A poorly lit photo of a man walking on the trail at night</p></li></ul></li><li><p><strong>(highly recommended)</strong> Starting your positive prompt with the phrase "A poorly lit photo of ..." will tend to yield very realistic results. Take note though, this can smooth out details in some cases. If you notice your generations look like they were taken by a low quality camera then you would want to remove it from the prompt and just stick with "A photo of..."</p></li><li><p>For more examples of positive prompts you can look at the sample photos for the model.</p></li></ul></li><li><p><strong>Upscaling: </strong>This model works will still generate photorealistic images without upcaling, but upscaling can add a lot of detail. You'll need to use the ESRGAN upscaling model (not R-ESRGAN) in the hires fix section for decent results. Set the weight anywhere from 0.3 to 0.5 for best results, and the upscale amount to 2. I normally set my weight to 0.5 or 0.45.</p></li><li><p><strong>Sampler: </strong>Most samplers work fine with this model. I personally use Euler A or DPM++ 2M Karas, though Euler A works best for v2. There isn't really a notable difference in quality between different samplers (except for the bad ones - you'll know it when you see it).</p></li><li><p>If you notice that your images are suffering from the "studio photoshoot" over-dramatized look, you can do the following:</p><ul><li><p><strong>Reduce your CFG scale:</strong> The default <span style="color:rgb(0, 0, 0)">classifier free guidance scale</span> scale of 7 works good, but occasionally this can be too high. Reduce the CFG scale until you like the results - I generally bottom out at 4.5, as anything lower than that and the negative prompt starts getting ignored. If you have the dynamic thresholding plugin for the webui (<a target="_blank" rel="ugc" href="https://github.com/mcmonkeyprojects/sd-dynamic-thresholding">https://github.com/mcmonkeyprojects/sd-dynamic-thresholding</a>), then you can enable it and set the mimic scale to 4.5</p></li><li><p><strong>Include the words "poorly lit photo" and "natural lighting" in the positive prompt: </strong>This can help to avoid the photoshoot look, and will yield decent results. Do note that it'll probably generate a window as well when you use "natural lighting".</p></li><li><p><strong>Zoom out your shot a bit:</strong> Extreme closeups tend to be harsher lit than medium shots or full body shots. You can zoom out a bit by prompting "medium photo" instead of just photo, so a prompt like "a perfect photo of a woman at the train station" might become "a perfect medium photo of a woman at the train station".</p></li></ul><p></p></li></ul>