## TheSabu Style LoRA 
### 一、模型概述

- 标签：`anime`, `style`, `art style`
- 下载数：3797
- 收藏人数：641
- 评论人数：2
- 评分人数：5
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] TheSabu-StyleA1

- 统计数据
  - 发布时间：2023-02-13T17:36:37.536Z
  - 原始模型：SD 1.5
  - 下载数：3323
  - 评分人数：5
  - 评分：5
- 下载地址
  - [TheSabu-Style-A2.safetensors](https://civitai.com/api/download/models/10095)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/df40b042-95f1-4c2e-453f-8389bf625d00/width=450/98388.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3207ec94-4566-4fb7-d5c5-582503e80100/width=450/98402.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b6453c8e-2e98-45b7-a6c5-2dc9d912c900/width=450/98401.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/65b14df4-d3b0-4c71-b225-b297a16c4800/width=450/98400.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] TheSabu-StyleA2

- 统计数据
  - 发布时间：2023-02-13T17:36:37.536Z
  - 原始模型：SD 1.5
  - 下载数：474
  - 评分人数：0
  - 评分：0
- 下载地址
  - [TheSabu-Style-A1.safetensors](https://civitai.com/api/download/models/10096)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cad657d3-b753-4f81-2c27-055912419800/width=450/98412.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f72f81ba-971c-415e-deac-839248fa0a00/width=450/98411.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2211596d-6e13-472c-f11f-73d3e5760100/width=450/98410.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9cc72d46-8fa9-4305-731e-aca80b02eb00/width=450/98409.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This model was trained on <strong>TheSabu</strong>'s artstyle<em>/s</em>. There is two versions of this LoRA, <strong>A1 </strong>and <strong>A2</strong>. I think setting the weight of the LoRA to 0.6-1.2 works fine, they're pretty flexible.</p><p></p><ul><li><p><strong>A1</strong> was trained <u>both on their cartoony &amp; realistic art</u>.</p></li><li><p><strong>A2 </strong>was trained on <u>only the cartoony style</u>.</p></li></ul><p></p><p>Both have tokens to activate them. <em>(Not necessary but helpful)</em></p><ul><li><p><strong>A1</strong>= "<strong>SabuCartoon</strong>" <em>&amp; </em>"<strong>SabuRealism</strong>"</p></li><li><p><strong>A2</strong>= "<strong>SabuCartoon</strong>"</p></li></ul><p></p><p>I personally like both of them, but A1 and A2 do have their differences. A1 is usually more flexible with the style. But both can be tough to tame at times.</p><p>I also would suggest using some helping tags like the following depending on which style you're going for <u>when using </u><strong><u>A1</u></strong>, these are some tag templates that worked well for me. </p><p><em>(put them at the start of your prompt, you can substract from them or add to them if you want, i also recommend changing the weights depending on how your output images look if they look bad or inaccurate)</em></p><ul><li><p><strong>SabuRealism</strong>: <em>(SabuRealism:1.5)</em>, <em>(realistic:1.3), (realism, hyperrealism:1.3), (oil painting, painterly:1.3), (soft lighting, soft shading:1.2)</em></p><p></p></li><li><p><strong>SabuCartoon</strong>: (SabuCartoon:1.5), (cartoon:1.5), (sketch:1.3), (lineart:1.3), (cellshading:1.1), (painterly:1.1)</p></li></ul><p></p><ul><li><p><strong>Random Sketch Style Event</strong>: </p></li></ul><p>I'd also advise putting <strong>(monochrome, greyscale:1.3)</strong> in the negatives</p><p></p><p></p><p><em>Sample images were made using </em><a rel="ugc" href="https://civitai.com/models/4451/abyssorangemix2-hardcore"><em>AbyssOrangeMix2_Hard</em></a></p>