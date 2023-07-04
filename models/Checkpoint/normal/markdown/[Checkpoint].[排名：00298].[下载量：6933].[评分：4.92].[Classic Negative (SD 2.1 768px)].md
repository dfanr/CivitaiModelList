## Classic Negative (SD 2.1 768px)
### 一、模型概述

- 标签：`film`, `photorealistic`, `general purpose`, `analog`, `analog style`, `photography`, `photorealism`, `realistic`
- 下载数：6933
- 收藏人数：1620
- 评论人数：35
- 评分人数：12
- 评分：4.92

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] Classic Negative 768px v0.2

- 统计数据
  - 发布时间：2023-02-02T12:13:55.694Z
  - 原始模型：SD 2.1 768
  - 下载数：5784
  - 评分人数：5
  - 评分：5
- 下载地址
  - [classicNegativeSD21_classicNegative768px.ckpt](https://civitai.com/api/download/models/7388)
  - [classicNegativeSD21_classicNegative768px.yaml](https://civitai.com/api/download/models/7388?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/04d107af-7f5e-4e38-00e0-cd319418aa00/width=450/68853.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c3d2b1b4-7923-4bdc-be81-83ee84449e00/width=450/68854.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c455d445-5acd-4d56-3591-c4a21cb88a00/width=450/68851.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d9e30d15-738b-4ca5-d8e2-c94a16f8a400/width=450/68850.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] Classic Negative 768px v0.1

- 统计数据
  - 发布时间：2023-02-02T12:13:55.694Z
  - 原始模型：SD 2.1 768
  - 下载数：1149
  - 评分人数：7
  - 评分：4.86
- 下载地址
  - [classicNegativeSD21_classicNegative768px.ckpt](https://civitai.com/api/download/models/5209)
  - [classicNegativeSD21_classicNegative768px.yaml](https://civitai.com/api/download/models/5209?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f16ac74f-14b9-48e0-373d-e34419f6d500/width=450/39650.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/766574f4-27a4-49de-f3a5-cdd263c98b00/width=450/39649.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2d9a3848-2db2-480c-3fb9-fe9da216ce00/width=450/39648.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c5c13d5c-19c9-4dfa-44b3-164a27cd0800/width=450/39647.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>02 Feb 2023</strong></p><p><strong>Classic Negative (SD 2.1 768px v0.2)</strong></p><p>I finally managed to train an improved version of my original Classic Negative Model for SD 2.1 768.</p><p>The improvements mostly come from better and more accurate captions, as well as a more diverse dataset. I also used some pictures generated with the original version for the training.</p><p>I attached a few comparisons between the default 2.1 model, v0.1 and v0.2 I used for evaluating if it actually improved. Compared to the default model, it offers vastly improved lighting, a more pleasing color palette, better depth of field and composition. Compared to v0.1, it improves further on a smooth depth of field fall of and creates slightly more realistic images. The colors are also more in line with what I originally intended.</p><p></p><p><strong>15 Jan 2023</strong></p><p><strong>- Update -</strong></p><p>After several failed attempts, I finally managed to train a usable 2.1 version on the same dataset I used for my 1.5 Classic Negative model. I wish I could show you a more diverse set of pictures, but I'm busy creating one cute animal after the other.</p><ul><li><p>for 2:3 aspect ratio images, 1152x768px works really well</p></li><li><p>for 21:9 aspect ratio images, 1344x576px works really well</p><p></p></li></ul><p>Make sure to place the config file into the same folder as the model and make sure they are named exactly the same.</p><p></p><p><strong>13 Jan 2023</strong></p><p><strong>- Original Post -</strong></p><p>I'll preface this by saying that I have no idea what I'm doing. Also, this is by no means a complete or perfect model. But after many tries I'm at a point where I'm happy with sharing some pictures and an early version for you to try out.</p><p><strong>Classic Negative (SD 1.5)</strong></p><p>With Classic Negative I tried to train a model with DreamBooth which closely mimics my style of photography. Its name comes from a built in camera profile in Fujifilm cameras, "Classic Negative". I use a modified version of this profile in basically all of my photos. To mimic my style, the model must achieve the following:</p><ul><li><p>recreate the color profile of classic negative: muted and desaturated greens</p></li><li><p>introduce faded blacks and diffused highlights (like a Tiffen Glimmerglass Filter would do)</p></li><li><p>reliably create a nice depth of field effect like you would get with large aperture lenses</p></li><li><p>improve the composition of the default model (foreground and background objects, framing, point of view)</p></li><li><p>improve the lighting of the default model</p></li><li><p>add grain and preferably a slight vignetting</p></li><li><p>try to recreate the look and feel of old 35mm film photos</p><p></p></li></ul><p><strong>Training</strong></p><p>For training I used 100 of my personal images, consisting mainly of environmental portraits and photos of my dog, some macro and some landscape shots. The model is probably biased towards forests and garden pictures, since that's where I took the majority of my photos. It seems to be on the verge of being overfitted, in some generated pictures I could clearly make out the general structure of my backyard.</p><p>The captions were written manually for all of the photos. Nothing too complicated, here's an example: <a target="_blank" rel="ugc" href="https://i.imgur.com/prf8VxS.png">https://i.imgur.com/prf8VxS.png</a></p><p>I trained for 1800 steps with a learning rate of 1e-5 and 350 text encoder steps using TheLastBen's Fast DreamBooth ipynb.</p><p></p><p><strong>Prompts &amp; Parameters</strong></p><p>The prompts I tried so far are very simple. The activation token is classicnegative</p><p>- classicnegative photo of a cute raccoon sitting between bushes in a garden, purple tulip flowers</p><p>- classicnegative photo of a cute small red panda sitting on a branch in the jungle</p><p>- classicnegative photo of a white fluffy rabbit standing in a garden illuminated by fairy lights, winter, heavy snow, snowflakes</p><p><strong>Parameters:</strong> Euler A, CFG Scale 7, 30 Steps, 860x360px</p><p>I then went seed hunting. Although in a batch of 4 there was at least one usable picture so far. If a good picture was generated, I set the same seed and ran it again with Hires. fix enabled (which takes like 3,5 minutes with my GTX 1070 for one picture).</p><p><strong>Hires. fix Parameters:</strong> ESRGAN_4x, 30 Steps, 0.3 Denoising, Upscale by 2</p><p>I discovered this by accident, but using these settings the picture stays exactly the same and all the film photo characteristics like the grain won't get lost during upscaling.</p><p>If the effect of the model is too strong, try adding tokens like sharp focus, high contrast, clarity to your prompt. Or just increase the contrast in post. But yes, sometimes it becomes a bit too much, I'll have to take a look into it for a future revision.</p><p></p><p><strong>What's next</strong></p><ul><li><p>more testing is needed, different parameters and subjects</p></li><li><p>create a SD2.1 768px version</p></li><li><p>finetuning</p></li></ul><p>Please feel free to try the model out, test its limitations and if you have any advice on how I can create a better version of it, please let me know ;)</p>