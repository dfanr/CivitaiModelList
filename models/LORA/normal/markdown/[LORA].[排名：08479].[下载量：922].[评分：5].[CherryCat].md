## CherryCat
### 一、模型概述

- 标签：`celebrity`, `realistic`, `1girl`, `highres`
- 下载数：922
- 收藏人数：181
- 评论人数：30
- 评分人数：5
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] CherryCat_v0.11

- 统计数据
  - 发布时间：2023-04-02T01:01:38.685Z
  - 原始模型：SD 1.5
  - 下载数：485
  - 评分人数：2
  - 评分：5
- 下载地址
  - [CherryCat_cloud_v1-000002.safetensors](https://civitai.com/api/download/models/33095)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/16b79d84-e042-4546-dd9a-adc5669ae000/width=450/381526.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4f8a7eb7-4593-4248-338a-70175cb16700/width=450/377008.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d970fd7a-7ade-4a91-250f-840423d4e200/width=450/377007.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/215d7424-b73f-43ab-6adf-43d83f543a00/width=450/377006.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] CherryCat_v0.1

- 统计数据
  - 发布时间：2023-04-02T01:01:38.685Z
  - 原始模型：SD 1.5
  - 下载数：437
  - 评分人数：3
  - 评分：5
- 下载地址
  - [CherryCat_cloud_v1-000002.safetensors](https://civitai.com/api/download/models/32636)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f68c1b65-4b59-4917-4eff-212c62030900/width=450/381472.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/01ca76c8-ce6e-4f43-b740-3abfaf5c8000/width=450/374939.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b8a382f5-d1de-4f66-ee54-ed4e42191f00/width=450/374700.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1d8076a6-d24a-4f43-b598-10fcd1475300/width=450/374941.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1><strong>仅作学习目的，详细记录一下目前得到较好结果的训练过程，希望分享一些训练经验。</strong></h1><p></p><h3><strong>DO NOT POST YOUR NSFW WORKS HERE.</strong></h3><p></p><p><strong>This model is clearly over-baked</strong>, and does not respond well to prompts like hair color (probably caused by the mis-tagged training data I've fed to model), I'm still working on it.</p><p></p><h3><strong>Notes on usage:</strong></h3><ol><li><p><strong>Add "hair over one eye" to your negative prompts, </strong>I've fed some Rem cosplay which were not tagged well, they seem to be toxic in the results.</p></li><li><p>LoRA weights around 1.0 should work fine when this model is the only one applied on.</p></li><li><p>The new sampler UniPC works well for me at a iterating numbers around 30.</p></li><li><p>Try different photo types such as <strong>face</strong> <strong>close-up, portrait and full-body</strong>, and different angles like <strong>from side, from behind and from above, </strong>the model will give decent results.</p></li></ol><p></p><p></p><h3>What is the purpose of this model?</h3><p>I've spent last few days training LoRA models, and found out that most of my models were able to give a decent headshot or protrait output, but failed to keep the face structure when it came to a full-body photo.</p><p>Therefore, I'm looking forward to train a model with the capability to present <strong>both close-up and full-body</strong> photos.</p><p>The results are quite good, try different types of photo which are of various values on the proportion of the face in the photo <strong>(face close-up | portrait | full-body)</strong>, the model will give good results to all of them.</p><p></p><h3><strong>Training Setup:</strong></h3><p>Using Akegarasu(<a target="_blank" rel="ugc" href="https://space.bilibili.com/12566101">秋葉</a>)'s Lora-Scripts (based on Kohya's).</p><p>The whole training process of this model is completed on the <a target="_blank" rel="ugc" href="http://AutoDL.com">AutoDL.com</a> with the system image provided also by Akegarasu.</p><p>The base SD-model I've used to train this model is simply ChilloutMax, it may work with other SD-model.</p><p></p><h3><strong>Detailed scripts settings:</strong></h3><ol><li><p>network_dim=network_alpha=32:</p><p>higher network dimension settings do not give better results for my datasets, so I pick the one with smallest file size.</p></li><li><p>resolution="768, 1024":</p><p>An aspect ratio of 3:4 just matches perfectly with the ratio of headshot photos.</p></li><li><p>batch_size=4:</p><p>Larger batch size will make the training faster, but requires more GPU memory, I'm using an A40 GPU, its 24GB memory supports this resolution and batch_size setting.</p></li><li><p>max_train_epoches=8:</p><p><strong>Since this model I trained is obviously over-baked</strong> (even for the result from epoch=2), the setting for max_train_epoches is not going to be discussed here.</p></li><li><p>noise_offset=0.05:</p><p>According to the comments in scripts, this may have some effects on dynamic range of output.</p></li><li><p>clip_skip=2:</p><p>Though someone has adviced that it might be better to set clip_size to 1 while working on realistic photos, but I've found no noticeable difference here, so I kept this value as 2.</p></li><li><p>The other parameters are as same as the default settings from Akegarasu's scripts.</p></li></ol><p></p><h3><strong>Training Data:</strong></h3><p>From what I've observed, the key to generate a decent output image without corrupted faces, is to feed the model with high-quality photos and use regularization.</p><p></p><p><strong>The datasets can be divided into 3 tiers:</strong></p><ol><li><p>Lowest quality photos obtained from various platforms.</p><p>These photos are mostly headshot photos and of really low-resolution, especially the ones that are even smaller than training resolution. If you're picky to the generated images, these photos should be considered as toxic to the model.</p></li><li><p>Some headshot photos and few full-body photos which are not of low-resolution.</p><p>You can generate decent upper-body or close-up images from these data, but when it comes to the full-body photo, there will be a great chance for to have a corrupted and twisted face. The lack of full-body photo and face from a full-body photo is the reason why the model behaves poorly.</p></li><li><p><strong>The Ideal condition is that you have dozens of photos, which are of high-resolution (something like 5k*7k or higher).</strong></p></li></ol><p></p><p><strong>Regularization:</strong></p><p>The regularization is quite helpful to train the model of a person, a simple explanation for regularization is that, telling the model where to put the person's face at.</p><p>There are plenty of ways to build both training and regularization sets, I'm just going to discuss the way I've taken here.</p><p>For any photo I have in hand, first I'll crop out the whole area where the person is located, and use this cropped photo as the regularization part. Then I'll zoom in to make the head/face fill the region of the training resolution (768*1024 in my case), and cropped the headshot as the training part.</p><p>It's not neccessary to match the training photo with the regularization photo since the scripts even allow that (num_repeats*num_photo) of regularization and training parts are not equal, but the way I build datasets just makes them match naturally.</p><p></p><p><strong>Tagging:</strong></p><p>As for the tagger, I use the wd14-vit-v2 to tag <strong>both of the regularization and training sets</strong>, with a threshold of 0.35,</p><p></p><h3>TODO:</h3><ol><li><p>I'm currently working on training a LoRA model to learn the concepts of posture and clothing set, but the results are just not good when it comes to postures that are just a little bit complicated (such as squatting down and wrapping hands around legs).</p></li><li><p>Try a smaller training set.</p></li></ol>