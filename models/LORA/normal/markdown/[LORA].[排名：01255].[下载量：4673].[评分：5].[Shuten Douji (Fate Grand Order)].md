## Shuten Douji (Fate Grand Order)
### 一、模型概述

- 标签：`anime`, `character`, `female`, `fate`, `fate grand order`
- 下载数：4673
- 收藏人数：984
- 评论人数：4
- 评分人数：10
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-04-19T13:04:20.329Z
  - 原始模型：SD 1.5
  - 下载数：3725
  - 评分人数：7
  - 评分：5
- 下载地址
  - [ShutenDoujiV11-000003.safetensors](https://civitai.com/api/download/models/49860)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ff963e4f-0287-45ba-019e-83567bff8800/width=450/538763.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d795c760-b4ad-47e3-4d50-b50c7865d300/width=450/536191.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b3662a74-9000-47ba-465c-1125849faf00/width=450/536192.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/317400a8-0c2a-47e4-9130-bdaff5a7e600/width=450/536193.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v0.9

- 统计数据
  - 发布时间：2023-04-19T12:59:35.541Z
  - 原始模型：SD 1.5
  - 下载数：948
  - 评分人数：3
  - 评分：5
- 下载地址
  - [ShutenDoujiV09-000024.safetensors](https://civitai.com/api/download/models/48336)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9b7ff6a9-2461-4d70-6b92-ee9d681fb700/width=450/519099.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ec3d04c-c596-4dda-3c4c-4c591751b300/width=450/519088.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1dc84a90-c2e9-4eab-db49-4b696de8f400/width=450/519089.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b3cbc36b-6d08-4b8c-40b9-1faba653d500/width=450/519105.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Replaced main image because it triggered me that I accidentally made all the images in different size than usual. Those cheap oni tricks! Got me again!</p><h3>v1 Description</h3><p>Lora model of Shuten Douji from Fate Grand Order. Preview images done with weight 0.8-1.</p><p>I think this one will finally be a final version. It still have faults, but it feels more accurate than the previous one and I think I can leave it at that ^_^; I feel I bit more than I could chew cause I intended to try out different approaches here for better results, but at the same time I used bigger dataset than ever before so it was slow process. I should do something smaller next try to test more rapidly.</p><p>Also random disclaimer - keep in mind that if you copy generation data from Civitai images <u>make sure to change lora name in tag to your lora file name</u>. Earlier I stopped including that part in prompt because it was driving me mad to see so many get that wrong &gt;_&lt; it's the same for all Lora so keep it mind.</p><p>So now to prompts, they are mostly similiar to the ones before. I've ogranized them better from top to bottom for your convenience:</p><ul><li><p>Standard minimum outfit - <strong>shuten douji, headpiece, revealing clothes, bare arms, ankle ribbon, barefoot sandals. </strong>Kimono will often try to make its wy back so you can add things like <strong>purple kimono, off shoulder, open kimono</strong> to negative to ease the problem.</p></li><li><p>Standard kimono outfit - <strong>shuten douji, headpiece, revealing clothes, purple kimono, bridal gauntlets, obi, knee pads, ankle ribbon, barefoot sandals</strong>. You can control how much kimono is open by using <strong>open kimono</strong> and <strong>off shoulder</strong>, but it's not the exact science. Also a lot depends on tags <strong>obi </strong>and <strong>revealing clothes</strong>. Just include what you want to see.</p></li><li><p>Jiangshi outfit - <strong>shuten douji, jiangshi, qing guanmao, (ofuda:0.9), hair rings, china dress, frilled sleeves, long fingernails, sash, jingle bell, flats</strong>. Fingernails are a pain cause they just make hand problems more obvious so you may want to be careful with that. Also better do ofuda weight lower like in example cause you can get too many of them otherwise.</p></li><li><p>Halloween caster outfit - <strong>shuten douji, forehead jewel, earrings, black choker, short twintails, dudou, rope, shimenawa, detached sleeves, shawl, star print, layered skirt, fundoshi, pelvis curtain, stirrup legwear. </strong>The prompt for rope, shimenawa may often require more weight to look right. Also it can be pretty hard to remove shawl, star print.</p></li><li><p>Black kimono - <strong>shuten douji, headpiece, horn ornament, choker, black kimono, obi, floral print, geta, anklet. </strong>Tag for facial mark was trained too but I wouldn't bother cause it's not looking anything liek it's suppose to. Also you can try adding <strong>(checkered clothes, black scarf) </strong>but it rarely works like it's suppose to. From my experience this often needs lower Lora weight more than others.</p></li><li><p>Maid outfit - <strong>shuten douji, maid, maid headdress, headpiece, detached collar, bowtie, puffy sleeves, black dress, wrist cuffs, maid apron, garter straps, black thighhighs, high heels</strong>. She is very likely to display upskirt if pose allows it (at least on base model I used) so you may want to add something like<strong> skirt lift, panties, holding clothes</strong> to negative.</p></li><li><p>Travel outfit - <strong>shuten douji, headpiece, black choker, hood, black jacket, off shoulder, open jacket, pink hoodie, clothes writing, leggings, sneakers</strong>. Hoodie will often end up green because model failed to learn consistenly that green comes from inside of jacket, but I feel it still looks fine.</p></li><li><p>Punk outfit - <strong>shuten douji, eyewear on head, headpiece, multicolored hair, collar, leather jacket, open jacket, print shirt, clothes writing, bracelet, wristband, spiked bracelet, black shorts, fishnet pantyhose, thigh strap</strong>. Details are fairly off but still looks somewhat right ^_^ eyewear on head is a hit or miss so might want to remove that if you don't want it.</p></li></ul><p></p><h3>v0.9 Description</h3><p>Lora model of Shuten Douji from Fate Grand Order. Preview images done with weight 0.8-1.</p><p>Sadly even after I spent few days on this, it's still work in progress T_T so hopefully I'll update shortly.</p><p>I'll describe prompts better when I'm happy with it, so for now just in short:</p><ul><li><p>Standard minimum outfit - <strong>shuten douji, revealing clothes, headpiece, ankle ribbon, barefoot sandals, bare arms</strong></p></li><li><p>Standard kimono outfit - <strong>shuten douji, revealing clothes, headpiece, ankle ribbon, barefoot sandals, bridal gauntlets, purple kimono, obi, knee pads</strong></p></li><li><p>Jiangshi outfit - <strong>shuten douji, jiangshi, qing guanmao, long fingernails, china dress, hair rings, jingle bell, flats, sash, frilled sleeves, ofuda</strong></p></li><li><p>Halloween caster outfit - <strong>shuten douji, dudou, forehead jewel, detached sleeves, earrings, short twintails, fundoshi, shimenawa, black choker, shawl, star print, stirrup legwear, layered skirt, pelvis curtain</strong></p></li><li><p>Black kimono - <strong>shuten douji, black kimono, hair flower, floral print, choker, facial mark, headpiece, geta, anklet, black scarf, obi, horn ornament</strong></p></li><li><p>Maid outfit - <strong>shuten douji, maid, maid headdress, black thighhighs, puffy sleeves, garter straps, wrist cuffs, maid apron, high heels, bowtie, detached collar, headpiece, black dress</strong></p></li><li><p>Travel outfit - <strong>shuten douji, hood, black jacket, open jacket, pink hoodie, sneakers, leggings, black choker, off shoulder, clothes writing, headpiece</strong></p></li><li><p>Punk outfit - <strong>shuten douji, open jacket, clothes writing, bracelet, collar, wristband, leather jacket, print shirt, fishnet pantyhose, thigh strap, eyewear on head, multicolored hair, black shorts, headpiece, spiked bracelet</strong></p></li></ul><p>The last two, while not closely accurate actually work best for me.</p>