## Flat-2D Animerge
### 一、模型概述

- 标签：`anime`, `style`, `cartoon`
- 下载数：23641
- 收藏人数：5143
- 评论人数：15
- 评分人数：67
- 评分：4.93

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v3.0

- 统计数据
  - 发布时间：2023-06-25T03:56:17.835Z
  - 原始模型：SD 1.5
  - 下载数：6711
  - 评分人数：10
  - 评分：5
- 下载地址
  - [flat2DAnimerge_v30.safetensors](https://civitai.com/api/download/models/103436)
  - [flat2DAnimerge_v30.safetensors](https://civitai.com/api/download/models/103436?type=Model&format=SafeTensor&size=full&fp=fp32)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3f8bd781-0f9b-44de-8328-42804bb5727e/width=450/1279314.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c5738e6a-22f6-49ca-b2e2-08488915cf14/width=450/1279307.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7edb658e-0862-4b28-a72b-18e389f80576/width=450/1279315.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c057a8b1-c8f4-439a-b53a-9213d4090756/width=450/1279319.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v2.0

- 统计数据
  - 发布时间：2023-06-25T03:38:05.339Z
  - 原始模型：SD 1.5
  - 下载数：9818
  - 评分人数：20
  - 评分：4.95
- 下载地址
  - [flat2DAnimerge_v20.safetensors](https://civitai.com/api/download/models/91560)
  - [flat2DAnimerge_v20.safetensors](https://civitai.com/api/download/models/91560?type=Model&format=SafeTensor&size=full&fp=fp32)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/27302cb1-eec1-4420-91ab-7cb61773055e/width=450/1069724.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/23e0c2a2-34a5-45fd-946a-0c83cbb28ab0/width=450/1069725.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fc73e8e3-4bb1-4e40-bdb4-ac9377e3d933/width=450/1069728.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d6036e2b-977f-491c-b5fd-8bfdb1662814/width=450/1069731.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v1.0

- 统计数据
  - 发布时间：2023-06-25T03:38:05.339Z
  - 原始模型：SD 1.5
  - 下载数：7112
  - 评分人数：37
  - 评分：4.89
- 下载地址
  - [flat2DAnimerge_v10.safetensors](https://civitai.com/api/download/models/42138)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/876018ca-1764-449c-5aa2-48d290d93f00/width=450/471674.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c356ede8-01b1-43b9-9c0d-6b0ee77a2f00/width=450/462760.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/89812eef-294e-4722-1bab-d147cd53c600/width=450/462766.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0939d67c-9e32-4c1a-675c-f6d5bbc8af00/width=450/471673.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2 id="heading-705">Description</h2><p>This is a merge of some random anime based and cartoon based models to achieve a somewhat cartoony anime style, more similar to what you would actually see in anime as opposed to the more common hyper-detailed anime models.</p><p>Version 3 includes some custom training to further enhance the style. More details available in "About this Version" on the sidebar. Most positive prompts for the v3 sample images were randomly generated.</p><p></p><h2 id="heading-706">Usage Guide</h2><ul><li><p><strong>(highly recommended) </strong>Use the dynamic thresholding plugin (all example images do with cfg scale 10 mimic 7): <a target="_blank" rel="ugc" href="https://github.com/mcmonkeyprojects/sd-dynamic-thresholding">https://github.com/mcmonkeyprojects/sd-dynamic-thresholding</a></p><ul><li><p>Set the CFG scale to 10.0</p></li><li><p>Click the checkbox "Enable Dynamic Thresholding (CFG Scale Fix)"</p></li><li><p>Set the Mimic CFG Scale to 7</p></li><li><p>If you don't want to use this plugin, then set the config scale to 5 or 6</p></li></ul></li><li><p><strong>(highly recommended)</strong> Use a negative embedding for best results</p><ul><li><p>I use verybadimagenegative_v1.3 and easynegative (all examples use this)</p></li><li><p>verybadimagenegative_v1.3</p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/11772/verybadimagenegative">https://civitai.com/models/11772/verybadimagenegative</a></p></li></ul></li><li><p>easynegative</p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative">https://civitai.com/models/7808/easynegative</a></p></li></ul></li><li><p>Place the downloaded files into the "embeddings" folder of the SD WebUI</p></li><li><p>In the negative prompt, paste "verybadimagenegative_v1.3, easynegative"</p></li></ul></li><li><p><strong>(highly recommended)</strong> Upscaling at 2x using R-ESRGAN 4x+ Anime6B works very well (no need for high weights, 0.45 will work fine). Additionally, generating the pre-upscaled image at a higher resolution such as 768x768 will improve quality a lot.</p></li><li><p>This merge is very easy to prompt, and does not require a ton of prompt engineering to get good results. The following format will yield decent results:</p><ul><li><p>Prompt:</p><ul><li><p>(best-quality:0.8), perfect anime illustration, &lt;normal description of the image, e.g. a woman running in tokyo at night, a flaming meteor, etc.&gt;</p></li></ul></li><li><p>Negative:</p><ul><li><p>(worst quality:0.8), verybadimagenegative_v1.3, easynegative, (surreal:0.8), (modernism:0.8), (art deco:0.8), (art nouveau:0.8)</p></li></ul></li></ul></li><li><p>The model is capable of NSFW</p></li></ul>