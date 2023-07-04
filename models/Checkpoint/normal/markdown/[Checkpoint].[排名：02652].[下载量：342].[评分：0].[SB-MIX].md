## SB-MIX
### 一、模型概述

- 标签：`anime`, `style`, `girls`, `stylemix`, `dreambooth`
- 下载数：342
- 收藏人数：127
- 评论人数：4
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-05-09T01:48:34.311Z
  - 原始模型：SD 1.5
  - 下载数：297
  - 评分人数：0
  - 评分：0
- 下载地址
  - [sbMIX_v10.safetensors](https://civitai.com/api/download/models/65958)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6b9376ee-5fb5-48dc-9cc0-e73f0c066366/width=450/731688.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4997a608-566e-4393-903d-f27f2b85bfad/width=450/731774.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/38b3109b-0718-4e3f-b4ed-6aae0fb2832b/width=450/731843.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e5c9f9ed-f402-4614-966d-403d74e32a88/width=450/731863.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v0

- 统计数据
  - 发布时间：2023-05-09T01:48:34.311Z
  - 原始模型：SD 1.5
  - 下载数：45
  - 评分人数：0
  - 评分：0
- 下载地址
  - [sbMIX_v0.safetensors](https://civitai.com/api/download/models/66009)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/db6fd053-9d84-4c51-a908-c5e302552136/width=450/732018.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a8600ab9-030a-49dc-9532-badf15fbd731/width=450/731977.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9478fedc-9064-41aa-95ba-dbca123afe31/width=450/732124.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a026f1b8-aa1e-4891-865e-3a28b4b552e8/width=450/732044.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3 id="heading-316">SB-MIX并不是简单提示词就能出很好效果的模型！v0版本接近nai模型的表现，需要合适的提示词组合才能发挥他的优势，而v1版本进一步融模以进行彻底的风格化，对提示词的要求低于v0。</h3><p>我在吐司平台发布了一个新的Lora:<a target="_blank" rel="ugc" href="https://tusi.art/models/605521961319198991">https://tusi.art/models/605521961319198991</a></p><h2 id="heading-317"><strong>制作流程</strong></h2><p>此模型先是基于e9进行DB训练得到两个不同的底模，再与tmnd模型进行三模合并，并将in层和midd层以及base层重置为e9的内容物后，得到了基础版本SB-MIX-v0，此版本关于对tag的服从性异常优秀，但缺点是风格化不够明显。</p><p>接着我将SB-MIX-V0里unet的out层中的其中一份DB底模的成分替换为了新的DB底模，再将DarkSushi模型中unet的in层替换入此模型，得到了现版本SB-MIX-v1，这次操作令v1模型对tag的服从性变差了，大约只有e9的70%-80%（估算），勉强能接受的范围，但是大幅提升了模型本身的风格化表现，我认为这是有意义的。</p><p></p><h2 id="heading-318">后续改进</h2><p>后续会考虑进一步在unet中的in层动工，in曾全占比使用某个模型的内容还是简单了一些，我认为有可剔除和改进的空间，以改善模型对tag的服从性。至于midd层和base层我暂时不想去动它，不可控因素太多，我并没有很好的了解清楚这两个层的影响范围。</p><p></p><h3 id="heading-319">感谢</h3><p>感谢bilibili的up主<a target="_blank" rel="ugc" href="https://space.bilibili.com/12566101"><strong>秋葉aaaki</strong></a>，以及QQ频道秋叶的甜品店，让我接触到SD-webui以及学习到许多相关知识。</p><p></p><h3 id="heading-320">声明</h3><p><s>尽管不会有太多人关注以及使用此模型，但我仍需要在这里叠个甲</s>：</p><h3 id="heading-321">禁止用于任何商业用途，包括但不限于：打包售卖、转载于有门槛需收费的平台、进行处理后进行售卖，用次模型生成图片贩卖等。模型本身属于免费，可自由使用及融合，也可转载于其他平台但需要标明来源及附上链接。</h3><h3 id="heading-322"><strong><u>某个户口本只有一页的炼丹阁禁止转载。</u></strong></h3>