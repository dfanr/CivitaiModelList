## Supercutecat_v10
### 一、模型概述

- 标签：`animals`, `colorful`, `cat`, `cute`, `depth of field`, `animal`
- 下载数：1162
- 收藏人数：173
- 评论人数：2
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.1

- 统计数据
  - 发布时间：2023-05-28T16:36:03.005Z
  - 原始模型：SD 1.5
  - 下载数：606
  - 评分人数：0
  - 评分：0
- 下载地址
  - [RPGcat.safetensors](https://civitai.com/api/download/models/83867)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/03ea6fda-a25f-4a16-a107-6155f324d86f/width=450/946567.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7828d804-2e12-46da-b9b3-0e1795422c98/width=450/946487.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/303a474e-40f8-45e2-b675-cdd51cb4d3b3/width=450/946494.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f60c5095-23da-4768-aa05-c7e863618fee/width=450/946497.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-05-28T16:27:38.532Z
  - 原始模型：SD 1.5
  - 下载数：556
  - 评分人数：0
  - 评分：0
- 下载地址
  - [Supercutecat_v10.safetensors](https://civitai.com/api/download/models/79883)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ccb24eb2-9a4a-4823-9eef-36cb0d7aa55d/width=450/908432.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4c888a61-b5e5-4a80-92f6-8f1500ca8d14/width=450/908444.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/07f3a52b-024a-41ee-bb38-86b0ab9f2757/width=450/908458.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1ec0f137-d9b7-4d1e-bcfa-d8133306dd92/width=450/908430.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>这是一个关于猫的lora，超级超级可爱~~</p><p>触发词只需要很少，类似一只猫，一只狗这种就可以，当然加上画面质量的相关词也可以。用的1.5基础底模训练，配合其他猫类大模型效果应该最佳，只实测了几个本人含有的模型效果也还可以。</p><p>以下是注意事项：<br /><br /><strong><em>负面提示词自己写，不要复制封面图上的，实测之前CFG只能设置3是因为负面提示词权重设置为 :2 太高了。</em></strong></p><p>采样器用Euler a或者DPM ++2M Karras或者DPM ++SDE Karras 区别不大，步数可以大一点30以上都行。图片尺寸512*704是默认训练尺寸，画面质量已经很高清了，如果点高清修复（<span style="color:rgb(229 231 235 / var(--tw-text-opacity))">Denoising strength设置为0.45-0.6，</span><strong><em><span style="color:rgb(229 231 235 / var(--tw-text-opacity))">建议0.5</span></em></strong><span style="color:rgb(229 231 235 / var(--tw-text-opacity))">）</span>，不然会出现重复的肢体。</p><p>特殊触发词：cutemaomao(不加触发词也可以，只是会更贴合提示词的内容，权重越低越不容易猫化~~)</p><p>lora权重在0.6开始有明显作用，并且有意想不到的效果（各种猫头少女，似猫似狗，似猫似鸟的不明动物...），0.9-1就基本会稳定出可爱猫图了~~<br /><br /><br /><strong><em>1.1：</em></strong><br />1.1搭配<strong>A-Zovya RPG Artist Tools效果更好，</strong>增加lora画面质量有很大的提升，权重不要设置太高，0.6左右，可能会有崩坏，多尝试~<br /><br />This is a lora about a cat, super super cute~~</p><p>Trigger words only need very little, similar to a cat, a dog such can, of course, plus the quality of the picture related words can also be. With the 1.5 basic base model training, with other cats big model effect should be the best, only a few actual test I contain the model effect is also okay.</p><p>The following are notes:</p><p></p><p><strong><em>Negative tips write their own words, do not copy the cover image, the actual test before the CFG can only be set to 3 because the negative tip word weight is set to :2 too high.</em></strong></p><p>Sampler with Euler a or DPM ++2M Karras or DPM ++SDE Karras not much difference, the number of steps can be a little larger than 30 can. Image size 512 * 704 is the default training size, the quality of the screen is already very high definition, if the point HD repair (Denoising strength set to 0.45-0.6, recommended 0.5), otherwise there will be duplicate limbs.</p><p>Special trigger word: cutemaomao (no trigger word can also be added, it will just fit the content of the prompt word more closely, the lower the weight the less likely to catastrophize ~~)</p><p>lora weight in 0.6 began to have an obvious role, and unexpected effects (a variety of cat-headed girls, like a cat like a dog, like a cat like a bird of unknown animals ...) 0.9-1 will basically stabilize the cute cat figure ~ ~</p><p>1.1:</p><p>1.1 with A-Zovya RPG Artist Tools better results, increase lora picture quality has been greatly improved, the weight should not be set too high, about 0.6, there may be a collapse, try more ~<br /><br /><strong>Everything is gradually catastrophizing</strong></p>