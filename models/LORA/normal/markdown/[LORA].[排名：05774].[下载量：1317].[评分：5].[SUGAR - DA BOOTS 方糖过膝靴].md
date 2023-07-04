## SUGAR - DA BOOTS 方糖过膝靴
### 一、模型概述

- 标签：`girl`, `woman`, `clothing`, `boots`
- 下载数：1317
- 收藏人数：413
- 评论人数：7
- 评分人数：3
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v2.0

- 统计数据
  - 发布时间：2023-03-22T13:52:38.749Z
  - 原始模型：SD 1.5
  - 下载数：1317
  - 评分人数：3
  - 评分：5
- 下载地址
  - [SUGARV2.safetensors](https://civitai.com/api/download/models/25256)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7ce92d80-8cf8-487f-486e-d562e765cb00/width=450/283544.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1cd95e20-ac79-4e33-d95a-b37179daea00/width=450/283543.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/378cd2b1-5dcf-45a5-0495-9616d0b5c900/width=450/283542.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9f160d94-b812-477c-4314-c916f22fd400/width=450/283541.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>It's A lora trained for fashion style boots designed by Chinese Brand <em>DAPHNE. </em>It's quite popular in China these days.</p><p>I learned something from previous failures, so now the style polution and facial problems were gone.</p><p>good with all kinds.</p><p>Since it's a pair of very long thigh boots, so it would be better to set the ratio pretty long, if you want a standing full body shot, otherwise the leg will be shorted, and it looks wierd.</p><p>====================================</p><p>这个lora主要用于生成由国牌达芙妮设计的一种方头款式过膝长靴，</p><p>“方糖”这两年在睿站舞蹈区和小某书上面有多火就不用我多说了吧。</p><p>我从前几次失败的lora训练中汲取了一些教训，所以这次的发布版一上来就可以用，没有画风污染，没有面部问题（立flag呢）。无论二次元还是写实都挺好用的。（大嘘）</p><p>【国人特供の避雷点&amp;解决方法】</p><p>1.可能是因为用novelai做底模训练的缘故，二次元情况下，大概率会出现古早的肢体问题，比如三条腿或者大腿和靴筒位置对不上，站姿基本无问题。</p><p>【解】</p><p>一、多试不同结点。</p><p>二、减少稀奇古怪的角度和姿势，dynamic angle之类的少用。</p><p>三、试试各类negative的embedding比如EasyNagtive之类的。</p><p>四、用controlnet插件。</p><p>五、忍着，然后用inpainting修复抹除。</p><p></p><p>2.在写实情况下，画面比例尽量拉长，否则要么没有下半截靴子，要么全身照会侏儒化，看着很是怪异。</p><p>【解】</p><p>一、拉长图像生成比例</p><p>二、多试试不同的checkpoint，chilloutmix的比例问题比二次元风的要多。</p><p>三、用controlnet插件，openpose可以很好的解决这个问题，唯一注意点是腿部骨骼离画面边缘不要太近，否则厚底鞋很有可能会只露半个鞋头。</p><p>四、（YYDZ，鉴定为纯纯的猜想）狡猾的小某书崽种手机摄影家们都喜欢干什么事情来让照片里的模特显腿长？没错！【P图拉腿】、【低角度拍摄】和【广角镜头畸变拉腿】视觉欺骗三件套。</p><p>所以相对应的，你可以：</p><p>①用某图秀秀后期拉腿P图</p><p>②加上prompt“from below”</p><p> ③加上prompt“wide shot”</p><p></p><p>3.和一些同时带衣服特征的lora一起用的时候依然会崩崩崩，比如c站的两个蛇喰梦子lora，我每次和它们并用都会出一堆2.05D的鬼图（捶地），但是和一些真人脸模一起用就没辣么大的问题，所以我也不清楚这锅归哪边。</p><p>【解】</p><p>一、尽量只找脸模，不用一体模。</p><p>二、原生脸加prompt微调大法</p><p>三、降低权重，摁调说不定能有个平衡值。</p><p></p><p>想要改进请自取哈，别客气。</p><p>另外，给点review啊各位！秋梨膏！</p>