## LamiaDiffusion
### 一、模型概述

- 标签：`anime`, `girl`, `fantasy`
- 下载数：867
- 收藏人数：177
- 评论人数：1
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] V1

- 统计数据
  - 发布时间：2023-03-03T22:52:09.617Z
  - 原始模型：SD 1.5
  - 下载数：867
  - 评分人数：1
  - 评分：5
- 下载地址
  - [LamiaX-000006.safetensors](https://civitai.com/api/download/models/18198)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b94b84d4-9372-4f69-08d2-4736ad88e800/width=450/187161.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c4151e8a-bf7b-499c-bd83-ca04e8c7fd00/width=450/187175.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/abd437a1-b066-4592-5636-03b752982d00/width=450/187174.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8b44d6c2-127c-4eca-a471-f71394a33c00/width=450/187173.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is my latest and only published attempt at making lamia lora. Trained on 110 512x512 lamia pictures with manual tagging. The model however seems to best work when height is incrased to around 512x808 or higher. Using 512x512 resolution often causes distorted faces.</p><p></p><p>All of the images were tagged with "lamia", but reoccuring traits like popular tail colors (blue,red,green,white and purple) and hair colors were also tagged. Many characters also had tops, dresses or kimonos and those were also tagged. I also tagged reoccuring characters with tags miia and jasmin-chan but the lora seems not fit for making accurate art of these characters. I also tagged "tongue", but it seems like the lora is not good at those.</p><p></p><p>Out of the models I tested the winner was abyssOrangeMix2_Hard. All of the generations had their negative promt set as "bad-artist". If you want to get this embedding it should be the one downloadable here: <a target="_blank" rel="ugc" href="https://huggingface.co/nick-x-hacker/bad-artist">https://huggingface.co/nick-x-hacker/bad-artist</a></p><p></p><p>I also want to thank <a target="_blank" rel="ugc" href="https://github.com/Snowad14/BatchPrompter">https://github.com/Snowad14/BatchPrompter</a> for assisting at tagging the pictures used in training.</p><p></p><p>If you want to help improve this lora you can contact me. I also have versions that were trained more epochs but this seemed to make the overall quality worse. This lora was trained on batch size of 2 and 6 epochs (5 steps per image).The other loras I have are 3,9,12 and 15 epoch versions.</p>