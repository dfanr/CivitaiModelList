## Jim Lee (DC Comics / Marvel) Style LoRA
### 一、模型概述

- 标签：`batman`, `superhero`, `marvel`, `dc comics`, `comics`, `style`, `art style`, `wonder woman`, `superman`, `jim lee`, `artstyle`
- 下载数：16813
- 收藏人数：3145
- 评论人数：67
- 评分人数：36
- 评分：4.97

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] offset

- 统计数据
  - 发布时间：2023-03-24T07:25:44.794Z
  - 原始模型：SD 1.5
  - 下载数：16384
  - 评分人数：31
  - 评分：5
- 下载地址
  - [jim_lee_offset_right_filesize.safetensors](https://civitai.com/api/download/models/10580)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/671dc47e-cace-49e6-4bb4-7a0997b10100/width=450/102779.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c5d6b7e8-b036-4f17-1aab-87446e078500/width=450/103823.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/db1107bc-2493-4354-84d4-82a83cc3b600/width=450/102795.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/30ab31cf-2332-460b-0ec4-8871541a4d00/width=450/102794.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] original

- 统计数据
  - 发布时间：2023-03-24T07:25:44.794Z
  - 原始模型：SD 1.5
  - 下载数：429
  - 评分人数：5
  - 评分：4.8
- 下载地址
  - [jim_lee.safetensors](https://civitai.com/api/download/models/10754)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bc39aa5e-75ca-4cf8-f5a8-4c6614134b00/width=450/104946.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4b688d25-51d3-4bed-52ee-66ca7fcf3600/width=450/104945.jpeg" /> |
| ---- | ---- |


### 三、详情
<h2>Jim Lee (DC Comics / Marvel) style LoRA</h2><p><strong>Making models can be expensive. Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong></p><p>Been wanting to try this for a long time now. I think this came out pretty nicely and captures the style of Jim Lee quite well. I tested it on AnyLoRA and AbyssOrangeMix2 with my negative embeddings and it's pretty convincing <strong>at weight=1 for the offset version and 0.65 for the original (check "original" tab for a comparison)</strong>. Use the prompt <code>jim lee</code> for better accuracy.</p><p>Keep in mind that, while this can make Superman, Batman and Wonder Woman pretty well, this is not a character LoRa but a Style LoRA. Have fun making your own superheroes!</p><p><strong>NOTE: </strong>I used ControlNet on some of the examples. Check the full generation data.</p><p>2nd pic courtesy of <strong>sadxzero </strong>from the reviews.</p><p></p><p><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight</strong> <strong>according to the instructions of the model </strong>(by default it's <code>:1</code>)</p></li></ul>