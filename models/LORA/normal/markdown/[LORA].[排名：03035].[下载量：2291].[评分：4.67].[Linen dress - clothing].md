## Linen dress - clothing
### 一、模型概述

- 标签：`anime`, `dress`, `clothes`, `outfit`, `clothing`, `realistic`
- 下载数：2291
- 收藏人数：518
- 评论人数：0
- 评分人数：3
- 评分：4.67

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v0.3a

- 统计数据
  - 发布时间：2023-04-23T00:18:48.753Z
  - 原始模型：SD 1.5
  - 下载数：2291
  - 评分人数：3
  - 评分：4.67
- 下载地址
  - [linen_dress_v0.3a.safetensors](https://civitai.com/api/download/models/52803)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3146320b-e341-4492-4b8e-539e83cfd700/width=450/569732.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/79fb7d1a-9500-4d6b-c7d6-5f4b580cb800/width=450/569735.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fe600605-46e3-453b-e181-d237f1470a00/width=450/569760.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c4a77d47-bd0c-4277-b395-819629f29c00/width=450/569761.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is a simple LoRA to generate an off-white linen dress.</p><p><u>(edit: Does not seem to work on more realistic models. Given how it was kind of brute force trained to work on anime models. Works best on models like AnythingV5, AnyLora, YesMix, etc. and does not work on AOM2 or other very stylized/realistic models)</u></p><p>How to use: weight 1.0 (or less), regular CFG, trigger word <strong><em>linen dress</em></strong>, and <u>add the word </u><strong><em><u>realistic </u></em></strong><u>to the negative prompt</u>. It works even better if you add a well trained style LoRA. See the example images. I used other style and character LoRAs of mine combined.</p><p>I made it to see if I could figure a way to train clothing using photos only and use it in an anime model. This was trained on NAI using 8 photos of a single dress from a random clothing store.</p><p>The main challenge was to attempt to use the dress without affecting the anime style, i.e. without making it realistic. I tried multiple combinations of LoRA weights, but couldn't figure out a way to select blocks without affecting the training of the actual dress and its details. I made dozens of attempts! The second challenge was to also get a very subtle floral pattern to show up. Disabling the training of the blocks that affect realism would also affect the training of this pattern. You can see in the example images how it appears more often than not.</p><p>In the end the best result was a combination of specific training parameters (LR/optimizer/batch/repeats), disabling some blocks, and tagging the dataset with "<em>(realistic:1.3)</em>" and use the weighted captions option in kohya-ss gui.</p><p>These were the blocks used:</p><p>"down_lr_weight": "1,1,1,0,0,0,0,0,0,0,0,0",</p><p>"mid_lr_weight": "0",</p><p>"up_lr_weight": "0,1,1,1,1,1,1,1,1,1,1,1",</p><p>Does anyone know a better way?</p><p><s>This should work on more realistic models given the dataset, but didn't test it</s>.</p><p>If this kind of stuff is something you'd like to see more of, let me know.</p><p><u>Additional info</u></p><p>I make these models for fun and for the challenge and release them for free for everyone to enjoy, for non-commercial use (see license). The one thing I ask of you is to provide rating and feedback! That helps me understand where I can improve and helps me stay motivated to produce more content!</p><p>I accept suggestions or requests here or on Civitai discord server.</p><p>You can also check my more polished images and upcoming models on my <a target="_blank" rel="ugc" href="https://www.pixiv.net/en/users/25545070">pixiv </a>profile.</p>