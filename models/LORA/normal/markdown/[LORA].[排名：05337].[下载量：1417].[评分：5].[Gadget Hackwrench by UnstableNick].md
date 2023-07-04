## Gadget Hackwrench by UnstableNick
### 一、模型概述

- 标签：`character`, `girl`, `disney`, `female`, `cartoon character`, `anthro`, `furry`, `cartoon`, `gadget hackwrench`
- 下载数：1417
- 收藏人数：230
- 评论人数：0
- 评分人数：1
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-05-27T15:02:28.642Z
  - 原始模型：Other
  - 下载数：814
  - 评分人数：0
  - 评分：0
- 下载地址
  - [gadget_hackwrench_by_UnstableNick_v10.safetensors](https://civitai.com/api/download/models/82785)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/821cad43-fbe2-4f1a-8a7d-d7bfb4c68451/width=450/932338.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d77c48cb-ff19-4a68-81f1-139b2e929f12/width=450/932787.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8416b7fb-d6e9-4c2f-8620-c515950ee1f6/width=450/932343.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f954fe4e-4962-4cec-a83c-d4c400ca17b1/width=450/932344.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v0.1

- 统计数据
  - 发布时间：2023-05-27T14:17:33.992Z
  - 原始模型：Other
  - 下载数：603
  - 评分人数：1
  - 评分：5
- 下载地址
  - [gadget_hackwrench.safetensors](https://civitai.com/api/download/models/27866)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/379dad8c-4c05-4bfc-bce0-72984552d300/width=450/312950.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8012ff87-6c2f-4760-b9ab-416effdf0f00/width=450/312958.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e8e6bd11-3a48-444b-9d60-94bde1d12d00/width=450/312957.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9f621788-d9f7-42a6-4875-1f454a2f8200/width=450/312956.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>LoRA for Gadget Hackwrench, character from "Chip 'n Dale: Rescue Rangers". Can produce both SFW and NSFW images, works with other LoRAs.</p><h2 id="v10">V1.0:</h2><p>Retrained with more screenshots from the show, face looks much better. However, <strong>gh_clothes</strong> is weaker and seems to not work with other characters anymore. New trigger added, <strong>gh_original</strong>, to make the style closer to original, but it doesn't seem to have much impact neather.</p><p>It works best with <a target="_blank" rel="ugc" href="https://civitai.com/models/7371/rev-animated">revAnimated</a> and anime models (AOM, <a target="_blank" rel="ugc" href="https://civitai.com/models/9409/anything-v5-or-anything-diffusion-original">Anything v5</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/4855/anythingelse-v4">AnythingElse v4</a>, Meina, GrapefruitMix, etc.). Works surprisingly bad with furry models.</p><h3 id="tips">Tips:</h3><ol><li><p>Use with weights <strong>0.8 - 1.0 </strong>for more cartoonish look. Also add <strong>gh_original, simple style, cartoon style, anime </strong>to prompt and <strong>realism, realistic, photo, 3d render</strong> to negatives.</p></li><li><p>Use with weights <strong>0.6 - 0.8 </strong>for more stylized look (depending on the used model) and more flexibility.</p></li><li><p>If the facial features are lacking, add <strong>mouse ears, snout</strong> to prompt (this happens sometimes with lower weights). Also, sometimes adding <strong>colored skin</strong> to negative can be useful.</p></li></ol><p></p><h2 id="v01">V0.1:</h2><p>Trained on <a target="_blank" rel="ugc" href="https://civitai.com/models/4449/abyssorangemix2-nsfw">AOM</a>, also works with <a target="_blank" rel="ugc" href="https://civitai.com/models/66/anything-v3">Anything</a> and <a target="_blank" rel="ugc" href="https://civitai.com/models/4698/lawlass-yiff-mix">Lawlas</a>. My first LoRA, so it can have some troubles, like generating tail. I suggest generating a smaller image and using highres.fix/img2img. All example images are generated in one run though.</p><h3 id="tips">Tips:</h3><ol><li><p>To generate classic outfit, use <strong>gh_clothes, jumpsuit, long sleeves</strong>. Can also be used on other characters.</p></li><li><p><strong>gh_goggles </strong>works <em>sometimes. </em>Better use with <strong>goggles, goggles on head</strong>, or add to negative.</p></li><li><p>Lawlas's mix most of the time generates wolf-like faces, use <strong>wolf, canine, fox, dog</strong> for negative.</p></li></ol>