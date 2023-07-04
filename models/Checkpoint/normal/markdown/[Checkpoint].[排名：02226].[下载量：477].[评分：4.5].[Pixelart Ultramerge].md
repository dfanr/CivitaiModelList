## Pixelart Ultramerge
### 一、模型概述

- 标签：`pixel art`, `base model`, `pixel`, `pixelart`
- 下载数：477
- 收藏人数：115
- 评论人数：2
- 评分人数：2
- 评分：4.5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Pixelart Ultramerge V2

- 统计数据
  - 发布时间：2023-04-03T08:57:25.200Z
  - 原始模型：SD 1.5
  - 下载数：477
  - 评分人数：2
  - 评分：4.5
- 下载地址
  - [pixelartUltramerge_pixelartUltramergeV2.pt](https://civitai.com/api/download/models/16611?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [pixelartUltramerge_pixelartUltramergeV2.safetensors](https://civitai.com/api/download/models/16611)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e52ed635-a714-4db6-078e-cb48c9d5f200/width=450/167602.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/43352f71-c39a-4544-25a4-c2b136c89200/width=450/167621.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b3bf648d-b824-45e0-84e1-703582c59900/width=450/167620.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0a5f959a-b2af-43a2-6340-2698d45d5600/width=450/167619.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Hi,</p><p>This is a merge of 30 models in 60 Steps, with the focus on pixel art. No complex prompt engineering necessary, but you can use also complex prompts.</p><p></p><p>Try different<strong> trigger words</strong> like: <em>pixelart, sprite, 1-bit </em>till<em> 16-bit,</em></p><ul><li><p>You can play with the weights (range ~ +-2)</p></li><li><p>Not every trigger works for every scenery. While in one just <em>pixelart </em>works great, in the next scene you need to weight the trigger. And in the next one you will need to use it together with negative prompts.</p></li><li><p>Use <em>border, mosaic, voxel</em> as <strong>negative </strong>(separated or combined). It can help, if it looks some kind of blocky. Then you will need also to raise the positive weights for the trigger words.</p></li><li><p><strong>For some combinations, it doesn't seem really to work.</strong> Try to enforce it with the own pixel art Lora (in downloads ~18mb) and <em>(mosaic, voxel:0.0) </em>(and -1 sometimes also gives a good result") negative prompt. The voxel and mosaic style seems hardly to interfere with the pixel art style. If somebody knows how to subtract these values from the model, maybe the quality can be improved(Is it maybe some kind of unet issue?).</p></li><li><p><strong>Try to use luisa_pinguins Pixelart Lora, </strong>to improve the output in these hard cases <a target="_blank" rel="ugc" href="https://civitai.com/models/10706/luisap-pixel-art-lora">https://civitai.com/models/10706/luisap-pixel-art-lora</a> pixelart in the prompt trigger it.</p></li><li><p><strong>Use luise_pinguins Pixelart Lora</strong> to get more/other/fancy results. Range +1.4 ~ -1</p></li><li><p><strong>Anti Burn plugin for Automatic1111</strong> can improve the quality, if you smooth down steps.</p></li></ul><p>The model is not perfect. But there are also nice outcomes through imperfection. Sometimes it mixes pixel art and non pixel art. From time to time, you will have borders around chars or mosaiclike pixel art.</p><p></p><p><strong>You can try to trigger specific styles:</strong></p><ul><li><p><em>Nvinkpunk;</em></p></li><li><p><em>modern disney style</em></p></li><li><p><em>classic disney style</em></p></li><li><p><em>dreamlike</em></p></li><li><p><em>samdoesarts</em></p></li><li><p><em>charliebo artstyle</em></p></li><li><p><em>holliemengert artstyle</em></p></li><li><p><em>marioalberti artstyle</em></p></li><li><p><em>andreasrocha artstyle</em></p></li><li><p><em>pepelarraz artstyle</em></p></li><li><p><em>jamesdaly artstyle</em></p></li><li><p><em>modelshoot style</em></p></li><li><p><em>mdjrny-v4 style</em></p></li><li><p><em>estilovintedois</em></p></li><li><p><em>jarcher style</em></p></li><li><p><em>archer style</em></p></li><li><p><em>arcane style</em></p></li><li><p><em>modelshoot style</em></p></li><li><p><em>anime pencil concept style</em></p></li><li><p><em>MTG card art</em></p></li><li><p><em>sjh style</em></p></li><li><p><em>jwst (Deep Space photography)</em></p></li></ul><p></p><p>All images are rendered with Euler a 20 Steps. You can have a look into the examples for more details.</p><p>Can produce some nice NSFW stuff, but there is no explicit merge in it.</p><p></p><p>I had a lot of fun with this model and also to create it. I hope you will too!</p><p></p>