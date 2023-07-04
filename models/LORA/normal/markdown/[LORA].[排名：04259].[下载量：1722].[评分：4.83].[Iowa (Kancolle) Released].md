## Iowa (Kancolle) Released
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `kantai collection`, `kancolle`, `game character`
- 下载数：1722
- 收藏人数：392
- 评论人数：2
- 评分人数：6
- 评分：4.83

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v6

- 统计数据
  - 发布时间：2023-04-25T08:56:52.051Z
  - 原始模型：SD 1.5
  - 下载数：1174
  - 评分人数：3
  - 评分：4.67
- 下载地址
  - [KC_IowaV6F-000009.safetensors](https://civitai.com/api/download/models/32907)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/19efb83e-a3a1-40a0-90ac-12094be91700/width=450/374933.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f517dd0f-881a-48c0-b78f-2f66ae846c3f/width=450/1247447.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/87167be1-6468-42d0-01cb-1aea7cbc9800/width=450/374934.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c1f86440-6320-45da-c736-7a0b15502d00/width=450/374932.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] Beta v2

- 统计数据
  - 发布时间：2023-04-03T18:11:16.853Z
  - 原始模型：SD 1.5
  - 下载数：548
  - 评分人数：3
  - 评分：5
- 下载地址
  - [KC_IowaV2-000012.safetensors](https://civitai.com/api/download/models/24944)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d06a548a-79dd-48d3-27d9-3f73b746da00/width=450/276344.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/98cb56d9-a526-45b1-e8c6-9836c43b6900/width=450/276343.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ac8a566d-06b2-4ae1-d393-13b09b486200/width=450/276342.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6800f0a1-b0cf-4bd9-7548-b24fab072500/width=450/276341.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Finally.</p><p><strong>This LoRA model isn't very user-friendly, be patient to read description if you want to get a good result.</strong></p><p>I learnt a lot from this model (like training methods, tuning configs, tagging, and dataset quality controls), I hope this will also help you to find way to control other models :D</p><p></p><p><u>在开始之前，我希望大家可以阅读一下</u><a target="_blank" rel="ugc" href="https://www.pixiv.net/artworks/106439383"><u>这篇</u></a><u>关于我训练的模型的使用守则。最近我已经看到不少作者因为有人逾越了模型允许使用的范围，让作者不得不下架模型的情况。请不要让我成为下一个。</u></p><p><u>始める前に、私がトレーニングしたモデルの使用に関するこの</u><a target="_blank" rel="ugc" href="https://www.pixiv.net/artworks/106439383"><u>利用規範</u></a><u>を読んでいただきたいのです。 最近、モデルの使用を許可範囲を越えてしまったために、作者がモデルを削除しなければならない事例をかなり見てきました。 どうか私を次の人にさせないでください。</u></p><p><u>Before we started, I hope you read </u><a target="_blank" rel="ugc" href="https://www.pixiv.net/artworks/106439383"><u>this</u></a><u> for acknowledging my model's guideline. I've seen lot of authors stop sharing models because some of you exceeding the author permission. Don't make me become the next one.</u></p><p></p><p>Done? Good, let's go. :)</p><h3>Base Prompts and Settings</h3><p>Settings:</p><ul><li><p>DPM++ Series(SDE Karras, 2M Karras, etc.)</p></li><li><p>Base Width&amp;Height: 512&lt;X&lt;1024</p></li><li><p>If you want to generate eyes bit easily, a larger hi-res fix resolution + more render steps + prompts to closer character is necessary. <u>Recommend resolution is over 1600x900.</u></p><p></p></li></ul><p>Prompts:</p><p>Sorted from top to bottom. If you want to generate closer looks, start with tags like <u>cropped legs, feet out of frame, </u>and delete the part you don't want to show.</p><ul><li><p>Base (Weight 0.8):</p><ul><li><p><strong>iowa \(kancolle\), IowaOthers,</strong> alternate costume, ahoge, blue eyes, (star-shaped pupils:1.2),long hair</p><p>large breasts</p></li><li><p>Negative:(IowaOrigin, alternate haristyle:1.3)</p><p></p></li></ul></li></ul><ul><li><p>Original Outfits (Weight 0.9-0.1):</p><ul><li><p><strong>iowa \(kancolle\), IowaOrigin, </strong>ahoge, long hair, blue eyes, (star-shaped pupils:1.2),(headgear:1.1),</p><p>breasts, cleavage, underbust, front-tie top, chain, bare shoulders,</p><p>elbow gloves, wrist cuffs, (fingerless gloves:1.2),</p><p>midriff, garter straps, garter belt, buckle, belt, miniskirt, striped skirt,</p><p>(vertical-striped legwear, mismatched legwear:1.2),</p><p>high-heel boots, (knee boots: 1.2),</p></li><li><p>Negative: (pleated skirt, skirt, ponytail, alternate costume, alternate hairstyle:1.2),</p></li></ul></li></ul><p></p><ul><li><p>New Year Outfits (Kimono) (Overfitted, Weight 0.6-0.8):</p><ul><li><p><strong>iowa \(kancolle\), IowaKimono, </strong>hair flower, kanzashi, alternate hairstyle, ahoge, folded ponytail , blue eyes, (star-shaped pupils:1.2), (headgear:1.1), hair ornament,</p><p>japanese clothes, vertical-striped kimono, fur trim, fur-trimmed kimono, furisode, obi, obiage, obijime</p><p>tabi, geta,</p></li><li><p>Negative: Nsfw, (legs, barefoot, bare legs, thighs, knees, bare shoulders, cleavage, collarbone, short kimono, kimono skirt, skirt, miniskirt, IowaOrigin,:1.4),</p></li></ul></li></ul><p></p><ul><li><p>Swimsuit (Bikini+Baseball cap) (Overfitted, Weight 0.8-0.9):</p><ul><li><p><strong>iowa \(kancolle\), IowaBikini, </strong>baseball cap, alternate costume, alternate hairstyle, ahoge, blue eyes, (star-shaped pupils:1.2),blue eyes, star hair ornament,</p><p>sandals</p></li><li><p>Negative: short shorts</p></li></ul></li></ul><p></p><h3>Model Suggestion</h3><p>If you want the chara be very detailed, <strong>get rid of AOM3 series or other painting model like Dalcefo series</strong>, untested on 3d models, but definitely not suggested.</p><p>Since my laptop is pretty poor in SD generations, I haven't test much models, but those models/LoRAs are good to use with the chara LoRA.</p><ul><li><p>Models:</p><ul><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/andite/anything-v4.0">Anything V4.5</a></p><ul><li><p>Basic, easy to handle with bunch of artstyle LoRA.</p></li></ul></li><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/mdl-mirror/ExpMix_Line/discussions/1">Expmix_Line</a></p><ul><li><p>A Counterfeit-based Mix, pretty good on generate details, but will make the outline very thick. You can merge it with AOM3 to improve AOM3's LoRA capability.</p></li></ul></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/4468/counterfeit-v25">Counterfeit V2.5</a></p><ul><li><p>Okay to use, but poor artstyle LoRA capability. Good enough for big scene.</p></li></ul></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/24387/aniflatmix-anime-flat-color-style-mix">Aniflatmix</a></p><ul><li><p>Color is bit hard to control, but definitely is the easiest one to generate good pics with the least twist. Still, don't have a very good LoRA capability, the chara's cloth will be slightly different to original one.</p></li></ul></li></ul></li><li><p>Artstyle LoRAs:</p><ul><li><p>Pastel Mix</p><ul><li><p>Don't need to say anything about it. It Just works.jpg</p></li></ul></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/5406/ligne-claire-stylecogecha">ligne claire style</a></p><ul><li><p>Add details, helpful for better eyes.</p></li></ul></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/5941/asanagi-style-lora">Asanagi artstyle</a></p><ul><li><p>Believe it or not, it will help with better eyes. Suggest weight &lt;0.4</p></li></ul></li><li><p><a rel="ugc" href="https://civitai.com/models/16997/standing-full-body-with-background-style-lora">Standing Full Body with Background Style LoRA</a></p><ul><li><p>Good background with less drawbacks for charactor details.</p></li></ul></li><li><p>Other fixs like <a rel="ugc" href="https://civitai.com/models/8730/hipoly-3d-model-lora">Hipoly 3D Model LoRA (Weight 0.2-0.3)</a>or <a rel="ugc" href="https://civitai.com/models/16993/badhandv4-animeillustdiffusion">badhandv4 + easynegatives </a>are good for generate stable characters.</p></li></ul></li></ul>