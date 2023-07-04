## Pokemon - Hilda / Touko [SD 1.5 Character LoRA]
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `female`, `woman`, `girls`, `pokemon`, `video game`, `touko`, `hilda`
- 下载数：1788
- 收藏人数：268
- 评论人数：5
- 评分人数：3
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v3

- 统计数据
  - 发布时间：2023-06-28T00:21:47.703Z
  - 原始模型：SD 1.5
  - 下载数：225
  - 评分人数：0
  - 评分：0
- 下载地址
  - [character_pokemon_hilda_v3.safetensors](https://civitai.com/api/download/models/105543)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/836e4f63-0c6a-4463-ba8e-77fa87004ea2/width=450/1314947.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/799d1653-fef6-4c0d-adaa-ffb68e7f401e/width=450/1314948.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/44b2dd9d-0b01-40f2-94b1-9376e1dd2795/width=450/1314946.jpeg" /> |
| ---- | ---- | ---- |

#### [版本2/共3个版本] v2

- 统计数据
  - 发布时间：2023-06-28T00:20:28.473Z
  - 原始模型：SD 1.5
  - 下载数：1039
  - 评分人数：2
  - 评分：5
- 下载地址
  - [character_pokemon_hilda_v2.safetensors](https://civitai.com/api/download/models/28647)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4b125929-87f6-4430-27d1-d14944bc8e00/width=450/323006.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5a8bb358-8a8b-47b5-195c-e3e576174900/width=450/323005.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8c866b4b-0d08-4d15-e3e1-75b1e0fa2600/width=450/323004.jpeg" /> |
| ---- | ---- | ---- |

#### [版本1/共3个版本] v1

- 统计数据
  - 发布时间：2023-06-28T00:20:28.473Z
  - 原始模型：SD 1.5
  - 下载数：524
  - 评分人数：1
  - 评分：5
- 下载地址
  - [character_pokemon_hilda_v1.safetensors](https://civitai.com/api/download/models/27608)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4b44e62c-6d0d-438f-aba9-fa8e906dca00/width=450/304258.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7e8a63fd-c16f-4c69-280e-c5cdfccaec00/width=450/304260.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1c5acf79-c127-457e-2b86-4118abda7d00/width=450/304259.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<p><strong>Please read through the <u>entire</u> description (might need to be expanded) <u>and</u> the version change notes as they cover a lot of information about basic use cases and limitations. The description is always focused on the latest version. Thank you!</strong></p><p></p><p>This is an SD 1.5 LoRA for the character Hilda / Touko from Pokemon.</p><p></p><p>Example images were picked from pure 512x512 txt2img results and then re-created at 1024x1024 using txt2img with moderate Hi-res Fix settings (upscaler Lanczos, denoising strength 0.4). This improves faces and other details that are almost impossible to get correctly and consistently at 512x512 (limitation of the technology) while still giving a realistic impression of what it looks like. Pure 512x512 results will have more distorted faces and less detail.</p><p></p><p>Please see the version change notes for the training and example image generation models as well as the used weights as they might change between versions. Remember that you might need to adjust weights to best suit your use case!</p><p></p><p>Remember to add the tag <strong>hilda \(pokemon\)</strong> (with backslashes intact) to your positive prompt.</p><p></p><p>The training set contained multiple variations of Hilda's signature look so you might need to put combinations of the following tags in your positive or negative prompts to get the desired results:</p><p></p><ul><li><p>baseball cap</p></li><li><p>boots</p></li><li><p>shorts</p></li><li><p>shoulder bag</p></li><li><p>sleeveless shirt</p></li><li><p>socks</p></li><li><p>vest</p></li><li><p>wristband</p></li><li><p>xtransceiver (the wristwatch-like device)</p></li></ul><p></p><p>As the training set contained a few images with floating hair, you might need to add <strong>floating hair</strong> to the negative prompts if not desired.</p><p></p><p>Known Limitations / Problems:</p><ul><li><p>The boots, socks and xtransceiver were not present in a lot of images and not a focus for the training so they sadly will not be consistent.</p></li><li><p>The exposed pockets (or whatever they are) from the shorts are very inconsistent, especially when sitting and from behind (they seem to be mostly missing then).</p><ul><li><p>They will also often affect alternative clothing like panties etc. which will then appear with the same exposed pockets and perhaps even denim material as the shorts. Putting extra weight on both <strong>shorts </strong>in the negative prompts and the alternative clothing in the positive prompts might help but not by a lot.</p></li></ul></li><li><p>Might generate a lot of midriff peeks or similar visible gaps underneath the shirt</p><ul><li><p>Try <strong>midriff peek</strong> and similar tags in the negative prompts</p></li></ul></li><li><p>It seems to be very difficult to remove the sleeveless shirt and vest separately from each other.</p><ul><li><p>Keeping only the vest seems especially difficult and luck-based.</p></li><li><p>Might need additional weight in the negative prompts (but even then it's very inconsistent).</p></li><li><p>Even when it works, the color of e.g. the vest might mix into the sleeveless shirt etc.</p></li></ul></li><li><p>The hair might come out of wrong spots in the baseball cap (or not at all), especially from behind, and is pretty wild and inconsistent in general</p><ul><li><p>Basically, good luck getting the hair to look like you want!</p></li><li><p>To be fair, that is also the case for a lot of regular Hilda art.</p></li></ul></li><li><p>Shots from behind are very inconsistent in general due to extremely limited training data. Might for instance generate wrong hair, not apply poses correctly etc. Not much I can do without a bit more training data.</p></li><li><p>The baseball cap might require additional weight in the negative prompt to remove. Still, it just loves to pop up. How nice!</p></li></ul>