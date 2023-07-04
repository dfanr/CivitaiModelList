## Species
### 一、模型概述

- 标签：`character`, `general purpose`, `woman`, `fantasy`, `game character`, `man`, `video game`
- 下载数：1059
- 收藏人数：214
- 评论人数：19
- 评分人数：3
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v0.8

- 统计数据
  - 发布时间：2023-06-12T01:40:38.552Z
  - 原始模型：SD 1.5
  - 下载数：218
  - 评分人数：0
  - 评分：0
- 下载地址
  - [species_v08.safetensors](https://civitai.com/api/download/models/93446)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/590ac11c-edca-4610-830d-b5cbcb315a9e/width=450/1115839.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0feac723-8ff6-4359-b3ca-0864776f3d56/width=450/1115836.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0939d766-92c7-4c07-96f6-39f1f2df1da5/width=450/1115838.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9ae99f7a-5e53-4958-af37-9bb7f7b4afa9/width=450/1115840.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v0.3

- 统计数据
  - 发布时间：2023-06-11T00:51:24.668Z
  - 原始模型：Other
  - 下载数：276
  - 评分人数：1
  - 评分：5
- 下载地址
  - [species_v03.ckpt](https://civitai.com/api/download/models/20758?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [species_v03.safetensors](https://civitai.com/api/download/models/20758)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/af0fcc7e-bde3-4439-7615-a62bbb963200/width=450/219741.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8cb8156d-0a06-489b-a514-fea35709fe00/width=450/219742.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c210b728-ec97-43a8-7200-29c338c80800/width=450/221111.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8ab51c36-6a9a-4114-296e-c3effbed7000/width=450/219744.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v0.5

- 统计数据
  - 发布时间：2023-06-11T00:51:24.668Z
  - 原始模型：SD 1.5
  - 下载数：565
  - 评分人数：2
  - 评分：5
- 下载地址
  - [species_v05.ckpt](https://civitai.com/api/download/models/25724)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f41416a5-b338-4837-ff69-50adcd6b7900/width=450/282733.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/548270dc-f524-403e-fbda-747d5f5d6300/width=450/282732.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/818ce453-5c98-4b99-f927-b460a3dea400/width=450/282731.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/63b54f62-0946-4e03-1668-d9684b176d00/width=450/282730.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-1573">Species</h1><p>This model is mostly an experiment to see if I could add various concepts that I wanted into the base model. I think it worked well enough so I'm sharing in case anyone else also wants those things</p><p>trained at 768x768 using EveryDream2</p><p>some folks have asked for LORAs, I've decided I'm not going to bother. I really doubt a lora can reasonably handle this many things. you should find one for the specific species you want if you want a lora</p><h3 id="heading-1574">concepts included:</h3><ul><li><p>"Centaur" and "x taur" (where x is some animal, "deer", "cat", etc), both of these work really well across multiple styles and characters, although you will occasionally get a horse or a mutant</p></li><li><p>"slime" also works very consistently</p></li><li><p>"Klingon" works very well, "bat'leth" is in there but sucks.</p></li><li><p>"Twi'lek" works well, but messes up the head tails about as often as it does arms</p></li><li><p>"Trill" works okay, but tends to add spots in the wrong places, probably needed more training</p></li><li><p>"Ferengi", gets the head shape good, but faces are a bit weird</p></li><li><p>"Asari" works really well, does men fine even though there were none in training data</p></li><li><p>"Satyr" works pretty well, occasionally it thinks "centaur" for no reason I understand</p></li><li><p>"Cardassian" works nicely</p></li><li><p>"Tortle" is good, "ninja tortle" does too ;)</p></li><li><p>it's silly but I added "foodfolk" in</p></li><li><p>"Myconid" generally works, although it wants to just do people with mushroom hats a lot</p></li><li><p>"gorgon" is alright. sometimes it even gets the snake heads kinda okay. wants them to be screaming, so I should have labeled facial expressions better. added a bit of "naga" as well, and the two mix well</p></li><li><p>"giant x" works pretty well given context, like "walking in a tiny city" or "in the mountains"</p></li><li><p>"tiny x" works sometimes, but is inconsistent. definitely needs context. "trapped in a jar" or "on a giant table" work fairly well</p></li><li><p>"salarian" works good</p></li><li><p>"quarian" works good</p></li><li><p>"krogan" works well, but it doesn't really get gender (not a lot of art of krogan women without a veil)</p></li><li><p>"drell" works well</p></li><li><p>"luxan" works pretty good, although it's hyperfocused on the one character it's seen a lot of</p></li><li><p>can do "leviathan pilot" as long as you don't want the body</p></li><li><p>"andorian" is pretty good, forgets the antenna a lot, same for "namekian"</p></li><li><p>"togruta" is good, though it gets the tails messed up sometimes</p></li><li><p>"wookie is good, but it doesn't really get gender there</p></li><li><p>"bolian" is okay, gets it right sometimes but not always. didn't put enough data in there</p></li><li><p>"t-rex" is better trained than it was, gets things right sometimes</p></li><li><p>"gungan" is pretty good, maybe 30% without big mistakes?</p></li><li><p>"drowned folk" came out pretty well imo</p></li><li><p>I added "dullahan" but it really confuses things and rarely gets it right, same for "cyclops"</p></li><li><p>"x elemental" works nicely, try weird things for x ;)</p></li><li><p>"goblin" got a lot of training in here. lots of modifiers too, try these: "pathfinder", "cute", "orc", "half orc". a bunch of more general ones listed below</p></li><li><p>"talaxian" works pretty well</p></li><li><p>"jem'hadar" works nicely in some styles, not all</p></li><li><p>"na'vi" works pretty well but also has a big style bias</p></li><li><p>"kaminoan" is pretty good, although neck length is all over the place</p></li><li><p>added some "human" training to prevent bleed, feel free to use it in the negatives too</p></li><li><p>"garuda" works pretty well</p></li><li><p>"poseable doll" is a fun one, really wants to be a photo though</p></li><li><p>"lizardfolk" and "draconic lizardfolk" are good</p></li><li><p>"viera" is pretty good, although goes full rabbit head more than I'd like</p></li><li><p>"vulcan" works good, some are also tagged "romulan"</p></li><li><p>lots of fantasy things that had some representation got more training and work more reliably now: "naga", "merfolk", "fairy", "angel", "succubus", "minotaur", "mummy", "griffin", "gnoll", "elf", "dryad", "treefolk", "ghost", "harpy", "sphinx", "genie"</p></li><li><p>lots of generic tags were included in training, haven't tested this super well, but all of these should be useable in positive and negative prompts: "blue/red/green/bark/purple skin", "red/glowing eyes", "tail", "devil tail", "pointed ears", "pointed nose", "tusks", "extra arms", "small/hip/dragon/feathered wings", "clothes torn", "holding x", "x on their shoulder", "small/ram/big horns" and probably lots more I'm forgetting</p></li><li><p>"transformation sequence" I added on a lark, and wasn't expecting it to work well. It doesn't exactly work well, but it's better than I expected. "transformation sequence, man into woman" works the best, but "transformation sequence, x into y" is the format and sometimes works for whatever. "3-part" likewise works most consistently, but you can make it a long image and do a larger "x-part" too. you'll almost definitely need to fix some details (especially faces)</p></li></ul><p></p><p><strong>feedback welcome! I'll be doing more versions with more species I think, so let me know which ones you want the most</strong></p>