## WLOP style version 2
### 一、模型概述

- 标签：`anime`, `concept art`
- 下载数：530
- 收藏人数：149
- 评论人数：2
- 评分人数：3
- 评分：4.33

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] V2

- 统计数据
  - 发布时间：2023-01-09T14:16:56.284Z
  - 原始模型：SD 1.5
  - 下载数：530
  - 评分人数：3
  - 评分：4.33
- 下载地址
  - [wlopStyleVersion2_v2.ckpt](https://civitai.com/api/download/models/4585)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d031df19-5326-4cf6-8b14-12308bce3800/width=450/32936.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8574f719-5ede-4805-9609-6a44c5612c00/width=450/31632.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f57fd33d-bf93-40b8-b828-8412d374d200/width=450/32935.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6b1ed376-9ac1-45e3-9754-c2562d4e6c00/width=450/31629.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Generate thick painting style images similar to wlop.Trying to keep the original author's style</p><p>This version is the V2, the V1 link: <a target="_blank" rel="ugc" href="https://huggingface.co/hhyxnh/WLOP-style_stable_diffusion">https://huggingface.co/hhyxnh/WLOP-style_stable_diffusion</a></p><p></p><p>中文社区链接 Chinese link：<a target="_blank" rel="ugc" href="https://bbs.cgkit.cn/forum.php?mod=viewthread&amp;tid=8593&amp;page=1#pid51146">https://bbs.cgkit.cn/forum.php?mod=viewthread&amp;tid=8593&amp;page=1#pid51146</a></p><p></p><p>Detailed description is in the huggingface.</p><p></p><p>below I will briefly describe the features of this version</p><p></p><p>1. 768 resolution is used for training, V1 is 512 ,so V2 will create more details. In v2 ,If the resolution settings is too small(below 768*768), the results will not be great.</p><p></p><p>2. Maybe due to the influence of training set,in V2, the logic of text2img is poor than V1. If you want to use text2img , you can try the V1, or use text2img then use img2img to improve quality</p><p></p><p>3. this model focuses on the generation of portraits. I have not trained for grand scenes. Too many elements are easy to cause training mismatch.</p><p></p><p>I will give a typical parameter. The quality in img2img will be good</p><p></p><p>***Too low resolution settings will affect the generation of head details. If you want to generate a bust,please set  higher resolution .</p><p></p><p>Style word: wgz style</p><p></p><p>typical parameters;</p><p></p><p>Prompt :wgz style,portrait of a beautiful women highly detailed,perfect femine face,Classical oil painting,by masamune shirow, by William-tae Kim</p><p>Negative prompt: old,men,two poeple,Three dimensional facial features,deep shadows on the five senses,tall nose,Eye shadow,[High bridge], [narrow nose],Deep orbital fossa</p><p>Steps: 20, Sampler: DPM++ 2S a Karras, CFG scale: 9.5, Denoising strength: 0.51, Mask blur: 4</p><p></p><p>I hope you guys enjoy this model and create works that satisfied</p><p></p><p>If you have any doubts or want to communicate, you can contact me,welcome<br /></p><p>PS:I try hard to achieve the painting style I want by using stable diffusion. I have tried a lot, with failures and successes. With my current technology, I can hardly find progress now. So this model will not be updated in a short time. If you have ideas or want to improve together, you can contact me,happy new year guys.</p><p></p><p>Telegram: <a target="_blank" rel="ugc" href="https://t.me/hhhyxnh">https://t.me/hhhyxnh</a></p><p>QQ:1602821649</p><p></p>