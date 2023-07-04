## Hirasawa Seiji (ZenHirasawa) Style Lora
### 一、模型概述

- 标签：`style`, `fate`, `hentai`, `style lora`
- 下载数：1901
- 收藏人数：346
- 评论人数：1
- 评分人数：0
- 评分：0

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v1.000002

- 统计数据
  - 发布时间：2023-06-22T17:40:29.579Z
  - 原始模型：Other
  - 下载数：307
  - 评分人数：0
  - 评分：0
- 下载地址
  - [hizen0620-000028.safetensors](https://civitai.com/api/download/models/101730)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e6c05375-31bd-4b4a-ab0e-3a67dd0425af/width=450/1246849.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/94f342f8-be35-4298-a58b-585b40d83941/width=450/1246851.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3045af46-387b-455f-8f41-b0f09e4692fc/width=450/1246852.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f7acd26b-f1f8-41a0-b4d4-912453c552ba/width=450/1246855.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v1.000001

- 统计数据
  - 发布时间：2023-06-22T17:30:16.025Z
  - 原始模型：Other
  - 下载数：966
  - 评分人数：0
  - 评分：0
- 下载地址
  - [hizen_equaldim_lowlr-000012.safetensors](https://civitai.com/api/download/models/74257)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/364efa6a-c5d9-4391-98ea-d60f439f0cbb/width=450/829854.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/828d2523-7c98-4fd8-ac08-be62f6466258/width=450/829858.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6dd69c72-13ae-446b-a40a-49f247525d9d/width=450/829856.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3b8aa8f1-4405-4fa6-8c61-ff0481778925/width=450/829857.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v1.0

- 统计数据
  - 发布时间：2023-06-22T17:30:16.025Z
  - 原始模型：Other
  - 下载数：628
  - 评分人数：0
  - 评分：0
- 下载地址
  - [hizen-09.safetensors](https://civitai.com/api/download/models/68987)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f1431190-35b4-4dad-82ab-70accd10d2f0/width=450/769726.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/08b5bf94-5dfa-47a7-8e87-8b05ea30e00f/width=450/769728.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6870b2a0-754d-4867-a591-c3761496a2ee/width=450/769729.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/042d58bd-c54a-41a8-994e-d7cb93902d5b/width=450/769730.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Lora trained with Hollowstrawberry's script on 3:4/4:3/1:1 aspects using NAI as base. Dataset pool - 82 images 768px. Generates Morgana, Altria, Lartoria, Lartoria Alter even without tagging them, some artifacts are possible. Definetely overtrained, tends to accurately replicate training image. I prefer using 9th epoch in [0.45; 0.55] weight range on NAI and aom3, didn't test on other models. Lora has no activation words.</p><p>Generated characters will always have sidelocks, even males since there is no lockless person in dataset lol, same goes for steam, unfortunately. Sometimes draws bad hands, so watch out and adjust negatives respectively. Genereates good on euler-a, with Steps 31 and CFG 6-8</p><p>upd:</p><p>changed dim and alpha to 32, added 2 new images to dataset, corrected and cleaned tags, set different lr. looks like some concepts got in as well, for some reason straight-on pov is hard to achieve. 1.0 weight works fine for me, generetes oversize booba, adjust sizes by replacing huge with medium etc.</p>