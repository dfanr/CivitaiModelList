## Girlish-Bloom
### 一、模型概述

- 标签：`anime`, `digital illustration`
- 下载数：1789
- 收藏人数：675
- 评论人数：4
- 评分人数：9
- 评分：5

### 二、下载地址（共4个版本）

#### [版本4/共4个版本] Girlish-Bloom

- 统计数据
  - 发布时间：2023-04-03T19:08:21.597Z
  - 原始模型：SD 1.5
  - 下载数：1556
  - 评分人数：9
  - 评分：5
- 下载地址
  - [girlishBloom_girlishBloom.safetensors](https://civitai.com/api/download/models/34566)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/10285347-4d43-4d87-76a6-b65847465200/width=450/419479.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8bb1e531-b028-433d-8306-59d8078fa300/width=450/419480.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/180c4266-a41d-4561-fbd2-a1a2d1a96e00/width=450/395407.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/56b1319a-eb6f-4430-2ad1-de0af730e200/width=450/395379.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本3/共4个版本] Girlish-Bloom-fp16

- 统计数据
  - 发布时间：2023-04-03T19:08:21.597Z
  - 原始模型：SD 1.5
  - 下载数：108
  - 评分人数：0
  - 评分：0
- 下载地址
  - [girlishBloom_girlishBloomFp16.safetensors](https://civitai.com/api/download/models/34592)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/94c4204c-d765-4739-5b63-767e18632800/width=450/395072.jpeg" /> |
| ---- |

#### [版本2/共4个版本] Girlish-Bloom-VAEless

- 统计数据
  - 发布时间：2023-04-03T19:08:21.597Z
  - 原始模型：SD 1.5
  - 下载数：62
  - 评分人数：0
  - 评分：0
- 下载地址
  - [girlishBloom_girlishBloomVaeless.safetensors](https://civitai.com/api/download/models/34567)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/aeac550c-57e8-43b7-3700-145bf8cbfe00/width=450/394821.jpeg" /> |
| ---- |

#### [版本1/共4个版本] Girlish-Bloom-VAEless-fp16

- 统计数据
  - 发布时间：2023-04-03T19:08:21.597Z
  - 原始模型：SD 1.5
  - 下载数：63
  - 评分人数：0
  - 评分：0
- 下载地址
  - [girlishBloom_girlishBloomVaeless.safetensors](https://civitai.com/api/download/models/34608)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5ed5e1c6-b081-494c-1177-6ea5e5d80000/width=450/395228.jpeg" /> |
| ---- |


### 三、详情
<p></p><p>(Anything_V5), (7th_Layer), (old fish v1.1)に加えて、Orange MixのVAEを追加し、合成したマージモデルです。</p><p></p><h3><strong>[[ EasyNegativeの使用を推奨します ]]</strong></h3><h3><strong>[[ Recommend using EasyNegative ]]</strong></h3><p></p><h2><strong>・特徴 features</strong></h2><p>2Dのフラットカラーイラストに特化したモデルです。</p><p>This model is suitable for creating 2D flat color illustrations.</p><p></p><p>あまり検証が出来ておらず、プロンプトが画風にどれほど影響を及ぼすかは未知数で、かなり扱いの難しいマージモデルです。</p><p></p><p>(flat illustration)や(flat color), (line drawing)などのプロンプトを用いることで、理想的なフラットイラストを生成できると思います。</p><p>You may create the ideal flat illustration by using prompts such as (flat illustration), (flat color), (line drawing), etc.</p><p></p><p>上記のプロンプトを用いるとどうしても背景が単調になりがちですが、ControlNetのmlsdなどで少し線を足すことで、ほどよく細かい描写の背景が生成されると思います。(あまりにも細かい線を指定すると、平面的な構図が失われイラストの整合性が取れなくなる傾向があります)</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3e9d6080-9535-4628-33aa-c612972f0b00/width=525/3e9d6080-9535-4628-33aa-c612972f0b00" /><p></p><p>具象的なプロンプトや品質プロンプトを多用すると、リアルな描写に近くなり、フラットイラストとは程遠くなる傾向があります。</p><p></p><p>Orange MixのVAEを標準で備えているため、追加のVAEを設定する必要ありませんが、seed値やプロンプトによっては色が薄くなってしまう事例も確認されているため、自分好みのVAEを使いたいという方はGirlish-Bloom-VAElessをお使いください。</p><p>This merge model contains Orange Mix VAE, so you don't need to set up VAE. However, illustration colors may be faded depending on the seed and prompt.</p><p>Therefore, if you want to use your own VAE, you should use "Girlish-Bloom-VAEless" or "Girlish-Bloom-VAEless-fp16".</p><h2></h2><h2><strong>・ステータス設定 status settings</strong></h2><p>SamplerはDPM++ 2M Karrasがおすすめです。</p><p>CFG Scaleは8~9が安定すると思います。</p><p>UpscalerはSwinIR_4xとの相性が良く、Hires stepsは20程度で生成するのが最適だと感じます。</p><p>個人的にはUpscalerは出来る限り使うことをおすすめします。</p><p>I personally suggest using upscaler if possible.</p><h3></h3><p>追加でDeepNegativeを使用することで全体的なクオリティの向上が期待できます。</p><p>I also recommend using of DeepNegative to improve the overall quality.</p><h2></h2><h2><strong>・注意事項 </strong>cautions</h2><p>本モデルのライセンスや商業利用の可否については、マージ元である(Anything_V5), (7th_Layer), (old fish), (Orange Mixs)の規約を確認し、準拠してください。</p><p>If you want to know imformation about the licensing and commercial use of this model, please check and comply with the terms and agreements of "Anything_V5", "7th_Layer", "old fish", "Orange Mixs" which is the source of this merge model.</p><p></p><p>Anything_V5:</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/9409">https://civitai.com/models/9409</a></p><p>7th_Layer / syaimu:</p><p><a target="_blank" rel="ugc" href="https://huggingface.co/syaimu/7th_Layer">https://huggingface.co/syaimu/7th_Layer</a></p><p>old fish:</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/14978/old-fish">https://civitai.com/models/14978/old-fish</a></p><p>Orange Mixs / WarriorMama777:</p><p><a target="_blank" rel="ugc" href="https://huggingface.co/WarriorMama777/OrangeMixs">https://huggingface.co/WarriorMama777/OrangeMixs</a></p><p></p><p></p><p>I will add the English translation later.</p>