## Texture Hell
### 一、模型概述

- 标签：`texture`, `asset`, `tool`, `albedo`, `game development`, `pbr`
- 下载数：1535
- 收藏人数：507
- 评论人数：10
- 评分人数：4
- 评分：4

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-17T15:02:50.668Z
  - 原始模型：SD 2.1 768
  - 下载数：1535
  - 评分人数：4
  - 评分：4
- 下载地址
  - [textureHell_v10.safetensors](https://civitai.com/api/download/models/48111)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6439cd5c-c6b3-452d-d703-d3bbcc50c100/width=450/517576.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ceb41579-2378-45d4-fcae-69a9c6b02300/width=450/517575.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ca3c4060-0781-4bb3-8d4c-ed0752bcc700/width=450/517591.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/73bc1663-ffe1-435e-d8a4-27d8ae918d00/width=450/517574.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>Introducing Texture Hell</h1><p>This is my first publicly released sd model. It is meant specifically to create albedo/diffuse textures for use in video games and animations. It has been fully finetuned on the sd2.1 768 base model to provide you with high resolution results. Let's dive into the details.</p><p><strong>Please read my description first before using this model, as it is rather diffrent to use than the usual sd models.</strong></p><h2>Training and prompt tips</h2><p>The dataset consists of 350 high-quality images sourced from Poly Heaven, ensuring a diverse and representative range of albedo textures. </p><p>Clip 1 was used throughout training.</p><p>Prompts where comma seperated tag lists (no clip/bert full text descriptions). The most import one is "texture", followed by any material you are interested. Though because of the limited dataset, there are lacking domains (e.g. flesh and cloth). I plan to improve on diversity on subsequent versions. A full list of tags used on images with a frequency usage statistic is available -here- to help you identify potentially interesting tags. But there is probably a lot of room to experiment with other words, i was only able to do rudimentary testing.</p><p>Very Important: there are some aerial textures inside the dataset (ie. beach taken by drone from very far up) for landscape textures. If you don't want this type of texture, put "aerial" into negative prompt.</p><p>All example images have full prompt information inside them for more information about samplers, steps etc.</p><h2>Tiling and WebUI</h2><p>Please note that the textures generated do not perfectly tile. While there is a tiling option available in the WebUI, i do not recommend using it. Instead, i have found a "reasonable" manual workflow to turn them into seamless textures. A tutorial  can be found on my Huggingface page:</p><p><a target="_blank" rel="ugc" href="https://huggingface.co/Nazzaroth2/texture-hell">https://huggingface.co/Nazzaroth2/texture-hell</a></p><p>I hope to improve the inherent tiling ability of the model in further versions, especially a bigger dataset and good tagging should help here.</p><h2>Other Textures</h2><p>My first try involded generating the full set of textures needed for the normal pbr-based render pipeline(normal, height, roughness, etc). The initial results are promising, though the reduction in resolution and limited dataset made me change my plans. This might change in the future.</p><p>In the meantime you can use other software to create these textures from the albedo image. I personally used the free option Materialize <a target="_blank" rel="ugc" href="https://boundingboxsoftware.com/materialize">https://boundingboxsoftware.com/materialize</a> . But there are of course also paid versions like Substance Designer.</p><p>I am curious to see what you all are able to make with this model and hope it can help you in your projects. If you have any ideas for improvements or a specific material type you think is lacking inside the model, i am happy to hear from you.</p><p>Happy texturing!</p><p>P.S. Why Texture Hell? Because hell is way more interesting than boring old heaven :3</p>