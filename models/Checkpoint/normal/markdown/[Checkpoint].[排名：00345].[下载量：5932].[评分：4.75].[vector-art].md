## vector-art
### 一、模型概述

- 标签：`vector`, `illustration`
- 下载数：5932
- 收藏人数：1160
- 评论人数：55
- 评分人数：16
- 评分：4.75

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] vector-art-beta

- 统计数据
  - 发布时间：2023-02-10T20:34:03.037Z
  - 原始模型：SD 2.1 768
  - 下载数：5532
  - 评分人数：12
  - 评分：4.75
- 下载地址
  - [vectorArt_vectorArtBeta.ckpt](https://civitai.com/api/download/models/5265?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [vectorArt_vectorArtBeta.safetensors](https://civitai.com/api/download/models/5265)
  - [vectorArt_vectorArtBeta.yaml](https://civitai.com/api/download/models/5265?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e67a2171-07b7-4f82-0513-2b2af7170f00/width=450/61832.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d504c861-f698-41e4-10b6-5765090c0700/width=450/61831.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2c68141e-520a-47ae-89f3-192f654b4c00/width=450/43590.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0a2801a4-1ece-441c-372e-d632629c1e00/width=450/61830.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] pulp-vector-beta

- 统计数据
  - 发布时间：2023-02-10T20:34:03.037Z
  - 原始模型：SD 2.1 768
  - 下载数：400
  - 评分人数：4
  - 评分：4.75
- 下载地址
  - [vectorArt_pulpVectorBeta.ckpt](https://civitai.com/api/download/models/5859?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [vectorArt_pulpVectorBeta.safetensors](https://civitai.com/api/download/models/5859)
  - [vectorArt_pulpVectorBeta.yaml](https://civitai.com/api/download/models/5859?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6e5fb7b8-93ec-490a-852a-2c1e760e2a00/width=450/64186.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/76944195-6955-44fb-2f5d-18caeb279700/width=450/49162.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/788a444a-75ae-46a4-95ea-4cfb17a13d00/width=450/49150.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/afdfd8aa-749f-4598-7d80-d8bae839ab00/width=450/49161.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>About model:</strong><br />Style model for Stable Diffusion mimicking "vector style". This model is open source so you can share, merge or use for monetization as you like (that will apply to other versions as well)<br /></p><p><strong>License and support:</strong></p><p>If you like what I am doing and you want to support my current and upcoming projects: here is my <a target="_blank" rel="ugc" href="https://www.buymeacoffee.com/pmejna">coffee jar</a></p><p></p><p>You can use this model as you like. I love open source so have fun with it. :) If you like it I appreciate your support ^^ <br />Cheers!</p><p><br /><strong>Installation:</strong><br />As it is model based on 2.1 to make it work you need to use .yaml file with name of a model (vector-art.yaml). The yaml file is included here as well to download. Simply copy paste to the same folder as selected model file. Usually this is the <code>models/Stable-diffusion</code> one.</p><p></p><p><strong>Versions:</strong></p><p>There are two versions of this model - they both give a bit different output. <code>Pulp</code> one is great for "oldschool poster" stuff and comic book related. The <code>vector-beta</code> vanilla is more focused on mimicing vector style. (tshirt design, vector-style posters and stickers). I am working on tshirt and sticker model now -so this one will get a general update next time to be more vector-focused but giving more versatile results and styles as well.<br /></p><p><strong>Black images issue:</strong></p><p>2.1 models need to have a web-ui config modified - if you are getting <strong>black images </strong>- go to your config file and add to COMMANDLINE_ARGS= <code>--no-half</code> - potentially it could work with <code>--xformers</code> instead (if supported). This line might slow your generations a bit but will not affect negatively your output.</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ef662aec-6a48-4acc-3bca-574a9f3f2e00/width=525" /><p><br /><strong>Other:</strong><br />The model has been trained the way it is not overfitted and same time give you it's strong style.</p><p></p><p>Try-out some prompts below, dont be afraid to use different encoders:<br /><br />Example prompts:</p><p><code>portrait of a very handsome man made of fruit by guiseppe arcimboldo and greg rutkowski, donato giancola, joseph christian leyendecker, wlop, boris vallejo, breathtaking, 8 k resolution, extremely detailed, beautiful, establishing shot, artistic, hyperrealistic, beautiful face, octane render, cinematic lighting, dramatic lighting, masterpiece by vector-art</code></p><p></p><p><code>`e-sport logo illustration of a spectral gorilla-punk in astronaut suit by guiseppe arcimboldo and greg rutkowski, donato giancola, joseph christian leyendecker, wlop, boris vallejo, breathtaking, 8 k resolution, extremely detailed, beautiful, establishing shot, artistic, hyperrealistic, beautiful face, octane render, cinematic lighting, dramatic lighting, masterpiece by vector-art`</code></p><p><br />Negative prompt: <code>low poly, tetric, mosaic, disfigured, kitsch, ugly, oversaturated, grain, low-res, Deformed, blurry, bad anatomy, disfigured, poorly drawn face, mutation, mutated, extra limb, ugly, poorly drawn hands, missing limb, blurry, floating limbs, disconnected limbs, malformed hands, blur, out of focus, long neck, long body, ugly, disgusting, poorly drawn, mutilated, mangled, old, surreal, pixel-art, black and white, childish, watermark</code></p><p></p><p>Separated subjects:</p><p><code>`die-cut sticker illustration of monk skateboarding, full body on black background, standing, cinematic lighting, dramatic lighting, masterpiece by vector-art, apparel artwork style by vector-art`</code></p><p></p><p><code>`black eagle on a light background vector-art, cinematic lighting, dramatic lighting, masterpiece by vector-art, apparel artwork style by vector-art`</code></p><p></p><p>Negative Prompt:</p><p><code>low poly, tetric, mosaic, disfigured, kitsch, ugly, oversaturated, grain, low-res, Deformed, blurry, bad anatomy, disfigured, poorly drawn face, mutation, mutated, extra limb, ugly, poorly drawn hands, missing limb, blurry, floating limbs, disconnected limbs, malformed hands, blur, out of focus, long neck, long body, ugly, disgusting, poorly drawn, mutilated, mangled, old, surreal, pixel-art, black and white, childish, (((watermark))), (((dreamstime))), (((stock image)))</code></p><p></p><p>Stickers:</p><p><code>((die_cut sticker)) colored punk animal illustration, die_cut sticker in style of vector-art</code></p><p></p><p><code>((die_cut sticker)) colored tiger illustration on white background, centered, die_cut sticker in style of vector-art</code></p><p><br />Negative prompt: <code>low poly, tetric, mosaic, disfigured, kitsch, ugly, oversaturated, grain, low-res, Deformed, blurry, bad anatomy, disfigured, poorly drawn face, mutation, mutated, extra limb, ugly, poorly drawn hands, missing limb, blurry, floating limbs, disconnected limbs, malformed hands, blur, out of focus, long neck, long body, ugly, disgusting, poorly drawn, mutilated, mangled, old, surreal, pixel-art, black and white, childish</code></p><p></p><p>I will add some more interesting prompts here.<br /><br />Img2Img:</p><p>Keep things simple, use negative. There are some screenshots with examples and prompt part. Experiment with generated images.</p>