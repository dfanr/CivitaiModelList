## [V3 Final]Artist: mignon | Mignon artist's painting style
### 一、模型概述

- 标签：`anime`, `style`, `artist`, `girls`, `style art`, `artists`, `style lora`
- 下载数：2682
- 收藏人数：556
- 评论人数：43
- 评分人数：8
- 评分：4

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v3.0

- 统计数据
  - 发布时间：2023-06-11T15:32:30.922Z
  - 原始模型：SD 1.5
  - 下载数：769
  - 评分人数：2
  - 评分：5
- 下载地址
  - [style_mignon_3.0.safetensors](https://civitai.com/api/download/models/93883)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/81ec0181-6ad5-4bf5-9232-6f7532ea40ea/width=450/1110571.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/df1c2ae3-d318-489a-826d-5cbe94f3bf04/width=450/1110327.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3e2828d7-c7f0-464d-90ce-bd79a9ab3b8a/width=450/1110291.jpeg" /> |
| ---- | ---- | ---- |

#### [版本2/共3个版本] v2.0

- 统计数据
  - 发布时间：2023-06-11T15:00:45.869Z
  - 原始模型：SD 1.5
  - 下载数：628
  - 评分人数：3
  - 评分：3.67
- 下载地址
  - [style_mignon.safetensors](https://civitai.com/api/download/models/91445)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6f15bc94-152a-4fcc-b527-1bda935a8627/width=450/1068362.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d2fcf350-4db4-430d-9911-3b18172b2392/width=450/1068373.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7cbc161d-f9b8-4488-9f06-63b2d64c57d9/width=450/1070850.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4fdc9713-540c-4acb-9b19-0cd193a1790d/width=450/1068363.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v1.2

- 统计数据
  - 发布时间：2023-06-11T15:00:45.869Z
  - 原始模型：SD 1.5
  - 下载数：1285
  - 评分人数：3
  - 评分：3.67
- 下载地址
  - [style_mignon.safetensors](https://civitai.com/api/download/models/71312)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e95d15c1-d81e-4428-8aec-0f167f73cbbc/width=450/796656.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/22edc5a8-2811-4b63-9300-74a441a5b50d/width=450/796639.jpeg" /> |
| ---- | ---- |


### 三、详情
<h3 id="heading-43">All illustrated characters are adults. Please abide by local laws and ensure appropriate content generation.</h3><p></p><h1 id="heading-44">Mignon Style LoRA V3</h1><p>中文 | English <span style="color:#fa5252">使用前阅读 | Read before use</span></p><p>  .</p><p>✅R18</p><p>--</p><p>最终版本，这个模型以后不会再更新。</p><p>Final version, this model will not be updated in the future.</p><p>--</p><h2 id="heading-14505">题外话和互动环节</h2><p>为了解决一些令人懊恼的问题，这个周末我整理了一些资料和论文，实现了一些技术上的突破：</p><ul><li><p>已实现完全可控的绘画技法或后期效果拟合，如厚涂、泼彩、色相分离（待验证）等。</p></li><li><p>已实现完全可控的肢体动作拟合。</p></li><li><p>已实现完全可控的构图偏好拟合，比如大透视构图、对角线构图等。</p></li><li><p>完全可控是指可以随意调整其拟合程度。</p></li><li><p>V3版本的训练法对训练素材基本不挑剔，绝大多数时候能够完全利用上素材。</p></li></ul><p>具体到这个模型的话：</p><ul><li><p>有人反馈之前的版本的动作过拟合了，我弱化了肢体动作上的拟合，但没有完全移除，完全移除后感觉没那种精气神了。</p></li><li><p>同时，有人反馈之前的版本对作者的绘画技法体现得不够明显，我增强了这方面的权重。</p></li></ul><p>一直没深入探讨过怎样的模型才算画风模型，以往我都是按怎么看着顺眼怎么来整的，不过最近收到的反馈有好有坏，我想针对使用群体优化其体验，看看大家的偏好，“投其所好”。</p><p></p><p><strong>如果有空的话，请在评论区做个选择，我会在以后按多数人的喜好进行训练：</strong></p><p>A. <strong>完全是构图。</strong>对画师的作画风格学习只学习构图和肢体动作。</p><p>B. <strong>主要侧重于构图，不看重作画技法。</strong>对画师的作画风格学习主要侧重于构图和肢体动作，其次是作画技法。</p><p>C. <strong>主要侧重于人物和构图。</strong>对画师的作画风格学习主要侧重于面部细节和体型等，此外是构图偏好，最后是作画技法。</p><p>D. <strong>主要侧重于人物和技法。</strong>对画师的作画风格学习主要侧重于面部细节和体型等，此外是作画技法，最后是构图偏好。</p><p>E. <strong>完全是人物。</strong>对画师的作画风格学习主要侧重于面部细节和体型等，其他的都是浮云。（这个显然就不能叫做画风模型了）</p><p>F. <strong>主要侧重于技法。</strong>对画师的作画风格学习主要侧重于作画技法，其次是构图，最后是人物。</p><p>G. <strong>完全是技法。</strong>对画师的作画风格学习只学习作画技法。</p><p>.</p><p>不可能“我 · 全 · 都 · 要 · ！”，全都要就是完全拟合了。</p><p>--</p><h2 id="heading-14506">Digression &amp; Interaction</h2><p>To solve some frustrating problems, I organized some materials and papers this weekend and achieved some technological breakthroughs:</p><ul><li><p>Fully controllable painting techniques or post-effect fitting have been implemented, such as thick paint, splashed colors, hue separation (to be verified), etc.</p></li><li><p>Fully controllable limb movement fitting has been achieved.</p></li><li><p>Fully controllable composition preference fitting has been achieved, such as large perspective composition, diagonal composition, etc.</p></li><li><p>Fully controllable means that the degree of fitting can be adjusted freely.</p></li><li><p>The V3 version training method is not very picky about the training materials and can fully utilize the materials in most cases.</p></li></ul><p>Regarding this model:</p><ul><li><p>Someone gave feedback that the previous version overfitted the actions, so I weakened the fitting on limb movements, but did not completely remove it, as it felt lacking in taste without it.</p></li><li><p>At the same time, some people gave feedback that the previous version did not reflect the author's painting technique, so I enhanced the weight in this aspect.</p></li></ul><p>I have never delved into what kind of model constitutes a painting style model. In the past, I just did it according to my own preferences. However, the feedback I have received recently is mixed. I want to optimize the experience for the user group and see everyone's preferences to "suit their tastes".</p><p></p><p><strong>If you have time, please make a choice in the comments. I will train according to the preferences of the majority in the future:</strong></p><p>A. <strong>Focus solely on composition.</strong> Learn from artists' drawing styles only in terms of composition and limb movements.</p><p>B. <strong>Mainly focus on composition and pay less attention to painting techniques.</strong> Learn from artists' drawing styles mainly in terms of composition and limb movements, followed by painting techniques.</p><p>C. <strong>Mainly focus on characters and composition.</strong> Learn from artists' drawing styles mainly in terms of facial details and body shape, with an emphasis on composition preferences and lastly on painting techniques.</p><p>D. <strong>Mainly focus on characters and techniques.</strong> Learn from artists' drawing styles mainly in terms of facial details and body shape, with emphasis on painting techniques followed by composition preferences.</p><p>E. <strong>Focus solely on characters.</strong> Learn from artists' drawing styles mainly in terms of facial details and body shape, and everything else is irrelevant. (Obviously, this cannot be called a painting style model.)</p><p>F.<strong> Mainly focus on technique.</strong> Learn from artists' drawing styles mainly in terms of painting techniques, followed by composition, and lastly characters.</p><p>G. <strong>Focus solely on technique.</strong> Learn from artists' drawing styles only in terms of painting techniques.</p><p>--</p><h2 id="heading-14503">关于模型</h2><p>仿Mignon的作画风格的LoRA模型。</p><p></p><p><strong>权重建议值：</strong>1.0 (or 0.5~1.2)</p><p><strong>基于模型：</strong><span style="color:rgb(193, 194, 197)">CreationMixV1 Trimmed</span></p><p><strong>训练信息：</strong>共计558张原画（含裁剪图和视频截图），迭代1116步，多分辨率迭代训练。</p><p><strong>其他的一些建议：</strong>必要时请加入词条：uncensored。</p><p><strong>更新：</strong> V2 --&gt; V3</p><ul><li><p>弱化动作拟合</p></li><li><p>提升技法拟合</p></li></ul><p>--</p><h2 id="heading-14504">About</h2><p>LoRA model with a painting style imitating Mignon。</p><p><strong>Recommended weight value:</strong> 1.0 (or ranging from 0.5 to 1.2).</p><p><strong>Based on the model:</strong> <span style="color:rgb(193, 194, 197)">CreationMixV1 Trimmed</span></p><p><strong>Training information:</strong> A total of 558 paintings (including <span style="color:rgb(193, 194, 197)">cropped images and </span>video screenshots) were used for training, with 1116 iterations using multi-resolution iteration training.</p><p><strong>Other suggestions:</strong> When necessary, please add the tag "uncensored".</p><p><strong>Update:</strong> V2 --&gt; V3</p><ul><li><p>Weakening action fitting</p></li><li><p>Improving painting techniques fitting</p></li></ul><p>--</p><p>如果你创作出了好作品，欢迎分享它。如果它无法满足你的需求，我是说，我的朋友，请不要给出一星好评。</p><p><span style="color:rgb(193, 194, 197)">If you've created something good, feel free to share it. If it doesn't meet your needs, I mean, my friend, please don't give a one-star 'praise'.</span></p>