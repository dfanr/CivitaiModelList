## Pokemon - Serena (Game) [SD 1.5 Character LoRA]
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `female`, `woman`, `girls`, `pokemon`, `video game`, `serena`
- 下载数：2907
- 收藏人数：478
- 评论人数：15
- 评分人数：9
- 评分：4.89

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v3

- 统计数据
  - 发布时间：2023-06-25T21:41:08.783Z
  - 原始模型：SD 1.5
  - 下载数：360
  - 评分人数：1
  - 评分：5
- 下载地址
  - [character_pokemon_serena_v3.safetensors](https://civitai.com/api/download/models/104094)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d281d53e-2ff0-4a69-be54-ad3b37419481/width=450/1289359.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e41333bf-0e19-4d31-b0cc-aaf1b540612c/width=450/1289361.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cbc4c766-b473-4d59-8577-3fdc8b7fdc5c/width=450/1289360.jpeg" /> |
| ---- | ---- | ---- |

#### [版本2/共3个版本] v2

- 统计数据
  - 发布时间：2023-06-25T21:39:44.949Z
  - 原始模型：SD 1.5
  - 下载数：1770
  - 评分人数：4
  - 评分：5
- 下载地址
  - [character_pokemon_serena_v2.safetensors](https://civitai.com/api/download/models/24849)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/02524862-9c0d-4c43-ac26-edf9f1c2b400/width=450/276529.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ad195557-ef42-496e-0179-6bec31e9ed00/width=450/276528.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d30601a7-ee30-4cf8-d17b-b16fb0a60300/width=450/276527.jpeg" /> |
| ---- | ---- | ---- |

#### [版本1/共3个版本] v1

- 统计数据
  - 发布时间：2023-06-25T21:39:44.949Z
  - 原始模型：SD 1.5
  - 下载数：777
  - 评分人数：4
  - 评分：4.75
- 下载地址
  - [character_pokemon_serena_v1.safetensors](https://civitai.com/api/download/models/19158)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b2c5f284-a6ef-4df5-e734-0df3dfb07b00/width=450/200640.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d37922c7-cdde-4d56-5c07-2db1d3f87d00/width=450/200642.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2f1085cb-78b9-4390-6e30-b9d404d0d100/width=450/200641.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<p><strong>Please read through the <u>entire</u> description (might need to be expanded) <u>and</u> the version change notes as they cover a lot of information about basic use cases and limitations. The description is always focused on the latest version. Thank you!</strong></p><p></p><p>This is an SD 1.5 LoRA for the character Serena from Pokemon.</p><p></p><p>Example images were picked from pure 512x512 txt2img results and then re-created at 1024x1024 using txt2img with moderate Hi-res Fix settings (upscaler Lanczos, denoising strength 0.4). This improves faces and other details that are almost impossible to get correctly and consistently at 512x512 (limitation of the technology) while still giving a realistic impression of what it looks like. Pure 512x512 results will have more distorted faces and less detail.</p><p></p><p>Please see the version change notes for the training and example image generation models as well as the used weights as they might change between versions. Remember that you might need to adjust weights to best suit your use case!</p><p></p><p>Remember to add the tag <strong>serena \(pokemon\)</strong> (with backslashes intact) to your positive prompt.</p><p></p><p>The training set contained multiple variations of Serena's signature look (from the game, <strong>not </strong>the anime, sorry) so you might need to put combinations of the following tags in your positive or negative prompts to get the desired results:</p><p></p><ul><li><p>hat</p></li><li><p>eyewear on headwear</p></li><li><p>sleeveless shirt</p></li><li><p>high-waist skirt</p></li><li><p>thighhighs</p></li><li><p>shoes</p></li><li><p>mega ring</p></li><li><p>shoulder bag</p></li></ul><p></p><p>As the training set contained a few images with floating hair, you might need to add <strong>floating hair</strong> to the negative prompts if not desired.</p><p></p><p>Known Limitations / Problems:</p><ul><li><p>This model is only trained on the game design for Serena, <strong>not </strong>the anime. I'm currently not interested to do the anime design, sorry.</p></li><li><p>The shoes and bag were not present in a lot of images and not a focus for the training so they sadly will not be consistent at all.</p></li><li><p>The face, eyes and mega ring will similarly be very inconsistent because of a lot of different interpretations in the training set, especially for wider shots. The eye color should be specified explicitly in the positive prompts, e.g. <strong>grey eyes</strong>.</p></li><li><p>Depending on the image composition (angle, distance etc.), it might be more or less difficult to remove the hat. Both <strong>hat </strong>and <strong>eyewear on headwear</strong> in the negative prompts and <strong>no headwear</strong> in the positive prompts should help but you still may need some luck.</p></li><li><p>Even with <strong>floating hair</strong> in the negative prompts, it tends to go a bit wild. To be fair, that's true for many images I've seen as well.</p></li><li><p>Shots from behind are very inconsistent due to extremely limited training data. Might for instance generate wrong hair, not apply poses correctly etc. Not much I can do without a bit more training data.</p></li></ul>