## 国风幻维 GuoFengDimensionMix
### 一、模型概述

- 标签：`girl`, `clothes`, `style`, `styles`, `scence`
- 下载数：523
- 收藏人数：136
- 评论人数：6
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-31T12:12:08.577Z
  - 原始模型：Other
  - 下载数：523
  - 评分人数：0
  - 评分：0
- 下载地址
  - [Guofengdimensionmix_v10.safetensors](https://civitai.com/api/download/models/86138)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/aa7f2adb-2c2c-4375-a36f-004b5c15c398/width=450/979023.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8f19c052-bfda-4891-8c45-b5f20132323d/width=450/980265.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7c4ea1ce-e209-4d0b-aa2f-3cfc41fcf341/width=450/980217.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/56c6c5a9-ac4d-4e89-a133-3db1de56ffca/width=450/980214.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/70da5326-9014-4568-a9cb-6ee78b408b28/width=525/70da5326-9014-4568-a9cb-6ee78b408b28.jpeg" /><h1 id="guofengrealmix"><strong><span style="color:rgb(253, 126, 20)">介绍 - GuoFengDimensionMix</span></strong></h1><p><span style="color:rgb(250, 82, 82)">欢迎使用GuoFengDimensionMix模型，这是一个基于GuoFeng系列模型融合的二次元于真实质感结合的模型可以适应多种风格、服装、场景。</span></p><p>======</p><p><span style="color:rgb(34, 139, 230)">Welcome to use the GuoFengDimensionMix model, which is a combination of anime and realistic texture based on the fusion of GuoFeng series models, and can adapt to a variety of styles, clothing, and scenes.</span></p><h1 id="install"><span style="color:rgb(253, 126, 20)">安装教程 - install</span></h1><ol><li><p><span style="color:rgb(250, 82, 82)">将GuoFengDimensionMix.safetensors模型放入SD目录</span> - <span style="color:rgb(34, 139, 230)">Put GuoFengDimensionMix.safetensors model into SD directory</span></p></li><li><p><span style="color:rgb(250, 82, 82)">请记得选择任意一个VAE文件，否则图形将可能为灰色</span> - <span style="color:rgb(34, 139, 230)">Please remember to select any VAE file, otherwise the graphics may be grayed out</span></p></li></ol><h1 id="how-to-use"><span style="color:rgb(253, 126, 20)">如何使用 - How to use</span></h1><p><span style="color:rgb(250, 82, 82)">VAE建议使用840000-ema-pruned</span> - <span style="color:rgb(34, 139, 230)">VAE recommends using 840000 ema run</span></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/tree/main">stabilityai/sd-vae-ft-mse-original at main</a></p><p><span style="color:rgb(250, 82, 82)">如果你的出图全身图时出现脸部崩坏建议删除full body关键词或者使用脸部自动修复插件：</span></p><p><span style="color:rgb(250, 82, 82)">国外源地址：</span><a target="_blank" rel="ugc" href="https://github.com/ototadana/sd-face-editor.git">https://github.com/ototadana/sd-face-editor.git</a></p><p><span style="color:rgb(250, 82, 82)">国内加速地址：</span><a target="_blank" rel="ugc" href="https://jihulab.com/xiaolxl_pub/sd-face-editor.git">https://jihulab.com/xiaolxl_pub/sd-face-editor.git</a></p><p>======</p><p><span style="color:rgb(34, 139, 230)">If you experience facial collapse during the full body image, it is recommended to delete the full body keyword or use the facial automatic repair plugin:</span></p><p><span style="color:rgb(34, 139, 230)">Foreign source address:</span><span style="color:rgb(76, 110, 245)"> </span><a target="_blank" rel="ugc" href="https://github.com/ototadana/sd-face-editor.git">https://github.com/ototadana/sd-face-editor.git</a></p><p><span style="color:rgb(34, 139, 230)">Domestic acceleration address: </span><a target="_blank" rel="ugc" href="https://jihulab.com/xiaolxl_pub/sd-face-editor.git">https://jihulab.com/xiaolxl_pub/sd-face-editor.git</a></p><p><strong><span style="color:rgb(250, 82, 82)">可用负面词</span> <span style="color:rgb(34, 139, 230)">Available Negative Words</span> - <span style="color:rgb(250, 82, 82)">感谢群友提供的负面词</span>:</strong></p><pre><code>(((simple background))),monochrome ,lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, lowres, bad anatomy, bad hands, text, error, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, ugly,pregnant,vore,duplicate,morbid,mut ilated,tran nsexual, hermaphrodite,long neck,mutated hands,poorly drawn hands,poorly drawn face,mutation,deformed,blurry,bad anatomy,bad proportions,malformed limbs,extra limbs,cloned face,disfigured,gross proportions, (((missing arms))),(((missing legs))), (((extra arms))),(((extra legs))),pubic hair, plump,bad legs,error legs,username,blurry,bad feet</code></pre>