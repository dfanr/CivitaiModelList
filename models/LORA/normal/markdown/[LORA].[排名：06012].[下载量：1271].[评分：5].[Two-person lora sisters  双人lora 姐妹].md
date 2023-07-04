## Two-person lora sisters  双人lora 姐妹
### 一、模型概述

- 标签：`anime`, `female`, `girls`, `two-person lora`
- 下载数：1271
- 收藏人数：299
- 评论人数：4
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Two-person-sisters

- 统计数据
  - 发布时间：2023-03-27T14:21:25.190Z
  - 原始模型：SD 1.5
  - 下载数：1271
  - 评分人数：2
  - 评分：5
- 下载地址
  - [2girls.safetensors](https://civitai.com/api/download/models/30066)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/579c3e15-f69a-47fb-0c79-c38f5bad6600/width=450/341097.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6803750b-70ae-4abb-28a4-a675190ea100/width=450/341102.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e7f71544-3260-406d-c744-23ed972b5100/width=450/341100.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/00b907bf-6226-4f39-e11e-ed3902d40b00/width=450/341098.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>这回训练的目的是，稳定生成两个角色，并且通过位置固定特征（画面左边的年龄更小）。</p><p> </p><p>基础功能：可稳定生成两个女性</p><p>初级用法：稳定生成两个女性，表现出她们的年龄差</p><p>权重0.8-1，使用Hires. Fix，Denoising 0.3-0.4</p><p> </p><p>进阶用法：使用两个角色lora，稳定她们的年龄，妹妹在左边，姐姐在右边（并不是100%稳定）</p><p>1.使用Hires. Fix，Denoising 0.3-0.4</p><p>2.同时打开latent couple和 Composable Lora。latent couple使用默认的矩阵即可。</p><p>3.使用lora插件（注意：必须是插件）加载本lora，建议权重0.3-0.5之间</p><p>4.按照以下格式填写prompt</p><p>“age difference, 2girls, girl on the left,</p><p>AND 1girl,age difference, 2girls, girl on the left,small breast,&lt;妹妹lora1:0.5&gt;,[lora1‘s trigger words]</p><p>AND 1girl,age difference, 2girls, girl on the left,big breast,&lt;姐姐lora2:0.5&gt;,[lora2‘s trigger words]”</p><p>要使用的两个角色lora需要适当调低权重。</p><p>需要找到本lora生效和过拟合之间的平衡点，建议使用xyz寻找。因为角色年龄受到角色lora影响，有时候需要配合其他prompt加大力度。</p><p></p><p>The purpose of this training is to generate two characters consistently and show their age difference through fixed position features (the younger character on the left side of the image).</p><p> </p><p>Basic function: Generate two females consistently.</p><p>Intermediate usage: Generate two females consistently and show their age difference.</p><p>Weight range: 0.8-1 Use Hires. Fix and Denoising 0.3-0.4.</p><p> </p><p>Advanced usage: Use two Lora characters and generate them consistently with the younger sister on the left and the older sister on the right (not 100% consistent).</p><p> 1.Use Hires. Fix and Denoising 0.3-0.4.</p><p>2.Enable latent couple and Composable Lora. Use the default matrix for latent couple.</p><p>3.Load the Lora plugin (must be a plugin) for this Lora. Suggested weight range: 0.3-0.5.</p><p>4.Use the following format for prompt:</p><p>"age difference, 2 girls, girl on the left,</p><p>AND 1 girl, age difference, 2 girls, girl on the left, small breast, &lt;younger sister Lora 1:0.5&gt;, [Lora 1's trigger words]</p><p>AND 1 girl, age difference, 2 girls, girl on the left, big breast, &lt;older sister Lora 2:0.5&gt;, [Lora 2's trigger words]"</p><p>Adjust the weights for the two Lora characters appropriately.</p><p>Find the balance point between the effectiveness and overfitting of this Lora by using XYZ. Because the age of the characters is influenced by the Lora characters, sometimes other prompts need to be combined to increase the effectiveness.</p>