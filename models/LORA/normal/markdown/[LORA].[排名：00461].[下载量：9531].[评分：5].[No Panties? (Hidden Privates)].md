## No Panties? (Hidden Privates)
### 一、模型概述

- 标签：`clothing`, `revealing clothes`, `suggestive`, `no panties`, `haitenai`
- 下载数：9531
- 收藏人数：2219
- 评论人数：12
- 评分人数：19
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-30T06:56:36.044Z
  - 原始模型：SD 1.5
  - 下载数：9531
  - 评分人数：19
  - 评分：5
- 下载地址
  - [npm-v11t-000005.safetensors](https://civitai.com/api/download/models/58682)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0bd27c5b-299f-4d01-264d-32d34a12e300/width=450/639320.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9a0d1778-1f10-4615-31a6-fce770221900/width=450/639326.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/abb14274-df05-4b32-d03f-baae28e00f00/width=450/639337.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c98bead3-d109-4f29-5975-675209938c00/width=450/639343.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is a Lora trained on images where a girl is probably or obviously not wearing panties, but pussy is not visible (such as haitenai? tag on pixiv). Most models, especially anime/booru models, can be too eager to go full nsfw when trying to generate suggestive images, and if you add "pussy juice" then it's pretty much impossible to not generate exposed pussy. This Lora will drastically improve consistency when generating those borderline suggestive prompts, and also contains training for various types of ways to display a lack of panties without exposing the crotch. See list of tags below for details.</p><p></p><h3>Main tags:</h3><p><strong>npmaybe</strong>, <strong>probably no panties</strong> : used on images where the lack of panties is questionable, or at least not too obvious. "probably no panties" will be affected by "no panties", depending on the base model, while "npmaybe" is new so should have an equal, but lesser effect. You can use both, or either, test and see.</p><p><strong>npclearly</strong>, <strong>obviously no panties</strong> : used when there's no way girl's wearing underwear. The training didn't really grasp the difference very well, so most of time it won't make any difference which tag you use, but it does sometimes make a difference as shown in the previews.</p><p><strong>hidden privates</strong> : used on all images in the dataset. Very effective at hiding privates, as you could guess. I would recommend always using it.</p><p><strong>hidden crotch</strong> or <strong>partially visible crotch</strong> : one or the other used depending on if the crotch, specifically the area right next to where you would expect the pussy to be, is visible or not. Ex: raising skirt right at the edge so bottom of crotch is barely visible, or a front slit cutting off right next to pussy.</p><p><strong>hidden by leg/clothes/hair/tail/border/other</strong> : These help hiding the crotch, but the "by" part doesn't seem to do anything. Probably not enough training data for each. "convenient leg" was also added with hidden by leg.</p><p></p><h3>Other new tags :</h3><p><strong>upthigh </strong>: when thigh is visible especially high, above groin. Usually on front view, skirt lift images.</p><p><strong>innerthigh </strong>: this one's ambiguous and I'm not sure it does much, but it's added on images where you can see the inner thigh right next to the crotch.</p><p><strong>sidethigh </strong>: when you can see the bare thigh from the side all the way up to the butt. Probably won't do much if the view isn't from the side, use "from side", or "side view" for more moderate effect.</p><p><strong>sitbare </strong>: when sitting down, usually on floor, with knees up, and you can see the bare bottom of butt. I haven't tested this much, I wouldn't expect a noticeable difference since default generation is like that already.</p><p><strong>backcrack </strong>: the opposite of groin I guess, lowleg from behind showing butt crack.</p><p><strong>underbutt </strong>: not a new tag, but putting it here since it's similar to above tags. underboob for butts.</p><p><strong>(slightly) lifting one side/both sides of skirt</strong></p><p><strong>very lowleg</strong></p><p></p><h3>Relevant existing booru tags :</h3><p>groin, skirt slit, side slit, front slit, skirt lift, lifted by self, wind lift, skirt tug, microskirt, bottomless, naked shirt/apron/tabard/etc, no bra, convenient censoring,</p><p>hair censor (check out hair censor loras, very few images with hair censoring in this one so it probably won't work great on its own),</p><p>see-through silhouette (lora for this will also help a lot, otherwise it usually becomes completely see-through, although it does always hide crotch)</p><p></p><h3>Notes</h3><p>If you'd like, you can check out example (partial) prompts on this wildcard I made to test the lora: <a target="_blank" rel="ugc" href="https://files.catbox.moe/lb3l8g.txt">https://files.catbox.moe/lb3l8g.txt</a></p><p>The :TT after lora in previews is a preset for the Lora Block Weight extension. It reduces the lora's impact on the background, in particular. To reproduce, add this line in the presets:</p><p>TT:1,0.2,0.2,0.2,0.5,0.5,0.5,0.5,1,1,1,1,0.5,0.5,0.5,0.5,0.5</p>