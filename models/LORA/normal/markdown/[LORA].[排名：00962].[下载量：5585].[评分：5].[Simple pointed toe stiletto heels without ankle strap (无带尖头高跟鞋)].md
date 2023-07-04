## Simple pointed toe stiletto heels without ankle strap (无带尖头高跟鞋)
### 一、模型概述

- 标签：`clothing`, `high heels`, `shoes`, `stiletto heels`, `footwear`
- 下载数：5585
- 收藏人数：976
- 评论人数：15
- 评分人数：5
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v2.1

- 统计数据
  - 发布时间：2023-06-10T07:06:32.429Z
  - 原始模型：SD 1.5
  - 下载数：3160
  - 评分人数：0
  - 评分：0
- 下载地址
  - [ggx_V2.1_16.safetensors](https://civitai.com/api/download/models/92892)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/95f9270c-bfa1-4c20-8bdc-6ee82a4fa63c/width=450/1093468.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0a546fe1-a410-4b56-a68c-2d45fc057678/width=450/1093264.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8b758ccd-165c-4966-90c0-5bde36659ce5/width=450/1093274.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1c6cb0cd-bad5-43b3-97fb-a815cad3fc7a/width=450/1093271.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v2.0

- 统计数据
  - 发布时间：2023-06-10T06:46:11.383Z
  - 原始模型：SD 1.5
  - 下载数：1533
  - 评分人数：2
  - 评分：5
- 下载地址
  - [ggx_V2_11.safetensors](https://civitai.com/api/download/models/88728)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/552ba816-26e6-4606-aa43-1b0f3f3cb415/width=450/1021209.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/523ad45b-227e-4b1c-90d5-899dbd283ae0/width=450/1021201.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cc5997ca-c5c3-4e9f-8858-74219fafdd9b/width=450/1021202.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7610724a-5112-480b-aef0-ae1187b5cc83/width=450/1021203.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v1.0

- 统计数据
  - 发布时间：2023-06-10T06:46:11.383Z
  - 原始模型：SD 1.5
  - 下载数：892
  - 评分人数：3
  - 评分：5
- 下载地址
  - [ggx.safetensors](https://civitai.com/api/download/models/86587)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7c1110f1-732e-4f76-99e4-bc59fb9cd97a/width=450/986516.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2c7ba622-4bc0-4e64-952b-82582e77c288/width=450/986517.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9a5b91e7-faba-4b57-baec-940afb8d72be/width=450/986541.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1a6cf700-659b-499b-ac0c-a6bbac233e84/width=450/986549.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>It seems like sd always generates some strappy heels even though we put that in the negative prompt. This is a simple Lora that can potentially remove the ankle strap from the pointed-toe heels when the weight is above 0.4. From what I was testing, 0.4-0.8 seems to give an okay result with the realistic checkpoint models.</p><p></p><p>SD经常会生成带脚踝绑带的高跟鞋, 用反向提示词限制的效果也不太好, 这个lora就是用来去掉这根绑带的, 且对鞋的形状进行了微调. 使用时权重在0.4-0.8比较好, 更推荐从0.4开始逐步往上提, 0.8以上泛化就不是太好了, 颜色也会逐渐固定成黑色. 用真实系的checkpoint会还原的比较好, 二次元系的也行, 但会有点走样, 且权重得设得比较高才能把绑带去掉.</p><p></p><p>Tips for generating leg pose:</p><p>For simple leg poses, just use prompt and openpose, this Lora should be able to generate that pretty well.</p><p></p><p>For more complicated leg poses, it's too difficult for the current gen sd, usually you will get bunch of mutant legs and arms, and the heels will turn into a weird shape. For this problem, you may want to use edge detection in the controlnet, like canny, softedge and scribble, the main idea is to use the outline of the picture to keep the overall pose and heels' shape. </p><ul><li><p>First, you need to have a reference picture of the desired leg pose with the heels on, then throw it into controlnet</p></li><li><p>Then select the softedge in controlnet then generate a controlnet preview for the picture, and see if the outline of the heels has been detected correctly, if not, you may want to use the canny instead. The outline using canny is more defined than softedge.</p></li><li><p>Then set the controlnet's weight to somewhere between 0.5-1.0 then write your prompt and generate your picture. the lower the weight, the easier to change the background and the clothes, the higher the weight, the better the shape of the pose and heels.</p></li><li><p>If your desired clothes are far different from the reference picture, you can use scribble instead, it leaves more space for the AI to draw the content, but the shape captured is worse comparing the other two.</p></li><li><p>If all three edge-detecting methods failed, you may want to modify the controlnet preview manually to make the outline more clear and remove the unnecessary content. it's pretty simple, just cover the unwanted content with black colour and draw the outline with white colour, even the paint software integrated in windows can do that.</p></li></ul><p></p><p>绘制腿部姿势的小技巧:</p><p>简单的姿势只需用提示词或者controlnet里的openpose就可以了, 鞋子基本不会变形</p><p></p><p>复杂的姿势以目前的SD还达不到可用级别, 经常会生成有多条手臂和多条腿的图, 而且高跟鞋也会跟着变形, 所以我们得用controlnet里面的边缘检测去限制住大体的姿势不出错. 常用的有canny, softedgehe和scribble, normal和dept也能用, 但对高跟鞋的边缘检测没前三种好</p><p></p><ul><li><p>首先把穿着高跟鞋的参考图片放到controlnet里</p></li><li><p>然后选择softedge作为控制类型, 生成一下预览看看高跟鞋的形状有没有被勾勒出来, 如果没有, 可以尝试用canny, 出来的线条会更清晰</p></li><li><p>然后设置controlnet的控制权重为0.5-1.0, 低点儿的话方便换衣服换背景, 高点儿的话形状检测更准确. 设置好了就可以写提示词跑图了</p></li><li><p>如果你要换的衣服跟参考图片的差距很大, 可以考虑使用scribble, 它能给AI留出更多的创作空间, 但相对的高跟鞋的形状控制就会比另外两种方法差些.</p></li><li><p>如果三种方法都不能生成你想要的姿势的话, 那大概率是参考图片的背景太复杂了, 你可以手动修改一下controlnet的预览图, 把无关背景都用黑色盖上, 然后用白色勾勒一下想要的边缘. 十分简单, windows 自带的画图都能搞定</p></li></ul><p></p><p>测试下来, softedge对高跟鞋的检测是最好的, 换衣服之类的也很泛用, 所以首先选择softedge来做边缘检测</p><p></p><p></p><p>V2.1</p><ul><li><p>Expand the regularization and training set</p></li><li><p>Network dim set to 128</p></li><li><p>slightly higher prior loss weight with regularization</p></li></ul><p></p><ul><li><p>继续扩张训练集以及正则集</p></li><li><p>网络难度提高到128</p></li><li><p>正则权重稍微提高了</p></li></ul><p></p><p>V2.0</p><ul><li><p>The training set was reworked and expanded, removing all unnecessary content including background and face, so this version should work better when the weight is high.</p></li></ul><ul><li><p>Add dreambooth regularization training set, the heels' size and the attach location should work better.</p></li><li><p>Recommended weight: 0.3-0.9, I used 0.5-0.6 in my test image.</p></li><li><p>Work with many clothing Lora when setting the weight low</p></li><li><p>Not working very well when the shoe sole facing up, I think the problem is with the base model, since it also not working well when disabling my model</p></li></ul><p></p><ul><li><p>扩张了训练集并且抠掉了背景和脸部这些无关元素, 所以这个版本在高权重下应该不会污染到脸部之类的部位了.</p></li><li><p>新增了正则化训练集, 现在鞋子的大小和比例以及附着位置应该比之前要好.</p></li><li><p>推荐权重: 0.3-0.9, 测试图是用0.5-0.6跑的, 推荐逐渐提升权重</p></li><li><p>在权重较低时能兼容大部分服装Lora</p></li><li><p>鞋底朝上的姿势大概率会崩, 所以部分躺着的姿势都不太行, 我觉得应该是基模的问题, 因为就算不用我的lora也一样崩. 应该是基模没有对这些姿势进行训练</p></li></ul><p></p><p></p>