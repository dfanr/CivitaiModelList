## RitiumMix 1.1 | Universal Anime
### 一、模型概述

- 标签：`anime`, `style`, `illustration`, `nsfw`
- 下载数：634
- 收藏人数：195
- 评论人数：5
- 评分人数：1
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] Ritium+ v1.1 baked VAE

- 统计数据
  - 发布时间：2023-04-17T13:40:14.763Z
  - 原始模型：SD 1.5
  - 下载数：426
  - 评分人数：1
  - 评分：5
- 下载地址
  - [ritiummix11Universal_ritiumV11BakedVAE.safetensors](https://civitai.com/api/download/models/48084)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8c44ccb4-eceb-4f73-1528-7d3645a69100/width=450/516981.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f8614c68-39ba-4911-860c-646090aa9400/width=450/516984.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/39126c2c-e342-40e2-76b8-7c6858779200/width=450/516980.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f4c9804d-9f22-4e54-cbe2-6be05542a400/width=450/516977.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] RitiumInpainting+ v1.1

- 统计数据
  - 发布时间：2023-04-17T13:40:14.763Z
  - 原始模型：SD 1.5
  - 下载数：58
  - 评分人数：0
  - 评分：0
- 下载地址
  - [ritiummix11Universal_ritiuminpaintingV11.safetensors](https://civitai.com/api/download/models/48076)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ea7a6b75-2b10-4247-2271-b7aac0097700/width=450/516869.jpeg" /> |
| ---- |

#### [版本1/共3个版本] Ritium v1.0 Vae+F16

- 统计数据
  - 发布时间：2023-04-17T13:40:14.763Z
  - 原始模型：SD 1.5
  - 下载数：150
  - 评分人数：0
  - 评分：0
- 下载地址
  - [ritiummix11Universal_ritiumV10VaeF16.safetensors](https://civitai.com/api/download/models/45553)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8763c574-6120-447a-aab1-cd2fcea0a000/width=450/493332.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d280353c-e90a-475d-d51f-92db668fea00/width=450/494020.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6d971e37-f5fc-42b1-a567-862b319a1a00/width=450/493338.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/33a0d10f-1011-4e53-6525-669e7914ba00/width=450/493336.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>Ritium is a universal anime model.</h1><p>===========================================================</p><h3>Message for Russian-speaking friends</h3><p>Русскоязычных товарищей я приглашаю в наш уютный чатик по нейронным девочкам, и нейросетям в частности. Нас там не много, но все свои. Делимся артиками, фишками, общаемся и помогаем друг другу.<br /><a target="_blank" rel="ugc" href="https://t.me/neuroaestheticschat">https://t.me/neuroaestheticschat</a></p><p>Так же там отвечу на ваши вопросы по модели если они есть.<br />===========================================================</p><h3>The goals of working on it were as follows:</h3><ul><li><p>To achieve a good result without using the <em>hires fix</em>.</p></li><li><p>To make the model universal, not tied to a specific style.</p></li><li><p>Avoid using a lot of quality tags, such as <em>hyper-detailed, photorealistic, ultra realistic</em> and others, so as not to overload the query.</p></li><li><p>Use a short <em>negative prompt</em></p></li></ul><h3>The current version is Ritium+ 1.1, you can read more about the changes in the list of changes.</h3><p>A visual demonstration of the differences</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0b0c1b82-0dcc-4f73-a12f-3e1bce648200/width=525/0b0c1b82-0dcc-4f73-a12f-3e1bce648200.jpeg" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c70259c4-1e70-4bed-f6f9-01802340fe00/width=525/c70259c4-1e70-4bed-f6f9-01802340fe00.jpeg" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8944fda2-4dc3-45a4-3bfd-403c4eb5df00/width=525/8944fda2-4dc3-45a4-3bfd-403c4eb5df00.jpeg" /><p><em>The images are different from those attached to the first version, because the generation was done on a different hardware and operating system.</em></p><p></p><h3>The settings will also be universal:</h3><p>Set <code>clip skip 1-2</code>, <code>ENSD: 31337</code>, use samplers: <code>DPM++ 2M Karass, Eular A, DDIM</code>, <code>CFG Scale 6-10</code> on average, but values above or below may also give good results.</p><p></p><h3>My negative prompt:</h3><p><em>(deformed, distorted, disfigured:1.3), EasyNegative, (bad_prompt:0.8), (bad_prompt_version2:0.8), poorly draw, bad anatomy, wrong anatomy, extra limb, missing limb, floating limbs, (mutated hands and fingers:1.4)</em></p><h3><br /><strong>Alternative Negative:</strong></h3><p><em>(worst quality:1.4, low quality:1.4), (zombie, interlocked fingers), watermark, signature</em></p><p></p><h3>The embeddings i use in negative prompt:</h3><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/16993/badhandv4-animeillustdiffusion">badhandv4</a></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative">EasyNegative</a></p></li><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/datasets/Nerfgun3/bad_prompt/tree/main">bad_prompt</a></p></li></ul>