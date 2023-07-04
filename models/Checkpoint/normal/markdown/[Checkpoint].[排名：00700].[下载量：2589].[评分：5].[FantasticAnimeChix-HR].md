## FantasticAnimeChix-HR
### 一、模型概述

- 标签：`anime`, `female`, `base model`, `fantasy`, `semi-realistic`
- 下载数：2589
- 收藏人数：713
- 评论人数：7
- 评分人数：9
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0-fp16-no-ema

- 统计数据
  - 发布时间：2023-05-14T18:42:42.451Z
  - 原始模型：SD 1.5
  - 下载数：1935
  - 评分人数：8
  - 评分：5
- 下载地址
  - [fantasticanimechixHR_v10Fp16NoEma.safetensors](https://civitai.com/api/download/models/70739)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/33d89343-9268-4b1e-920d-7159c3285fba/width=450/790366.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dadba12c-193c-4229-a723-9da4f9cadbaa/width=450/790372.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a9899483-36c8-478a-a8f9-139a93836f95/width=450/790374.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ae97a3d-9d76-44cc-9a55-ee5c2eecb85c/width=450/790376.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-05-14T18:14:20.638Z
  - 原始模型：SD 1.5
  - 下载数：654
  - 评分人数：1
  - 评分：5
- 下载地址
  - [fantasticanimechixHR_v10.safetensors](https://civitai.com/api/download/models/69265)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/623f2f87-b400-4647-bbb3-8bde1ab2adde/width=450/781930.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cb8ebbb4-3020-4629-b3a8-2b14bb58c2f8/width=450/781931.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4f141329-517b-4930-a8b8-4bc18a67f752/width=450/781932.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/938dae6f-0e30-4e3d-89b1-48a4973a6108/width=450/781933.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>I was happy with my FantasticChix-HR model, so I decided to use it as a base for a more anime-styled version, and these are the results. </p><p></p><p>Merged models:</p><ul><li><p>FantasticChix-HR</p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/60933/fantasticchix-hr?modelVersionId=66857">https://civitai.com/models/60933/fantasticchix-hr?modelVersionId=66857</a></p></li></ul></li><li><p>Counterfeit V3.0</p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/4468/counterfeit-v30">https://civitai.com/models/4468/counterfeit-v30</a></p></li></ul></li><li><p>Dalcefo Painting V3 </p><ul><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/AnaNoSleep/models_by_dalcefo">https://huggingface.co/AnaNoSleep/models_by_dalcefo</a></p></li></ul></li></ul><p></p><p>Settings are basically the same as FantasticChix-HR, so follow the instructions there for how to use (including the VAE). Since it can sometimes have anatomy problems compared to FantasticChix-HR, I'd recommend also adding a <strong>(bad anatomy:1.4)</strong> prompt to the negatives. </p><p></p><p>This model also <strong><em>really</em></strong> likes to generate women, so if you want something else, you'll need to get a bit aggressive with positive and negative prompts. Just using a prompt like "giant mecha" will give you a female wearing mecha armor. Even using just "male" in the positive prompts will sometimes make a more androgynous male. </p><p></p><p>Only one of the sample images is using a LoRA. The rest are purely the model doing all the work. For some examples of prompts, see the samples of FantasticChix-HR. If you want more colorful results, make sure to include some prompts like "vibrant colors", "colorful", etc. </p><p></p><p>If you notice anything weird added to the image or any messed up anatomy <strong>after </strong>upscaling you may need to reduce the denoising strength of the upscaler from 0.5 to 0.4.</p>