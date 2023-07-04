## animal-human hybrids
### 一、模型概述

- 标签：`animals`, `people`, `photorealistic`, `fur`, `anthro`, `furry`, `anthropomorphization`, `animal`, `hybrid`
- 下载数：996
- 收藏人数：162
- 评论人数：7
- 评分人数：4
- 评分：4

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-06T20:45:45.584Z
  - 原始模型：SD 1.5
  - 下载数：996
  - 评分人数：4
  - 评分：4
- 下载地址
  - [animalHumanHybrids_v10.safetensors](https://civitai.com/api/download/models/64269)
  - [animalHumanHybrids_v10.ckpt](https://civitai.com/api/download/models/64269?type=Model&format=PickleTensor&size=pruned&fp=fp16)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7b70d835-bb68-452e-b96d-3f1bf76b4aa2/width=450/709832.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b57b234e-aacc-4626-ad45-a0f26575950a/width=450/709834.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2acc9b40-c9a8-44ca-8f8b-40889a9f9fcd/width=450/709837.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e4fb7a53-0ebd-45ec-8cfe-9b8f892eed5a/width=450/709840.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This model is fine-tuned on nearly 300 images of animal-human hybrids generated with MidJourney.</p><p></p><p>Fine-tuning was done at a resolution of 1024x1024 which allows it to natively produce images of that size without distortions or requiring Hires. fix</p><p></p><p>Since the training images were made with MidJourney, they were not explicit images and so you are unlikely to get those results when using the hybrid keywords (I have not gotten them in testing), but I cannot make assurances since it was finetuned from the RealisticVision 2.0 model located at: <a target="_blank" rel="ugc" href="https://civitai.com/models/4201/realistic-vision-v20">https://civitai.com/models/4201/realistic-vision-v20</a></p><p></p><h3><strong>Here are my suggested settings:</strong></h3><p><strong>Sampling Method:</strong> Euler</p><p><strong>Sampling Steps:</strong> 16-50 (images shown use 16-32 steps)</p><p></p><h2><strong>Prompting:</strong></h2><p>the keyword "hybrid" is used for the anthropomorphized characters and in training it was formatted as something like: "[animal type]-[human type] hybrid"</p><h3><strong>Here are some examples:</strong></h3><p>"a photo of a fox-woman hybrid"</p><p>"a photo of a deer-man hybrid as a lumber-jack"</p><p>"a photo of a hedgehog-girl as a student"</p><p></p><p>In training the "a photo of" prefix was used with the photo-realistic images although many were in other styles so this is only useful if you want something more realistic. I also put things such as "cartoon, 3d model" in the negative prompting to get more realism.</p><p></p><h2><strong>Animal-hybrid types used in training:</strong></h2><h3>(you shouldn't be limited to these though)</h3><p>Generic/unspecified animals | Badgers | Cats</p><p>Birds of various types | chameleons | cheetahs</p><p>deer | dogs | elephants</p><p>foxes | frogs | goats</p><p>hedgehogs | hyenas | lizards</p><p>llamas | monkeys | mice</p><p>rats | otters | owls</p><p>pandas (including red pandas) | pigs | bears</p><p>rabbits | raccoons | rhinos</p><p>rodents | seals | sheep</p><p>skunks | squirrels | turtles</p><p>and walruses</p>