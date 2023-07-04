## 'Alignment' turn humans to robots (concept replacement example)
### 一、模型概述

- 标签：`concept`, `funny`, `singularity`, `robot`, `alignment`
- 下载数：144
- 收藏人数：39
- 评论人数：5
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] 2000 steps

- 统计数据
  - 发布时间：2023-03-29T03:26:24.023Z
  - 原始模型：SD 1.5
  - 下载数：144
  - 评分人数：0
  - 评分：0
- 下载地址
  - [alignmentTurnHumansTo_2000Steps.safetensors](https://civitai.com/api/download/models/30947)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ba224054-8185-4972-4478-a62740340000/width=450/352097.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f3c87874-7446-4dd6-494c-25455d6aef00/width=450/352098.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/59e34082-04a2-4576-a030-ce25297b8200/width=450/352106.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fe93fa62-32ae-44a0-6719-7ab3bea37100/width=450/352105.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Use the trigger word '<em>human</em>'.<br /><br />'Alignment' is an example of using conceptmod to replace the 'human' concept with a 'robot' concept. It has been trained for <strong>2000 </strong>steps. It sometimes replaces 'woman'/'man' without the 'human' trigger, but not always.<br /><br /><strong>Trained using:</strong><br /><a target="_blank" rel="ugc" href="https://github.com/ntc-ai/conceptmod"><u>https://github.com/ntc-ai/conceptmod</u></a></p><p><em>Training does not require a dataset, only words.</em><br /></p><p><strong>Beware merging this mod</strong>. Weights are changed significantly as all humans are now machines.<br /><br />Trained on:<br /><br /><strong><em>"#:0.4|human=robot:0.8|robot%human:-0.1"</em></strong><br /></p><ul><li><p><strong>'#:0.4'</strong> means resist changing the empty (unconditional) prompt ''.</p></li><li><p><strong>'human=robot:0.8'</strong> - pull humans to robots</p></li><li><p><strong>'robot%human<em>:-0.1</em>'</strong> - make robots and humans closer together based on orthogonality.<br /></p><p></p></li><li><p>Technique based on <a target="_blank" rel="ugc" href="https://github.com/rohitgandikota/erasing">https://github.com/rohitgandikota/erasing</a></p></li><li><p>Model based on criarcys-fantasy-to-experience</p><p></p><p><br /></p></li></ul>