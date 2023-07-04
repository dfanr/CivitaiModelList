## vigee_MIX
### 一、模型概述

- 标签：`character`, `woman`, `girls`, `realistic`
- 下载数：297
- 收藏人数：111
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v1.1_bright

- 统计数据
  - 发布时间：2023-07-03T18:10:47.413Z
  - 原始模型：SD 1.5
  - 下载数：0
  - 评分人数：0
  - 评分：0
- 下载地址
  - [vigeeMIX_v11Bright.safetensors](https://civitai.com/api/download/models/109550)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c988ffed-a4b5-474f-b036-44a6cf5a8e32/width=450/1392156.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e98c12f0-a289-4f06-8ac2-10f8d82b0de0/width=450/1392159.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/51eef969-75c2-432f-938a-7fcc2d8861a7/width=450/1392161.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e457f5b3-7f4a-487b-8cdc-04a280d959f5/width=450/1392163.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v1._dark

- 统计数据
  - 发布时间：2023-07-03T18:17:04.845Z
  - 原始模型：SD 1.5
  - 下载数：0
  - 评分人数：0
  - 评分：0
- 下载地址
  - [vigeeMIX_v1Dark.safetensors](https://civitai.com/api/download/models/109577)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0ad83607-2ee4-447b-901d-a4c866bae428/width=450/1392645.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/60e53ee3-9b9a-49db-a674-b7444c329ab9/width=450/1392646.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d43c55d8-8735-45e3-be65-a9b1692aa761/width=450/1392649.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c57b9eff-e4e5-46fd-8905-09381cce5ad5/width=450/1392653.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v1.0

- 统计数据
  - 发布时间：2023-07-03T18:10:47.413Z
  - 原始模型：SD 1.5
  - 下载数：297
  - 评分人数：0
  - 评分：0
- 下载地址
  - [饱和度2-色彩清晰-ClearVAE.safetensors](https://civitai.com/api/download/models/107875?type=VAE&format=Other)
  - [vigeeMIX_v10.safetensors](https://civitai.com/api/download/models/107875)
  - [vigeeMIX_v10_trainingData.zip](https://civitai.com/api/download/models/107875?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c022d795-b449-4bb4-84a4-1e51d1a7c917/width=450/1356764.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cf7d8784-0702-4ab8-aaaf-9639008593eb/width=450/1359815.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e9b28131-9bde-48f8-9717-2393d2c02a90/width=450/1356767.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c45cba72-a11b-4f3e-b0a4-19ee221af258/width=450/1359817.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>V1.1:第一版的细节不够，所以添加了细节和阴影的效果。然后就出来两种风格。看个人喜好下载。</p><p>第一次融合模型，其实是我自己用的，拿来分享一下吧。这是我喜欢的风格。</p><p>试了一下，提示词的位置很影响NFSW的几率。要想出NFSW，要把其关键字尽量放前面，比如跟在1 girl的后面，这样的格式：1girl,((nude,nsfw))</p><p>建议采样方法：DPM++ 2M Karras，迭代步数25-30，面部修复采用<strong>ADetailer插件</strong>，同时<strong>ADetailer model这里选择 mediapipe_face_full</strong>。</p><p>当然你也可以尝试选择高清修复来生成更大尺寸的照片，因为我的显卡只有4G显存，就没有进行尝试了。</p><p>样图添加了 pureerosface_v1,ulzzang-6500-v1.1两个文本嵌入模型。可以让生成的脸型更符合亚洲的审美。没有添加脸型的lora。VAE配合使用的是clearVAE。</p><p>以上所需的文件如果你没有，可以联系我，我再上传。</p><p>正向提示词抽卡即可得到不错的效果：</p><p>best quality,masterpiece,realistic,photorealistic,1girl,pureerosface_v1,ulzzang-6500-v1.1</p><p>我的通用负面提示词：</p><p>(bad-artist,bad-hands-5,bad-image-v2-39000,bad_prompt_version2,EasyNegative,ng_deepnegative_v1_75t),advertisement,paintings,sketches,(worst quality:2),(low quality:2),(normal quality:2),</p><p></p><p>融合的模型：</p><p>majicmixRealistic_v6 <a target="_blank" rel="ugc" href="https://civitai.com/models/43331">https://civitai.com/models/43331</a></p><p>+realdosmix <a target="_blank" rel="ugc" href="https://civitai.com/models/6925">https://civitai.com/models/6925</a></p><p>+真人真实脸模 <a target="_blank" rel="ugc" href="https://civitai.com/models/93300">https://civitai.com/models/93300</a></p><p>以上三个模型的作者如果觉得本模型有侵权行为的话，请留言，我会下架本模型。</p><p>请勿用作商业用途，请勿用作真实公众人物的面部替换，如发生任何纠纷，请自行解决。</p><p>如有兴趣，欢迎本模型和任意模型进行融合，但请不要联系本人做技术咨询，因为我也是新手。- -</p><p></p><p></p><p>以下翻译来自deepl：</p><p>Translated with <a target="_blank" rel="ugc" href="http://www.DeepL.com/Translator">www.DeepL.com/Translator</a> (free version)</p><p></p><p>V1.1:The first version of the details are not enough, so I add the details and shadow effects. Then it came out in two styles. You can download according to your personal preference.</p><p>The first merged model, in fact, I use it myself, to share it. This is the style I like.</p><p>Tried it, the position of the cue words very much affect the chances of NFSW. To come up with NFSW, try to put its keyword in front, such as following 1 girl, such a format: 1girl, ((nude,nsfw))</p><p>Suggested sampling method: DPM++ 2M Karras, Sampling steps: 25-30, facial repair using <strong>ADetailer plug-in</strong>, while <strong>ADetailer model here choose mediapipe_face_full.</strong></p><p>Of course, you can also try to choose hires.fix repair to generate larger size and clearer photos, because my graphics card only has 4G video memory, so I did not try.</p><p>Two text embedding models, pureerosface_v1 and ulzzang-6500-v1.1, were added to the sample image. This allows the generated face shape to be more in line with Asian aesthetics. VAE is used in conjunction with clearVAE.</p><p>If you don't have the above required files, you can contact me and I will upload them.</p><p></p><p>U can get good results from simple prompt words:</p><p>best quality,masterpiece,realistic,photorealistic,1girl,pureerosface_v1,ulzzang-6500-v1.1</p><p>My generic negative words:</p><p>(bad-artist,bad-hands-5,bad-image-v2-39000,bad_prompt_version2,EasyNegative,ng_deepnegative_v1_75t),advertisements,paintings. sketches,(worst quality:2),(low quality:2),(normal quality:2).</p><p></p><p>The merged model:</p><p>majicmixRealistic_v6 <a target="_blank" rel="ugc" href="https://civitai.com/models/43331">https://civitai.com/models/43331</a></p><p>+realdosmix <a target="_blank" rel="ugc" href="https://civitai.com/models/6925">https://civitai.com/models/6925</a></p><p>+realistic face model <a target="_blank" rel="ugc" href="https://civitai.com/models/93300">https://civitai.com/models/93300</a></p><p>The authors of the above three models will take down this model if they feel that this model is infringing, please leave a message.</p><p>Please do not use it for commercial use, please do not use it as a facial replacement for real public figures, if any dispute occurs, please solve it by yourself.</p><p>If you are interested, you are welcome to merge this model with any model, but please do not contact me for technical advice, because I am also a novice.</p>