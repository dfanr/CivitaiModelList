## Anna Kendrick Embedding
### 一、模型概述

- 标签：`photorealistic`, `woman`, `celebrity`, `embedding`, `faces`, `portraits`, `realistic`, `real person`
- 下载数：2224
- 收藏人数：151
- 评论人数：8
- 评分人数：2
- 评分：4.5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] V1

- 统计数据
  - 发布时间：2023-01-29T19:17:32.677Z
  - 原始模型：SD 1.5
  - 下载数：2059
  - 评分人数：1
  - 评分：4
- 下载地址
  - [annakendrick.pt](https://civitai.com/api/download/models/6640)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7e616014-9dcb-4ab4-44ca-476758cd0800/width=450/60395.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bf5505be-e35f-4328-1c33-f3bc2fc07600/width=450/60399.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9f6e5fdb-77d4-4e41-e839-5044c366cb00/width=450/60398.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d31189fe-a15e-4532-37af-c874da04f900/width=450/60396.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] V1 - 1000

- 统计数据
  - 发布时间：2023-01-29T19:17:32.677Z
  - 原始模型：SD 1.5
  - 下载数：75
  - 评分人数：0
  - 评分：0
- 下载地址
  - [annakendrick-1000.pt](https://civitai.com/api/download/models/6642)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7f5225bb-ce13-4a3d-1093-3b256cc52600/width=450/60423.jpeg" /> |
| ---- |

#### [版本1/共3个版本] V1 - 1500

- 统计数据
  - 发布时间：2023-01-29T19:17:32.677Z
  - 原始模型：SD 1.5
  - 下载数：90
  - 评分人数：1
  - 评分：5
- 下载地址
  - [annakendrick-1500.pt](https://civitai.com/api/download/models/6643)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5a675585-c41a-49f1-73d8-2b25e52eab00/width=450/60424.jpeg" /> |
| ---- |


### 三、详情
<p><strong>Anna Kendrick</strong> embedding created by <strong>Airathias</strong></p><p></p><p>Main V1 embedding was created in 800 steps, and a pretty high number of vectors per token. <em>Try</em> to keep your prompt short, though I've seen it work fine with longer prompts. If you find the face not defined enough, just <em>(annakendrick:1.2)</em> it.</p><p>As you'll see, it doesn't like the base model SD 1.5 much, and it leans toward better results in photorealistic renders. It <em>does</em> perform for certain fantasy semi-realistic artstyles, though. Check the X/Y grid linked below for a comparison with a few checkpoints.</p><p>This time around I decided to offer the option of more epochs, just in case. I've created a bunch of X/Y grids for you to pick and choose:</p><ul><li><p>CFG Scales (<a target="_blank" rel="ugc" href="https://airathias.com/media/public/annakendrick-cfg-scales.png">https://airathias.com/media/public/annakendrick-cfg-scales.png</a>)</p></li><li><p>Checkpoints (<a target="_blank" rel="ugc" href="https://airathias.com/media/public/annakendrick-checkpoints.png">https://airathias.com/media/public/annakendrick-checkpoints.png</a>)</p></li><li><p>Colors for checking overtraining (<a target="_blank" rel="ugc" href="https://airathias.com/media/public/annakendrick-colors-overtraincheck.png">https://airathias.com/media/public/annakendrick-colors-overtraincheck.png</a>)</p><p></p></li></ul><p>For the initial version I chose the 3 I liked best, <strong>800</strong>,<strong> 1000 </strong>and <strong>1500</strong>. If you'd like another epoch count embedding let me know.</p><p>I added prompts to the example images, should work fine. These prompts were basically blatantly copied from other examples throughout the website. If I copied yours, mea culpa. You can use this without crediting me.</p><p>The embedding was trained on stock SD 1.5, so it should work for many if not most models based off of 1.5.</p><p>Images listed are made using a handful of models to test, including:</p><ul><li><p>Stock SD 1.5</p></li><li><p>DreamShaper (<a target="_blank" rel="ugc" href="https://civitai.com/models/4384/dreamshaper">https://civitai.com/models/4384/dreamshaper</a>)</p></li><li><p>UberRealistic Dreamy PFG Porn (<a target="_blank" rel="ugc" href="https://civitai.com/models/3751/uberrealistic-dreamy-pfg-porn">https://civitai.com/models/3751/uberrealistic-dreamy-pfg-porn</a>)</p></li><li><p>Babes (<a target="_blank" rel="ugc" href="https://civitai.com/models/2220/babes">https://civitai.com/models/2220/babes</a>)</p><p></p></li></ul><p><strong>Important for the examples</strong>: In the example images I use a keyword like "<em>annakendrick-sd-v2-800</em>", this was just for testing purposes but I've elected to keep it in there so you can see what version I ended up using for that render. In your prompt you should use "<em><u>annakendrick</u></em>", "<em><u>annakendrick-1000</u></em>" or "<em><u>annakendrick-1500</u></em>".</p><p></p><p>Also, the model names in the examples are like "<em>SD_15_Photoreal_NSFW_&lt;name&gt;</em>". This is my local model name formatting templated like "<em>&lt;basemodel&gt;_&lt;artstyle&gt;_&lt;sfw/nsfw&gt;_&lt;name&gt;</em>". Hashes are shown as well, but just in case you were wondering.</p>