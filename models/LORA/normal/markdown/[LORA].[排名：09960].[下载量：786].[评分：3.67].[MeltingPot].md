## MeltingPot
### 一、模型概述

- 标签：`character`, `sexy`, `black`, `asian`, `indian`, `woman`, `mixed race`
- 下载数：786
- 收藏人数：141
- 评论人数：2
- 评分人数：3
- 评分：3.67

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] 05

- 统计数据
  - 发布时间：2023-06-07T13:39:45.650Z
  - 原始模型：SD 1.5
  - 下载数：239
  - 评分人数：2
  - 评分：3
- 下载地址
  - [MeltingPot05.safetensors](https://civitai.com/api/download/models/91075)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cd37afa6-1078-4692-a868-eb21d1fa05a1/width=450/1061652.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6fc5bc70-2b4a-47a1-bbf9-ce1410c6ce83/width=450/1061653.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2ebc3b9b-25df-4479-bd25-a045633968ac/width=450/1061655.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3cc49ef2-3085-4f77-90bb-4dc5bab03315/width=450/1061656.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] 03

- 统计数据
  - 发布时间：2023-06-07T13:35:28.822Z
  - 原始模型：SD 1.5
  - 下载数：547
  - 评分人数：1
  - 评分：5
- 下载地址
  - [MeltingPot03.safetensors](https://civitai.com/api/download/models/48350)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/731c4187-33aa-442e-41a3-a5f6d915bd00/width=450/519363.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/62034430-44e8-4451-75a9-541ab0b87500/width=450/519336.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c9ba3960-f126-41ae-0c03-9ce2b317e600/width=450/519342.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/40d23b91-9d1a-46e7-ef44-58517ba79700/width=450/519347.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>*Version 05*</strong></p><p><em><span>Use ([white woman::0.xx], [asian woman::0.xx], [indian woman::0.xx], [black woman::0.xx]:1.0) syntax for this version</span></em></p><p></p><p>This LoRA was trained with a mixture of white, black, and asian references in an effort to make a mixed race model with a bit of play to it. My best results have come from keeping the CFG around 4, the steps close to 20, and the weight of the LoRA itself around 0.5.</p><p></p><p>To tweak the weight of each race further (admittedly by default the model leans towards white the most even though that's the race I used the least in training), use the following syntax in your prompt:</p><p></p><p>"photo of nude ([white::0.XX], [asian::0.XX], [black::0.XX] woman:1.0)"</p><p></p><p>Replacing "0.XX" with anything between 0.01 and 0.99; the closer to 0.99 means the more steps to which that race will be applied.</p><p>(If you are unaware, the [prompt::0.XX] syntax means "prompt" will be applied to XX% of your steps. So, for example, [blonde::0.78] and using 100 steps means the prompt "blonde" would be applied to your gen for the first 78 steps then disregarded for the final 22 steps.)</p>