## In the Dark - LORA (Blades in the Dark Style)
### 一、模型概述

- 标签：`dark`, `victorian`, `monochrome`, `style`, `fantasy`, `rpg`
- 下载数：1783
- 收藏人数：423
- 评论人数：3
- 评分人数：2
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] beta5 (64DIM)

- 统计数据
  - 发布时间：2023-06-14T04:23:27.351Z
  - 原始模型：SD 1.5
  - 下载数：657
  - 评分人数：1
  - 评分：5
- 下载地址
  - [inthedark-beta5-e14-DIM64.safetensors](https://civitai.com/api/download/models/95573)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/facadacf-154d-4554-a4a9-300c4a86b5d7/width=450/1137807.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fd97d0a0-2346-4778-8f26-c5d0a1d74163/width=450/1137656.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/494478fe-0098-4216-919a-5baa440766f8/width=450/1137839.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/77b45179-11ba-4f12-96cd-b818511c6dfc/width=450/1137680.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] beta2

- 统计数据
  - 发布时间：2023-06-14T02:28:39.330Z
  - 原始模型：SD 1.5
  - 下载数：697
  - 评分人数：1
  - 评分：5
- 下载地址
  - [inthedark-b2.safetensors](https://civitai.com/api/download/models/85958)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cddd1034-9d14-4975-b258-3b0baf0ec797/width=450/975872.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b0c20b6c-afe3-4675-8310-a4333a2e6a8f/width=450/976662.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5b9d0e2a-43d5-4b5c-80bc-b43d06cddc04/width=450/976691.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/64f063d0-e9d1-4ce6-a126-36019e35e969/width=450/975814.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] alpha1

- 统计数据
  - 发布时间：2023-06-14T02:28:39.330Z
  - 原始模型：SD 1.5
  - 下载数：429
  - 评分人数：0
  - 评分：0
- 下载地址
  - [inthedark-a1.safetensors](https://civitai.com/api/download/models/84160)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7a02111a-ed70-4e50-8a4e-188674706a9b/width=450/950130.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fceed4bf-8f03-4f3e-909e-ef4499283f5a/width=450/950095.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/386ac5f5-b6e7-44be-8942-002450455a5d/width=450/950086.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/524efc2a-156a-4201-8393-948b8948c573/width=450/950102.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><em>The world ended, a long time ago. The sun cracked, the gates of death broke, and the earth became a cursed world. Still, humanity survives. Stuck in the crowded slums of the lightning-caged cities, your only hope for a decent life is to seize it for yourself. By blade or bullet; by a charming word or occult incantation: you will take this city or die trying, your broken body lying in the dark.</em><br /></p><p><strong><u>Update 23/6/13:</u></strong></p><p>A smaller update. I fixed captioning issues and stretched out the dataset a bit. The biggest changes were from hyper-parameter optimization, so the model is both smaller and more true to the original style at high weights (with the right checkpoint of course). <br /><br /><strong><u>Update 23/5/30:</u></strong><br />I fixed a lot of issues, especially with the captioning. The model can now reproduce the original style at higher weights, and is overall more flexible. I will need to do more testing and figure out some way to expand the dataset before publishing a final version, but this update should be a major improvement.<br /><br />Notes:</p><ul><li><p>The trigger world <strong>bitdstyle </strong>is now impactful.</p></li><li><p>The recommended weights are lower. 0.6 - 0.8 should work well, although higher weights may give you interesting effects.</p></li><li><p>The monochrome effect has been somewhat disentangled from the general style, but you can guarantee it by adding "monochrome" to the prompt.</p></li></ul><p><br /><strong><u>Original Post 23/5/28:</u></strong><br />Hey folks,<br /><br />This model is based on the art of the Blades in the Dark tabletop roleplaying game. This is an alpha release on a limited dataset, but I wanted to try applying the style to anime models. Right now, the LORA feels a bit overtrained in some areas and undertrained in others, but I feel that it offers a cool monochrome style. I decided to release what I have so far and then work on an improved version down the line.<br /><br />This was trained on animefull, so it should have an impact on derived CLIP SKIP 2 models and merges. I tested with and was pretty happy with the results using <a target="_blank" rel="ugc" href="https://civitai.com/models/4468?modelVersionId=57618"><strong>Counterfeit V3</strong></a>. To get the monochrome effect, I recommend a weight of 0.8 - 1.0. There's no explicit trigger word, but using "silhouette" should get you closer to the style.<br /><br />Thanks,<br />Machinique</p>