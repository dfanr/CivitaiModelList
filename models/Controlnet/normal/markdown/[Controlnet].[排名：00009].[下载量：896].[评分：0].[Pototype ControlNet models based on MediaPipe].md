## Pototype ControlNet models based on MediaPipe
### 一、模型概述

- 标签：`character`
- 下载数：896
- 收藏人数：288
- 评论人数：25
- 评分人数：0
- 评分：0

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] e11

- 统计数据
  - 发布时间：2023-03-24T08:10:55.859Z
  - 原始模型：SD 1.5
  - 下载数：805
  - 评分人数：0
  - 评分：0
- 下载地址
  - [pototypeControlnet_e11.ckpt](https://civitai.com/api/download/models/19369)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fb6a7541-1cce-455d-1f24-af938cf18000/width=450/203106.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/87e4deca-c924-47b2-3312-8c022ff2f400/width=450/203110.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c6970ee3-0367-490f-6acd-f4f3bff4ab00/width=450/203109.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e10f903b-d020-49f3-ded0-d1cd2df32500/width=450/203108.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] e7

- 统计数据
  - 发布时间：2023-03-24T08:10:55.859Z
  - 原始模型：SD 1.5
  - 下载数：56
  - 评分人数：0
  - 评分：0
- 下载地址
  - [pototypeControlnet_e7.ckpt](https://civitai.com/api/download/models/19370)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/914011cd-90f7-4c4b-fb9d-e07506370400/width=450/203115.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/273359b3-c791-4098-5d56-127cf0502b00/width=450/203114.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ecb947cf-d7e6-4c3f-346d-f37f59a76c00/width=450/203113.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/70f08fe3-e462-4721-e8e5-66a512ff2600/width=450/203112.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] e5

- 统计数据
  - 发布时间：2023-03-24T08:10:55.859Z
  - 原始模型：SD 1.5
  - 下载数：35
  - 评分人数：0
  - 评分：0
- 下载地址
  - [pototypeControlnet_e5.ckpt](https://civitai.com/api/download/models/19371)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/937e24ea-be61-4389-a99f-5b807c2c4f00/width=450/203120.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/95ce8fdd-c187-4c92-8da9-d4d5684b1c00/width=450/203119.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2ec68bd0-35bd-4049-5b47-a30638d7f400/width=450/203118.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a2db557a-24dd-4cb2-603f-9afb888cc700/width=450/203117.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Pototype ControlNet models based on MediaPipe for pose and hands estimation. Higger "e" numer is better estimation but also greater impact on image. You will need external preprocessor available <a target="_blank" rel="ugc" href="https://natakaro.gumroad.com/l/oprmi">here</a>!</p><p>Usage guideline:</p><p>1. Download preprocessor and txt file from <a target="_blank" rel="ugc" href="https://natakaro.gumroad.com/l/oprmi">gumroad</a><br />2. Install requirements - run <code>pip install -r requirements.txt </code>command (in folder where you have downloaded file)<br />3. Prepare folder with images that you want to preprocess<br />4. Run command <code>python preprocess.py -mh -mp -s C:\path\to\your\folder </code>- mh is for hands detection, mp for pose (you can try with just the pose which works great!)<br />5. Inside selected folder will appear detection folder (C:\path\to\your\folder\detection)<br />6. Copy downloaded models (.ckpt files) to ...\stable-diffusion-webui\extensions\sd-webui-controlnet\models<br />7. Inside Automatic1111 GUI select ControlNet enabled, preprocessor to None, one of the downloaded models and put image from earlier detection<br />8. Generate!</p>