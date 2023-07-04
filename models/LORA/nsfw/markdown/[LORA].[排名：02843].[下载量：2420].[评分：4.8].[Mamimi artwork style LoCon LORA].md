## Mamimi artwork style LoCon LORA
### 一、模型概述

- 标签：`anime`, `makima`, `komi shouko`, `style`, `art style`, `mitaka asa`, `mamimi`
- 下载数：2420
- 收藏人数：679
- 评论人数：35
- 评分人数：5
- 评分：4.8

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] V1.0

- 统计数据
  - 发布时间：2023-03-13T14:25:44.021Z
  - 原始模型：SD 1.5
  - 下载数：2420
  - 评分人数：5
  - 评分：4.8
- 下载地址
  - [Mamimi_style.safetensors](https://civitai.com/api/download/models/21123)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c9df0c51-6385-4c4f-c081-60cfef34b700/width=450/224855.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2b01fc85-cf5f-4587-8e76-2a06f8cf2f00/width=450/223952.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4021e426-d5b6-4478-6d78-5ce80c0fc500/width=450/223721.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1ac7544b-28df-444d-5182-da2918e71e00/width=450/224757.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>中文版在下面</p><p>(use LoCon)<br /></p><p>Recommended resolution: <strong>768x768</strong></p><p>Recommended vae: <strong>orangemix, anyting-v4.0, anyhentai_18</strong></p><p> </p><ul><li><p>If any other LoRA is not used, the suggested weight of this Lora is about: <strong>0.55-0.75</strong>.</p></li><li><p>tag of Regularization(optional):mamimi</p></li><li><p>Lower weight gets clearer picture, which may be similar to the early artstyle of Mamimi?</p></li><li><p>In the case of low resolution, the rendered image may be blurred, but it can be improved by using any upscale function in stable diffusion to fix it like high res fix or ultimate sd upscaler. Denoising recommends about 0.3-0.4.</p></li></ul><p></p><p>And after improving the resolution the art style is still kind similar to Mamimi.</p><p> </p><p>****Detailed weight recommendation of this LoRA:****</p><ul><li><p>Only this LORA used and using Additional Networks (LoRA): 0.65-0.75</p></li><li><p>Only this LORA used and using in prompt: 0.65-0.75</p></li></ul><p> </p><ul><li><p>Using with another single Lora: 0.65-0.75. If there have little blur, can repair it in High res fix.</p></li></ul><ul><li><p>Using with other multiple Lora: 0.55-0.75. If there have little blur, can repair it in High res fix.</p></li></ul><p> </p><p>When using the "Composable LoRA" and "Latent couple" plug-ins to generate multiplayer characters in the scene:</p><ul><li><p>Using Additional Networks (LoRA): 0.5-0.65. If using this LoRA results in the loss of some characters features, you can appropriately lower the weight of this LoRA or increase the weight of the character LoRA</p></li><li><p>Using in prompt: 0.65-0.75</p></li></ul><p></p><p>Unfortunately, I don't know how to train body position, if I know how to do it, I want to try to train some bestiality and other body position painted by Mamimi.</p><p></p><p></p><p>这里是中文说明：<br /><br />大佬们好，</p><p>你们能给我一些关于这个LoRA的反馈吗？</p><p>因为这是我第一次为艺术风格制作LoRA，而且我用了LOCON，所以我不确定它在其他电脑上是否能正常使用。</p><p>如果它不起作用比如报错了，请告诉我情况，然后我会修复一下。</p><p>谢谢各位。<br /></p><p>(用了LoCon)<br /></p><ul><li><p>可以用 "mamimi \(mamamimi\)"这个tag来获取更加匹配mamimi大佬的画风。</p></li></ul><p>Mamimi大佬的画风，第一版先凑合用。</p><p>用anything4.5训练的LoRA</p><p>只训练了250多张图片（加上正则化也才290多张），20epoch, 每张图片10step，然后用的Lion优化。 有没有大佬教一下哪种参数训练画风最好，感谢。</p><p></p><p>如果不输入女性的细节，那出来的女性大部分都很像 “古见 硝子”。。。</p><p>因为Mamimi大佬画的古见硝子太多了。。。</p><p></p><p>推荐分辨率：<strong>768x768</strong></p><p>推荐vae：<strong>orangemix, anyting-v4.0, anyhentai_18</strong></p><p></p><ul><li><p>如果不用任何其他LoRA，此lora的权重建议价是<strong>0.55-0.75</strong>左右。</p></li><li><p>正则化tag(可选）：mamimi</p></li><li><p>权重低的话可以保持比较清晰的画面，可能类似mamimi作者早期画风？</p></li><li><p>分辨率低的情况下，渲染出来的图可能会糊，但可以用高清修复来提高清晰度或者ultimate sd upscaler啥的，提高清晰度后的画风还是很像mamimi大佬的。denoising推荐0.3-0.4左右</p></li></ul><p></p><p>****这个LoRA的详细权重推荐:****</p><ul><li><p>单独使用/Additional Networks (LoRA)：0.65-0.75</p></li><li><p>单独使用/直接在prompt：0.65-0.75</p></li></ul><p></p><ul><li><p>与单个其他lora配合的权重：0.65-0.75，如果模糊，跑一边高清修复就行了</p></li><li><p>与多个其他lora配合的权重：0.55-0.7，如果模糊，跑一边高清修复就行了</p><p></p></li></ul><p>使用Composable lora和Latent couple 插件来生成多人图时：</p><ul><li><p>如果用的是Additional Networks (LoRA)：这个lora的权重建议价是0.5-0.65. 如果开启这个lora导致一些人物lora的特征丢失，那么可以适当把此lora权重调低，或把人物lora的权重弄高一点</p></li><li><p>如果是直接再prompt里使用：这个lora的权重建议价是0.65-0.75左右.</p></li></ul><p></p><p>可惜不知道怎么训练体位，要不然想试试训练出Mamimi大佬画的一些兽X之类的动作。</p>