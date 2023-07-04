## DreamS Archive
### 一、模型概述

- 标签：`anime`, `sexy`, `female`, `art`, `scenery`, `style`, `art style`, `woman`, `2d`, `girls`, `portraits`, `sketch`, `landscape`, `castle`, `2.5d`
- 下载数：2938
- 收藏人数：623
- 评论人数：3
- 评分人数：22
- 评分：4.82

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] SketchyDreamS

- 统计数据
  - 发布时间：2023-06-18T23:01:40.786Z
  - 原始模型：SD 1.5
  - 下载数：1122
  - 评分人数：5
  - 评分：4.6
- 下载地址
  - [dreamsArchive_sketchydreams.safetensors](https://civitai.com/api/download/models/99061)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/733a6d08-4f6d-418c-a45f-2fed515b1ad6/width=450/1199992.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/caa88da6-0869-4ff3-913c-846c44e6316a/width=450/1199993.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a4877d51-7003-4338-982d-5ccfc05f4b89/width=450/1199996.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/373e0553-5293-4d1a-b4b9-0ba28a11057e/width=450/1199999.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] S3Half

- 统计数据
  - 发布时间：2023-06-18T22:39:07.949Z
  - 原始模型：SD 1.5
  - 下载数：734
  - 评分人数：8
  - 评分：4.88
- 下载地址
  - [dreamsArchive_s3half.safetensors](https://civitai.com/api/download/models/82190)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5eda68eb-4b7a-49f2-808c-839ba3e539c6/width=450/924246.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/297a3154-3a57-4ed2-bfc5-a42f9492e1e5/width=450/924257.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b8b2a514-5ff3-4f25-82c9-b138e76be2b3/width=450/924269.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4f50a7fc-665f-4dec-aeec-5903ff55996c/width=450/924276.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] S3Full

- 统计数据
  - 发布时间：2023-06-18T22:39:07.949Z
  - 原始模型：SD 1.5
  - 下载数：1082
  - 评分人数：9
  - 评分：4.89
- 下载地址
  - [dreamsArchive_s3full.safetensors](https://civitai.com/api/download/models/87399)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/de2a3d65-9ee8-47f0-ba38-7a7df9cd6097/width=450/1001663.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/689ba5dc-5540-4df7-abdf-f2738cdf807d/width=450/1000523.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/08faa440-8fd0-415d-9b44-8e555e7e3984/width=450/1000522.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/43838ffc-2156-48a9-b63e-dcd747662845/width=450/1000621.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-350">SketchyDreamS</h1><p>Overhaul, rather than a direct continuation of ElusiveDreamS. Respects anime style much better, increased compatibility with loras, etc, etc.</p><p>I love how it works with sketchy styles, well, that was one of the points when i made it.</p><p>It utilizes Dreamwave v2 and Sketchy(unreleased) loras, + polishing by S12.</p><p></p><h1 id="heading-2356">ElusiveDreamS</h1><p>This model is a sort of continuation of ACMAR G Mix, as this is it, but spiced up with 3 trainings on top of it, combined using deep merge in 3 steps.</p><p>S3Full - Full merge of S12 on OUT0-11. Might have less leak, more abstraction, and a bit better control, but will surely have higher presence of various particles. Requires stron negative on (3d, realistic) to produce flat, or positive flat color.</p><p>S3Half - Half merge of S12 on OUT0-11. Might have less control, but will be less leaky in abstraction, i think. Doesn't demand negative (3d, realistic) to say 2.5d/anime.</p><h2 id="heading-2357">Highlights</h2><p>Usually quite aesthetically pleasing.</p><p>Partially capable of high level understanding of combination of various concepts, thanks to S12 being a cherry on top of this. + Possibility of high level of compositional abstraction.</p><p>Absolutely fire sketchy look, imho. <br /><br />Refer to S12 for possible new capabilities.</p><h2 id="heading-2358"></h2><h2 id="heading-2359">Downsides</h2><p>Quite rigid by default, so you will need to use more detailed prompts, which most of you already do anyway.</p><p>Is biased towards female characters, so you'll have to increase weight, and/or put appropriate tags in negative to have consistent male output.</p><p>Bias towards flowers. While they are aesthetically pleasing, sometimes you don't want them. Use nagative <code>flowers</code> for that.</p><p>Possibly could be hard to adapt to loras, but that needs testing.</p><p>Best used for 2.5, or 2d, as it's a bit f'ed up in terms of faces, if you promt <code>realistic, 3d</code></p><h2 id="heading-2360">TLDR Information</h2><p>This model is based on ACMAR G Mix, and contains 3 additional trainings, which were added through deep merge technique:<br />Dreamwave(Full), ElusiveWorld, S12(4.2 NAI)</p><p>Dreamwave and Elusive are used for dreamy looks and aestethics, while S12 is a polisher on top, that adds conceptual understanding. It is merged at very high percentages at all blocks to stabilize style at anime, rather than what Dreamwave and Elusive look like, while adding control over output style.</p>