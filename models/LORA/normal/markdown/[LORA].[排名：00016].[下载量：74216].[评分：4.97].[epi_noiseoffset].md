## epi_noiseoffset
### 一、模型概述

- 标签：`dark`, `noise offset`, `high contrast`, `tool`
- 下载数：74216
- 收藏人数：7326
- 评论人数：105
- 评分人数：103
- 评分：4.97

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v2

- 统计数据
  - 发布时间：2023-03-04T12:07:34.546Z
  - 原始模型：SD 1.5
  - 下载数：67343
  - 评分人数：86
  - 评分：4.99
- 下载地址
  - [epi_noiseoffset2.pt](https://civitai.com/api/download/models/16576?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [epi_noiseoffset2.safetensors](https://civitai.com/api/download/models/16576)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1068e7d8-e7ed-49a9-ae61-ae7e7cbb0f00/width=450/167154.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/22f5f5b4-d106-4019-32f3-ed3d64ac1800/width=450/178275.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bd17d3db-aa7a-429f-8b87-7063f0615000/width=450/167153.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/11466716-a836-4772-7f10-be3e382bb700/width=450/167152.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v2-pynoise

- 统计数据
  - 发布时间：2023-03-04T12:07:34.546Z
  - 原始模型：SD 1.5
  - 下载数：5540
  - 评分人数：13
  - 评分：4.85
- 下载地址
  - [epiNoiseoffset_v2-pynoise.pt](https://civitai.com/api/download/models/18445?type=Model&format=PickleTensor)
  - [epiNoiseoffset_v2-pynoise.safetensors](https://civitai.com/api/download/models/18445)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5a7a9f62-93e3-4431-c0ee-07bce869f800/width=450/190326.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ae2102d-1117-4677-e42c-7575d85d6400/width=450/190325.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b8b9eaee-c42e-4111-2f64-b2a0a0055400/width=450/190324.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3dc7c637-0800-4740-dc00-29bafd62e600/width=450/190323.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v1

- 统计数据
  - 发布时间：2023-03-04T12:07:34.546Z
  - 原始模型：SD 1.5
  - 下载数：1333
  - 评分人数：4
  - 评分：5
- 下载地址
  - [epi_noiseoffset.pt](https://civitai.com/api/download/models/16407)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ded8e577-8b8d-48fd-4439-7064cdfc1a00/width=450/165569.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7f6a5f4d-58bf-430b-f84c-a9facdd5c600/width=450/165568.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dfb2f1bf-cdb6-4610-01a7-4d6910f1b100/width=450/165567.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b44beee0-241e-41e0-3ade-d0e6995c5d00/width=450/165566.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>UPDATE: v2-pynoise released, read the Version changes/notes</strong></p><p>LORA based on the <a target="_blank" rel="ugc" href="https://www.crosslabs.org//blog/diffusion-with-offset-noise">Noise Offset post</a> for better contrast and darker images.</p><p></p><p>Weighting depends often on Sampler, kept it in the low-middle range (Maybe i will put up a stronger one).</p><p>Custom weighting is needed sometimes.</p><p>Works better if u use good keywords like: <code>dark studio, rim lighting, two tone lighting, dimly lit, low key</code> etc.</p><p></p><p>Didn't like the color saturation and image compositions from the <a target="_blank" rel="ugc" href="https://civitai.com/models/8765/theovercomer8s-contrast-fix-sd15sd21-768">theovercomer8sContrastFix_sd15</a> so i made this one.</p><p></p><p>UPDATE: v2 is slightly stronger in the whole composition</p><p>Update 2: added safetensor file</p><p></p><p><strong><em>Quick Comparsion</em></strong></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/af07d184-3f37-40bb-526e-a6cf9d41bf00/width=525/af07d184-3f37-40bb-526e-a6cf9d41bf00" />