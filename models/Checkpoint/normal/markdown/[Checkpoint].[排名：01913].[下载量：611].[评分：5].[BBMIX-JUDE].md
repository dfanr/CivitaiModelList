## BBMIX-JUDE
### 一、模型概述

- 标签：`anime`, `character`, `photorealistic`, `sexy`, `female`, `woman`, `girls`
- 下载数：611
- 收藏人数：176
- 评论人数：3
- 评分人数：3
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-16T11:50:15.021Z
  - 原始模型：SD 1.5
  - 下载数：611
  - 评分人数：3
  - 评分：5
- 下载地址
  - [clearvae_main2.safetensors](https://civitai.com/api/download/models/97212?type=VAE&format=Other)
  - [bbmixJUDE_v10.safetensors](https://civitai.com/api/download/models/97212)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ae32f539-a2f3-4b15-a36b-5235313c98ec/width=450/1165679.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c2b4cc0e-d955-47b2-97cb-5165a6e3ac25/width=450/1165644.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/eac77c5d-b893-4b7d-80f1-a991efc882cf/width=450/1165680.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/748bc8a6-a449-40a2-b091-573b50e5781d/width=450/1165801.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="bbmix-ruis">BBMIX-JUDE</h1><p>A model that prints well with a thick line touch, a little darker, and a wide background</p><p></p><p><strong>referral prompt</strong></p><ul><li><p>from above, from below</p></li><li><p>shiny skin</p></li></ul><p><strong>negative</strong></p><ul><li><p>{1$$EasyNegative|verybadimagenegative_v1.3}</p></li></ul><p><strong>VAE</strong></p><ul><li><p>clearvae_main , clearvae_main2</p></li><li><p>vae-ft-mse-840000-ema-pruned</p></li></ul><p><br />We will continue to add sample images after finding good Loras so that we can copy and use EXIF in the sample post.</p><p></p><h2 id="precautions-be-sure-to-observe-this">Precautions (Be sure to observe this)</h2><ol><li><p>Models may not be traded or sold. Because this is free. .</p></li><li><p>Models are not available for online paid services. (Free service available)</p></li><li><p>In using the model, all responsibility lies with the user.</p></li></ol><p></p><h1 id="how-to-high-quality">How to high quality</h1><ol><li><p>You can output an image like the sample by using an extension to increase the quality. (All sample images were used with the extensions below)</p></li></ol><ul><li><p>1. Hires.fix -&gt; SwinIR_4x <strong>or</strong> R-ESRGAN 4x+ Anime6B</p></li><li><p>2. Dynamic Thresholding (CFG Scale Fix)</p></li><li><p>3. Detection Detailer (must use)</p></li><li><p>4. SD upscaler <strong>or</strong> <a target="_blank" rel="ugc" href="https://oo.pe/https://www.upscayl.org/">https://oo.pe/https://www.upscayl.org/</a></p></li></ul><p></p><h3 id="1hiresfix-built-in-or">1.Hires.fix ( built-in ) or</h3><p></p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/19b03b42-7fc2-45b6-97f9-2586f5fa353e/width=525/19b03b42-7fc2-45b6-97f9-2586f5fa353e.jpeg" /></p><p></p><h3 id="2-dynamic-thresholding">2. Dynamic Thresholding</h3><p><a target="_blank" rel="ugc" href="https://github.com/mcmonkeyprojects/sd-dynamic-thresholding.git">https://github.com/mcmonkeyprojects/sd-dynamic-thresholding.git</a></p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a4af6e92-9d0c-4222-9131-d3445b22396f/width=525/a4af6e92-9d0c-4222-9131-d3445b22396f.jpeg" /></p><p></p><h3 id="3detection-detailer">3.Detection Detailer</h3><p><a target="_blank" rel="ugc" href="https://github.com/Bing-su/dddetailer.git">https://github.com/Bing-su/dddetailer.git</a></p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6599bfa0-373f-4e9f-988e-aac60caaf6f1/width=525/6599bfa0-373f-4e9f-988e-aac60caaf6f1.jpeg" /></p><p></p><p>Questions that do not use the above four cannot be answered. Please note that images printed without using the four extensions may not look good.</p><p></p><p></p><p></p><p></p><h1 id="tip">TIP</h1><p>In order to keep token 75, do not insert resolution, detail, or quality tokens. Since extension add-ons such as DD or DT handle it anyway, there is no need to insert tokens like the ones below.</p><h2 id="bad-prompt-do-not-use">bad prompt (do not use)</h2><p>official art, unity 8k wallpaper, ultra detailed, ultra high res, 8k uhd, film grain, delicate, RAW, light particles, detailed skin texture, detailed armor texture, detailed face, intricate details, ultra detailed</p><p>Reality Emphasis Prompt Excludes Detail Emphasis Prompt.</p><p></p><p></p><h1 id="notice">Notice</h1><p>The sample images are created with random prompts and are only examples of what these images can be generated for.<span style="color:rgb(60, 64, 67)"> </span>Therefore, images and prompts may not match.</p>