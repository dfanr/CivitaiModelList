## Ears Down/Sad Ears LORA 
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `ears down`, `girls`
- 下载数：919
- 收藏人数：149
- 评论人数：4
- 评分人数：3
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] EarsDownV1

- 统计数据
  - 发布时间：2023-02-13T05:42:00.980Z
  - 原始模型：SD 1.5
  - 下载数：659
  - 评分人数：2
  - 评分：5
- 下载地址
  - [Ears Down.safetensors](https://civitai.com/api/download/models/9716)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9eacdcc1-f586-4ca6-63d1-1240aa221f00/width=450/96815.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0f7ce0d9-1433-41b1-78df-fe715c031e00/width=450/96814.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ecb76829-9608-46d7-7984-f5e733514d00/width=450/96813.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f3e733fb-c02a-4ed2-382a-3a5c395e8600/width=450/96812.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] EarsDownV2

- 统计数据
  - 发布时间：2023-02-13T05:42:00.980Z
  - 原始模型：SD 1.5
  - 下载数：120
  - 评分人数：0
  - 评分：0
- 下载地址
  - [Ears Down V2.safetensors](https://civitai.com/api/download/models/9717)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4cd5d35f-f431-41ce-334f-b0762d69d800/width=450/96825.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a1786d23-4b90-4972-652e-21b39e9ee200/width=450/96824.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8b245c90-cf87-4892-5ec9-80b1d9890f00/width=450/96821.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0e1766e8-c597-41ac-fbec-cca244a07200/width=450/96820.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] EarsdownV3

- 统计数据
  - 发布时间：2023-02-13T05:42:00.980Z
  - 原始模型：SD 1.5
  - 下载数：140
  - 评分人数：1
  - 评分：5
- 下载地址
  - [Ears Down V3.safetensors](https://civitai.com/api/download/models/9718)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8e670866-4f74-4696-a03d-2ddb7ca18300/width=450/94085.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/746ebd73-6514-413c-0dd6-3717605c7600/width=450/96836.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cc8a1708-6705-4753-3377-afa3dee1a300/width=450/96835.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c7a08736-8d36-4b90-68d7-d1d814c88400/width=450/96834.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Another thing the AI doesn't seem to be able to reproduce is animal ears in a down position, so once again, I have gone ahead and made a lora for that too. It should work on bunny girls, cat girls, and fox girls. Wolf ears in a down position bear resemblance to that of fox ears so I didn't bother training on those.</p><p>As a bonus, because I was curious at the time, and since it seemed unachievable through my own tests with prompting, giving girls bat ears is also possible with this LORA. Results sort of vary, however.</p><p></p><p>Generally speaking, the LORA does as asked. It's cons come in the form of sometimes giving girls double pairs of animal ears, asymmetrical or uneven ears, two mismatched ears, or just giving one ear. Rabbit ears can come out kind of scuffed too sometimes, maybe because I mixed in images with both bunny ears and rabbit ears tags, which can be two different things according to danbooru😅.</p><p></p><p>I trained three different versions in my attempts to make this LORA better:</p><p>V1: This version works but is also prone to frying or messing up images when combined with other LORAs sometimes. Regarding rabbit ears, it seems this version provided more correct results than V2 and 3. Take that with a grain of salt though.</p><p></p><p>V2: Trained for less time using the same dataset. Easier to mix with other LORAs.</p><p></p><p>V3: Trained on a slightly different dataset for nearly the same amount of time as V1. Should improve on fox/wolf ears looking more like Yae Miko's or Sucrose's ears (Genshin Impact), whereas V1 and 2 tend to make them look similar to cat ears sometimes. This version may also be worse(...?) with rabbit ears. The amount of images for fox ears was increased so I'm not sure if that diminished the effect of rabbit ears. Should still be able to mix with other LORAs.</p><p></p><h3>Note On Bat Ears:</h3><p>Each version is capable of producing bat ears, however, it seems to be a hit or miss. Sometimes it gets it right, other times it suffers from the following issues:</p><p></p><ul><li><p>Generating other ears instead</p></li><li><p>Generating both bat and fox ears (can look nice sometimes, see previews)</p></li><li><p>Simply doing nothing at all</p></li></ul><p></p><p>Naturally, it will try to add bat wings and bats into the picture too so add those to the negatives if you don't want that. Just be aware that might make it harder to get them at all.</p><p></p><p>Trained on a collection of 120-140 images by V3, each version for separate amounts of time. Extensively tested across multiple models. Tokens are the same for all versions.</p><p><strong>Images in preview are varying results from all three models! Make sure to use the right one if trying to replicate!</strong></p>