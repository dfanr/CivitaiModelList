## Yaoi Diffusion
### 一、模型概述

- 标签：`anime`, `gay`, `bara`, `art`, `traditional`, `style`, `furry`, `male`, `man`, `realistic`, `comic`, `artists`, `manly`
- 下载数：764
- 收藏人数：132
- 评论人数：3
- 评分人数：1
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v1.0

- 统计数据
  - 发布时间：2023-04-23T03:49:08.290Z
  - 原始模型：SD 1.5
  - 下载数：701
  - 评分人数：1
  - 评分：5
- 下载地址
  - [yaoiDiffusion_v10.ckpt](https://civitai.com/api/download/models/41998)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/015f43fe-897c-4a56-aae5-19d33c5eda00/width=450/462528.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9d3cb704-d7b7-455e-fbbd-de8afe32ea00/width=450/462529.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7c199754-41c9-4f42-d591-232828beed00/width=450/462527.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dd40bdf8-e523-427b-0431-c01bd1a06800/width=450/462627.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v1.0 noise_offset

- 统计数据
  - 发布时间：2023-04-23T03:53:24.159Z
  - 原始模型：SD 1.5
  - 下载数：33
  - 评分人数：0
  - 评分：0
- 下载地址
  - [yaoiDiffusion_v10NoiseOffset.ckpt](https://civitai.com/api/download/models/52901)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c7a5e6d5-e6cd-4def-569c-93c9ebdaf500/width=450/570924.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2c122bc7-0f69-4d6e-44be-7a6104508600/width=450/570925.jpeg" /> |
| ---- | ---- |

#### [版本1/共3个版本] v0.0

- 统计数据
  - 发布时间：2023-04-23T03:49:08.290Z
  - 原始模型：SD 1.5
  - 下载数：30
  - 评分人数：0
  - 评分：0
- 下载地址
  - [yaoiDiffusion_v00.ckpt](https://civitai.com/api/download/models/52917)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ec4a3dab-ea1b-49e1-f4e1-2b998146dc00/width=450/571036.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/08c01f04-a6e6-448c-a852-ace28344cf00/width=450/571037.jpeg" /> |
| ---- | ---- |


### 三、详情
<p><strong>Yaoi Diffusion V1</strong></p><p><br />768 resolution model finetuned on yaoi, bara, furry, s....<strong>,</strong> s.... c.., fine arts and reallife males, in short a general homoerotic model.<br />I've seen people finetuning LORAs of artists, so may as well upload a model that has lots of them, here the list of tags that can recognize<br /><a target="_blank" rel="ugc" href="https://pastebin.com/XNHPxYdA">https://pastebin.com/XNHPxYdA</a><br />There's a version trained with noise offset if you like images with lots of contrast, that version doesn't have synthetic tags though.<br /><br /><strong>HOW TO PROMPT:</strong><br /></p><p>[short description] by [artist]. [e621/gelbooru tags separated by comma and space].<br /><br />ex: <br />An anthro furry dragon male laying on bed by iszotic. solo, pectorals, penis, realistic.</p><p>Also check out the demo images with the prompts used</p><p><br /><strong>Features:</strong></p><ul><li><p>over 900 artists tags of homoerotic artists (including myself, lol), no tags where used for pure 3D artists.</p></li><li><p>NSFW and SFW</p></li><li><p>(optional) unique synthetic tags to play with, these goes at the end of the sentence:</p><ul><li><p>lightness: highmean, lowmean</p></li><li><p>contrast: highstd, lowstd</p></li><li><p>sharpness: highacutance, lowacutance</p></li><li><p>saturation: highsat, lowsat</p></li><li><p>details: highrand, lowrand</p><p></p></li></ul></li></ul><p><strong>Training details:</strong></p><p>Trained from a merge of NAI and yiffye18 at 0.5, with 45k of target images and 40k of misc images, batch size of 256 in everydream2 trainer, bucketing, with dropout of 0.04, zero frequency ratio of 0.0, lr: 1.25e-5 for 8 epochs, then linear decay another 8 epochs to 4e-6.<br />Synthetic tags are calculated as taking the 2.5% of the lowest and highest of each category, lightness is the mean, contrast is the standard deviation, sharpness is the mean of applying a laplace filter, and details uses this function skimage.restoration.estimate_sigma. Captioning of gay images was done with BLIP interrogator and deepdanbooru with e621 and wd14-vit models, misc images are from google, traditional art collections, and LAION. Images below 768x768 resolution where superscaled with Real-ESRGANx4 and below 384x384 where discarded.<br /><br /><strong>TODO:</strong></p><p>Use BLIP2 with <a target="_blank" rel="ugc" href="https://huggingface.co/sentence-transformers/clip-ViT-L-14"><strong>clip-ViT-L-14 </strong></a>in clip-interrogator, new <code>wd14-swinv2-v2</code> model, add more synthetic tags, like cafeaesthetic, resolution, use a lower lr, some images came with borders, remove these. The majority of Images will use the true tags used in 5 booru sites rather than predicted in deepdanbooru, if the same image is available in 2 or more boorus the tags will automatically be merged. Also add mainstream artists like greg, :).<br /><br />I think maybe in 3 months, by August or July I will get the new version, it has too much going on.</p>