## Pseudo Flex (Base)
### 一、模型概述

- 标签：`base model`, `portrait`, `fantasy`, `2.1`, `widescreen`, `photoreal`, `stable-diffusion-2-1`, `multi-aspect`
- 下载数：110
- 收藏人数：24
- 评论人数：0
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-27T01:47:24.605Z
  - 原始模型：SD 2.1 768
  - 下载数：110
  - 评分人数：1
  - 评分：5
- 下载地址
  - [pseudoFlexBase_v10.safetensors](https://civitai.com/api/download/models/104575)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da5eee51-a31e-433d-9606-337548ebfe8e/width=450/1298171.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b04ddfb8-89a1-469e-8d4b-71c81b69746c/width=450/1298172.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/be3f49b9-5280-4025-9966-82b11fcd99c4/width=450/1298173.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cd1d81c6-2db0-4b74-89c1-eee8b249b70a/width=450/1298177.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c8c2fef3-df26-4f70-9f1e-f355cb8f46f2/width=525/c8c2fef3-df26-4f70-9f1e-f355cb8f46f2.jpeg" /></p><h2 id="heading-9760">Capabilities</h2><ul><li><p>Widescreen &amp; portrait up to 1536x1024 and 1024x1536</p><ul><li><p>1920x1080 sometimes works, sometimes not. This is a limitation of pre-SDXL models' internal transformer architecture.</p></li></ul></li><li><p>Photorealism - prompt with a year, a location, and a camera make.</p></li><li><p>Adventure - prompt coherence to allow silly requests.</p></li><li><p>Dark images - High guidance level with low CFG rescaling allows CRAZY dark images.</p></li><li><p>Bright images - Not bound to darkness like offset noise models, this terminal SNR prototype model is capable of producing pure white scenes.</p></li><li><p><strong>Intentionally under-trained</strong> to allow additional fine-tuning.</p></li><li><p>Combine with textual inversions and see the true power of OpenCLIP!</p></li></ul><p></p><h3 id="heading-9761">No NSFW is trained into this model at all. It is family friendly.</h3><p></p><h2 id="heading-9762">Why it looks broken in Automatic1111?</h2><p></p><p>Most of stable-diffusion-webui's samplers are unfortunately broken due to sampling from the leading timestep during inference. This is incongruent with the nature of training and inference in diffusion models:</p><ul><li><p>During training, noise is added to a sample.</p></li><li><p>During inference, noise is removed from a sample.</p></li></ul><p>When the noise addition ends during training, the instance is on the trailing timestep.</p><p>Most samplers start from the leading timestep, emulating a forward pass, rather than properly emulating the backwards pass.</p><h3 id="heading-9763">Solution</h3><ul><li><p>Use DPM++ 2M sampler.</p></li><li><p>Install the A1111 extension <a target="_blank" rel="ugc" href="https://github.com/AMorporkian/sd-dynamic-thresholding-rcfg">for CFG (classifier-free guidance) rescaling</a></p></li></ul><p></p><p>I find that higher CFG values around 7.5-9.5 produce stunning images, and a rescale of 0.0 allows the creation of very bright and very dark images.</p><p>However, if images appear over-contrasted or washed-out, you might need to up the CFG rescaling value to around 0.3 to 0.5. The maximum recommended value is 0.7, but this can result in washed-out images in a low-contrast manner.</p><p></p><p></p><h2 id="heading-9764">Comparison vs 2.1-v and realism-engine:</h2><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e60cb878-134e-4258-ad31-b9edd1f2edeb/width=525/e60cb878-134e-4258-ad31-b9edd1f2edeb.jpeg" /></p><p></p><h2 id="heading-9765">Training details</h2><p><a target="_blank" rel="ugc" href="https://huggingface.co/ptx0/pseudo-flex-base">The original Huggingface Hub </a>model card contains all information available on the training of this model.</p>