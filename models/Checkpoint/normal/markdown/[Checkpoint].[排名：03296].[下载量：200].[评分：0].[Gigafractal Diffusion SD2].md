## Gigafractal Diffusion SD2
### 一、模型概述

- 标签：`midjourney`, `style`, `fantasy`
- 下载数：200
- 收藏人数：23
- 评论人数：1
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] PickleTensor

- 统计数据
  - 发布时间：2022-12-04T22:38:13.626Z
  - 原始模型：SD 2.0 768
  - 下载数：160
  - 评分人数：0
  - 评分：0
- 下载地址
  - [gigafractalDiffusion_pickletensor.ckpt](https://civitai.com/api/download/models/1232)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da555ff0-11d0-440a-afe9-5c209a7d9500/width=450/10151.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/545f58ef-c43d-4d1d-4caf-7b799db04200/width=450/10150.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a07024ad-64a3-468c-a9bc-ad6ef4cfa100/width=450/10149.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f18230c2-cf04-48e6-76fa-f081aa7cdd00/width=450/10148.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] SafeTensors

- 统计数据
  - 发布时间：2022-12-04T22:38:13.626Z
  - 原始模型：SD 2.0 768
  - 下载数：40
  - 评分人数：0
  - 评分：0
- 下载地址
  - [gigafractalDiffusion_safetensors.safetensors](https://civitai.com/api/download/models/1233)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/57688da1-ee2d-4662-3fda-db0af74f9900/width=450/10161.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/63a3adbd-9631-497b-a98f-2fe268de4000/width=450/10160.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b30fd930-163a-484a-63d2-6fb1fcd06b00/width=450/10159.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/67c792a8-c9b6-4c5c-18bb-aebd01616e00/width=450/10158.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Originally posted to <a href="https://huggingface.co/kabachuha/gigafractal2-diffusion" rel="ugc" target="_blank">HuggingFace by kabachuha</a></p><p>Gigafractal2 Diffusion is a latent text-to-image diffusion model based on the original StabilityAI Stable Diffusion v2.0 and then fine-tuned on 40 images origanally made with another diffusion model named 'Disco Diffusion' using Dreambooth. This model has been created to explore the possibilities and limitations of Dreambooth training with training steps increased much more than usual and to overcome biases in the model created by the text incoder's token associations. The purpose of this model is to provide the biomorphic fractalism effect present in Disco Diffusion, but without the bias to 'Disco parties' and especially 'discoballs' for which [the model by snek](was known for).</p><p><strong>Dreambooth hyperparameters</strong></p><p>export MODEL_NAME="stabilityai/stable-diffusion-2"</p><p>export INSTANCE_DIR="/home/{USERNAME}/kml/datasets/styles/dscdif"</p><p>export CLASS_DIR="/home/{USERNAME}/kml/datasets/styles/dscdif2"</p><p>export OUTPUT_DIR="/home/{USERNAME}/kml/models1"</p><p>accelerate launch train_dreambooth.py \</p><p>  --pretrained_model_name_or_path=$MODEL_NAME  \</p><p>  --instance_data_dir=$INSTANCE_DIR \</p><p>  --class_data_dir=$CLASS_DIR \</p><p>  --output_dir=$OUTPUT_DIR \</p><p>  --with_prior_preservation --prior_loss_weight=1.0 \</p><p>  --instance_prompt="gigafractal artstyle" \</p><p>  --class_prompt="biomorphic" \</p><p>  --resolution=768 \</p><p>  --train_batch_size=1 \</p><p>  --gradient_accumulation_steps=1 \</p><p>  --learning_rate=1e-6 \</p><p>  --lr_scheduler="constant" \</p><p>  --lr_warmup_steps=0 \</p><p>  --num_class_images=200 \</p><p>  --max_train_steps=2040 \</p><p>  --mixed_precision 'no' \</p><p>  --train_text_encoder</p><p><br /></p><p>The regularization dataset of 200 AI-generated images had been produced in AUTOMATIC1111's webui with the following prompt which may have had a positive effect on the resulting quality.</p><p><br /></p><p><strong>License</strong></p><p>This model is open access and available to all, with a CreativeML OpenRAIL-M license further specifying rights and usage. The CreativeML OpenRAIL License specifies:</p><p>You can't use the model to deliberately produce nor share illegal or harmful outputs or content The authors claims no rights on the outputs you generate, you are free to use them and are accountable for their use which must not go against the provisions set in the license You may re-distribute the weights and use the model commercially and/or as a service. If you do, please be aware you have to include the same use restrictions as the ones in the license and share a copy of the CreativeML OpenRAIL-M to all your users (please read the license entirely and carefully)</p><p><strong>Please read the full license here</strong></p><p><strong>Downstream Uses</strong></p><p>This model can be used for entertainment purposes and as a generative art assistant.</p><p><strong>Acknowledgements</strong></p><ul><li>Inspired by <a href="https://huggingface.co/SDAddictsAnon/Snek" rel="ugc" target="_blank">snek's work</a></li><li>This project would not have been possible without the incredible work by the CompVis Researchers, Disco Diffusion, Deforum devs and all the artists who made the content for training even if they were an AI.</li><li>The author is grateful to snek for the provided dataset.</li></ul><p><strong>Subjective opinion:</strong> the quality of the output images is comparable to that of another text2image generator, Midjourney.</p>