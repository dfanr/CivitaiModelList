## 时尚摄影（风格）| Fashion Magazine - Style
### 一、模型概述

- 标签：`female`, `fashion`, `style`, `accessory`
- 下载数：4464
- 收藏人数：1303
- 评论人数：6
- 评分人数：17
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-17T05:32:57.666Z
  - 原始模型：SD 1.5
  - 下载数：4464
  - 评分人数：17
  - 评分：5
- 下载地址
  - [LoRA-FashionMagCover.safetensors](https://civitai.com/api/download/models/47756)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d015d1a7-0021-4621-be76-bb8454ffeb00/width=450/514424.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2f593120-bf64-4542-495e-63a8add8f600/width=450/514425.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/525e3783-31b9-4e9c-f78c-8480e3730000/width=450/514426.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c5f00ded-9c1f-41d8-21f0-ed48b0e7fd00/width=450/514427.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-50">专为中文用户写的声明：别来我这发乱七八糟的推广小广告，不感兴趣、不会回复、会直接拉黑。国内互联网随地大小便的陋习别tm带到这来。<br /></h1><p><br />类似时尚摄影杂志的风格LoRA，建议搭配写实或3D风格checkpoint使用，不过二次元也可以有比较一致的效果。</p><p>训练使用：v1.5-pruned-bakedVAE，分辨率512*768（2:3画幅）。</p><p>A LoRA that can create fashion photography magazine cover. It is recommended to use it on realistic / 3D checkpoints. The model used for training is v1.5-pruned-bakedVAE with a resolution of 512*768 (2:3 aspect ratio).</p><p></p><h1 id="heading-51">摄影指南 | How to properly use this</h1><p>这是一个普通的LoRA，不需要LoCON插件即可使用。</p><p>会在画面中添加类似杂志封面的文字，同时能够对配饰相关的提示词做出响应，画出复杂、夸张的发饰 / 项链 / 耳环等元素。</p><p>It's a normal LoRA (not LyCORIS). Good at: generating complex hear accessories / necklace / chocker / earrings / etc. However you must prompt with corresponding words.</p><p>Read below info carefully. This LoRA isn't perfect yet, so extra steps are needed to get high quality images.</p><p></p><h3 id="heading-52">1. 提示词 | Prompts</h3><p>在prompt中添加下列提示词（🔸必须 | 🔹可选）：</p><p>The prompts（🔸mandatory kinda | 🔹optional）：</p><p>🔸LoRA引用 / &lt;lora:xxxxx&gt;</p><p>🔹FashionMagCover</p><p>🔹magazine cover</p><p>🔹english text, watermark, artist name, signature</p><p></p><h3 id="heading-53">2. 进阶用法 | Advanced Usage</h3><p>如果你不需要文字，或者需要通过<a target="_blank" rel="ugc" href="https://github.com/hako-mikan/sd-webui-supermerger">SuperMerger</a>将其融合到大模型中，请使用：<a target="_blank" rel="ugc" href="https://github.com/hako-mikan/sd-webui-lora-block-weight">LoRA Block Weight</a>插件，并参考最后三张示例图的各层权重影响进行调节。</p><p>对于普通用户来说，可以通过使用0.7-0.9的LoRA权重，并在负面提示词中加入“english text, watermark, artist name, signature”等词来尽可能避免产生文字。</p><p>I made this into normal LoRA becasuse LoHA is not well supported by LBW extension. If you want to merge this into checkpoints, please use <a target="_blank" rel="ugc" href="https://github.com/hako-mikan/sd-webui-lora-block-weight">LoRA Block Weight</a> extension, and refer the the last three xyz plot images for block weight guide.</p><p></p><p>For lazy person, the LBW preset for this LoRA:</p><p>MAGCOVER:1,0.9,0.9,0.9,0.9,0.2,0.8,0.9,0.9,0.8,0.8,0.9,0.9,0.4,0.9,0.9,0.9</p>