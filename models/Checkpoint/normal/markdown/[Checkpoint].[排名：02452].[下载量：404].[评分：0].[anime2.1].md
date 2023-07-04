## anime2.1
### 一、模型概述

- 标签：`style`, `styl`
- 下载数：404
- 收藏人数：135
- 评论人数：1
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.5

- 统计数据
  - 发布时间：2023-05-09T07:51:50.295Z
  - 原始模型：SD 2.1 768
  - 下载数：284
  - 评分人数：0
  - 评分：0
- 下载地址
  - [anime21_v15.yaml](https://civitai.com/api/download/models/66018?type=Config&format=Other)
  - [anime21_v15.safetensors](https://civitai.com/api/download/models/66018)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3e4d2732-ccb7-4aea-80d4-4e39aa0dd29d/width=450/733803.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/100d4877-d4f4-4240-a4aa-d84d6c9c92b6/width=450/733813.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fdf19d93-a450-4b38-92f4-819838fc4818/width=450/733808.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/88d8ffd5-9e49-47d4-b425-78ef96f237a6/width=450/733810.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-05-09T07:53:01.441Z
  - 原始模型：SD 2.1 768
  - 下载数：120
  - 评分人数：0
  - 评分：0
- 下载地址
  - [anime21_v10.safetensors](https://civitai.com/api/download/models/63242)
  - [anime21_v10.yaml](https://civitai.com/api/download/models/63242?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5edd0cb6-340e-4a55-bff5-d012a832d8b9/width=450/708683.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/78c6b975-0020-414b-9c06-974d875cc93a/width=450/700650.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5b442ab0-9225-4a3b-964a-ad1e767cbd55/width=450/700649.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/795448c6-6ebe-4e97-b5a8-aeda3cd2c7bd/width=450/708380.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<ul><li><p>现在来到了200w steps loss曲线仍在降低虽然很慢,同时我的偏置噪声似乎设定的有些高了.初始Noise offset 0.05.从画面图像来看有部分颜色有些失真或溢出..比如绿色（。也许有人能用lora合并来修复画面问题。</p><p>(在sd2.1的fintune模型上lora好像泛用性较低,也许需要在该模型上训练的才会有效果）我尝试了一个sd2.1的lora发现对画面没有起效，不知道原因在哪</p></li><li><p>Now we have reached 200w steps. The curve loss is still decreasing, though very slowly. Meanwhile, my bias noise seems to have been set too high. Initial Noise offset 0.05. Judging from the image, some colors are distorted or overflow.. For example, green (. Maybe someone can fix the graphics with lora merge.</p><p>(lora seems to be less general on sd2.1 fintune model, maybe it needs to be trained on that model to be effective) I tried an sd2.1 lora and found it didn't work on the screen, I don't know why</p></li><li><p>这个模型在3.1w张niji图像训练了200个gpu小时合计120w steps。但是loss任未收敛至合适范围.同时由于训练文本倾向原因导致模型短语理解能力失调.可能需要重新调整.也就是说这个模型不能通过简单的1girl出图.有兴趣的人可以在上面继续做微调，亦或是能给我提供补充数据集也欢迎联系我</p></li><li><p>This model was trained on 3.1w niji images for 200 gpu hours totaling 120k steps. However, the loss does not converge to the appropriate range. At the same time, the training text tendency causes the dyscomprehension of model phrases. May need to readjust. That is to say, this model cannot be mapped by a simple 1girl. If you are interested, please feel free to contact me for further fine-tuning, or if you can provide me with supplementary data sets</p></li></ul>