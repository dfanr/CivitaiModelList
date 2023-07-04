## Z_phyr Noise Transformation
### 一、模型概述

- 标签：`dark`, `fix`, `noise offset`, `high contrast`, `tool`, `light`, `merge`
- 下载数：149
- 收藏人数：36
- 评论人数：7
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1-5-n-t

- 统计数据
  - 发布时间：2023-04-08T12:26:35.143Z
  - 原始模型：SD 1.5
  - 下载数：149
  - 评分人数：1
  - 评分：5
- 下载地址
  - [zPhyrNoise_v15NT.ckpt](https://civitai.com/api/download/models/39938?type=Model&format=PickleTensor&size=pruned&fp=fp16)
  - [zPhyrNoise_v15NT.safetensors](https://civitai.com/api/download/models/39938)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6c7c1cb9-1dbb-4493-4be6-47180aeadf00/width=450/442383.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7c64085a-32b1-4ee0-dbde-8c444d7c3c00/width=450/442382.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8b6fccb0-fdb0-479b-83e6-a15482df7d00/width=450/442381.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2896fa73-77b9-4128-ae40-47d845862100/width=450/442380.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>(Example for simplification only). Imagine a histogram of any generated image. What does noise offset do? It completely shifts this histogram to the left or right, as if you were changing the exposure on the camera. Instead, I suggest stretching/normalizing both ends of the histogram so that they occupy the entire color space and at the same time there are no too sharp transitions along its entire length. (I tried to depict the function on the last graph, it looks like the “Curves” tool in Photoshop). This affects only those U-Net blocks that are responsible for color, brightness and detail, while almost not affecting the blocks of the general composition of the frame. The strength of application can be controlled in the same way as when merging noise offset.</p><p>（仅为简化而设的示例）。想象一下任何生成图像的直方图。噪声偏移会做什么？它完全将这个直方图向左或向右移动，就像你在相机上改变曝光一样。相反，我建议拉伸/归一化直方图的两端，使它们占据整个色彩空间，同时在其整个长度上没有太大的跳变。（我试图在最后一个图上描绘这个函数，它看起来像Photoshop中的“曲线”工具）。这只影响那些负责颜色、亮度和细节的U-Net块，而几乎不影响帧的总体构图块。应用的强度可以像合并噪声偏移一样进行控制。</p><p>(Пример исключительно для упрощения понимания). Представим гистограмму любого сгенерированного изображения. Что делает смещение шума? Полностью смещает эту гистограмму влево или вправо, как если бы вы меняли экспозицию на фотоаппарате. Вместо этого я предлагаю растянуть/нормализовать оба конца гистограммы так, чтобы они занимали всё цветовое пространство и при этом не было бы слишком резких перепадов на всём его протяжении. (Попытался изобразить функцию на последнем графике, она похожа на инструмент "Кривые" в Фотошопе). При этом затрагиваются только те блоки U-Net, которые отвечают за цветность, светлость и детализацию, при этом почти не затрагивая блоки общей композиции кадра. Силу применения можно контролировать точно так же, как при подмешивании смещения шума.</p>