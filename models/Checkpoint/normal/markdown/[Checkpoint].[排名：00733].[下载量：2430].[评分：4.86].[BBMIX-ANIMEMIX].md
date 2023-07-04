## BBMIX-ANIMEMIX
### 一、模型概述

- 标签：`anime`, `sexy`, `female`, `base model`, `woman`, `girls`
- 下载数：2430
- 收藏人数：583
- 评论人数：9
- 评分人数：7
- 评分：4.86

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2.0

- 统计数据
  - 发布时间：2023-06-30T07:38:48.408Z
  - 原始模型：SD 1.5
  - 下载数：1155
  - 评分人数：4
  - 评分：5
- 下载地址
  - [bbmixANIMEMIX_v20.safetensors](https://civitai.com/api/download/models/107134)
  - [clearvae_main.safetensors](https://civitai.com/api/download/models/107134?type=VAE&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ecdafad5-cee8-4bbd-8104-f273fd570479/width=450/1343814.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2eabf750-a5bd-47fb-97f9-103ac1dece2f/width=450/1343772.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d1ae6b11-d88f-4c56-a119-3c7fdce21717/width=450/1344852.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c083e8d6-8d17-4af7-97fb-8a6029e5e2a2/width=450/1343817.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-06-30T07:31:55.490Z
  - 原始模型：SD 1.5
  - 下载数：1275
  - 评分人数：3
  - 评分：4.67
- 下载地址
  - [clearvae_main2.safetensors](https://civitai.com/api/download/models/104297?type=VAE&format=Other)
  - [bbmixANIMEMIX_v10.safetensors](https://civitai.com/api/download/models/104297)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7f8628df-4a46-4e0d-96d9-626bd71ef595/width=450/1293503.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da177b19-1552-4288-813c-bd3bc5af0e82/width=450/1293498.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fca30713-3b84-460b-bac1-0f11714df3a8/width=450/1293453.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1113774f-ab2d-4a75-abe0-cbfa0bee00e4/width=450/1293511.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="bbmix-ruis">BBMIX-ANIME-MIX</h1><p>Base model for animation</p><p><strong>I tested for several days. It is a merge model that fits very well with most LORA. I would like to test it once. When using Lora, it is weighted from 0.68 to 1, but around 0.7 fits well with this model and Lora.</strong></p><p></p><p></p><p></p><p><strong>referral prompt (i use)</strong></p><ul><li><p>(masterpiece),(intricate details),1girl,pale skin,mature female,__myhair__,{1$$laughing|happy smile},{1$$large breasts:1.3|huge breasts:1.5} BREAK park,{1$$((full body))|((upper body)) BREAK looking at viewer,{1$$dynamic angle|random angle|dynamic pose|random pose|dutch angle}</p><p></p></li></ul><p><strong>negative</strong></p><ul><li><p>{1$$EasyNegative|verybadimagenegative_v1.3}</p></li></ul><p><strong>VAE</strong></p><ul><li><p>clearvae_main , clearvae_main2</p></li><li><p>vae-ft-mse-840000-ema-pruned</p></li></ul><p><br />We will continue to add sample images after finding good Loras so that we can copy and use EXIF in the sample post.</p><p></p><h2 id="precautions-be-sure-to-observe-this">Precautions (Be sure to observe this)</h2><ol><li><p>Models may not be traded or sold. Because this is free. .</p></li><li><p>Models are not available for online paid services. (Free service available)</p></li><li><p>In using the model, all responsibility lies with the user.</p></li></ol><p></p><h1 id="how-to-high-quality">How to high quality</h1><ol><li><p>You can output an image like the sample by using an extension to increase the quality. (All sample images were used with the extensions below)</p></li></ol><ul><li><p>1. Hires.fix -&gt; SwinIR_4x <strong>or</strong> R-ESRGAN 4x+ Anime6B</p></li><li><p>2. Dynamic Thresholding (CFG Scale Fix)</p></li><li><p>3. Detection Detailer (must use)</p></li><li><p>4. SD upscaler <strong>or</strong> <a target="_blank" rel="ugc" href="https://oo.pe/https://www.upscayl.org/">https://oo.pe/https://www.upscayl.org/</a></p></li></ul><p></p><h3 id="1hiresfix-built-in-or">1.Hires.fix ( built-in ) or</h3><p></p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/19b03b42-7fc2-45b6-97f9-2586f5fa353e/width=525/19b03b42-7fc2-45b6-97f9-2586f5fa353e.jpeg" /></p><p></p><h3 id="2-dynamic-thresholding">2. Dynamic Thresholding</h3><p><a target="_blank" rel="ugc" href="https://github.com/mcmonkeyprojects/sd-dynamic-thresholding.git">https://github.com/mcmonkeyprojects/sd-dynamic-thresholding.git</a></p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a4af6e92-9d0c-4222-9131-d3445b22396f/width=525/a4af6e92-9d0c-4222-9131-d3445b22396f.jpeg" /></p><p></p><h3 id="3detection-detailer">3.Detection Detailer</h3><p><a target="_blank" rel="ugc" href="https://github.com/Bing-su/dddetailer.git">https://github.com/Bing-su/dddetailer.git</a></p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6599bfa0-373f-4e9f-988e-aac60caaf6f1/width=525/6599bfa0-373f-4e9f-988e-aac60caaf6f1.jpeg" /></p><p></p><p>Questions that do not use the above four cannot be answered. Please note that images printed without using the four extensions may not look good.</p><p></p><p></p><p></p><p></p><h1 id="tip">TIP</h1><p>In order to keep token 75, do not insert resolution, detail, or quality tokens. Since extension add-ons such as DD or DT handle it anyway, there is no need to insert tokens like the ones below.</p><h2 id="bad-prompt-do-not-use">bad prompt (do not use)</h2><p>official art, unity 8k wallpaper, ultra detailed, ultra high res, 8k uhd, film grain, delicate, RAW, light particles, detailed skin texture, detailed armor texture, detailed face, intricate details, ultra detailed</p><p>Reality Emphasis Prompt Excludes Detail Emphasis Prompt.</p><p></p><p></p><h1 id="notice">Notice</h1><p>The sample images are created with random prompts and are only examples of what these images can be generated for.<span style="color:rgb(60, 64, 67)"> </span>Therefore, images and prompts may not match.</p>