## Chinese architectural style Suzhou gardens     building(中国传统建筑样式 苏州园林suzhouyuanlin) about architecture
### 一、模型概述

- 标签：`suzhouyuanlin`
- 下载数：2185
- 收藏人数：594
- 评论人数：11
- 评分人数：9
- 评分：4.67

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] suzhouyuanlinV1

- 统计数据
  - 发布时间：2023-03-26T01:37:02.864Z
  - 原始模型：SD 1.5
  - 下载数：2185
  - 评分人数：9
  - 评分：4.67
- 下载地址
  - [suzhouyuanlinV1.safetensors](https://civitai.com/api/download/models/28913)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/57f61c55-3236-4770-5226-1b9e69205900/width=450/326222.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/96fb4bde-0dff-4216-3edb-2163c1a78200/width=450/330276.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4deee1a9-2bcd-4c74-303c-922935d25800/width=450/326232.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9c860de9-ca37-44c1-0268-a147c6359e00/width=450/326227.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>推荐尺寸 512*768,768*1024，或接近该尺寸比例的横图皆可</p><p>推荐tag :</p><p>masterpiece,best quality ,realistic,(architectural photography:1.1)</p><p><strong>suzhouyuanlin</strong>,no humans,garden,Building details,facade details,water,tree,white wall,out doors</p><p></p><p>例图里的tag仅供参考，核心的tag以上为准</p><p></p><ul><li><p>基于SD1.5 Base SD1.5</p></li><li><p>推荐权重<strong>0.4-0.8 </strong>recommend  <strong>0.4-0.8  </strong></p></li><li><p><strong>(低于0.4效果不明显，容易生成中国传统建筑风格而非苏州园林)</strong></p></li><li><p>触发词<strong>suzhouyuanlin </strong>Tag:<strong>suzhouyuanlin</strong></p></li></ul><p></p><p>经过测试，目前主流大模型内直接使用tag，就可生成有中国风的建筑，</p><p>本lora是对suzhouyuanlin南方园林风格,山水概念的针对性特化训练</p><p></p><p></p><p>可使用的大模型dalcefoPainting_v4,realisticVisionV13_v13,deliberate_v2,AARG_render-mix_sd-v.15_12000,dreamlikePhotoreal20_dreamlikePhotoreal20,perfectWorld_v2Baked,v1-5-pruned,anything-v4.5,dvarchMultiPrompt_dvarch,protogenX58RebuiltScifi_10,chilloutmix_Ni,protogenX34Photorealism_1</p><p>基于苏州园林建筑风格训练,<strong>在各大模型上的泛化性都不错</strong></p><p>可单独用于建筑，也可兼容人物lora改变背景内容为园林建筑</p><p>训练集全部为无人建筑照片，搭配人物时请降低权重</p><p></p><p>相较于中国传统建筑的区别在于更倾向于生成假山，半透的廊道和窗纹，水池等园林所包含的概念</p><p></p><p>伴随人像时,Chinese cloths,Japanese cloths这类词条会影响到背景风格</p><p>因为这类词条在大模型内训练集的背景本身就包含了中式,日式建筑，形成了词条关联</p><p></p><p>砖瓦窗格细节的问题应该和手指一样，手指，瓦片等细节，在大图片在压缩为小尺寸图片训练的时候分配到每个瓦片，木条的细节像素过少了，画图由很少像素的小尺寸细节再放大，细节就经不起看，或许在后续版本增大训练集体积能解决这个问题</p><p></p><ul><li><p>有无lora对比测试</p></li></ul><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2c299195-e1c9-49fe-6ddf-5a0fa6596200/width=525/2c299195-e1c9-49fe-6ddf-5a0fa6596200" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a9ae47a8-d4b9-4235-3130-707ed27c5500/width=525/a9ae47a8-d4b9-4235-3130-707ed27c5500" /><p></p><p></p><p></p><ul><li><p>作为人物背景使用 (是否使用lora对人物背景的影响)</p></li></ul><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cded4659-5190-4c64-c43b-eb83a13e3900/width=525/cded4659-5190-4c64-c43b-eb83a13e3900" /><ul><li><p>大模型泛化测试</p></li></ul><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e60d9f01-9306-4e92-442b-83e4db903800/width=525/e60d9f01-9306-4e92-442b-83e4db903800" /><ul><li><p>各权重下表现测试</p></li></ul><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b4f3dbf7-409a-4426-6d6d-ff4bdb64e900/width=525/b4f3dbf7-409a-4426-6d6d-ff4bdb64e900" /><p></p><ul><li><p>使用controlnet控制画面</p></li><li><p>案例1</p></li></ul><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/836ad56a-837e-4dde-3fde-fa066991b700/width=525/836ad56a-837e-4dde-3fde-fa066991b700" /><p></p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/58625ea3-d781-4ba8-c292-4b1e4be9b200/width=525/58625ea3-d781-4ba8-c292-4b1e4be9b200" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/aeb573fe-e664-4d82-3f6d-4ab28945c600/width=525/aeb573fe-e664-4d82-3f6d-4ab28945c600" /><p></p><p></p><ul><li><p>案例2</p></li></ul><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/83dcc5d2-de81-4aa8-69c6-eff552ad0800/width=525/83dcc5d2-de81-4aa8-69c6-eff552ad0800" /><p></p><p></p><p></p><p></p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/414b360d-ec66-49c9-93e8-ad915ea0d000/width=525/414b360d-ec66-49c9-93e8-ad915ea0d000" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dcb71f33-9d68-4b76-cb5c-515d5a32f700/width=525/dcb71f33-9d68-4b76-cb5c-515d5a32f700" /><p></p>