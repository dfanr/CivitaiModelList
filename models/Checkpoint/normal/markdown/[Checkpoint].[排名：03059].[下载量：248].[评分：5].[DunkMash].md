## DunkMash
### 一、模型概述

- 标签：`base model`
- 下载数：248
- 收藏人数：38
- 评论人数：2
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-28T14:06:58.314Z
  - 原始模型：SD 1.5
  - 下载数：248
  - 评分人数：2
  - 评分：5
- 下载地址
  - [dunkmash_v10.safetensors](https://civitai.com/api/download/models/89900)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/24d3554e-9985-4182-b0a0-f21f26abc67b/width=450/1041869.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ae35b1dc-ad19-4893-b37f-09ebc0c18d1a/width=450/1041953.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d11e902c-0e90-4be0-99e0-0a31c5b3c59d/width=450/1041854.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9e1adebd-c496-4464-afdf-5eec44363679/width=450/1041870.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2 id="heading-22088">A Showcase of Re-Basin Merging:</h2><p>This mix is intended to reach that oh-so-popular digital art style that many other models have. The goal was to get that style while preserving the variability of the base models using high iteration re-basin merges. It has a default painterly aesthetic, but it can be pushed into both anime and digital photorealism.</p><p>As a consequence of the popular trends that went into it, this model does bias towards human subjects, but it's not so strong that you can't prompt against it.</p><h2 id="heading-22089">What is a Re-Basin Merge?</h2><p>In a normal interpolation merge, a model that makes good anime and a model that makes good photographs typically merge together to create a bad mush in the middle. This happens because nearly unused weights in the anime model are being merged with critical texture and composition weights in the photograph model, ruining details like hands and material textures in the outcome. This was less of a problem when every model was a light finetune of the NovelAI leak, but as finetunes get more advanced the models have become less compatible.</p><p>Re-basin merging is a technique that shuffles the weights around inside a model in way that does not affect the outcome of the neural network, but also lines up similar weights to make merging less destructive. The result is a model that can achieve the style of both input models while also preserving the lower level details of each.</p><p>Special thanks to T0b1maru for creating such an easy tool to get this done quickly <a target="_blank" rel="ugc" href="https://github.com/T0b1maru/re-basin_merger">https://github.com/T0b1maru/re-basin_merger</a></p><h2 id="heading-22090">What's In This Mix?</h2><ul><li><p>Merge 1 - 75% Nothing v2.3 : 25% MeinaMix 9</p></li><li><p>Merge 2 - 40% I Can't Believe It's Not Photography</p></li><li><p>Merge 3 - 30% DreamShaper 6</p></li><li><p>Merge 4 - 15% AtoZovya v2 Art</p></li><li><p>Add Difference 20% Noise Offset Model</p></li></ul><p>These models were selected to provide as varied a dataset as possible. All merges (aside from the noise offset) were 500 iteration re-basin merges, all layers. By merge 2, the model was already similar in style to DreamShaper, but leaned too heavily towards anime-shaped faces.</p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9791e53c-e183-49c3-a25e-af68bc0def3f/width=525/9791e53c-e183-49c3-a25e-af68bc0def3f.jpeg" /></p><h2 id="heading-8914">Generation Recommendations</h2><h3 id="heading-22091">Controlling Style</h3><p>Without style input, the model will trend towards a painted texture. This is mostly the result of the 15% AtoZovya which, while it does add lots of unique variation to fantasy themes and faces, it did slightly poison the model's ability to make clean anime images. If you are finding the textures not to your liking, I suggest using negative "Painting" in your prompts.</p><p>When going for the extreme ends of style (anime/realism) it's best to put your style keywords at the start of the prompt and remember to include negatives from the opposite end. Specific style information like "cel shaded anime" or "toriyama anime style" work better than generic "anime" descriptors.</p><p>For realism, terms like "photograph" and "macro photograph" push the style harder than "photorealistic" which is generally used to tag digital art that is meant to look similar to realism. This model will not be able to create fully photo-realistic images, since the most realistic model in the merge is ICBINP which itself is not fully realistic. If your goal is perfect realism or anime, then this is simply not the model for you.</p><h3 id="heading-22092">Highres Fix</h3><p>Highres fix is highly recommended to get the best details out of any model these days.</p><p>An unfortunate side effect of this merge style is that edges are not very sharp, and small subjects/faces are not very detailed. Highres fix improves this, but it works best with denoise values between 0.45-0.7 to avoid soft edges. If you try to use highres fix with a more sane value (&lt;0.3) then you will get lackluster results. If you want to get an upscaled result without destroying the composition with higher denoise, then I suggest using the ControlNet Tile upscale to keep things clean.</p><h3 id="heading-22093">Prompt Tips</h3><p>Be specific and concise with your prompts. If you put the entire magna carta in your negatives, then you will lose control of the style and composition. You do not need a boiler-plate negative here. I recommend generating your test images without any negatives, and then add specific negative tags to avoid specific issues you are having.</p><p>While this model is fine at producing nudity, it has excellent creative clothing results as long as you remember to prompt for clothes.</p>