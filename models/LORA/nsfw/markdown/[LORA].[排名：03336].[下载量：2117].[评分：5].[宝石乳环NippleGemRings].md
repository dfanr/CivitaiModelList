## 宝石乳环NippleGemRings
### 一、模型概述

- 标签：`photorealistic`, `sexy`, `porn`, `bdsm`, `gem`, `nipple rings`, `nipples`, `breasts`, `clothing`, `girls`, `realistic`, `jewelry`, `nipple piercing`, `ring`, `breast`, `nipple`
- 下载数：2117
- 收藏人数：466
- 评论人数：1
- 评分人数：4
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2.0

- 统计数据
  - 发布时间：2023-07-03T06:33:33.989Z
  - 原始模型：Other
  - 下载数：318
  - 评分人数：1
  - 评分：5
- 下载地址
  - [NippleGemRings_v2.safetensors](https://civitai.com/api/download/models/109228)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/66a7a6c5-b51e-451c-82d2-aa1a95bd1224/width=450/1385735.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/846fe70b-e9c5-4224-be8e-c1b9e3fe10e3/width=450/1385736.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4ada3944-a4fd-41f7-8c91-d33f88ee6ae3/width=450/1385737.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b84f646c-57ab-41af-9848-1e739f7c12ff/width=450/1385739.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.2

- 统计数据
  - 发布时间：2023-07-03T05:43:58.266Z
  - 原始模型：Other
  - 下载数：1799
  - 评分人数：3
  - 评分：5
- 下载地址
  - [NippleGemRings_v12.safetensors](https://civitai.com/api/download/models/82823)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2cddffa9-8764-4810-ba09-070efc30b77e/width=450/933193.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8ff6d802-4777-427c-81db-b0ce0a1a2a21/width=450/933210.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4d3a2320-ad2e-4ad7-b799-a351de0920e0/width=450/933233.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0dfb11a0-78ca-4010-85db-b7ac2684293c/width=450/933197.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>0703更新v2.0</strong></p><p>· 推荐权重&lt;lora:NippleGemRings_v2:0.7&gt;, (nipple_rings:1.1),</p><p>· 大幅优化了穿衣露胸的能力，结果而言不加nipple_rings就可以用来当breast_ouside的lora</p><p>· 样图我都用尽量简单的Prompt，并且不使用其他lora以及各种附加模型，只使用了面部修复（Codeformer，权重0.8）来提升了一点皮肤纹理的效果</p><p>· 如果有用LoRA Block Weight，可以用MIDD或OUTD来减少乳环之外的影响，我自己调了一个两侧递减的权重配置是OUTD-3:1,0.3,0.4,0.5,0.6,0.7,0.8,0.9,1,1,1,1,0.8,0.6,0.4,0.2,0，效果可以看样图里有2张xyz图</p><p>· 训练素材的脸部用bra_v5重绘过，所以这次出来的脸就比较亚洲美女了</p><p>· small_breasts稍微优化了一些，但还是容易糊，最好还是inpaint</p><p>· from_side有一定优化，做了一些透视侧面的ring效果，但是还是容易糊</p><p></p><p>依然存在的缺点（暂不打算继续修就是了）</p><p>· 缺点1：胸部和乳晕的边缘和乳环有交错的话容易变得不连续，还好用inpaint还是很容易修的</p><p>· 缺点2：默认都是大胸，我尽力了，不标small和标small的小胸和标medium的小胸都加了，看来AI口味还是和我一样大</p><p>· 缺点3：二次元效果不佳，毕竟我都是整的偏真人风格的</p><p></p><p>——————————————————</p><p>以下是v1.2版本时的说明</p><p><strong>使用说明</strong></p><p>· 推荐权重&lt;lora:NippleGemRings_v12:0.7&gt;, (nipple_rings:1.1),</p><p>· 特意备了不少small_breasts的图，但效果就是容易出large_breasts，想要small_breasts建议再+skinny效果好一点，而且需要提高权重&lt;lora:NippleGemRings_v12:0.8&gt;, (nipple_rings:1.1), small_breasts, skinny, 这样</p><p>· 宝石可以用 diamond_\(gemstone\) | red_gemstone, ruby | blue_gemstone, sapphire | green_gemstone, emerald 这些关键词进行引导，但不保证效果，因为没做这方面的trigger</p><p>· 同样环的材质可以用 platinum ring shank | gold ring shank | silver ring shank | bronze ring shank 进行引导</p><p>· 然后负面tag也有可能影响乳环效果，比如常用的负面embedding之一 easynegative就似乎和乳环非常不对付不建议用，而ng_deepnegative_v1_75t也有一点影响，建议用分步渲染只在最后25%调整[:ng_deepnegative_v1_75t:0.75],</p><p>· 素材基本没脸，可能是nipple_rings自带一点欧美因子，所以跑出来长相会偏欧美风一点，还有就是容易自带耳环</p><p>· 素材都是nude，所以换装效果目前也比较差，可以考虑i2i，后续会完善这一点</p><p>· 还有就是侧面效果目前也不太好</p><p></p><p><strong>更新计划</strong></p><p>· 其实还不算特别满意，只是最近没空，那就v1.2先发布了</p><p>· 后续打算优化一下ps痕迹，目前还不是很完美</p><p>· 以及上面提到的小胸、换装、侧面等，应该过几个月有空会整个效果都改进的v2.0</p><p></p><p><strong>炼制记录</strong></p><p>· 打算重新炼一遍乳链，先从乳环开始</p><p>· 尝试过的乳环lora在想要realistic时效果都不太好，也试着做自己炼常规的乳环发现非常难做出清晰的效果</p><p>· 所以就干脆做个夸张的，i2i+ps融了一堆宝石戒指上去</p><p>· v1.0和v1.1是基于sd1.5炼的，在sd1.5上跑得挺好，到chilloutmix上就不行了，于是干脆基于chilloutmix炼了v1.2，效果还行</p>