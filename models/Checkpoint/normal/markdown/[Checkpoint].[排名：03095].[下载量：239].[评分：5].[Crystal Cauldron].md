## Crystal Cauldron
### 一、模型概述

- 标签：`3d`, `horror`, `base model`, `sci-fi`, `fantasy`, `general`
- 下载数：239
- 收藏人数：101
- 评论人数：1
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-22T20:41:04.040Z
  - 原始模型：SD 1.5
  - 下载数：239
  - 评分人数：1
  - 评分：5
- 下载地址
  - [crystalCauldron_v10.safetensors](https://civitai.com/api/download/models/101783)
  - [crystalCauldron_v10.safetensors](https://civitai.com/api/download/models/101783?type=Model&format=SafeTensor&size=full&fp=fp16)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6377f030-d6a5-4e42-a853-e64260faffc8/width=450/1248306.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e822e1d5-3fb0-491c-8114-e26fe1500dbd/width=450/1248353.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c1b405bb-fd0e-42f0-b755-78dc907f7ecd/width=450/1248355.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/09718d97-d693-411e-a9f8-75ede809fdeb/width=450/1248365.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>I'm uploading this at the request of user 'oofy' who liked some of the images I shared from it.</p><p>This is just an experimental merge, not really a highly polished mix, so if you want consistency try something else.</p><p>That being said, I think it can produce some very detailed and dramatic looking images with high contrast and vivid colors. It seems to default to a hyper-realistic 3d rendered type of output, but it can be pushed into other styles.</p><p>However, this mix is not without its problems. Known issues include: Producing multi-pane images without asking it to, adding unwanted borders, making horrific 'double faces', and of course... hands. But If you're willing to put up with its quirks, and like the example images, give it a try. </p><p>No refunds.</p><p>NOTE:  For some reason the pruned version has noticably reduced color and contrast, and lacks some of the details. I recommend the full version, but some may prefer the pruned.</p><p>All example images were made without any LoRa, inpainting, controlnet, face restore, further upscaling, etc., and mainly just a stack of negative embeddings which I will link to at the bottom. </p><p>I do highly recommend trying it with various LoRa as they can improve the consistency a lot.</p><p>Most of my testing was done with the following settings, so try these first:</p><p>Sampler: UniPC</p><p>Steps: 20</p><p>CFG: 7</p><p>Size: 512x768</p><p>Hi-res fix: 2x Latent</p><p>Denoising: 0.7</p><p>Clip skip: 1</p><p>VAE: vae-ft-mse-840000-ema</p><p></p><p>The exact merge recipe is unfortunately forgotten, but I can say with some confidence that it at least involved the following models:</p><p>Orusium by rMadart, RunDiffusion FX Photo and 2.5D by RunDiffusion, ICBINP by residentchiefnz, Juggernaut by KandooAI, Dreamshaper by Lykon, Project Cryengine by hotfantasyai, aZovyaPhotoreal by aZovya, zPhyrNoise by Z_phyr, and (possibly) TerrorYamer2 by Yamer</p><p>I also mixed in some % of one of my older merge experiments, which itself was based on previous versions of Dreamshaper and Project Cryengine, Realistic Vision, Eidomode by Jim Poison, and (possibly) HorrorS4w3d0ffBlend and duchaitendarkside, plus several others that I sadly can't remember.</p><p>Thanks to all of them and any I may have forgotten.</p><p></p><p>This model also features <a rel="ugc" href="https://paste.ee/r/d6IoK/0">a unique blend of essential oil fragrance and the latest in water vapor diffusion technology.</a> :)</p><p></p><p>Negative embeddings:</p><p><a rel="ugc" href="https://civitai.com/models/7808?modelVersionId=9208">easynegative</a> </p><p><a rel="ugc" href="https://civitai.com/models/55700/badprompt-negative-embedding">bad_prompt_2</a> </p><p><a rel="ugc" href="https://civitai.com/models/4629?modelVersionId=5637">NG_DeepNegative_V1_75T</a> </p><p><a rel="ugc" href="http://huggingface.co/Cordeliya/animefull-latest/tree/main">bad-image-v2-39000 and bad_quality</a> </p>