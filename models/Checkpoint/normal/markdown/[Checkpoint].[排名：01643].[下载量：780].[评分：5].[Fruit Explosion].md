## Fruit Explosion
### 一、模型概述

- 标签：`anime`, `scifi`, `modern`, `style`, `fantasy`, `semirealistic`
- 下载数：780
- 收藏人数：239
- 评论人数：2
- 评分人数：6
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Fruit Explosion v1.0

- 统计数据
  - 发布时间：2023-06-08T22:50:28.040Z
  - 原始模型：SD 1.5
  - 下载数：780
  - 评分人数：6
  - 评分：5
- 下载地址
  - [fruitExplosion_fruitExplosionV10.safetensors](https://civitai.com/api/download/models/85474)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c7aa1224-280d-479e-b341-3c32d06ae11e/width=450/1077620.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/af8698c0-a566-4218-b5d8-22c79480e0a4/width=450/1077641.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7e79c60b-cf97-46b9-ab70-bdd01051f3bc/width=450/1077647.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f8448dcd-a199-4744-8885-2bd29343c765/width=450/1077664.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is intended for generating detailed anime style images in wide, tall, or square images. It has been tested with the following ratios: 16:9, 9:16, 3:2, 2:3, 4:3, 3:4</p><p>Note that things can get weird when the initial resolution is fairly high without using high res fix. Since that adds a significant amount of time for those I typically start with a max of 768 along one side, though that can get wonky sometimes due to how Stable Diffusion works.</p><p>For example, I like my 2:3 images to be 512x768. After doing whatever initial inpainting I find necessary, I use <a target="_blank" rel="ugc" href="https://github.com/Coyote-A/ultimate-upscale-for-automatic1111">Ultimate SD Upscaler</a> to increase resolution. It may take some testing with the denoising strength, etc.</p><p>Experiment with upscalers to see which gives a better result for the project in particular.</p><p>Upscalers I like:</p><p><a target="_blank" rel="ugc" href="https://drive.google.com/file/d/1lELx_WiA25_S8rYINm_DyMNpFOhfZAzt/view">Foolhardy Remacri</a></p><p><a target="_blank" rel="ugc" href="https://icedrive.net/s/43GNBihZyi">NMKD Siax 200k</a></p><p><a target="_blank" rel="ugc" href="https://icedrive.net/s/43GNBihZyi">NMKD Superscale SP 178000 G</a></p><p><a target="_blank" rel="ugc" href="https://upscale.wiki/wiki/Model_Database">UltraSharp</a></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/hollowstrawberry/upscalers-backup/blob/main/ESRGAN/lollypop.pth">lollypop</a></p><p><a rel="ugc" href="https://huggingface.co/utnah/esrgan/blob/main/4x-UltraMix_Restore.pth">4x-UltraMix Restore</a></p><p>Please do not hesitate to ask questions. I am by no means an expert, but I will try to help if I can.</p><p>Note that the images above were upscaled in img2img a couple times using Ultimate SD Upscaler (see link above) using ControlNet tiling. I do tweak the prompts depending on the image, but as a general test the first img2img upscale removes the negative prompt without changing the positive prompt and upscales x2 with denoise strength around 0.2-0.4. After tweaking it from there, that image is upscaled again x2 with no prompts at all at about 0.05-0.1 denoise strength using ControlNet tiling once again.</p><p>ALSO note that some images do not have the sampler listed since they used DPM++ 2M SDE Karras and that is not on the list at civitai yet.</p>