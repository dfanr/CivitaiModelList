## 🛠️ Forge - Negatives & Helpers (1.5 & 2.1)
### 一、模型概述

- 标签：`negative embedding`, `helper`, `tool`
- 下载数：6636
- 收藏人数：610
- 评论人数：14
- 评分人数：1
- 评分：5

### 二、下载地址（共4个版本）

#### [版本4/共4个版本] 2.1 - Neg - General 1.0

- 统计数据
  - 发布时间：2023-04-26T10:35:18.723Z
  - 原始模型：SD 2.1 768
  - 下载数：3447
  - 评分人数：0
  - 评分：0
- 下载地址
  - [rz-neg-general.pt](https://civitai.com/api/download/models/18190)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e3d8f41a-823f-42c4-d74b-e568b07d4a00/width=450/187080.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d2d7358e-ba1b-44bd-c389-f8e4d331dc00/width=450/187086.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d14e0cf2-d3c4-4033-5cad-2d4170737600/width=450/187081.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6f9dd746-0780-4d84-cf44-35fc6bbc2c00/width=450/187085.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本3/共4个版本] 2.1 - Neg - Contrast 1.0

- 统计数据
  - 发布时间：2023-04-26T10:35:18.723Z
  - 原始模型：SD 2.1 768
  - 下载数：618
  - 评分人数：0
  - 评分：0
- 下载地址
  - [rz-neg-forbettercontrast.pt](https://civitai.com/api/download/models/55806)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/18a3f9d5-d171-495d-ac67-f19f02524400/width=450/604596.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3751e357-3fb3-4dc6-e62a-000239293c00/width=450/604594.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/595cd3dc-158b-4c6c-9fdc-2d85bc432e00/width=450/604597.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/06fbbd8e-50f8-466e-be43-6cdc9becd600/width=450/604598.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共4个版本] 2.1 - Neg - ForAnalog 1.0

- 统计数据
  - 发布时间：2023-04-26T10:35:18.723Z
  - 原始模型：SD 2.1 768
  - 下载数：1057
  - 评分人数：0
  - 评分：0
- 下载地址
  - [rz-neg-foranalogportrait.pt](https://civitai.com/api/download/models/20885)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8793e2c1-573a-49d4-5b1c-1c7038fd6c00/width=450/221535.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6d676a67-f807-4dec-c384-3aacda8fae00/width=450/221534.jpeg" /> |
| ---- | ---- |

#### [版本1/共4个版本] 1.5 - Neg - ForAnalog 1.0

- 统计数据
  - 发布时间：2023-04-26T10:35:18.723Z
  - 原始模型：SD 1.5
  - 下载数：1514
  - 评分人数：1
  - 评分：5
- 下载地址
  - [rz-neg-15-foranalog.pt](https://civitai.com/api/download/models/24385)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1ad69fa6-49dd-41e9-99c6-c58438599e00/width=450/265412.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/de8c16b6-45f1-4e0d-7492-40cb0ae51d00/width=450/265411.jpeg" /> |
| ---- | ---- |


### 三、详情
<p>See versioning below for 1.5</p><p></p><p>Summary :</p><p></p><p><strong>Negative - General //</strong> Pruning most of "bad things" in the average standart</p><p>Not suitable for <strong>natural </strong>realistic portrait</p><p></p><p><strong>Negative - ForAnalog</strong> // Heavy pruning of everything related to digital, painting, 3d, artwork and so on</p><p>Not suitable if you want painting and vivid colors</p><p></p><p><strong>Negative - Contrast &amp; scenic</strong> // Pruning of contrasts antagonists</p><p>not suitable for classical painting, minimalism or other movements of that kind</p><p></p><p>The pruning of contrast's antagonist may fix weird body / situations behaviour (sometimes) even if it don't include any body face fix at all</p><p></p><h2>Negative - General 2.1</h2><p>All plots (grids) was generated on <strong>v2-1_768-nonema-pruned</strong> <em>4711ff4dd2</em></p><p>If you are getting the error <em>"Textual inversion embeddings skipped(3): rz-neg-general", it's because you are on a wrong StableDiffusion version (</em><strong>2-x required)</strong></p><p></p><p>This negative embedding is suitable for everything, enhanced faces details and coherence, better colours, less blurry generations.unwanted paintings. More realistic overall.</p><p>If you wants generations more concept art oriented please <strong>emphasis down</strong> the negative</p><p></p><p>Samples :<br /></p><p>A photo of a beautiful woman medium shot with long hairs</p><p>Negative prompt: <strong>rz-neg-general</strong></p><p>Steps: 40, Sampler: Euler a, CFG scale: 8, Seed: 2001, Size: 768x768</p><p><br /></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3248ed56-0229-4be8-ea9f-bb75fe78af00/width=525/3248ed56-0229-4be8-ea9f-bb75fe78af00" /><p></p><p><em>A photo of an handsome man</em></p><p>Negative prompt: <strong>rz-neg-general</strong></p><p>Steps: 40, Sampler: Euler a, CFG scale: 8, Seed: 2001, Size: 768x768</p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5eb1a983-b57f-4c52-dd21-96af1f2cb700/width=525/5eb1a983-b57f-4c52-dd21-96af1f2cb700" /><p></p><p><em>A beautiful woman wearing a cyberpunk outfit by Ilya Kuvshinov, krenz cushart, Greg Rutkowski, trending on pixiv, a beautiful highly detailed digital painting</em></p><p>Negative prompt: <strong>rz-neg-general</strong></p><p>Steps: 25, Sampler: DPM++ SDE Karras, CFG scale: 8, Seed: 2001, Size: 768x768</p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f48c4500-2f5f-4345-5b1a-0de267dcc300/width=525/f48c4500-2f5f-4345-5b1a-0de267dcc300" /><p></p><p><em>A sophisticated restaurant room with large window with view to a midcentury cozy kitchen, well maintained, clean, medieval, fantasy genre, natural light, fantasy, natural light, concept art, by greg rutkowski and craig mullins, cozy atmospheric and cinematic lighting, trending on artstation</em></p><p>Negative prompt: <strong>rz-neg-general</strong></p><p>Steps: 20, Sampler: DPM++ SDE Karras, CFG scale: 8, Seed: 2001, Size: 768x768</p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7ca90ac5-62f3-4dcf-81d6-ff17d191b400/width=525/7ca90ac5-62f3-4dcf-81d6-ff17d191b400" /><p></p><p><em>A picture of a classy retro car parked in paris, baroque, trending on artstation</em></p><p>Negative prompt: <strong>rz-neg-general</strong></p><p>Steps: 35, Sampler: Euler a, CFG scale: 7, Seed: 2001, Size: 768x768</p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/89949616-7b5d-421f-eeaf-0c5cbf609800/width=525/89949616-7b5d-421f-eeaf-0c5cbf609800" /><p></p><h2>Negative - ForAnalogPortrait 2.1</h2><p>There is no body / face modification for the tokenizer, only a careful pruning.</p><p>(no vae loaded for thoses generation, raw 2.1 768)</p><p></p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/038571fb-68eb-449d-9bbe-ed27c3e96000/width=525/038571fb-68eb-449d-9bbe-ed27c3e96000" /><p></p><p>A photo of a beautiful woman in paris, medium shot, detailed face, cinestill800t, analog</p><p>Negative prompt: <strong>rz-neg-foranalogportrait</strong></p><p>Steps: 20, Sampler: DPM++ SDE Karras, CFG scale: 8, Seed: 3002, Size: 768x768</p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4af4c79e-de6f-4558-cd3f-33a479ee2400/width=525/4af4c79e-de6f-4558-cd3f-33a479ee2400" /><p></p><p><em>A photo portrait of an handsome man at the beach, medium shot,bokeh, detailed face, cinestill800t, analog</em><br />Negative prompt: <strong>rz-neg-foranalogportrait</strong><br />Steps: 20, Sampler: DPM++ SDE Karras, CFG scale: 8, Seed: 3002, Size: 768x768</p><p></p><h2>Negative - ForAnalog 1.5</h2><p>All plots (grids) was generated on Model hash: <strong>cc6cb27103</strong>, Model: <strong>v1-5-pruned-emaonly</strong></p><p></p><p>There is no body / face modification for the tokenizer, only a careful pruning. Body and face modification tokens greatly reduce the overall analog feel, so take care if you need to add them and don't want to lose a lot of details.</p><p></p><p><em>An analog photo of a beautiful young woman portrait with a detailed face, cinestill800t, cute<br />Negative prompt: rz-neg-15-foranalog<br />Steps: 20, Sampler: DPM++ SDE Karras, CFG scale: 7, Seed: 75824, Size: 512x512, Model hash: cc6cb27103, Model: v1-5-pruned-emaonly</em></p><p><br /></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2c46a3a1-b3de-4337-fb18-94f445359500/width=525/2c46a3a1-b3de-4337-fb18-94f445359500" /><p></p><p><a target="_blank" rel="ugc" href="http://romerorz.art"><strong>romerorz.art</strong></a> - <a target="_blank" rel="ugc" href="https://twitter.com/romero_erzede"><strong>Twitter </strong></a>- <a target="_blank" rel="ugc" href="https://www.deviantart.com/romerorz"><strong>DeviantArt</strong></a> - <a target="_blank" rel="ugc" href="https://romerorz.gumroad.com/"><strong>Gumroad</strong></a></p>