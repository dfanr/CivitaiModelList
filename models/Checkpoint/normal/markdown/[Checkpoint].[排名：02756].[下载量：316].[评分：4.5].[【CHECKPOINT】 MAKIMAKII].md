## 【CHECKPOINT】 MAKIMAKII
### 一、模型概述

- 标签：`anime`, `female`, `woman`, `checkpoint`, `basemodel`
- 下载数：316
- 收藏人数：85
- 评论人数：1
- 评分人数：2
- 评分：4.5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-21T12:03:56.226Z
  - 原始模型：SD 1.5
  - 下载数：316
  - 评分人数：2
  - 评分：4.5
- 下载地址
  - [CHECKPOINTMAKIMAKII_v10.safetensors](https://civitai.com/api/download/models/76710)
  - [CHECKPOINTMAKIMAKII_v10.safetensors](https://civitai.com/api/download/models/76710?type=Model&format=SafeTensor&size=full&fp=fp16)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2bbda001-07d4-47aa-9357-5bbf35610b54/width=450/871150.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/93250729-0e3d-4acf-aa81-6b896b664ba7/width=450/871153.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/70db84ee-7da5-439c-96cf-5707c6b69bb6/width=450/871147.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/31b96f49-5cf4-4e61-ade3-6282798137b1/width=450/869393.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="2023524-update">2023/5/28 update</h1><p>・このモデルは作者の意向で量産型にしたくありません。</p><p>　500DLを上限として、以降はこのページのチェックポイントファイルが削除されます。</p><p></p><h1 id="2023524-update">2023/5/24 update</h1><p>・シャープなイラストのニーズに対応するため既存LoRaのテストを行いました。</p><p>　Sharpness Tweaker LoRA　でシャープになる事を確認しています。</p><p>　他の対応策もHPで検証結果を含めて記載しています。</p><p></p><h1 id="2023523-update">2023/5/23 update</h1><p>・私のHPで概要を記載しました。Civitaiよりも少し詳しく記載しています。。</p><p>　また、今後サポートは私のHPで実施いたします。（将来に渡って無料です。）</p><p><a target="_blank" rel="ugc" href="https://www.makima.site/stable-diffusion/makimakii/">https://www.makima.site/stable-diffusion/makimakii/</a></p><p></p><h1 id="2023522-update">2023/5/22 update</h1><h3 id="heading-1558"><strong>・モデル変更はありませんが重要な事が判明したので記載</strong></h3><p>①BREAK構文で区切る事でシャープになり発色が良くなることが分かりました。</p><p>　[品質],BREAK,[背景],BREAK,[女の子]　など</p><p>　モデル自体の不具合ではなく、Counterfeltのように少し癖のある呪文が必要です。</p><p></p><p>②裏を返せば、BREAK構文を使わない場合はソフトに描き、BREAK構文を使えばくっきりシャープなイラストを描けます。</p><p>この点が分かったので、下記に記載している問題点は解消とさせていただきます。</p><p></p><p>③サンプリング回数は23回以上を推奨とさせて頂きます。かなり少ない方なので効率的に作画ができると思います。</p><p></p><p>④こちらは元々記載していた内容ですが、単語の羅列でも描画はしますが推奨はセンテンスを記載する事です。具体的に記載するほど描画精度はあがります。</p><p></p><p>⑤品質呪文を調整する事で少し崩れた綺麗なアニメ風イラストも描けます。</p><p></p><p>BREAK構文が入っているサンプルを保存したので記載方法はサンプルの呪文をご確認ください。</p><p></p><h1 id="2023521-update">2023/5/21 update</h1><p>このモデルは女の子を線画を細く描きながら、表情を柔らかく、背景はシャープネスが残るような少しアニメに寄った感じの描画する事を目的に作成しました。</p><p>このモデルは高精細というよりは、味のあるイラストになる事を目指しています。</p><p>優しい表情の女の子が多く描画されます。背景のみでも機能します。</p><p>初心者の方が直ぐに描きやすいようにVAEは焼き込んでいます。</p><p></p><h3 id="heading-1559">特徴：</h3><p>・女の子をソフトに描きます。</p><p>・人間の肌色をなるべく再現できるように頑張っています。</p><p>（黒くなり過ぎないようにしています。）</p><p>・女の子を柔らかく描写する目的がありソフトフォーカス寄りのイラストになります。</p><p><s>　※シャープに描きたい時は、呪文でContrastやSharpnessを唱えてあげると良くなる場合があります。（強度はイラストによって異なります。当然、効かない場合もあります。）</s></p><p>BREAK構文を記載する方が確実なので訂正します。</p><p>・背景は基本的にしっかりと描きます。</p><p>・エフェクトや洋服は種類多く、背景なども種類が多いと思います。</p><p>・VAEについてはチェックポイントに焼き込んであります。</p><p>（vae-ft-mse-840000-ema-pruned.safetensors）</p><p>　色が濃くなりすぎる時はVAEを自動設定にしてください。薄いと感じる場合はお好みのVAEを設定ください。</p><p></p><h3 id="heading-1560">呪文の記載方法：</h3><p>基本的に単語でも描画しますが、うまくいかない時はセンテンスで記載する事を推奨しています。</p><p></p><h3 id="heading-1561">補足：</h3><p>今後も適時バージョンアップを行う予定です。</p><p>ディテールがパキって出る素晴らしいモデルは既に多数存在しているので、私は女の子をソフトに描くモデルを作り続けるでしょう。</p><p></p><h3 id="heading-1562">ファイルの種類：</h3><p>MAKIMAKI_V1.safetensors：フルバージョンです</p><p>MAKIMAKI_light_V1.safetensors：軽量化版です</p><p></p><h3 id="heading-1563">サンプル画像：</h3><p>・アップスケーラを通すと高精細なのが描けます。</p><p>・個人的にお勧めはControlnetのShuffulとSoftedge_hedです。</p><p></p><h3 id="heading-1564">問題点：</h3><p>・ファイルが重いです。ごめんなさいデータ詰め込んだらこうなりました。</p><p>　→　ファイルは重いですが、多くのファイルがあるため多種多様な描写ができます。</p><p>　　　ここは今後も修正予定はありません。</p><p>　　　１０GBを超えないようにコントロールはしたいと考えています。</p><p><s>・ワイドビューの時に女の子の顔が崩れやすいですが、絵柄としてはアーティスティックな作品になる事が多いです。</s></p><p>　→　解消済（5/22Update内容をご参照ください）</p>