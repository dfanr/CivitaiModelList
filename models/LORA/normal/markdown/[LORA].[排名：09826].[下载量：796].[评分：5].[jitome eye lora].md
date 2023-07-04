## jitome eye lora
### 一、模型概述

- 标签：`anime`, `jitome`
- 下载数：796
- 收藏人数：128
- 评论人数：0
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] jitome v1.0

- 统计数据
  - 发布时间：2023-02-08T15:55:27.283Z
  - 原始模型：Other
  - 下载数：796
  - 评分人数：1
  - 评分：5
- 下载地址
  - [jitome v1.0.safetensors](https://civitai.com/api/download/models/8736)
  - [vroid jitome.zip](https://civitai.com/api/download/models/8736?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6b096741-1624-4913-79a4-dbc76b013f00/width=450/83192.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8f5f676a-966d-4331-6b9e-f09ac6303e00/width=450/83189.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/97ebeb83-e905-47e0-b6b7-81a084656c00/width=450/83191.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/94ac0aad-f5da-496e-7304-cf8d7c5da900/width=450/83190.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>使い方</p><p>ぐるぐる目loraと同じようにinpaintで使います。</p><p></p><p>①普通にイラストを生成します。</p><p></p><p>②そのままimg2imgに持っていきます。</p><p></p><p>③プロンプトに</p><p>loraの呼び出しタグ&lt;jitomeEyeLora_jitomeV10:1&gt;,jitome,目の色</p><p>を追加します。</p><p>例</p><p>&lt;jitomeEyeLora_jitomeV10:1&gt;,jitome,gray eyes</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ef041dc-0127-451e-c2bf-003c70e6a100/width=525" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7c15aaf2-f7f7-4545-2761-a0123f3eca00/width=525" /><p></p><p>④inpaintで雑に目を塗りつぶします。</p><p></p><p>⑤元の画像の比率を保ったままで自分のGPUで出力できる最大の解像度に設定します。</p><p>Only masked padding, pixelsも最大にしたほうがいいです。</p><p></p><p>Denoising strengthを調整しながらいい感じになるまで生成します。</p><p>お好みでlooking away,looking at viewerなどを足してください。</p><p></p><p>Denoising strengthは0.6くらいが良さげです。</p><p></p><p>⑥完成です。</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ea734d3b-0177-473d-9e23-c475ea21b400/width=525" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f0993978-83fb-4309-102a-a543d56ea000/width=525" /><p></p><h3>How to use</h3><p>Use inpaint in the same way as Gurume lora.</p><p>(1) Generate an illustration as usual.</p><p>(2)Take it to img2img as it is.</p><p>(3) At the prompt, enter the following</p><p>Add the lora call tag &lt;jitomeEyeLora_jitomeV10:1&gt;,jitome,eye color</p><p>to the prompt.</p><p>Example</p><p>&lt;jitomeEyeLora_jitomeV10:1&gt;,jitome,gray eyes</p><p>(4) Fill the eyes roughly by inpaint.</p><p>(5) Set the resolution to the maximum that can be output by your GPU while keeping the ratio of the original image.</p><p>Only masked padding, pixels should also be set to maximum.</p><p>Adjust the Denoising strength until you get a good result.</p><p>Add looking away, looking at viewer, etc. to your liking.</p><p>Denoising strength should be about 0.6.</p><p>(6) Completed.</p><p>Translated with <a target="_blank" rel="ugc" href="http://www.DeepL.com/Translator">www.DeepL.com/Translator</a> (free version)</p>