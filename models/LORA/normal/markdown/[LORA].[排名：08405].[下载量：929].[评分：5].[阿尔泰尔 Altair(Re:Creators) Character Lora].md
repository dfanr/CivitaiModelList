## 阿尔泰尔 Altair(Re:Creators) Character Lora
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `nudes`, `altair`, `re:creators`
- 下载数：929
- 收藏人数：267
- 评论人数：5
- 评分人数：6
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] V2.5

- 统计数据
  - 发布时间：2023-03-26T19:51:52.560Z
  - 原始模型：Other
  - 下载数：585
  - 评分人数：2
  - 评分：5
- 下载地址
  - [altairV2.5.safetensors](https://civitai.com/api/download/models/26320)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/885f1f7b-14d5-4388-e684-dad0934c3c00/width=450/289731.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b5f1f99f-f15d-4320-3cd0-6b3a9c0cb500/width=450/289730.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fdb2277d-27b9-405a-859f-4b74d9596b00/width=450/289729.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/09411b5a-34b2-4fcf-3f1f-8d5a17fa7a00/width=450/289728.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] V1.0

- 统计数据
  - 发布时间：2023-03-26T19:51:52.560Z
  - 原始模型：SD 1.5
  - 下载数：344
  - 评分人数：4
  - 评分：5
- 下载地址
  - [altairV1.safetensors](https://civitai.com/api/download/models/23091)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4dd24127-df87-4bfd-f2b5-46ac891b2f00/width=450/249856.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a3680411-88dc-4cfb-cf54-6e461accbf00/width=450/249874.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8a2a1750-375a-45bb-574b-807453172000/width=450/249873.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b79ba1a4-e766-4c3c-3a9a-3eeeeb279800/width=450/249872.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>这是我第一次制作Lora模型，这个模型还有很多问题，非常抱歉。</strong></p><p>————23.3.20————</p><p>V2.0更新了什么：</p><p>这次我使用了768x768的数据集进行训练。</p><p>增加了更多的Trigger Words，现在可以生成Q版的阿尔泰尔，以及动画中阿尔泰尔在占据席利乌斯的身体后的最终形态，还有裸体围裙（实际上还有其他的服饰，但是生成相对有些困难）的阿尔泰尔以及不带帽子的阿尔泰尔</p><p>测试了anyhentai，kotosmix以及AbyssOrangeMix2，在这几个模型上运行的相对不错，其他模型我并未尝试，如果可以的话，希望有人可以尝试使用其他的模型（包括真人模型）进行生成，并把结果发布在评论区。</p><p>请注意，这个版本的部分关键词是用于生成不同风格和不同服饰的阿尔泰尔的，因此部分关键词可能存在冲突。</p><p>如果生成的人物图像面部不佳，推荐您勾选高清修复。</p><p>在使用关键词final-form时可能会导致人物面部出现问题。</p><p>部分情况下画面会偏向于蓝色，未来我会调整数据集并重新训练模型。</p><p>细节上，整体而言相对于V1.0更好，但是部分情况下可能仍然会出现问题。</p><p>————————</p><p>这个Lora模型是基于<strong>final-prune.ckpt</strong>（【旧短哈希1d4a34af】新短哈希22fa233c2d）训练出的。</p><p>使用的是512x640的数据集，大多数图片来自danbooru，少部分来自rule34，以及我个人使用mikumikudance的阿尔泰尔模型截图得到的图片。</p><p>这个模型可以生成<strong>nsfw</strong>的图片。</p><p><strong>这个模型在生成真人的效果上非常糟糕，而且用它生成的人物的眼睛会有不少问题，另外在使用部分2d模型时画面可能会比较模糊，必须勾选高清修复，才能得到比较好的效果，可能是在训练时我没有设置好，导致模型过拟合了。</strong></p><p><strong>在高分辨率的情况下可能会出现奇怪的问题。</strong></p><p>推荐使用0.6-0.8的权重，除了提到的触发词以外，其他的人物特征是不必要提到的，但如果你想要更好的效果，也可以添加，因为一些细节（比如人物的袖章，或者护手可能会在生成时丢失）。</p><p><strong>通常altair和1girl这两个触发词是必须的。</strong></p><p>如果你想得到我展示的一部分图片的效果，请使用AbyssOrangeMix2或者AbyssOrangeMix3，还有Perfect World以及anyhentai这些模型中的一个，并使用orangemix.vae，这个vae的下载链接可以在AbyssOrangeMix2 - Hardcore的下载页面找到。</p><p>然后，设置40steps，7CFG Scale，采样方法(Sampler)选择DPM++2M Karras，或者其他DPM++ Karras的采样方法，下方的Lora权重设置为0.75，想要更好的效果可以勾选面部修复以及高清修复，但高清修复可能会导致生成一些人体结构奇怪的图片。</p><p>推荐使用512x640的分辨率。</p><p>近期可能还会对这个模型进行改进，直到它令我满意为止。</p><p>我很喜欢Re:Creators里面的这个<s>白色拖把精</s>（阿尔泰尔），但是civitai上没有她的lora，所以只能自己训练它了。</p><p><strong>英语是用Google翻译翻译的，如果有造成误解之处非常抱歉。</strong></p><p>This is the first time I make a Lora model, there are still many problems with this model, I am very sorry.</p><p>——— 23.3.20————</p><p>What's updated in V2.0:</p><p>This time I used a 768x768 dataset for training.</p><p>Added more Trigger Words, now you can generate the Q version of Altair, and the final form of Altair in the animation after occupying the body of Silius, and the naked apron (actually there are other costumes, but generated Relatively difficult) Altair and Altair without hat</p><p>I have tested anyhentai, kotosmix and AbyssOrangeMix2, and they work relatively well on these models. I have not tried other models. If possible, I hope someone can try to use other models (including real-life models) to generate and publish the results. in the comments section.</p><p>Please note that some keywords in this version are used to generate Altairs with different styles and different clothing, so some keywords may conflict.</p><p>If the face of the generated character image is not good, it is recommended that you check HD Repair.</p><p>When using the keyword final-form, it may cause problems with the character's face.</p><p>In some cases, the picture will be biased towards blue. In the future, I will adjust the data set and retrain the model.</p><p>In terms of details, overall it is better than V1.0, but there may still be problems in some cases.</p><p>———————</p><p>This Lora model is trained based on<strong> final-prune.ckpt</strong> ([old short hash 1d4a34af] new short hash 22fa233c2d).</p><p>The data set of 512x640 is used, most of the pictures are from danbooru, a small part is from rule34, and I personally use the pictures obtained from the screenshot of the Altair model of mikumikudance.</p><p>This model can generate pictures of <strong>nsfw</strong>.</p><p><strong>This model is very bad at generating real people, and the eyes of the characters generated with it will have many problems. In addition, when using some 2D models, the picture may be blurry. You must check HD repair to get better results. , it may be that I did not set it properly during training, which caused the model to overfit.</strong></p><p><strong>Strange issues can occur at high resolutions.</strong></p><p>It is recommended to use a weight of 0.6-0.8. Except for the trigger words mentioned, other character characteristics are not necessary to mention, but if you want better results, you can also add them, because some details (such as the character's armband, Or the gauntlet might be missing on spawn).</p><p><strong>Usually the two trigger words altair and 1girl are required.</strong></p><p>If you want to get the effect of some of the pictures I show, please use AbyssOrangeMix2 or AbyssOrangeMix3, and one of the models Perfect World and anyhentai, and use orangemix.vae, the download link of this vae can be found on the download page of AbyssOrangeMix2 - Hardcore.</p><p>Then, set 40steps, 7CFG Scale, sampling method (Sampler) to select DPM++2M Karras, or other sampling methods of DPM++ Karras, and set the Lora weight below to 0.75. If you want a better effect, you can check the face repair and high-definition repair , but the high-definition restoration may result in some strange images of human anatomy.</p><p>A resolution of 512x640 is recommended.</p><p>This model may be improved in the near future until it satisfies me.</p><p>I really like the <s>white mop spirit</s> (Altair) in Re:Creators, but there is no her lora on civitai, so I can only train it myself.</p><p><strong>English is translated by Google Translate, sorry if there is any misunderstanding.</strong></p>