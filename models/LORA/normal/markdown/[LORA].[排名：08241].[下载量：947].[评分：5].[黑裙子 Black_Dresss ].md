## 黑裙子 Black_Dresss 
### 一、模型概述

- 标签：`standing`, `xxx_dresss`, `black_dresss`, `dresss`
- 下载数：947
- 收藏人数：243
- 评论人数：2
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Black_dresss_V1.1.0.14

- 统计数据
  - 发布时间：2023-04-02T08:07:16.706Z
  - 原始模型：Other
  - 下载数：947
  - 评分人数：1
  - 评分：5
- 下载地址
  - [Black_dresss_V1.1.0.14.safetensors](https://civitai.com/api/download/models/33593)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8133d41c-a43e-4a60-f651-2e7cfc9a1400/width=450/382987.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dcc56e5d-d4d7-40e7-e826-54f1f6be9b00/width=450/382997.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/93cb54f9-d981-4111-03ab-21eaa17b1500/width=450/382996.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8a5c00dd-d68f-4203-717c-05b503491100/width=450/382995.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>The English instructions are below.</p><p>大家好，</p><p>我想生成一些穿裙子的图片，但自带的裙子在高清修复后总是满是褶皱、胸部下方包裹的非常紧、且材质看起来很没质感，所以我自己炼了一个只是黑裙子的lora。</p><p>我也是第一次炼服饰类的lora，炼制过程中尽量完成了以下几个目标</p><ol><li><p>为了不污染原有词汇，关键词设置为dresss（但似乎不用lora打dresss还是能识别出dress）</p></li><li><p>我炼制lora时没有出现脸，所以头可以随意搭配。但实测用纯粹脸的lora+黑裙子lora，拼接效果并不是很理想，所以可能需要搭配controlnet</p></li><li><p>权重0.5左右效果更好，更高的权重容易出现脸超出画框的问题</p></li><li><p>实际出图的黑裙子的长短、样式，你用的大模型影响还是会更大（lora只能改改材质，少点褶皱）</p></li><li><p>部分解决了裙子会展示腹肌、肚脐、肋骨的问题</p></li></ol><p><strong>已知的问题：</strong></p><ol><li><p>还是会出没有头的图片，如果出现的很频繁，请添加负面prompt：(head out of frame:1.8),</p></li><li><p>偶尔会出多人图片（controlnet的openpose可以解决）</p></li><li><p>偶尔会出手持手机自拍的姿势</p></li><li><p>黑裙子都是极简风格的，但因为原图有很多又瘦又平胸的素材，所以在身材方面尤其是胸部大小的问题我很遗憾…</p></li><li><p>只能说是部分解决裙子胸部总有两条垂直的，从最高点连到腰间的细线的问题</p></li><li><p>图片大部分是正面和背面，出侧面图可能会有问题（因为侧面的素材有很多包、围巾、外套等干扰元素，所以素材比较少）</p></li></ol><p></p><p>参考数值：</p><p>DPM++SDE Karras, Lanczos,</p><p>Lora权重weight：0.5</p><p>Prompt：(dresss, black_dresss:1.2), standing,</p><p>NP：(head out of frame: 1.8)</p><p></p><p>Hello everyone,</p><p>I want to generate some pictures of people wearing dresses, but the built-in dresses always have a lot of wrinkles and look very artificial even after high-resolution repair. Therefore, I trained a LORa model specifically for black dresses.</p><p>This is my first time training a LORa model for clothing, and during the training process, I tried to achieve the following goals:</p><ol><li><p>To avoid contaminating existing vocabulary, I used the keyword "dresss" for the model (although it seems that the model can still recognize "dress" even without using "dresss").</p></li><li><p>Since the LORa model I trained did not include faces, it can be matched with any type of face. However, I found that the combination of a pure face LORa model and a black dress LORa model did not produce very good results, so it may be necessary to use a controlnet.</p></li><li><p>The model works better with a weight of around 0.6, and higher weights can cause issues where the face goes beyond the frame.</p></li><li><p>The actual length and style of the black dress generated will still be influenced by the larger model used (LORa can only adjust the texture and reduce wrinkles).</p></li><li><p>Partial solution to the problem of showing abs, belly button, and ribs when wearing a skirt.</p></li></ol><p><strong>Known issues:</strong></p><ol><li><p>There will still be pictures without heads. If they appear frequently, please add a negative prompt: (head out of frame: 1.8).</p></li><li><p>Occasionally, it will generate images with multiple people (which can be resolved using Controlnet's OpenPose).</p></li><li><p>Occasionally, it will generate images of people taking selfies with their phones.</p></li><li><p>The black dresses generated are all minimalist in style, but due to the nature of the source materials (many with small breasts and flat chest), the issue of body shape, especially breast size, is still a challenge for me.</p></li><li><p>I can only say that it partially solves the problem that there are always two vertical lines from the highest point of the chest to the waistline on the dress.</p></li><li><p>Most of the pictures are front and back views, there might be issues with side views (as there are many interfering elements like bags, scarves, jackets, etc. in the side view, so there are fewer materials available).</p></li></ol><p></p><p></p>