## Aerial
### 一、模型概述

- 标签：`anime`, `character`, `sexy`, `illustration`, `fantasy`, `girls`
- 下载数：326
- 收藏人数：94
- 评论人数：0
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Aerial_v0

- 统计数据
  - 发布时间：2023-06-15T15:51:56.196Z
  - 原始模型：SD 1.5
  - 下载数：326
  - 评分人数：2
  - 评分：5
- 下载地址
  - [aerial_V0.safetensors](https://civitai.com/api/download/models/96495)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/505ca494-af99-49ca-93c2-f6caf21fb7aa/width=450/1155652.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b7d1bd43-eb9c-4348-993f-fc05303b177d/width=450/1155054.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0be4dea4-356d-42b3-90c3-b16d62a19139/width=450/1152524.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/03fc0842-7658-4e1d-adc0-d3c613349002/width=450/1152105.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-9766"><span style="color:rgb(209, 213, 219)">Aerial is a model that focuses on anime and the cool 2.5D style</span></h1><p><span style="color:rgb(193, 194, 197)">--------------------------------------------------------------------------------</span></p><h3 id="heading-9767"><span style="color:rgb(121, 80, 242)">SD needs enough "space" to create a wonderful image！</span></h3><h3 id="heading-9768"><span style="color:rgb(209, 213, 219)">so you need use highres-fix to fix the broken and get more and more details.</span></h3><p><span style="color:rgb(193, 194, 197)">--------------------------------------------------------------------------------</span></p><h3 id="heading-9769"><span style="color:rgb(209, 213, 219)">Recommend Setting:</span></h3><p>Sampler<span style="color:rgb(209, 213, 219)">:DPM ++ 2M Karras,DPM ++ SDE Karras,DDIM</span></p><p><span style="color:rgb(209, 213, 219)">Base Resolution:512*512,512*768,768*512(Don't go beyond this size unless you want to end up with messed-up bodies or some crazy stuff :). )</span></p><p><span style="color:rgb(209, 213, 219)">Step:20-30</span></p><p><span style="color:rgb(209, 213, 219)">CFG Scale:5-8</span></p><p><span style="color:rgb(209, 213, 219)">Highres-fix:Like I said, if you want better results, you need to give it more 'breathing room.' A 1.5x scale will do the trick for portraits, but for other images, you'll want to go with 2x or higher!</span></p><p><span style="color:rgb(209, 213, 219)">Upscale and denoise:</span><span style="color:rgb(209, 210, 211)">Use lantent with a denoise strengh of 0.5 to get more details. Use R-ESRGAN  with a denoise strength of 0.35-0.5 for a 2.5D style. For an anime style, use R-ESRGAN Anime6B with a denoise strength of 0.35-0.5.</span></p><p><span style="color:rgb(209, 213, 219)">Tips:I found DPM ++ 2M Karras and lantent </span><span style="color:rgb(209, 210, 211)">don't work well together :(</span></p><p></p><p></p><h3 id="heading-9770"><span style="color:rgb(209, 213, 219)">My Workflow:</span></h3><p><span style="color:rgb(209, 213, 219)">Step-1:Get a base image of 512*768,and take a look at the composition and elements to make sure everything is on point.</span></p><p><span style="color:rgb(209, 213, 219)">Step-2:When you're ready,click this pretty botton to reuse the seed from your last generation.</span></p><p><span style="color:rgb(209, 213, 219)"><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/10f8d8a5-faa5-4ffb-8c40-87ba59712635/width=525/10f8d8a5-faa5-4ffb-8c40-87ba59712635.jpeg" /></span></p><p>Step-3:<span style="color:rgb(209, 210, 211)">Open the highres-fix and generate images by 1.5-2x upscaling.</span></p><p><span style="color:rgb(209, 213, 219)">Step-4:</span><span style="color:rgb(209, 210, 211)">Send the image to both the image-to-image and the ControlNet model.</span></p><p><span style="color:rgb(209, 213, 219)">Step-5:</span><span style="color:rgb(209, 210, 211)">Set a much higher resolution and open the ControlNet-tile model, then you will get a much better image!  </span></p><p></p><p><span style="color:rgb(209, 210, 211)">My GPU is very slow so it is very difficult to generate a high resolution image (it takes 30 minutes for 1080P), so this model has not been tested extensively. I hope you can post the images you generated to let me know the limit of this model! If you like this model, please give me a 5-star preview.</span></p><p><span style="color:rgb(209, 210, 211)">Thanks and enjoy!</span></p>