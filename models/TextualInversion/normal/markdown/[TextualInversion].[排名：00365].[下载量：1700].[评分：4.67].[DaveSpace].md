## DaveSpace
### 一、模型概述

- 标签：`spaceship`, `science fiction`, `space ship`, `textual inversion`, `style`, `embedding`, `sci fi`
- 下载数：1700
- 收藏人数：239
- 评论人数：1
- 评分人数：3
- 评分：4.67

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] DaveSpaceFour 768x768

- 统计数据
  - 发布时间：2022-12-18T14:25:26.698Z
  - 原始模型：SD 2.0 768
  - 下载数：1512
  - 评分人数：1
  - 评分：4
- 下载地址
  - [DaveSpaceFour.pt](https://civitai.com/api/download/models/1597)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/543654cc-ca4a-4c9c-b7e6-e17abe084100/width=450/14805.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/570bd41f-17a5-4ec0-3b5d-809b97191700/width=450/14804.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5b446a9a-c63d-4bd2-cef4-6b5954e71200/width=450/14803.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/74a15116-fdd1-434f-41e6-c18406b4bb00/width=450/14802.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] DaveSpaceOne 1088x768

- 统计数据
  - 发布时间：2022-12-18T14:25:26.698Z
  - 原始模型：SD 2.0 768
  - 下载数：188
  - 评分人数：2
  - 评分：5
- 下载地址
  - [DaveSpaceOne.pt](https://civitai.com/api/download/models/1502)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4577eed0-1073-4868-d81b-561e83122a00/width=450/13202.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/46ba68c7-f7fc-4ddf-2ee0-46f4e48c5200/width=450/13221.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/71ac9e80-8b48-43b7-5105-ab92a29ab500/width=450/13220.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5a3d903c-81c1-4c18-3375-b91ab2dff200/width=450/13219.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This embed creates space ships, it has a tendency to also create earths/planets so if that is not wanted then neg planets.</p><p>First embed I have created and I am open to advice.</p><p>I trained it on the 768 model of SD 2.0 and the example images are from SD 2.1, the training resolution was 1080x768 (I wanted to go wide-screen given the subject matter but this maxed out my 3090!)</p><p>I have done renders in 768x768 and 1088 x 768.</p><p>To create the training data, I grabbed a load of space ship images and used birme to cut them down to the correct size (this lead to a few ships cut apart, so i may need to find a better method). I then used Lama cleaner to remove text and some of the extra ships in the images (the removal of text means I do not think I can share the training data). I then used automatic1111 to prepare the files by adding comment txt files and by making flipped copies. Once done I went through and corrected each comment file (most of them said station not ship). The embed is set to 5 tokens, though does like to take over the whole image if you use it in a prompt as a style rather than a subject.</p><p><strong>Suggested prompts:</strong></p><p>a <em>DaveSpaceOne</em> landing on the moon</p><p>a <em>DaveSpaceOne</em> seen through a ships window</p><p>a <em>DaveSpaceOne </em>firing rockets at a city on fire, detailed, 8k, hyper realistic</p><p>A lone soldier stares up at a <em>DaveSpaceOne </em>as it flys over firing lasers, hyper detailed, 8k, trending on artstation</p><p>where <em>DaveSpaceOne</em> is the filename of the embed</p><p><strong>To install:</strong></p><p>Download and place it into the embeds folder of automatic1111</p>