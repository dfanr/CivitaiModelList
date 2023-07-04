## Row of 35 people POSE , multi view，35个人的动作PNG图，多视图
### 一、模型概述

- 标签：
- 下载数：1286
- 收藏人数：180
- 评论人数：2
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.7

- 统计数据
  - 发布时间：2023-03-25T04:10:27.348Z
  - 原始模型：SD 1.5
  - 下载数：1286
  - 评分人数：1
  - 评分：5
- 下载地址
  - [rowOf35PeoplePOSEMultiView35_v17.zip](https://civitai.com/api/download/models/28686)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/940838d5-e859-4a89-65cc-de26fdd3d800/width=450/323545.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/df3d15ca-2f85-4e2e-aead-0e36d01a5800/width=450/323562.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c5120f22-e304-4834-d58d-15e7f6eab300/width=450/323561.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/23b54e96-d430-4f06-b0b4-4e2d67d85a00/width=450/323560.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>没有什么，就是一排人物的动作骨骼图而已。</p><p>安装CONTRONET，点启动CONTRONET，预处理器选 无，处理模型选OPENPOSE，把这个骨架图拖进去就好。不用什么提示词，可以搭配各种大模型（前提是大模型里有人）。</p><p>35人版本：应该是现在8G显存显卡的pose人数极限了。分辨率最好是1824X1568(8G显存)。快速采样方法:用DPM++ 2M的7步(7Steps)或者用DPM++ SDE Karras的5步(5Steps)。</p><p>12人版本：应该是现在单排的人数极限了。分辨率最好是2048X352，要开面部修复。显卡好的开高清修复(8G显存不够)，快速采样方法:Euler a的7步(7Steps)或者DPM++ SDE Karras的5步(5Steps)</p><p>优点是能显示更多人物，背景变好了。缺点就是分辨率低了，脸变形严重。</p><p>8人版本：分辨率最好是2048X512，要开面部修复。显卡好的开高清修复(8G显存不够)。</p><p>5人版本：使用16:9 图片比例更好 ，1920X1080或 768X432分辨率（开高清修复，低分辨率会有更多样的角色）</p><p>关于采样方法(Sampler)的对比：</p><p>快组：Euler a、Euler、LMS、DPM++ 2M、DPM fast、LMS Karras、DPM++ 2M Karras 这些都是一个速度，比较快但是模糊</p><p>慢组：Heun、DPM2、DPM2 a、DPM++ 2S a、DPM++ SDE、DPM2 Karras、DPM2 a Karras、DPM++ 2S a Karras、DPM++ SDE Karras、DDIM、PLMS</p><p>这些都是一个速度，慢几乎一半，但是清楚一些所以可以少几乎一半的采样迭代步数(Steps)，综合下来也差不多。但是，根据分辨率高低不同，在低步数下有不同的表现。</p><p>这个动作POSE图用于测试各种模型，一张顶很多张~包括正面、背面、侧面、跪势、坐势、曲腿</p><p>35个人的视图。为了微调每个人不同的动作，我渲染了接近1千次。不过不同的模型角度是不同的，出错的就说明这个模型里面没有那个角度。</p><p>just  POSES PNG.</p><p>Install CONTRONET, "ENABLE". select "None" for the preprocessor, select "OPENPOSE" for the model, and drag the PNG into it. GENERATE!</p><p>Without any prompting words, it can match various models</p><p>To fine-tune the different movements of each person, I rendered close to 1,000 times</p><p>Sampler for fast rendering: DPM++ 2M (8Steps) or DPM++ SDE Karras (4Steps)</p><p>Test various models, one top several~including front, back, side, kneeling, sitting, and bent legs</p><p>View of 12 people. If there are many errors, does it mean that the diversity of the model is insufficient?</p><p>35 person version: It should be the limit for the number of poses on 8G graphics cards. The resolution is preferably 1824X1568.Sampler for fast rendering: DPM++ 2M (8Steps) or DPM++ SDE Karras (4Steps)</p><p>12-person version: resolution 2048X352.Due to the reduced resolution, the background of the screen is much better, and the diversity of characters is also increased.Sampler for fast rendering: Euler a(7Steps) or DPM++ SDE Karras(5Steps)</p><p>8-person version: resolution 2048X512. open a 'Restore faces'.If the graphics card is properly opened 'Hires. fix'. The advantage is that it can display more characters. The disadvantage is that the resolution is low and the face is severely deformed</p><p>5-person version: uses a 16:9 image ratio that is better, with 1920 x 1080 or 768 x 432 resolution (with HD repair enabled, there will be more diverse characters at low resolutions)</p><p>View of 35 people. To fine tune the different movements of each person, I rendered close to 1,000 times. However, the angle is different for different models, and an error means that the model does not have that angle inside.</p>