## Gigafractal Diffusion SD1.5
### 一、模型概述

- 标签：`midjourney`, `style`, `fantasy`
- 下载数：291
- 收藏人数：62
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] PickleTensor

- 统计数据
  - 发布时间：2022-12-04T22:39:36.352Z
  - 原始模型：SD 1.5
  - 下载数：242
  - 评分人数：0
  - 评分：0
- 下载地址
  - [gigafractalDiffusion_pickletensor.ckpt](https://civitai.com/api/download/models/1230)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a48f1988-45f2-4f47-842e-3e6b5346e400/width=450/10165.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ec1144c7-8eea-43db-1432-48d432078f00/width=450/10172.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/edbae46b-1c99-4de2-fff9-9455bb985c00/width=450/10171.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5c5e79fc-8e7f-4017-6823-eb0dad5acc00/width=450/10170.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] SafeTensor

- 统计数据
  - 发布时间：2022-12-04T22:39:36.352Z
  - 原始模型：SD 1.5
  - 下载数：49
  - 评分人数：0
  - 评分：0
- 下载地址
  - [gigafractalDiffusion_safetensor.safetensors](https://civitai.com/api/download/models/1231)
  - [gigafractalDiffusion_safetensor_trainingData.zip](https://civitai.com/api/download/models/1231?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a80dfbe1-1dad-4450-af96-f3a2cea0a700/width=450/10140.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bc8314e8-5c22-499b-c1f3-946f7d8b4800/width=450/10139.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c767604d-ebcd-45c9-a2b3-43934c1d1f00/width=450/10138.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/513b2fe6-a2a3-45ea-f5fc-cfc54fbc6c00/width=450/10137.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Originally posted to <a href="https://huggingface.co/kabachuha/gigafractal-diffusion" rel="ugc" target="_blank">HuggingFace by kabachuha</a></p><p>Gigafractal Diffusion is a latent text-to-image diffusion model based on the original CompVis Stable Diffusion v1.5 and then fine-tuned on 40 images origanally made with another diffusion model named 'Disco Diffusion' using Dreambooth. This model has been created to explore the possibilities and limitations of Dreambooth training with training steps increased much more than usual and to overcome biases in the model created by the text incoder's token associations. The purpose of this model is to provide the biomorphic fractalism effect present in Disco Diffusion, but without the bias to 'Disco parties' and especially 'discoballs' for which [the model by snek](was known for).</p><p><br /></p><p><strong>Dreambooth hyperparameters</strong></p><p>python main.py --base configs/stable-diffusion/v1-finetune_unfrozen.yaml \ -t \ --actual_resume /home/{USERNAME}/kml/stable-diffusion-webui/models/Stable-diffusion/v1-5-pruned.ckpt \ -n dscdif \ --gpus 0, \ --data_root /home/{USERNAME}/kml/datasets/styles/dscdif \ --reg_data_root /home/{USERNAME}/kml/datasets/styles/dscdif1 \ --class_word biomorphic \ --no-test \ --max_steps 2040</p><p>The regularization dataset of 200 AI-generated images had been produced in AUTOMATIC1111's webui with the following prompt which may have had a positive effect on the resulting quality.</p><p><br /></p><p><strong>License</strong></p><p>This model is open access and available to all, with a CreativeML OpenRAIL-M license further specifying rights and usage. The CreativeML OpenRAIL License specifies:</p><p>You can't use the model to deliberately produce nor share illegal or harmful outputs or content The authors claims no rights on the outputs you generate, you are free to use them and are accountable for their use which must not go against the provisions set in the license You may re-distribute the weights and use the model commercially and/or as a service. If you do, please be aware you have to include the same use restrictions as the ones in the license and share a copy of the CreativeML OpenRAIL-M to all your users (please read the license entirely and carefully)</p><p><strong>Please read the full license here</strong></p><p><strong>Downstream Uses</strong></p><p>This model can be used for entertainment purposes and as a generative art assistant.</p><p><strong>Acknowledgements</strong></p><ul><li>Inspired by <a href="https://huggingface.co/SDAddictsAnon/Snek" rel="ugc" target="_blank">snek's work</a></li><li>This project would not have been possible without the incredible work by the CompVis Researchers, Disco Diffusion, Deforum devs and all the artists who made the content for training even if they were an AI.</li><li>The author is grateful to snek for the provided dataset.</li></ul><p><strong>Subjective opinion:</strong> the quality of the output images is comparable to that of another text2image generator, Midjourney.</p>