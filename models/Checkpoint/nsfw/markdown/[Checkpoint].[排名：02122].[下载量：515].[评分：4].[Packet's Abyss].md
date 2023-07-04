## Packet's Abyss
### 一、模型概述

- 标签：`anime`, `porn`, `stylized`, `fantasy`, `girls`, `portraits`
- 下载数：515
- 收藏人数：144
- 评论人数：1
- 评分人数：2
- 评分：4

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Packet's Abyss v1

- 统计数据
  - 发布时间：2023-02-23T23:07:57.199Z
  - 原始模型：SD 1.5
  - 下载数：515
  - 评分人数：2
  - 评分：4
- 下载地址
  - [packetsAbyss_packetsAbyssV1.safetensors](https://civitai.com/api/download/models/13798)
  - [kl-f8-anime2.vae.ckpt](https://civitai.com/api/download/models/13798?type=VAE&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/96e03471-8ea3-4f34-059d-64150dd28a00/width=450/133748.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/42af54c4-a470-45ed-b960-fea07f957f00/width=450/133764.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/48be1668-b193-42df-7b2d-5628a3a47700/width=450/133766.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/77a7f324-42a6-4478-1035-bc1832e08f00/width=450/133765.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2528333e-8e6a-469f-0027-66e8af3c5e00/width=525" /><h2><strong>Packet's Abyss v1</strong></h2><p>I really liked AOM3A3, but had some issues when I tested it out with my prompts, so I ended up creating a big multi model block weighted merge until I felt like I had something satisfactory, and then merged the upper 18 layers of that into AOM3A3. It will usually hit close to the <em>composition</em> of a scene from AOM3A3 if given the same prompt and seed, but not necessarily the appearance. <strong><u>FOR ME</u></strong> my mix does anatomy better. No guarantees the same will be true for you. Ultimately it has similar capabilities to AOM3, but its own look.</p><p></p><p>I struggled with whether I should upload this or not, Civit is already overrun with mixes. I've tried a lot of them actually and most of them just don't do it for me. They tend to be either too generalized, too focused, too airbrushed looking, so on. This mix is capable of much more than what I've posted in the examples, but I want people to see what they can make minimal effort. You don't need a buttload of style tags on your prompt with this model. Most (maybe all) of the images I provided use simple prompts that were made by ChatGPT, along with the suggested positive and negative tags listed below.</p><p></p><p>It contains bits of the following:</p><p>Abyss Orange Mix 3 A3, Darkfruit, Ventidos, Eunpyon, Anylact, Woop10, Liberty, Protogenx58, and a personal mix I tossed together months ago that I no longer have the recipe to, but was also a BWM mess of multiple models. Generally As I'm merging stuff together I think about what model does which thing well, and try to merge the corresponding layers that contain the wanted details in a tiny bit at a time until I get something that looks good. I tried to remember to keep the base alpha and M layer of AOM3A3 the entire time. This is a slow process, there were probably ~50 merges made when putting this together. Was it worth the effort? Probably not, it seems every time I find myself happy with a mix something new gets posted.</p><p>*I actually already also have a few variants of this I've tossed together that I'll upload eventually.</p><p></p><p>Yes you can make hardcore with it, though I haven't really tried beyond a quick prompt or two to verify the capability was indeed there.</p><p></p><p>Prompting information and settings</p><p>Just like AOM3 I suggest your prompts start with at least:</p><p>positive: hires, best quality</p><p>negative: (low quality:1.4),(worst quality:1.4)</p><p>(hyper-realistic digital illustration) in the positive cranks up the detail a bit, but if you're wanting to stay close to anime you might not want that.</p><p></p><p>I like to use:</p><p>postive: (hyper-realistic digital illustration), hires, best quality</p><p>negative: (low quality:1.4),(worst quality:1.4), (((watermark))), extra fingers, mutated hands, ((poorly drawn hands)), ((extra limbs)), (extra anuses), (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (fused arm), (fused leg), (conjoined twin), (too many fingers)</p><p></p><p>Not long ago I didn't believe that negatives could actually help hands but.. this seems to actually work quite well.</p><p></p><p>Sampler: DPM++ 2m Karras @ 24 steps</p><p>CFG Scale: 9-11</p><p>Hires Upscaler: 4x-UltraSharp</p><p>Denoise Strength: 0.47</p><p></p><p></p><p>As for licensing - <strong>assume you can't use this for any commercial purposes whatsoever</strong>, since this may contain bits of models that had licensing stipulations.</p><p></p>