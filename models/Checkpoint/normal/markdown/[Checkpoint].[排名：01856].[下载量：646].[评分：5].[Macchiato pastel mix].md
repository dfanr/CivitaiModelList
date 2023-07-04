## Macchiato pastel mix
### 一、模型概述

- 标签：`anime`, `base model`, `skinny`, `pastel`
- 下载数：646
- 收藏人数：187
- 评论人数：1
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-15T19:06:47.769Z
  - 原始模型：SD 1.5
  - 下载数：646
  - 评分人数：2
  - 评分：5
- 下载地址
  - [macchiatoPastelMix_v10.safetensors](https://civitai.com/api/download/models/96706)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c32326e3-7b32-4265-a09e-24163223becd/width=450/1157946.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/828b90eb-d516-43c8-b8ac-4a6d9878bbd5/width=450/1157931.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dbab469e-d4c3-4cec-8950-d106ac72ae6d/width=450/1157945.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/899369d4-e036-4bbb-aa8f-b7e7f2ef774d/width=450/1157948.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>来源：此模型由很久之前的旧模型合并改进而来，具体来源我也不是很清楚。</p><p>特点：此模型的风格有点像kaoming风格。经过测试，和许多lora有很好的兼容性。画女性身体的能力很不错，男性身体的话就稍微差点。（或许你需要调整权重）</p><p>支持nsfw，裸体身材偏骨感。（kaoming的风格就是如此）</p><p>vae：推荐pastel-waifu-diffusion.vae</p><p>negative embeddings:推荐使用easynegative, deepnegative, badv5,bad-hands-5,negative_hand-neg,verybadimagenegative_v1.3</p><p>如果你想接近预览图效果，以下是我采用的步骤，仅供借鉴。你可以根据配置和设备性能调整参数。</p><p>第一步，text2img生成初始图片。我一般不开高清修复，因为高清修复曾破坏过角色型lora的效果。DPM++ 2M Karras, CFG scale: 12。此步骤你可以使用controlnet和adetailer。</p><p>第二步，使用img2img改进初始图，放大倍数根据设备性能自行决定（1.25-？），Denoising strength: 0.3。然后controlnet使用tile_resample，并再次使用adtailer。</p><p>此时你就可以花比较短的时间得到相对清晰且细节没有被破坏的图片。</p><p>English Translation :</p><p>Source: This model is an improved version that was merged from older models a long time ago. I'm not exactly sure about the specific origin.</p><p>Features: The style of this model is somewhat similar to the Kaoming style. Through testing, it has shown good compatibility with many Lora. It has a great ability to draw female bodies, while male bodies are slightly less impressive (you might need to adjust the weights). It supports NSFW content, with nude body shapes leaning towards a skinny appearance (which is typical of the Kaoming style).</p><p>VAE: I recommend using pastel-waifu-diffusion.vae.</p><p>Negative embeddings: I recommend using easynegative, deepnegative, badv5, bad-hands-5, negative_hand-neg, and verybadimagenegative_v1.3.</p><p>If you want to achieve results similar to the preview image, here are the steps I used as a reference. You may adjust the parameters according to your configuration and device performance.</p><p>Step 1: Use text2img to generate the initial image. I usually don't use highres fix, as it has previously ruined the effects of character-type Lora. Use DPM++ 2M Karras with a CFG scale of 12. In this step, you can use controlnet and adetailer.</p><p>Step 2: Use img2img to improve the initial image. Choose the magnification factor based on your device's performance (from 1.25 to ?) and set the denoising strength to 0.3. Then use controlnet with tile_resample, and apply adtailer once more.</p><p>At this point, you should be able to obtain a relatively clear and detailed image in a faster speed without damaging the original details.</p><p>日本語翻訳：</p><p>ソース：このモデルは、かなり古い古いモデルを統合して改良されたものであり、具体的なソースはよくわかりません。</p><p>特徴：このモデルのスタイルは、kaomingスタイルに少し似ています。テストの結果、多くのloraと非常に互換性があります。女性の体を描く能力は非常に優れており、男性の体の場合はやや劣っています。（おそらく重みを調整する必要があります）</p><p>nsfwをサポートし、裸体の体型は骨格的な傾向があります。（kaomingスタイルの特徴です）</p><p>vae：pastel-waifu-diffusion.vaeをお勧めします。</p><p>ネガティブな埋め込み：easynegative、deepnegative、badv5、bad-hands-5、negative_hand-neg、verybadimagenegative_v1.3の使用をお勧めします。</p><p>プレビュー画像の効果に近づきたい場合は、以下の手順を使用しました。設定とデバイスの性能に合わせて、パラメータを調整できます。</p><p>ステップ1：text2imgを使用して初期画像を生成します。通常、高解像度の修復を開始しないようにします。これは、高解像度の修復がキャラクター型loraの効果を破壊したことがあるためです。DPM++ 2M Karras、CFGスケール：12。このステップでは、controlnetとadetailerを使用できます。</p><p>ステップ2：img2imgを使用して初期画像を改善し、拡大倍率はデバイスの性能に応じて決定します（1.25-？）、デノイジング強度：0.3。次に、controlnetをtile_resampleで使用し、再びadtailerを使用します。</p><p>これで、比較的短時間で、比較的クリアで、詳細が破壊されていない画像を得ることができます。</p>