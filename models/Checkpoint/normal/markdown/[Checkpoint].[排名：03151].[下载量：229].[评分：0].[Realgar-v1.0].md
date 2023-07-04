## Realgar-v1.0
### 一、模型概述

- 标签：`anime`, `girl`, `style`
- 下载数：229
- 收藏人数：40
- 评论人数：3
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-20T05:54:47.152Z
  - 原始模型：SD 2.1 768
  - 下载数：229
  - 评分人数：0
  - 评分：0
- 下载地址
  - [kl-f8-anime2.ckpt](https://civitai.com/api/download/models/75396?type=VAE&format=Other)
  - [realgarV10_v10.safetensors](https://civitai.com/api/download/models/75396)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9fb910d2-b776-4c80-85e8-b2adb4a0e32b/width=450/843749.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f622cef6-2402-4a47-ad96-9a1ad12193b4/width=450/843534.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/02e449c6-0dc6-4792-9458-af95b4b2bbbe/width=450/843433.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4d6d23c3-12c9-4929-89bc-4d760dbaa2e0/width=450/843395.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Support me: <a target="_blank" rel="ugc" href="https://www.buymeacoffee.com/nyoplat">https://www.buymeacoffee.com/nyoplat</a></p><p></p><p>HuggingFace: <a target="_blank" rel="ugc" href="https://huggingface.co/p1atdev/Realgar-v1">https://huggingface.co/p1atdev/Realgar-v1</a></p><p></p><p>This model is a Stable Diffusion model based on WD 1.5 beta 3 base.</p><p>This model does not include the NovelAI Leak model.</p><p></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/waifu-diffusion/wd-1-5-beta3/blob/main/wd-beta3-base-fp16.safetensors">WD 1.5 beta3 base</a> をベースにしたモデルです。</p><p>NAI リークは含まれていません。</p><p></p><h2>Prompting</h2><p>This model aims for stability with short prompt. It may sometimes be difficult to generate with long prompt or special concepts. <code>masterpiece, best quality</code> is not needed.</p><p>However, as a minimum set of negative prompt, you can use <code>worst quality, low quality, bad aesthetic, oldest, bad anatomy, blurry</code>, or if you're unsure of good negative prompts, you can use the negative embedding <a target="_blank" rel="ugc" href="https://huggingface.co/p1atdev/Realgar-v1/blob/main/ParaNegative.safetensors">ParaNegative</a>.</p><p>To avoid NSFW outputs, it is recommended to include <code>nsfw, nude</code> and such in the negative prompt.</p><p><strong>If you want to avoid real life style, use </strong><code>anime</code><strong> in positive prompt.</strong></p><p>It is recommended to use highres fix if you can.</p><p></p><p>このモデルは短いプロンプトでの安定性を追求したモデルです。長いプロンプトや一部のコンセプトをただしく描けない可能性があります。 <code>masterpiece, best quality</code> は不要です。</p><p>ただし、最低限のネガティブプロンプトが必要です。すくなくとも <code>worst quality, low quality, bad aesthetic, oldest, bad anatomy, blurry</code> があるとよいですが、良いネガティブプロンプトがわからない場合は補助的にネガティブTI <a target="_blank" rel="ugc" href="https://huggingface.co/p1atdev/Realgar-v1/blob/main/ParaNegative.safetensors">ParaNegative</a> を使うことが出来ます。</p><p>NSFW な出力を避けるために、 <code>nsfw, nude</code> などをネガティブプロンプトに入れることを推奨します。</p><p><strong>写実的な画像の出力を避けたい場合は、`anime` をポジティブプロンプトにいれてください。</strong></p><p>Highres fix を使うことを推奨します。</p><p></p><h2>VAE</h2><p>It is recommended to use the same VAE as WD 1.4, which can be found here <a target="_blank" rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt">https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt</a></p><p></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt">WD 1.4 の VAE</a> が推奨です。</p><p></p><h2>License</h2><p>This model is released under the Fair AI Public License 1.0-SD (<a target="_blank" rel="ugc" href="https://freedevproject.org/faipl-1.0-sd/">https://freedevproject.org/faipl-1.0-sd/</a>). If any derivative of this model is made, please share your changes accordingly. Special thanks to ronsor/undeleted (<a target="_blank" rel="ugc" href="https://undeleted.ronsor.com/">https://undeleted.ronsor.com/</a>) for help with the license.</p><p></p><p>このモデルは WD 1.5 と同じ Fair AI Public License 1.0-SD (<a target="_blank" rel="ugc" href="https://freedevproject.org/faipl-1.0-sd/">https://freedevproject.org/faipl-1.0-sd/</a>) の下配布されます。生成サービスなどでこのモデルまたは派生モデルを使う場合は、サービスの利用者にモデルを公開する必要があります。詳しい・正確なライセンスは <a target="_blank" rel="ugc" href="https://freedevproject.org/faipl-1.0-sd/">原文</a> を参照ください。</p>