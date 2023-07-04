## Zeroscope V2 576w (txt2video)
### 一、模型概述

- 标签：`tool`, `txt2video`
- 下载数：422
- 收藏人数：140
- 评论人数：20
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-24T17:33:19.570Z
  - 原始模型：SD 1.5
  - 下载数：422
  - 评分人数：0
  - 评分：0
- 下载地址
  - [zeroscopeV2576w_v10.bin](https://civitai.com/api/download/models/103028)
  - [zeroscopeV2576w_v10.pt](https://civitai.com/api/download/models/103028?type=Model&format=PickleTensor&size=full&fp=fp32)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f1ae5d2b-eb52-48c3-813f-e8f4e6f93532/width=450/1286391.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a34fae80-11fc-4c33-a54b-50a24266e5f1/width=450/1286393.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d75a3acd-8e2f-4930-8b9b-7f1f941315ce/width=450/1274102.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1798c7a6-8599-4244-9bc6-93dba7a3266e/width=450/1274190.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-1742">Stop! These models are not for txt2img inference!</h1><p><em><span style="color:rgb(230, 73, 128)">Don't</span></em> put them in your <strong>stable-diffusion-webui/models</strong> directory and expect to make images!</p><p></p><h2 id="heading-2">So what are these?</h2><p>These are new Modelscope based models for txt2video, optimized to produce 16:9 video compositions. They've been trained on 9,923 video clips and 29,769 tagged frames at 24 fps, 576x320 res.<br /><br />Note that they can look much better - I had to convert the mp4 outputs to gif for Civitai. We can also upscale these videos using the <strong>Zeroscope v2 XL</strong> txt2vid models, which I'm currently uploading!<br /><br />Note: this model is the lighter version of the <span style="color:#e64980">XL model</span> (<a rel="ugc" href="https://civitai.com/models/96563?modelVersionId=103179">available here</a>) which requires a lot more VRAM. <strong><span style="color:#e64980">If you have &gt;15GB of VRAM, you should be using the XL version</span></strong>.</p><p></p><div data-youtube-video><iframe width="640" height="480" allowfullscreen="true" autoplay="false" disablekbcontrols="false" enableiframeapi="false" endtime="0" ivloadpolicy="0" loop="false" modestbranding="false" origin playlist src="https://www.youtube.com/embed/HO3APT_0UA4" start="0"></iframe></div><p></p><h2 id="heading-1744">Where do they go?</h2><p>Drop them in the <strong>\stable-diffusion-webui\models\ModelScope\t2v folder</strong><br /><br />It's <em>imperative </em>you rename the<strong><span style="color:rgb(230, 73, 128)"> text2video_pytorch_model.pt</span> </strong>to<strong><span style="color:rgb(230, 73, 128)"> .pth </span></strong>extension after downloading.<br /><br />The files must be named <strong><span style="color:rgb(230, 73, 128)">open_clip_pytorch_model.bin</span></strong>, and <strong><span style="color:rgb(230, 73, 128)">text2video_pytorch_model.pth</span></strong></p><p></p><h2 id="heading-1745">Who made them? Original Source?</h2><p><a target="_blank" rel="ugc" href="https://huggingface.co/cerspense/zeroscope_v2_576w">https://huggingface.co/cerspense/zeroscope_v2_576w</a></p><p></p><h2 id="heading-1746">What else do I need?</h2><p>These models are specifically for use with the<a target="_blank" rel="ugc" href="https://github.com/kabachuha/sd-webui-text2video"> txt2video Auto1111 WebUI Extension</a><br /></p>