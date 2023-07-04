## Handpainted RPG Icons 
### 一、模型概述

- 标签：`handpainted`, `icons`, `fantasy`, `rpg`
- 下载数：2656
- 收藏人数：827
- 评论人数：3
- 评分人数：4
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v.1

- 统计数据
  - 发布时间：2023-02-07T14:22:32.214Z
  - 原始模型：SD 1.5
  - 下载数：2656
  - 评分人数：4
  - 评分：5
- 下载地址
  - [handpaintedRPGIcons_v1.ckpt](https://civitai.com/api/download/models/4525?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [handpaintedRPGIcons_v1.safetensors](https://civitai.com/api/download/models/4525)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c350e62f-aa73-4f08-0443-53f23d9ffb00/width=450/30907.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8ae569c9-298f-4219-e89c-a3b8ece60500/width=450/30920.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7824749d-142f-4413-638c-bdb5336c2b00/width=450/30919.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2b7ed428-8f61-4c1e-959c-b485334c0800/width=450/30918.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>Overall info:</strong></p><ul><li><p>It was made for hand-painted object icons generations specificly (but I did some reaserch and tests and you can get a whole variety of really interesting style images using this model if you know what you are doing - like landscapes, interiors or even portraits.</p></li><li><p>Note that a model might be a bit overtrained - that means there is a little tradeoff in style over objects in your prompt (but when you give it a proper amount of work on your generations you might be able to achieve satysfying and quantifiable results).</p></li><li><p>Samples results are mostly cherrypicked (but all of them were not modified or improved in any way).</p></li><li><p>Good results might require some more work than just typing a prompt. (<strong>VERY</strong> <strong>IMPORTANT - LOOK BELOW↓)</strong></p></li></ul><p></p><p><strong>Tips'n Tricks in using:</strong></p><ul><li><p>The most quantifiable balance between prompt, style and detail can be achieved by using bit of "prompt editing" and experimenting. Just keep the syntax of a trigger word like this: [<strong>rpgicondiff:4</strong>], where the number could be higher/lower depending on a variety of parameters. Shortly, the higher a number is a less style you get but probably more acurate.</p></li><li><p>I do not recommend using just raw trigger word because (due to bit of overtraining) it might make the generations too similar to model's fine-tuning images and does not reflect object from your prompts. The best results (from my experiences and experiments) is to use prompt editing. But yet, sometimes it generates quiet worth images with just trigger word so give it at least a try.</p></li><li><p><u>Parameters:</u></p><ul><li><p>I got the best results using <strong>Euler a</strong>, <strong>Euler</strong> samplers, <strong>20</strong> and <strong>50-70</strong> steps, <strong>7-15</strong> cfg scale. (I provide you with additional non cherrypicked <a target="_blank" rel="ugc" href="https://imgur.com/a/i0EML2N">sheets</a> from my experiments with various parameters to see for yourself)</p></li></ul><ul><li><p>You can declare <strong>negative prompt</strong>: "character,human, person, people, male, female, man, woman" if you want to increase a chance to get rid of characters from your images.</p></li></ul></li><li><p><u>Workflow:</u></p><ul><li><p>I recommend <strong>cfg 7</strong> and<strong> 20 steps</strong>, prompt <strong>without</strong> a <strong>trigger word</strong> as a starting point. Just find an object and seed that you are satisfied with (which reflects an object you want to generate) and then use this seed with edited trigger word ,f.e [rpgicondiff:<strong>4</strong>] and experiment with it.</p></li><li><p>Increasing a steps count to 50-70 and cfg scale to 10 might improve a detail in your generation (note that it can also modify it)</p></li><li><p><strong>I consider this method as the most effective in this iteration of the model.</strong></p></li></ul><p>Everything is a matter of experiments and trying to balance a style and a things we want to generate.</p><p></p></li></ul><p>I provide you with a .ckpt and .safetensors extension to download.</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/6876/handpainted-rpg-icons-style-lora">Here</a> you can find <strong>LoRA </strong>extracted from this model.</p><p></p>