## Caricature portraits
### 一、模型概述

- 标签：`portaits`, `style`, `caricature`
- 下载数：200
- 收藏人数：39
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-24T14:21:36.171Z
  - 原始模型：SD 1.5
  - 下载数：200
  - 评分人数：0
  - 评分：0
- 下载地址
  - [caricaturePortraits_v10.safetensors](https://civitai.com/api/download/models/79657)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d24e3768-12f4-4874-98af-0514d96653b3/width=450/893932.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d182bcfc-0b48-4fcb-9fd2-b2ed489f2f8c/width=450/893931.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/92b0aa58-14d3-488f-827d-de57aedb1967/width=450/893927.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3bb7794d-b7af-4bab-91fe-c0512441aaee/width=450/893921.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>Caricature portraits diffusion model</h1><p>Stable Diffusion v1.5 fine tuned on the 2D Caricature Dataset from <a target="_blank" rel="ugc" href="https://github.com/qq775193759/3D-CariGAN">3D-CariGAN</a> cropped to 512x512 and blip captioned. If you want more details on how to generate your own blip captioned dataset see this <a target="_blank" rel="ugc" href="https://colab.research.google.com/gist/Norod/ee6ee3c4bf11c2d2be531d728ec30824/buildimagedatasetwithblipcaptionsanduploadtohf.ipynb">colab</a></p><p>Training was done using this Hugging-Face's text to image training <a target="_blank" rel="ugc" href="https://github.com/huggingface/diffusers/blob/main/examples/text_to_image/train_text_to_image.py">script</a></p><p></p><h2>Dataset and Training</h2><p>Finetuned for 10,000 iterations upon <a target="_blank" rel="ugc" href="https://huggingface.co/runwayml/stable-diffusion-v1-5">runwayml/stable-diffusion-v1-5</a> on <a target="_blank" rel="ugc" href="https://huggingface.co/datasets/Norod78/caricature-portraits-blip-captions-512">BLIP captioned portraits portraits</a> using 1xA5000 GPU on my home desktop computer</p><p>Trained by <span data-type="mention" class="mantine-1yiar0p" data-id="mention:6761" data-label="norod78">@norod78</span></p><p></p><h3>The original Caricature dataset citation credits</h3><pre><code>@article{ye2021caricature,
 author = {Ye, Zipeng and Xia, Mengfei and Sun, Yanan and Yi, Ran and Yu, Minjing and Zhang, Juyong and Lai, Yu-Kun and Liu, Yong-Jin},
 title = {3D-CariGAN: An End-to-End Solution to 3D Caricature Generation from Normal Face Photos},
 journal = {IEEE Transactions on Visualization and Computer Graphics},
 year = {2021},
 doi={10.1109/TVCG.2021.3126659},
}
</code></pre>