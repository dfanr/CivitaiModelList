## Zeroscope V2 XL (txt2video)
### 一、模型概述

- 标签：`tool`, `txt2video`
- 下载数：269
- 收藏人数：101
- 评论人数：11
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-25T18:42:43.520Z
  - 原始模型：SD 1.5
  - 下载数：269
  - 评分人数：0
  - 评分：0
- 下载地址
  - [zeroscopeV2XL_v10.bin](https://civitai.com/api/download/models/103179)
  - [zeroscopeV2XL_v10.pt](https://civitai.com/api/download/models/103179?type=Model&format=PickleTensor&size=full&fp=fp32)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/753bab5f-eac5-4152-a796-4d478ebf98c8/width=450/1287405.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a154efb2-6b2f-4127-9a57-65a424e4d6b6/width=450/1287417.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c8f3b196-eed5-4b20-8986-d47e5f97e25c/width=450/1296139.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<h1 id="heading-1742">Stop! These models are not for txt2img inference!</h1><p><em><span style="color:rgb(230, 73, 128)">Don't</span></em> put them in your <strong>stable-diffusion-webui/models</strong> directory and expect to make images!</p><p></p><h2 id="heading-7">So what are these?</h2><p>These are new Modelscope based models for txt2video, optimized to produce 16:9 video compositions. They've been trained on 9,923 video clips and 29,769 tagged frames at 24 fps, <strong><span style="color:#e64980">1024x576</span></strong> res.<br /><br />Note that these are the <strong>bigger brothers</strong> to the <a target="_blank" rel="ugc" href="https://civitai.com/models/96454/zeroscope-v2-576w-txt2video">https://civitai.com/models/96454/zeroscope-v2-576w-txt2video</a> models. The <strong><span style="color:#e64980">XL</span></strong> models use <strong><em><span style="color:rgb(190, 75, 219)">15.3GB of VRAM</span></em></strong> when rendering <strong>30 fps at <span style="color:#e64980">1024x576.</span></strong></p><p></p><h2 id="heading-1744">Where do they go?</h2><p>Drop them in the <strong>\stable-diffusion-webui\models\ModelScope\t2v folder</strong><br /><br />It's <em>imperative </em>you rename the<strong><span style="color:rgb(230, 73, 128)"> text2video_pytorch_</span></strong><a target="_blank" rel="ugc" href="http://model.pt"><strong><span style="color:rgb(230, 73, 128)">model.pt</span></strong></a><strong> </strong>to<strong><span style="color:rgb(230, 73, 128)"> .pth </span></strong>extension after downloading.<br /><br />The files must be named <strong><span style="color:rgb(230, 73, 128)">open_clip_pytorch_model.bin</span></strong>, and <strong><span style="color:rgb(230, 73, 128)">text2video_pytorch_model.pth</span></strong></p><p></p><h2 id="heading-1745">Who made them? Original Source?</h2><p><a target="_blank" rel="ugc" href="https://huggingface.co/cerspense/zeroscope_v2_XL">https://huggingface.co/cerspense/zeroscope_v2_XL</a></p><p></p><h2 id="heading-1746">What else do I need?</h2><p>These models are specifically for use with the<a target="_blank" rel="ugc" href="https://github.com/kabachuha/sd-webui-text2video"> txt2video Auto1111 WebUI Extension</a></p>