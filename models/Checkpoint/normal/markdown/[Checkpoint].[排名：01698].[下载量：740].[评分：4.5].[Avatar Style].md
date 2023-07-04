## Avatar Style
### 一、模型概述

- 标签：`na'vi`, `avatar`, `style`
- 下载数：740
- 收藏人数：151
- 评论人数：18
- 评分人数：4
- 评分：4.5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] V1

- 统计数据
  - 发布时间：2023-02-18T10:14:06.981Z
  - 原始模型：SD 1.5
  - 下载数：637
  - 评分人数：4
  - 评分：4.5
- 下载地址
  - [avatarStyle_v1.ckpt](https://civitai.com/api/download/models/11851)
  - [avatarStyle_v1.yaml](https://civitai.com/api/download/models/11851?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/52d651aa-f662-436f-538d-c2abcd08f500/width=450/113264.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4b1692ef-3513-4144-d767-e0e522d49400/width=450/113277.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0ef4f032-a32a-4a49-e858-318dd7f78200/width=450/113276.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/37824a96-8f71-4616-5d96-1a0812f29100/width=450/113275.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] V1-Alt

- 统计数据
  - 发布时间：2023-02-18T10:14:06.981Z
  - 原始模型：SD 1.5
  - 下载数：60
  - 评分人数：0
  - 评分：0
- 下载地址
  - [avatarStyle_v1Alt.ckpt](https://civitai.com/api/download/models/11852)
  - [avatarStyle_v1Alt.yaml](https://civitai.com/api/download/models/11852?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c561654e-ce50-4de5-4072-32d0ce373100/width=450/113291.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/808a332e-0453-41bc-ee6d-4b71c57b8500/width=450/113290.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d78bcd7a-3832-4d13-4d95-ae84830c0c00/width=450/113289.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/799d12cb-9213-43f9-bc94-f4bf12398100/width=450/113288.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] V0.4

- 统计数据
  - 发布时间：2023-02-18T10:14:06.981Z
  - 原始模型：SD 1.5
  - 下载数：43
  - 评分人数：0
  - 评分：0
- 下载地址
  - [avatarStyle_v04.ckpt](https://civitai.com/api/download/models/11870)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/68110cdb-7e67-47f0-1d86-17ea5186ca00/width=450/113459.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/79e84aca-50fc-4d76-d38d-9a53719af200/width=450/113458.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4de034ac-0f2e-451f-d1b8-c3e24577b800/width=450/113457.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e1fdce6d-5631-493c-3795-0992d47d6a00/width=450/113456.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>A model trained on 67 images of different Na'vi faces from James Cameron's Avatar (2009), concept art and some statues. The V1 was trained for a total of 13,600 steps using a constant 1e-6 LR, while the V1-Alt was trained for a total of 20,400 steps. Both were trained using DDIM scheduler with captioned images and no class images. Using batch size of 2.<br /><br />Recommended to not use a VAE. Tho it's your choice if you wish to do so.<br /><br /><strong>Add Your Face: </strong>To add yourself you can easily train your face with Dreambooth using either the V1 or V1-Alt as the base model. Alternatively you can try doing inpainting or img2img using your images, tho the results may vary.<br /><br /><strong>Differences: </strong>V1 is good at some stuff and V1-Alt is good at other stuff. No particular preference just an alternative that was trained for 20,400 steps. As for V0.4 well, it does some good portraits so i thought why not give more options?<br /><br /><strong>Words: </strong>You may use emotions such as <code>(angry, sad, smile, crying, etc.)</code><br /><br />For hair control you may do whatever you want, it wasn't trained on a specific style but you can use <code>(braided hair, short hair, short mohawk, lose medium hair and side braids)</code><br /><br />For clothing options there are <code>(tribal clothing, military vest, military choker, loincloth, feathers on hair, brown top and tattoos)</code><br /><br />For the tail just do <code>tail</code>, but it has a lot of issues.<br /><br />You may use any clothing you want like a red dress or etc. <br /><br /><strong>Example prompt:</strong><br /><br />Positive: <code>(Avatar style), woman, cyberpunk</code><br /><br />Negative: <code>cross-eyed, (three hands, three feet, three arms, three legs, text bubble,no pupils), ((bad anatomy, deformed face)), undefined, incomplete, uncertain, smudge, melt, smear, disproportional, disfigured, deformed, malformed, mutant, monstrous, ugly, gross, disgusting, blurry, poorly drawn, extra limbs, extra fingers, missing limbs, amputee, malformed hands</code>|</p><p><br />Euler_a: <code>20 steps</code><br />cfg scale: <code>4</code><br />Seed: <code>3215741427</code><br />Dimensions: <code>512x640</code><br /><br />Alt Negative: <code>blurry, out of focus, depth of field, poorly drawn eyes, saturated, color burn, overly saturated colors</code><br /><br /><strong><em>Recommended to use 35 steps and HIGHLY recommend to use cfg scale 4.</em></strong><br /><br /><strong>Usage:</strong> You can do <code>boy, girl, old man, old woman, man, woman, teen boy</code><br /><br />Best to use Clip Skip 1, but you can also do Clip 2.<br /><br /><strong>Keyword:</strong> <code>Avatar Style</code> or <code>(Avatar style)</code><br /><br /><strong>Upscaling:</strong> I highly suggest to upscale using img2img or high-res fix using 2x or even 2.5x upscale at 0.6 denoise or 0.5. Recommend 35 steps. This will improve the face, body etc.<br />Currently if you generate at 512x512 the faces might be okay but if you upscale they can be better.<br /><br /><strong>Last minute info:</strong> For Metkayina, they aren't currently in this model. I am waiting for the Blu-ray release of the movie to come out so i can train them using the best possible quality.<br /><br /><strong>Foreseeable Future:</strong> I might also release a Pandora landscape model soon, currently it's WIP but it has produced some nice images. Still working on neytiri V3 tho. Don't have a specific date for that one yet.<br /><br /><strong>NOTE</strong>:<br />This model can produce NSFW content if you so wish but this model was trained for mainly SFW in mind. Also There are issues with the tails, i tried my best to improve it but i can only do so much. So if you encounter issues with the tails... sorry.</p>