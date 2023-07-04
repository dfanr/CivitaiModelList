## RZ - Analog ( 1.5 & 2.1)
### 一、模型概述

- 标签：`photorealistic`, `analog`, `style`, `photography`, `cinestill800t`
- 下载数：1894
- 收藏人数：231
- 评论人数：23
- 评分人数：4
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] SD 2.1 - 1.0

- 统计数据
  - 发布时间：2023-03-23T22:13:49.152Z
  - 原始模型：SD 2.1 768
  - 下载数：1340
  - 评分人数：2
  - 评分：5
- 下载地址
  - [rz884n4l0g.safetensors](https://civitai.com/api/download/models/23265)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/75ff262b-3c4f-4854-d4b3-ae22ea9e2a00/width=450/252216.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8effad5a-5ee5-42d9-bda9-38f29ddbd800/width=450/252212.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/85175a43-d824-4dcc-5fb4-4426a5770d00/width=450/252225.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b8eb621c-9aca-4b1c-db50-250894b8a500/width=450/252224.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] SD 1.5 - 1.0 - 768

- 统计数据
  - 发布时间：2023-03-23T22:13:49.152Z
  - 原始模型：SD 1.5
  - 下载数：554
  - 评分人数：2
  - 评分：5
- 下载地址
  - [rz884n4l0g_15.safetensors](https://civitai.com/api/download/models/25637)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bcf279eb-b814-4639-7422-820722002700/width=450/281782.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/25743650-fb28-4cb6-b745-09d945035c00/width=450/281781.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7d9d7027-9199-4a93-c9c2-9d3e37be8600/width=450/281780.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8b7932bd-dfba-42ba-7748-e6e30da58300/width=450/281779.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2>2.1 Lora Model for Analog photography</h2><p>Please see in the <strong>versionning BELOW</strong> for 1.5 download link.</p><p>What about a chemical processed diffusion ?</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4e7e4970-e106-4a9c-a90b-af04e307b700/width=525/4e7e4970-e106-4a9c-a90b-af04e307b700" /><p><strong>Analog Ext</strong> is available <a target="_blank" rel="ugc" href="https://romerorz.gumroad.com/l/analog-ext"><strong>on Gumroad</strong></a> as pay what you want, featuring exclusives assets with different finetuned version and his <strong>noise offset variant</strong>, an experimental<strong> 840*840 training</strong>, and a<strong> light leak helper embedding</strong> as long a<strong> 18 nice prompts</strong> !</p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bca86b06-3e39-4497-1d21-75fdf6690c00/width=525/bca86b06-3e39-4497-1d21-75fdf6690c00" /><p></p><p>Mostly trained on shots using <strong>Cinestill 800t</strong> films, pushing your analog generations to the closest reality level.</p><p>Please use the <a target="_blank" rel="ugc" href="https://civitai.com/models/15432/forge-negatives-and-helpers-21"><u>forAnalogPortrait</u></a> negative embeddings (found in versioning below the main embedding), it will cleanse unwanted styles to try to perform only analog outputs, please note that this negative is<strong> very strict</strong>.</p><p></p><p>Note : demo pictures was generated from raw 2.1 non-ema without VAE loaded.</p><p></p><p>If you want to generate landscapes who looks very natural, be kind on negatives, analog grain / glitches can be considered as “bad” for popular negative token.</p><p></p><p>512*768 / 640*936 for portrait are safe</p><p></p><p>For achieving perfection, you can also find your base subject / scene with no negatives at all then adding some gradually.<br /></p><p>An <strong>rz884n4l0g </strong>photo of a &lt;subject&gt;</p><p>An <strong>rz884n4l0g </strong>80’s photography of …</p><p>An <strong>rz884n4l0g </strong>movie scene of</p><p></p><p>For a lighter effect, removing the trigger works fine and still keeps the major bias, increase weight if needed.</p><p></p><h2>1.5 notes</h2><p>Use under 0.6 strength if you are generating with a 512*512 resolution</p><p>Trained on a 768*768 dataset, quite hard to get some grain, authentic analog effect on comparison of 2.1.</p><p></p><h2>Troubleshooting</h2><p></p><p>If you are getting the error "failed to match keys when loading Lora" it means you are either on the native Lora integration of Automatic1111 which may not support LoCon, please install the <a target="_blank" rel="ugc" href="https://github.com/kohya-ss/sd-webui-additional-networks">https://github.com/kohya-ss/sd-webui-additional-networks</a> extension to solve the issue.</p><p></p><p>Happy tuning everyone !</p><p><a target="_blank" rel="ugc" href="http://romerorz.art">romerorz.art</a> - <a target="_blank" rel="ugc" href="https://twitter.com/romero_erzede">Twitter </a>- <a target="_blank" rel="ugc" href="https://www.deviantart.com/romerorz">DeviantArt</a> - <a target="_blank" rel="ugc" href="https://romerorz.gumroad.com/"><u>Gumroad</u></a></p><p><br /></p>