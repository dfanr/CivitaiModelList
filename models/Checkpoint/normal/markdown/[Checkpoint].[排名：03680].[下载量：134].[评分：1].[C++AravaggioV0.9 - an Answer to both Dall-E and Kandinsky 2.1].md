## C++AravaggioV0.9 - an Answer to both Dall-E and Kandinsky 2.1
### 一、模型概述

- 标签：`dark`, `base model`, `general`, `everything`
- 下载数：134
- 收藏人数：25
- 评论人数：1
- 评分人数：1
- 评分：1

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v0.9

- 统计数据
  - 发布时间：2023-06-19T08:02:07.163Z
  - 原始模型：SD 1.5
  - 下载数：134
  - 评分人数：1
  - 评分：1
- 下载地址
  - [cAravaggiov09AnAnswerTo_v09.safetensors](https://civitai.com/api/download/models/99323)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a4b25e24-a3fa-41a4-962a-c1e340671b7b/width=450/1203676.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bf5eb390-8529-4c86-ab49-66e0a987b74a/width=450/1203950.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cb8081d4-dc4b-4f62-af59-07b276598e5e/width=450/1203679.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d7c53b5c-0485-401a-b930-cd9323e697af/width=450/1203683.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>EDIT: after the negative feedback i should make clear that the model is not completely a SD 1.5 and because of that it needs a different approach on generating images, the negative embedding i'm linking here should facilitate the use of negative prompt which is quite hard to get right on this model.</p><p>The model is tested on Automatic1111.</p><p>If you're having troubles generating images - if they look that bad - it's possibly a problem of your graphics card (turn the random number generator to CPU).</p><p>Another trick is that the ENSD works better set to 99999 rather than 31337, check it out for yourself.</p><p>If you can't in any way reproduce the images, even with the embeddings, try copying the info from the example images, it should help.</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/93766/embeddings-pack-for-caravaggio-reupload-with-images">https://civitai.com/models/93766/embeddings-pack-for-caravaggio-reupload-with-images</a></p><p></p><p>This model is not perfect and I'm very well aware of that, this was the first step of my current model which I'd rather not publish yet, anyway it still has plenty of power.</p><p></p><p>(VAE baked in, the model comes with some textual inversions, 768x768 resolution)</p><p></p><p>The procedure in making this model was first of all some merges, then i finetuned a 1.5 basic model with some of my black and white drawings/sketches (im not that much of an artist but it worked very good because it took the style in a nice way, making each humanoid output quite different from both anime and semirealistic models.</p><p></p><p>After i merged even the model finetuned on my drawings on this, then i took the final model and dissected it with the kohya extract diffusers tool... why? Because there are better text encoders around than the base one of Stable Diffusion! And in fact i scraped off Huggingface and tested each one to find the best compatibility. Now this model seems to understand well structured english, you can easily ask ChatGPT for a story and try it on this model, or copy your Midjourney prompts here... it works fine, but it ain't Midjourney, obviously.</p>