## NiobMix
### 一、模型概述

- 标签：`girl`, `person`, `photorealistic`, `blend`, `porn`, `digital art`, `mix`, `portrait`, `model`, `nudes`, `style`, `woman`, `sex`, `fantasy`, `girls`, `photography`, `photorealism`, `realistic`, `real person`, `merge`
- 下载数：307
- 收藏人数：100
- 评论人数：0
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-03-31T04:30:38.843Z
  - 原始模型：SD 1.5
  - 下载数：307
  - 评分人数：1
  - 评分：5
- 下载地址
  - [niobmix_v10.safetensors](https://civitai.com/api/download/models/32314)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/24561597-8d79-49ea-05fd-5182a992e700/width=450/367892.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/93c87dce-ba89-4a48-ae5b-214566071900/width=450/367899.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b09cc1d0-625a-432c-fe74-9c7c2fdda300/width=450/367898.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9b326882-e5d0-44f5-b1eb-a321fcb6eb00/width=450/367897.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1><strong>NiobMix</strong></h1><h3><strong><em>Chattiori ElementMixes-41:NiobMix</em></strong></h3><p>NiobMix is merge model of <a target="_blank" rel="ugc" href="https://civitai.com/models/6424/chilloutmix">ChilloutMix</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/18569/cartoonish">cartoonish</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/8437/ddosmix">DDosMix</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/20143/ez">EZ</a>, <a rel="ugc" href="https://civitai.com/models/9052/lofi">LOFI</a>, <a rel="ugc" href="https://civitai.com/models/25694/epicrealism">epiCRealism</a> and <a target="_blank" rel="ugc" href="https://huggingface.co/Chattiori/RetMix">RetMix</a></p><p><strong><u>Check out other ElementMixes and models at </u></strong><a target="_blank" rel="ugc" href="https://huggingface.co/Chattiori"><strong><u>HuggingFace</u></strong></a></p><h2>Merge Source<strong>:</strong></h2><ol><li><p>EZ:v1 + EZ:typeR 0.5 Weighted Sum &gt;&gt; (1)</p></li><li><p>cartoonish:v1 + DDosMix:v2 0.6 Weighted Sum &gt;&gt; (2)</p></li><li><p>epiCRealism:v1 + ChilloutMix:Ni-pruned-fp32-fix 0.5 Weighted Sum &gt;&gt; (3)</p></li><li><p>RetMix + LOFI:v2 0.6 Weighted Sum &gt;&gt; (4)</p></li><li><p>(1) + (3) 0.45 Weighted Sum &gt;&gt; (5)</p></li><li><p>(2) + (4) 0.6 Weighted Sum &gt;&gt; (6)</p></li><li><p>(5) + (6) 0.4 Weighted Sum &gt;&gt; NiobMix</p></li></ol><h2>Recommended Settings:</h2><ul><li><p>Sampler: “DPM++ SDE Karras” recommended.</p></li><li><p>Steps: 20~</p></li><li><p>Clipskip: 1 or 2</p></li><li><p>CFG Scale: 7 or higher recommended.</p></li><li><p>VAE: <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original">vae-ft-mse-840000-ema-pruned </a>baked</p></li></ul><h2>Recommended Prompt:</h2><p>Prompt : (8k, best quality, masterpiece:1.2), (realistic, photo-realistic:1.37), ultra-detailed,</p><p>Negative : (deformed,distorted,disfigured:1.3),poorly drawn,bad anatomy,wrong anatomy,extra limb,missing limb,noating limbs,(mutated hands and finger:1.4),disconnected limbs,mutabon,mutated,ugly,disgusting,blurry,amputation</p><h2>Recommended Embeds:</h2><ul><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/datasets/Nerfgun3/bad_prompt/resolve/main/bad_prompt_version2.pt">bad prompt</a></p></li><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/yesyeahvh/bad-hands-5/resolve/main/bad-hands-5.pt">bad hands</a></p></li><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/NiXXerHATTER59/bad-artist/resolve/main/bad-artist.pt">bad artist</a></p></li><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/embed/EasyNegative/resolve/main/EasyNegative.safetensors">Easy Negative</a></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/4629/deep-negative-v1x">Deep Negative</a></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/4514/pure-eros-face">Pure Eros Face</a></p></li></ul>