## Toudou Yurika (Aikatsu) LoRA (9.1MB update)
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `female`, `idol`, `2d`, `game character`, `girls`, `video game`
- 下载数：818
- 收藏人数：158
- 评论人数：0
- 评分人数：1
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v5.0

- 统计数据
  - 发布时间：2023-05-02T15:38:16.191Z
  - 原始模型：SD 1.5
  - 下载数：466
  - 评分人数：0
  - 评分：0
- 下载地址
  - [YurikaV5D8_e5.safetensors](https://civitai.com/api/download/models/60674)
  - [ToudouYurika.zip](https://civitai.com/api/download/models/60674?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e2ee143d-b631-4a2f-983e-ab49e464bc00/width=450/663856.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e75140b1-9ec9-4574-3ba2-2d832338f600/width=450/663901.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/451a62ad-618e-47d3-0d18-5272daecd400/width=450/663860.jpeg" /> |
| ---- | ---- | ---- |

#### [版本1/共2个版本] V3

- 统计数据
  - 发布时间：2023-05-02T15:31:53.036Z
  - 原始模型：SD 1.5
  - 下载数：352
  - 评分人数：1
  - 评分：5
- 下载地址
  - [ToudouYurika.safetensors](https://civitai.com/api/download/models/7873)
  - [ToudouYurika.zip](https://civitai.com/api/download/models/7873?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/efbe2032-526b-4cfa-73d9-ad13397b8900/width=450/74101.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e3ea47c4-ac47-47ed-d335-65f3db0e6100/width=450/74100.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bfec8b29-6e43-43f6-fdf8-48cc7b2ddf00/width=450/74099.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/53088184-5217-4c8a-051e-1c7fcf07d700/width=450/74098.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>Toudou Yurika (Aikatsu) LoRA</h1><p></p><h2>02-05-2023/V5 Update:</h2><ul><li><p>Reduce the model file size to 9MB.</p></li></ul><ul><li><p>Use a way lower network dim (8 instead of 160) and Alpha (1 instead of 160) to prevent overfitting</p></li><li><p>Add a new token for each canon outfit (using booru token was a bad idea):<br /><code>GothMagicCoord</code></p><p><code>StarlightAcademyWinter</code></p><p><code>CasualDress</code></p><p></p></li></ul><p></p><p></p><p></p><p>This is a LoRA, this mean that you need to update Voldy/AUTOMATIC1111's webui to use it (use <code>git pull</code>) .</p><p></p><p>That LoRA does not have a particular trigger (except the default <code>&lt;lora:LoRaName:1&gt;</code>).</p><p></p><p></p><p></p><h3>Weight:</h3><p></p><p><strong>V3 : </strong></p><p>I mostly tested it at weight <code>1.0</code> and it work well between weight <code>0.7</code> and <code>1.0</code>. But the more you reduce the weight the less her canon outfit are accurate.</p><p></p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/17460efc-b78a-4bbe-32a1-765734b2b300/width=525" /><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a4177073-4dd5-4e12-8f39-0d2eaf1adf00/width=525" /><p></p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cb93f34d-4f14-4865-13ff-cab2ec0b6500/width=525" /><p></p><p></p><h3>Recommended prompt:</h3><p>That LoRA can reproduice some of her canon outfit.</p><p></p><p>Goth Magic Coord (purple/blue gothic dress dress):</p><pre><code>purple_dress,drill hair,mini top hat,gothic lolita,  idol,bat wings, white ascot,frilled dress,purple headwear, striped pantyhose,  vertical-striped legwear, uneven legwear,   black wings, wings</code></pre><p><strong>V5: </strong></p><p>Add : <code>GothMagicCoord</code></p><p></p><p></p><p>Starlight Academy uniform:</p><pre><code>starlight academy uniform,white skirt,miniskirt</code></pre><p><strong>V5:  </strong>Add : <code>StarlightAcademyWinter</code></p><p></p><p>Casual dress:</p><pre><code>pinafore dress, green dress, white shirt,frilled sleeves, red ribbon, neck ribbon, glasses, black-framed eyewear</code></pre><p></p><p><strong>V5:  </strong>Add : <code>CasualDress</code></p><p></p><h3>Training settings:</h3><pre><code>101 images, 10 repeats,7 epoch,7070 steps
Learning rate: 1e-4
Text encoder learning rate: 5e-5 
Unet learning rate: 1e-4 
max bucket resolution: 512 
clip skip: 2 
dim/alpha: 160 
batch size=1 
Base model: AnythingV3, this mean that this LoRA work on any model derived from that particular model like AnythingV4/4.5, Pastel Mix, AOM 1/2,etc...</code></pre><p></p><p></p><h3>Model used for the example:</h3><p>V3:Pastel Mix, AnythingV4.5 and AbyssOrangeMix2 nsfw .<br />V5:AnythingV4.5</p><p>That character owned by Bandai Namco and Sunrise.</p>