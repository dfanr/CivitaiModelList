## [LoRA] Shibuya Kanon (Love Live! Superstar!!)
### 一、模型概述

- 标签：`anime`, `character`, `lovelive`, `lora`
- 下载数：1457
- 收藏人数：217
- 评论人数：2
- 评分人数：3
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2

- 统计数据
  - 发布时间：2023-05-27T13:10:10.360Z
  - 原始模型：SD 1.5
  - 下载数：742
  - 评分人数：2
  - 评分：5
- 下载地址
  - [shibukano-v2.safetensors](https://civitai.com/api/download/models/82716)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e6c57fa3-a50b-45d5-8294-f2688b2137a7/width=450/931498.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a3265816-146a-42a8-acd5-e52ef6d3abf5/width=450/931306.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/483ba25d-9c32-4201-8c4a-ebee9e96f7ad/width=450/931499.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d0aebed2-5e3b-453a-bee4-ce1694ab0b0b/width=450/931310.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1

- 统计数据
  - 发布时间：2023-05-27T13:00:51.479Z
  - 原始模型：SD 1.5
  - 下载数：715
  - 评分人数：1
  - 评分：5
- 下载地址
  - [shibukano-anime.safetensors](https://civitai.com/api/download/models/56136)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/41bd7297-8a94-4ca7-5359-2697a2f5d700/width=450/608799.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3d192163-01db-4c74-5a0a-1a5e8a22ce00/width=450/608718.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c65962d8-7f7c-4bf0-82d5-3b68dae83f00/width=450/608597.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6ad06e34-cbf2-4eb3-44f1-42604991ae00/width=450/608593.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Trained using around 150 anime screenshots from season 1 and season 2. 20-30 images are chosen from sideway angles (booru tag <code>from side</code>). This is important, as previous models I trained for Kanon as well as other characters lacked the ability to generate sideway images.</p><p></p><p>Activation tag: <code>shibuya kanon</code></p><p>To generate school uniform: <code>student uniform, gray dress, red ribbon, neck ribbon, pinafore dress, white shirt</code></p><p>To generate glasses: <code>glasses</code>. For v2, include <code>bangs, hair between eyes</code> as well (the model will generate her wearing glasses without bangs if not prompted)</p><p></p><h2 id="notes-for-v2">Notes for v2</h2><p>This version produces images extremely close to the anime art style. Most importantly, it rarely distorts her eyes. The key to this might be using a high repeat number and low learning rate, as well as a large enough LoRA capacity (I used 32/16). See changelog (<em>About this version</em> section on the left pane) for more details regarding the training parameters.</p><p>Model and ratio:</p><ul><li><p><strong>Meina_Hentai*</strong>: around 0.6-0.7. I recommend using this since it is what the LoRA has been fine-tuned from. Do not get fooled by the name, it is actually a good SFW model</p></li><li><p><strong>Anything v4.5, AOMv3</strong>: similar to the above. Also precisely describes Kanon, though generated images have high saturation</p></li></ul><p>Demo images did not went through any highres upscaler.</p><h2 id="notes-for-v1">Notes for v1</h2><p>Model and ratio:</p><ul><li><p>Anything v4.5: use a LoRA ratio of around 0.6-0.8</p></li><li><p>Corneos7thHeavenMix: ratio about 0.7-0.8. Good for generating anime style art</p></li><li><p>AOM3A1: around 0.6. Might confuse left and right bangs if generate sideway images</p></li></ul><p>AOM3A1 also has the tendency to change Kanon's hairstyle to <code>hair bun</code>, <code>hair tie</code>, or add random hair bow, ornament, etc. Consider adding those to the negative prompt if you don't want them to appear in your images.</p><p></p><h2 id="comparing-v2-and-v1">Comparing v2 and v1</h2><p>Left: v1, right: v2. All images are generated with <em>Meina_Hentai </em>and <em>AOMv3 </em>VAE</p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/61c06c3b-5443-4dda-9e26-b5e908f64bab/width=525/61c06c3b-5443-4dda-9e26-b5e908f64bab.jpeg" /><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/350cdc16-b19d-4446-888b-c26178ec51f2/width=525/350cdc16-b19d-4446-888b-c26178ec51f2.jpeg" /><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e9e28c14-cfc2-43ee-9653-12c764e25bb9/width=525/e9e28c14-cfc2-43ee-9653-12c764e25bb9.jpeg" />