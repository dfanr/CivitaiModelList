## Viscuit mix
### 一、模型概述

- 标签：`concept`, `model`
- 下载数：425
- 收藏人数：98
- 评论人数：5
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] final_pruned_fp16

- 统计数据
  - 发布时间：2023-03-16T12:04:57.101Z
  - 原始模型：SD 1.4
  - 下载数：222
  - 评分人数：0
  - 评分：0
- 下载地址
  - [viscuitMix_finalPrunedFp16.safetensors](https://civitai.com/api/download/models/24089)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/551980ef-bceb-4f1c-52e6-cbd67a57e400/width=450/261796.jpeg" /> |
| ---- |

#### [版本1/共2个版本] final

- 统计数据
  - 发布时间：2023-03-16T12:04:57.101Z
  - 原始模型：SD 1.4
  - 下载数：203
  - 评分人数：0
  - 评分：0
- 下载地址
  - [viscuitMix_final.safetensors](https://civitai.com/api/download/models/21871)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/96deba6d-20e7-4485-0223-4d3743b34500/width=450/233692.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8ed0698d-7111-409e-60da-7132781f2200/width=450/233693.jpeg" /> |
| ---- | ---- |


### 三、详情
<p>英語は機械翻訳です。</p><p>pruned fp16追加。更に軽くなりました。（<strong>ritcher1</strong>に感謝）</p><p>Added pruned fp16. It is now even lighter. (Thanks to ritcher1)</p><p></p><p>Oil Painting Style LoRA 1.0のサンプルイメージに使用しているモデルのfp16 safetensors版です。元はfp32でしたがファイルサイズが重すぎるので（7.5GB）軽量化しています。</p><p>その結果Oil Painting Style LoRA 1.0のサンプルイメージと異なる画像が出力されるので納得いかない場合はマージレシピで作ってみてください。</p><p>何故かこのモデルについて何度か聞かれたので置いときます。</p><p>古いマージモデルなので直感的に使いづらく、WD1.2の時代のPromptを使用しないとまともに生成されません。</p><p></p><p>my favorite setting</p><p>Sampling method : DDIM 20 steps</p><p>vae : mse-840000-ema-pruned</p><p>clip skip:1</p><p>CFG scale: 10+</p><p></p><p>This is a machine translation.</p><p>This is the fp16 safetensors version of the model used in the Oil Painting Style LoRA 1.0 sample image. The original was fp32, but the file size was too heavy (7.5GB), so it has been lightened.</p><p>If you are not satisfied with the resulting image, which is different from the Oil Painting Style LoRA 1.0 sample image, perhaps try making it with the correct merge recipe.</p><p>It is an old merge model, so it is not intuitive to use and does not generate properly unless you use Prompt from the WD1.2 era.</p><p></p><p>merge recipe(maybe)</p><p>WS@0.3 waifu1.2+waifu1.35=temp1<br />WS@0.25 Sirayuki+basil mix=temp2<br />WS@0.3 temp1+temp2=this model</p>