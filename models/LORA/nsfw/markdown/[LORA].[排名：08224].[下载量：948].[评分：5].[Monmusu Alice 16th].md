## Monmusu Alice 16th
### 一、模型概述

- 标签：`girl`, `lamia`, `monster girl`
- 下载数：948
- 收藏人数：233
- 评论人数：4
- 评分人数：4
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v0.3

- 统计数据
  - 发布时间：2023-04-01T23:08:47.791Z
  - 原始模型：SD 1.5
  - 下载数：591
  - 评分人数：2
  - 评分：5
- 下载地址
  - [mgq_alice16v0.3.safetensors](https://civitai.com/api/download/models/33422)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cf6372ca-a6fc-4840-01b2-ec1e8d4ec200/width=450/380958.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d9d7d3dd-fbec-4d12-ab7b-139c25a5cf00/width=450/380965.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1795b6c5-f3dc-4b5b-cde5-8860548af100/width=450/380964.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1ffff6ec-0e81-485a-68a0-d63f0fcd7500/width=450/380963.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v0.2

- 统计数据
  - 发布时间：2023-04-01T23:08:47.791Z
  - 原始模型：SD 1.5
  - 下载数：357
  - 评分人数：2
  - 评分：5
- 下载地址
  - [mgq_alice16v0.2.safetensors](https://civitai.com/api/download/models/29133)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/92393b65-197a-4a7d-a3ba-50981159ab00/width=450/329051.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/36908139-5db5-4fac-8338-28a0b6b07f00/width=450/329054.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1308df8e-58cb-4dec-9505-f0f232820b00/width=450/329053.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7dac7a77-5780-4734-ffac-719671dcbe00/width=450/329052.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>LORA trained on <a target="_blank" rel="ugc" href="https://omniversal-battlefield.fandom.com/wiki/Alice_Fateburn">Alipheese Fateburn XVI </a>(Alice) from MGQ.</p><p>Training based on ingame CG, fanart and v0.2 generated good images (curated with inpaint for better detail accuracy, eg tattoo shape and clothing)</p><p></p><p>Trained on <a rel="ugc" href="https://civitai.com/models/10028/neverending-dream-ned">NED</a> and tested also with <a target="_blank" rel="ugc" href="https://civitai.com/models/21728/aiomonstergirls">AIOMonsterGirls</a> and <a target="_blank" rel="ugc" href="https://huggingface.co/andite/anything-v4.0/tree/main">anything-v4.5</a>.</p><p></p><p>Related to v0.3:</p><p>This version is less overfitted than the previous, while focusing more accurately on alice's details.</p><p>Hence it should be much easier to obtain good pictures without seed-hunting and should also be adaptable to way more models.</p><p></p><p>Suggested weights:</p><ul><li><p><strong>0.65~0.8</strong>: For more photorealistic, look and less bound to the ingame details</p></li><li><p><strong>0.8~1.0</strong>: To more easily reproduce all of her details, especially for her lamia form</p></li></ul><p></p><p>Her monster form features are tied to the <strong><em>monster_girl </em></strong>and <strong><em>lamia </em></strong>tags, but sometime specifying <strong><em>purple_skin</em></strong> as well might help.</p><p>Also the <strong><em>tattoo</em></strong> and <strong><em>black_gloves</em></strong> should now be more ingrained in the lora, but not overfitted, (should be easier to obtain on high lora weight, but can be specified as a tag for lower weights). (It is possible to get the shape of her tattoos identical to the original, but without manually priming it and going with inpaint, it is still not super consistent)</p><p>Using the <strong><em>skirt </em></strong>prompt and higher lora weights should help get her skirt closer to the original.</p><p></p><p>I also suggest using the negative tag <strong><em>symmetry </em></strong>to help reproduce her look (eg tattoo, flower and skirt are totally non-symemtryic), and <strong><em>legs</em></strong><em> </em>when going for her lamia form (atleast for solo images).</p><p></p><p>As for the previous version, when going for the lamia form i would also suggest using a <strong>0.1~0.3</strong> of the <a target="_blank" rel="ugc" href="https://civitai.com/models/14136/anime-lamia">anime lamia LORA</a>. You can get good lamia stuff without, but the waist/tail connection is not consistent.</p><p></p><p>TODO for v1.0:</p><p>Try to also accurately reproduce many of her various monstergirl type feature. Not sure how likely it is to do all in a single LORA or if a more specific inpaint one is warranted.</p>