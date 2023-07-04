## IronCatFateToon
### 一、模型概述

- 标签：`anime`, `vibrant colors`, `line art`, `style`, `fate stay night`
- 下载数：799
- 收藏人数：266
- 评论人数：7
- 评分人数：8
- 评分：4.88

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-04-15T01:42:45.193Z
  - 原始模型：SD 1.5
  - 下载数：741
  - 评分人数：6
  - 评分：4.83
- 下载地址
  - [ironcatfatetoon_v10.safetensors](https://civitai.com/api/download/models/45203)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/13dc7a18-37f4-498f-9879-8c9186aaa100/width=450/497929.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/615a496b-0d8f-42ea-3653-5f01ba245800/width=450/497934.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/54acaaed-8a64-4447-67a2-54ec14558000/width=450/510716.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/38bb428f-e2ea-4b5d-43cd-85635d27cd00/width=450/510731.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0-no-vae

- 统计数据
  - 发布时间：2023-04-15T01:48:56.683Z
  - 原始模型：SD 1.5
  - 下载数：58
  - 评分人数：2
  - 评分：5
- 下载地址
  - [ironcatfatetoon_v10NoVae.safetensors](https://civitai.com/api/download/models/45969)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5a23c23e-e128-4163-16d6-cf2283060200/width=450/497560.jpeg" /> |
| ---- |


### 三、详情
<h2><strong>IronCatFateToon</strong></h2><p><strong>Making models is a thing I do for fun. So if you like what I do? You can help me out by just using the model and leaving a review!</strong></p><p>IronCatFateToon's goal is to be able to create nice looking anime style images with vibrant colours, more simplistic anime <em>(cartoony)</em> colour/style look and with influence of Fate/Stay Night: Unlimited Blade Works styling.</p><p><s>This checkpoint </s><strong><s>requires </s></strong><s>a VAE, I recommend </s><a target="_blank" rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/tree/main/vae"><s>kl-f8-anime2</s></a><s>, I've also used it for the examples.</s> <strong>Edit</strong>: Since the original upload of this checkpoint, I've updated <code>v1.0</code> itself and reuploaded the checkpoint with the VAE baked in. If you prefer the checkpoint without it baked in, download the <code>v1.0-no-vae</code> version.</p><p>In order to achieve what's just been promised I used <a target="_blank" rel="ugc" href="https://civitai.com/models/7240/meinamix">MeinaMix V8 </a>as the base checkpoint, I then merged two of my style LoRA's into MeinaMix V8; <a target="_blank" rel="ugc" href="https://civitai.com/models/32664/ironcatlora-3-anime-vibrancy-and-simplifier-style">Anime vibrancy &amp; simplifier Style</a> (Merge ratio of <code>0.4</code>`) &amp; <a target="_blank" rel="ugc" href="https://civitai.com/models/35050/ironcatlora-4-fatestay-night-ubw-style">Fate/stay night: UBW Style</a> (Merge ratio of <code>0.6</code>`) . And finally I merged the result of that with the checkpoint <a target="_blank" rel="ugc" href="https://civitai.com/models/24149/mistoonanime">Mistoon_Anime</a>. Where I did a weighted merge, 70% was used from the results of me merging the LoRA's into MeinaMix V8. And 30% was used for Mistoon_Anime. <em>(</em><strong><em>Note:</em></strong><em> I didn't use the exact same Anime vibrancy &amp; simplifier Style LoRA when merging, I retrained on the same dataset from that LoRA for a more nuanced look that complimented MeinaMix V8 better i.m.o.)</em></p><p>Some things you might recognize from Fate/stay night: UBW in this checkpoint, is in the way how eyes, scenery, city, cityscape, sky, grass, trees, certain 2.5D angles et cetera are generated. The anime/cartoony look is a combination from my Anime vibrancy &amp; simplifier Style LoRA and Mistoon_Anime. While MeinaMix V8 as a base gives in my own opinion a really sollid base for good looking art.</p><p>I haven't used any embeddings in the example images so you should get a good idea, in what the checkpoint can create on its own. I generated the images using some wildcard libraries, so the prompts might sometimes seem random.</p><p><strong>Advice</strong>:</p><ul><li><p>I would recommended a clip skip of 2</p></li><li><p>I personally like <a target="_blank" rel="ugc" href="https://upscale.wiki/wiki/Model_Database">lollypop </a>as an upscaler a lot, it gives anime images a nice soft upscaled touch.</p></li><li><p>I am personally a fan of using DPM++ SDE Karras with 15 steps and when Hires fixing, I like to use 10 for Hires steps and a denoise of about 0.35 or 0.4. Most example images use 512x768 as base resolution.</p></li><li><p>If you want the same vibrant, high contrast style look from my images you've seen, mostly in the images with girls, I suggest the following starter prompt: <code>(masterpiece, best quality:1.4), cinematic light, colorful, high contrast</code>, the prompt <code>cinematic light</code> is optional but I've used it in most of the example images since I liked the look. The <code>high contrast</code> prompt may sometimes do bad in certain NSFW generations, if you notice it in a seed you can try to remove it.</p><ul><li><p>The starter prompt is not necessarily needed, I also included 2 examples where I just typed out a story based prompt and only used the negative prompt like below. And those images also came out great i.m.o.</p></li></ul></li><li><p>I would advice the following starter negative prompt in general to get the look you see in most of my example images: <code>(worst quality:1.2), (low quality:1.2), (lowres:1.1), (monochrome:1.1), (greyscale), multiple views, comic, sketch</code>. You can also use my full negative prompt from my sample images, if you liked the look of them.</p><ul><li><p>The <a target="_blank" rel="ugc" href="https://huggingface.co/nick-x-hacker/bad-artist">bad-artist negative embedding</a> seems to work pretty nice too, which you can try instead of my suggested negative prompt.</p></li></ul></li></ul><p></p><p>This model wouldn't have been possible without these awesome creators:</p><ul><li><p><span data-type="mention" class="mantine-1yiar0p" data-id="mention:141871" data-label="Meina">@Meina</span> for <a target="_blank" rel="ugc" href="https://civitai.com/models/7240/meinamix">MeinaMix V8</a></p></li><li><p><span data-type="mention" class="mantine-1yiar0p" data-id="mention:94216" data-label="Inzaniak">@Inzaniak</span> for <a target="_blank" rel="ugc" href="https://civitai.com/models/24149/mistoonanime">Mistoon_Anime</a></p></li><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/hakurei">hakurei</a> for <a target="_blank" rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/tree/main/vae">kl-f8-anime2</a></p></li></ul>