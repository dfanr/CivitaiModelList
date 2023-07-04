## Clothing +/-  Adjuster  衣物增/减  LoRA
### 一、模型概述

- 标签：`photorealistic`, `style`, `woman`, `furry`, `cloth`
- 下载数：17275
- 收藏人数：4027
- 评论人数：43
- 评分人数：19
- 评分：4.89

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] ClothingAdjuster 2.0

- 统计数据
  - 发布时间：2023-06-14T03:55:49.380Z
  - 原始模型：SD 1.5
  - 下载数：14987
  - 评分人数：17
  - 评分：4.88
- 下载地址
  - [ClothingAdjuster2.safetensors](https://civitai.com/api/download/models/95588)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/498f156c-3ebd-43f5-a16f-6e9804f3d228/width=450/1138174.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/348fef11-595a-4792-b95a-4601647ca9a4/width=450/1138049.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6a3c4d84-1a06-457b-b877-f80717067bc2/width=450/1138044.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9a804b3b-8681-4953-93a1-872b7c2e0c64/width=450/1138037.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] ClothingAdjuster 1.0

- 统计数据
  - 发布时间：2023-06-14T03:23:39.427Z
  - 原始模型：SD 1.5
  - 下载数：2288
  - 评分人数：2
  - 评分：5
- 下载地址
  - [ClothingAdjuster.safetensors](https://civitai.com/api/download/models/93792)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6312ef0c-56bb-46d4-b08b-091df30dd2ab/width=450/1109609.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8d63128a-6c60-44e8-9ea2-9eeb15bb3517/width=450/1109549.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f4c22383-2527-4e78-8342-e857ea4d8700/width=450/1109525.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3f8f88fd-32ff-4f79-837a-e33e756e822a/width=450/1109343.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong><u>欢迎大家使用本模型。如果你喜欢我的工作，欢迎在ko-fi上为我</u></strong><a target="_blank" rel="ugc" href="https://ko-fi.com/leopasama"><strong><u>买杯咖啡</u></strong></a><strong><u>☕</u></strong></p><p><strong><u>Everyone is welcome to use th models! If you like my work, feel free to </u></strong><a target="_blank" rel="ugc" href="https://ko-fi.com/leopasama"><strong><u>buy me a coffee</u></strong></a><strong><u> on ko-fi ☕.</u></strong></p><p></p><p><strong><u>这是一个调节所绘制对象衣物多少的功能性LoRA。通过将LoRA权重从-1.0调节至1.0，可以实现绘制对象衣物的逐步减少。本模型在生成竖图时效果最好。</u></strong></p><p>本模型受青龙大佬在<a target="_blank" rel="ugc" href="https://www.bilibili.com/video/BV11m4y147WQ/?spm_id_from=333.337.search-card.all.click&amp;vd_source=98fa411a98cd1aa45fe8235bb8207969">此视频</a>中所介绍的第一种方法“复印学习法”启发。我进行了一些改进以实现多张图情况下的批量训练。具体的步骤如下：</p><p>步骤一：挑选N组不同人物的状态A与状态B对比图片，并形成状态A图像训练集与状态B图像训练集。保证相同人物的状态A与状态B两张图片的文件名相同。</p><p>步骤二：对状态A训练集添加txt标签，每个图片只打一个可以区分不同人物的特殊词汇标签。比如有10个人物，那就给每个人物从jinitaimei1至jinitaimei10分配各自的标签。然后将状态A训练集的所有标签复制粘贴进状态B图像训练集中。</p><p>步骤三：选择与训练集画风相近的底模C，使用状态A图像训练集进行Lora训练直至模型过拟合，输入人物N的对应标签后，只能生成人物N的状态A照片。</p><p>步骤四：将训练得到的过拟合LoRA模型以1.0的比例融合进底模C中（更新：经进一步测试，勾选上same to strength效果会更好），然后用状态B图像训练集基于新底模进行Lora训练。该训练过程不一定要训练至严重过拟合，可以选择LoRA过程文件进行AI绘图测试，只要能通过调节权重，实现状态A至状态B的过渡即可。（更新：经进一步测试，甜蜜点大概在每张图片400在800步范围内）</p><p>步骤五：如果训练的LoRA所涉及场景较复杂，在高权重下会出现过拟合的情况。有两种改良的建议：一是进行LoRA分层调节，降低LoRA中与A/B状态切换无关的层数的权重；二是压缩LoRA的维度，比如从64压缩至4。</p><p></p><p>除了这个LoRA之外，我的作品还包括：</p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/33208/filmgirl-film-grain-lora-and-loha"><strong>FilmGirl/胶片风</strong></a><strong> </strong>Lora<strong>模型：如果你想增加你所绘制人物的真实感，这个Lora就是目前最佳的选择。</strong></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/43977/moonfilm"><strong>MoonFilm</strong></a><strong> </strong>CheckPoint模型<strong>：可能是整个civitai上皮肤真实感Top5的写实模型。</strong></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/33194/pallass-catmanul-lora"><strong>Pallas's cat/兔狲</strong></a><strong> </strong>LoRA<strong>模型：兔狲是这个世界最有趣的猫科动物，请将你的GPU算力献给可爱的猫猫。</strong></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/52652/instant-photo-polaroid-loha-and-lora"><strong>拍立得/Polaroid</strong></a><strong> </strong>Lora<strong>模型：一个实现拍立得照片质感的LoRA，目前还在进一步改进中。</strong></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/51484/eva-neon-genesis-evangelion-lora"><strong>EVA『新世纪エヴァンゲリオン』</strong></a>LoRA<strong>模型：</strong><span style="color:rgb(193, 194, 197)">可以生成类EVA风格泛用人型决战兵器的LoRA，适配EVA 00、EVA 01、EVA 02、EVA 08四款机型。</span></p></li></ul><h3 id="heading-11"></h3><p></p><p></p><p><strong><u>This is a functional LoRA for adjusting the amount of clothing on the drawn objects. By adjusting the LoRA weight from -1.0 to 1.0, a gradual reduction of the clothing on the drawn objects can be achieved. This model works best when generating portrait images.</u></strong></p><p>This model is inspired by the first method "Copy Learning" introduced by Qinglong in <a target="_blank" rel="ugc" href="https://www.bilibili.com/video/BV11m4y147WQ/?spm_id_from=333.337.search-card.all.click&amp;vd_source=98fa411a98cd1aa45fe8235bb8207969">this video</a>. I made some improvements to implement batch training in the case of multiple images. The specific steps are as follows:</p><p>Step 1: Select N groups of comparison images of different characters in State A and State B. Put them into the State A image training set and the State B image training set, respectively. Please ensure that the file names of the two images of State A and State B for the same character are the same.</p><p>Step 2: Add txt labels to the State A training set, with each image receiving only one unique word label that distinguishes different characters. For example, if there are 10 characters, assign each character a label from jinitaimei1 to jinitaimei10. Then copy and paste all labels from the State A training set into the State B image training set.</p><p>Step 3: Choose a base model C with a similar style to the training set. Use the State A image training set for Lora training until the model overfits.</p><p>Step 4: Merge the overfitted LoRA model obtained from training into the base model C at a ratio of 1.0 (Update: After further testing, it will be better to choose same to strength). Then, use the State B image training set for Lora training based on the new base model. This training process does not necessarily need to be trained until severe overfitting occurs; you can choose the LoRA process file for AI drawing tests, as long as the transition from State A to State B can be achieved by adjusting the weight. (Update: 400～800 steps for single pic)</p><p>Step 5: If the LoRA training involves complex scenes, overfitting may occur at high weights. There are two suggested improvements: one is to perform layer-by-layer adjustment of LoRA, reducing the weights of layers unrelated to the A/B state switch; the other is to compress the dimensions of LoRA, such as from 64 to 4.</p><p></p><p>In addition to this LoRA, my works also include:</p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/33208/filmgirl-film-grain-lora-and-loha"><strong>FilmGirl Film Style Lora</strong></a> Model: If you want to increase the realism of the characters you draw, this Lora is currently the best choice.</p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/43977/moonfilm"><strong>MoonFilm CheckPoint</strong></a> Model: Possibly one of the top 5 most realistic skin models on Civitai.</p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/33194/pallass-catmanul-lora"><strong>Pallas's Cat LoRA</strong></a> Model: Pallas's cat is the most interesting feline in the world. Please dedicate your GPU power to these adorable cats.</p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/52652/instant-photo-polaroid-loha-and-lora"><strong>Polaroid Lora</strong></a> Model: A LoRA that achieves the texture of Polaroid photos, currently undergoing further improvements.</p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/51484/eva-neon-genesis-evangelion-lora"><strong>EVA "Neon Genesis Evangelion" LoRA</strong></a> Model: A LoRA that generates EVA-style general-purpose humanoid combat weapons, compatible with EVA 00, EVA 01, EVA 02, and EVA 08 models.</p></li></ul><p></p><p></p>