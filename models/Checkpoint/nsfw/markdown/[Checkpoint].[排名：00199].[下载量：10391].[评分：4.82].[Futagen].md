## Futagen
### 一、模型概述

- 标签：`anime`, `character`, `futanari`
- 下载数：10391
- 收藏人数：1417
- 评论人数：58
- 评分人数：22
- 评分：4.82

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] 2

- 统计数据
  - 发布时间：2023-01-16T07:07:02.472Z
  - 原始模型：SD 1.5
  - 下载数：9614
  - 评分人数：16
  - 评分：4.75
- 下载地址
  - [futagen_2.ckpt](https://civitai.com/api/download/models/5258?type=Pruned%20Model&format=PickleTensor&size=pruned&fp=fp16)
  - [futagen_2.safetensors](https://civitai.com/api/download/models/5258?type=Model&format=SafeTensor&size=full&fp=fp16)
  - [futagen_2.safetensors](https://civitai.com/api/download/models/5258)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e7130514-2528-4128-22b5-ff1a4d6a6500/width=450/40377.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d17f1b61-c870-47fa-9252-e3ee4c635100/width=450/40376.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/985de9f4-9d3a-4670-c1c9-8e4875046b00/width=450/40375.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1665bfa5-8b1b-4ece-c730-215a4483f000/width=450/40374.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] 1

- 统计数据
  - 发布时间：2023-01-16T07:07:02.472Z
  - 原始模型：SD 1.5
  - 下载数：777
  - 评分人数：6
  - 评分：5
- 下载地址
  - [futagen_1.safetensors](https://civitai.com/api/download/models/4590)
  - [futagen_1.ckpt](https://civitai.com/api/download/models/4590?type=Model&format=PickleTensor&size=full&fp=fp16)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/59233f8b-3196-4aa8-9599-4321068d6300/width=450/31671.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4235ecf8-d3be-4d19-3d79-dbd83d63da00/width=450/31675.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2076f745-ffd2-4d4c-48fe-7c2c15fc2700/width=450/31674.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ce2d184a-e34a-4206-8553-5c4da53f4f00/width=450/31673.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>Updated for Version 2</strong></p><p><a rel="ugc" href="https://huggingface.co/dreamlike-art/dreamlike-photoreal-2.0/blob/main/LICENSE.md">Obligatory Dreamlike License</a></p><p>Well...  I've been working on this update for several days and nothing has worked.  It's been one fail after another after another.  No matter what I did, every time I got promising results once I threw Protogen on top then it just destroyed the futanari results, and produced much more mangled genitalia.  It was frustrating, maddening, and I came very close to giving up.  Then I finally figured out the trick.  Part of the problem is that Protogen doesn't really understand male genitalia all that well, if even at all.  So once it got thrown in on top of the futanari stuff, it really broke the ability to render anything that decently resembled a penis.  So, I fixed it though.  I got something that I think is pretty decent, produces more consistent results, and <em>can</em> do much better penises.  It doesn't do them all the time, but it certainly can.  The fix to this was to include AIrotic Art's Penis model.  I had to include it on both ends though.  I had to do a merge to include it into Futa Anime, and then another merge to include it into Protogen 5.3, then slap those two together and this is what I got.  Not going to go into details on the formula, but that's the gist of it.  </p><p></p><p>Now, on to the new prompting.  I recommend you add weight attention to penis, and use the following keywords in your prompt:</p><p>"Penis, frenulum, penerec, erect penis"  </p><p>I also DON'T recommend that you use "1girl" in your prompt.  Doing so will produce weird lumpy vaginas...  Basically run a batch, find one that renders a decent penis, use that one as your seed, then re-run with the same prompt and a low variation amount to get similar results and clean up the penis (if it needs it).  </p><p></p><p>Also, because this is a merge with the AIroticArt Penis Model, it has a tendency to want to render men sometimes.  This doesn't happen often, but it can.  You can avoid this by making sure to mention "breasts" in your positive prompt.  you can also put terms like "male, man, boy" in your negative prompts to reduce the likelihood that it will happen. Just take a look at the example prompts on the images.  Those were all pretty easy to get, except the demon woman.  That one was a pain in the ass for some reason that I don't yet understand.  Some of the images required a little bit of seed work to clean them up a little bit, but none of them were edited, inpainted, or anything like that.  All of them are direct outputs from the model.</p><p></p><p>Getting cum is difficult.  You do really have to heavily weight cum in your prompt, but it can work.  </p><p></p><p>Seeing as the file size more than doubled with this new version, I also am providing pruned versions that are fp16 no-ema prunes.  </p><p></p><p>For best results use the <a rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/tree/main">Standard SD VAE</a></p><p></p><p>Disclaimer: All prompts in the example images are using InvokeAI Syntax NOT Automatic1111 syntax. The main difference here is that 'term+' is equivalent to '(term)' ++ is equivalent to (()) and so on.</p><p></p><p>Models included in this merge:</p><ul><li><p><a rel="ugc" href="https://civitai.com/models/4098/futa-anime">Futa Anime</a></p></li><li><p><a rel="ugc" href="https://civitai.com/models/3816/protogen-x53-photorealism-official-release">Protogen 5.3</a></p></li><li><p><a rel="ugc" href="https://civitai.com/models/1245/airoticarts-penis-model">AIroticArt's Penis Model</a></p></li></ul>