## TGL Psy
### 一、模型概述

- 标签：`dark`, `psycho`, `style`, `hallucinogenic`, `psychoactive`, `otherworldly`, `horrid`
- 下载数：273
- 收藏人数：63
- 评论人数：1
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-06T07:33:24.995Z
  - 原始模型：SD 1.5
  - 下载数：273
  - 评分人数：0
  - 评分：0
- 下载地址
  - [tglPsy_v10.safetensors](https://civitai.com/api/download/models/90218)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/74e750de-d2fd-40f7-9369-f7bb110cf6f2/width=450/1046654.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4a15f7da-0176-46cd-943b-d6bcd325055b/width=450/1046660.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e02eb049-a432-476e-aa09-6ec968397acb/width=450/1046665.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d87e866b-1b9e-460b-ab7b-1902011ed89b/width=450/1046656.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>A rather dark-psy inspired model (over)trained on 200+ AI Generated training images and a custom set of AI Generated regularization images, for a total of 23K steps.<br />The model was trained on images generated with SD 1.5 using the following artists and artstyles as sole prompts.</p><pre><code>Pablo Picasso, Alex Grey, Zdzisław Beksiński, Katsuhiro Otomo, H.P. Lovecraft, Clive Barker, M. C. Escher, H.R. Giger, Yves Tanguy, Andy Warhol, Jackson Pollock, Frida Kahlo, Marcel Duchamp, Salvador Dalí, Georgia O'Keeffe, Yayoi Kusama, Jean-Michel Basquiat, Ai Weiwei, Dadaism, Fluxus, Surrealism, Abstract Expressionism, Pop Art, Outsider Art, Neo-Dada, Street Art/Graffiti, Installation Art, Performance Art, Biomechanical, Soviet Propaganda</code></pre><p><strong><em>Even the regularization images</em> are AI generated interpretations of those artists/art styles!</strong></p><p></p><p>Use this model if you want to get surprises. Even just prompting for the class and keywords (`artstyle bse`) will get you quite some results.</p><p>It cannot do faces, hands very well. You can get lucky (see example shots), but it is not the purpose of the model anyway.</p><p><strong>I strongly suggest using this model when you want to get very artsy, psy, otherworldly. </strong><br /><br />I did a <em>lot</em> of experiments with this model and all its intermediaries (I saved each 5k steps during the dreambooth training) and found that it works best with the following settings:<br /><br /><strong>Positive prompt:</strong></p><p><code>artstyle bse ((YOUR TOPIC GOES HERE)), best quality, masterpiece, ultra high res, (photorealistic:1.4), raw photo, sharp focus, HDR, detailed skin</code><br /><strong>Negative Prompt</strong></p><p><code>Anime, cartoon, ng_deepnegative_v1_75t, (badhandv4:1.2), (worst quality:2), (low quality:2), (normal quality:2), lowres, bad anatomy, bad hands, normal quality, (monochrome), (grayscale), watermark</code><br /><strong>Resolution:</strong></p><p><code>512^2</code></p><p><strong><span style="color:rgb(229, 231, 235)">Sampling method</span></strong></p><p><code>DDIM</code></p><p></p><p>You can also get interesting results with larger resolutions like <code>1200x900</code>, by increasing the steps massively, although not useful for subjects, it can be interesting for "backgrounds"</p><p></p><p><strong>Resources:</strong><br /><strong>I used both </strong><code>badhandv4</code> (<a target="_blank" rel="ugc" href="https://civitai.com/models/16993/badhandv4-animeillustdiffusion">https://civitai.com/models/16993/badhandv4-animeillustdiffusion</a>) and <code>ng_deepnegative_v1_75</code> (<a target="_blank" rel="ugc" href="https://civitai.com/models/4629/deep-negative-v1x">https://civitai.com/models/4629/deep-negative-v1x</a>) in almost all prompts.<br /><br /><strong>PS:</strong><br /><strong>you will notice that the prompts in all pictures say the model used is </strong><code>baked</code>. That is because I dumbass renamed the model <em>after</em> I downloaded it from my SD online instance and <em>after</em> I generated all tons of images with it. As I had named it <code>baked</code> in the SD instance, that is what the images meta data tell too. However, the model used to generate those image <em>is</em> the current uploaded <code>TGL Psy</code> model, you can verify this by simply recreating the images.</p>