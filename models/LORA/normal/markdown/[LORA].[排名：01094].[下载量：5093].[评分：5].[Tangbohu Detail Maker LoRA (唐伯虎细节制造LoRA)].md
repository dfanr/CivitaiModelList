## Tangbohu Detail Maker LoRA (唐伯虎细节制造LoRA)
### 一、模型概述

- 标签：`anime`, `photorealistic`, `style`, `detail`, `style lora`, `tweaker`
- 下载数：5093
- 收藏人数：743
- 评论人数：5
- 评分人数：10
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v2.5

- 统计数据
  - 发布时间：2023-05-28T14:22:35.974Z
  - 原始模型：SD 1.5
  - 下载数：2518
  - 评分人数：4
  - 评分：5
- 下载地址
  - [tangbohu-detailmaker_v2.5.safetensors](https://civitai.com/api/download/models/83755)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d28d6142-d651-4ce2-818d-da7050514ab9/width=450/945033.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7b407054-0800-4281-adb0-fabe9a263690/width=450/945058.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2f04ad97-1b0e-4b16-8aec-87a7c20f3a00/width=450/945034.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f91aaff0-78d6-4195-aa0a-0cc028138373/width=450/945035.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v1.0 lite

- 统计数据
  - 发布时间：2023-05-28T14:11:04.449Z
  - 原始模型：SD 1.5
  - 下载数：327
  - 评分人数：1
  - 评分：5
- 下载地址
  - [detailmaker-lite.safetensors](https://civitai.com/api/download/models/67263)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5dbeb3a6-365e-45e5-8f21-97ac93615bd7/width=450/746992.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/916ed3ba-1cea-43cf-b2a3-d7e1239b4fc4/width=450/746960.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/39cce3bd-812e-43f8-ab3b-e50751ed1e14/width=450/746950.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/20ab4432-194c-42f1-88ca-b5c4fcd70b75/width=450/746994.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v1.0

- 统计数据
  - 发布时间：2023-05-28T14:11:04.449Z
  - 原始模型：SD 1.5
  - 下载数：2248
  - 评分人数：5
  - 评分：5
- 下载地址
  - [detailmaker.safetensors](https://civitai.com/api/download/models/67253)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0939a36b-48c3-4368-9b36-11a133df1799/width=450/747154.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4c3e31a1-e573-4af9-8941-cc8bc3978928/width=450/747246.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/91245131-97f6-4148-9888-5b66b7c8c5b8/width=450/747224.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/11292087-9057-4bf4-a35c-349e9791e594/width=450/746823.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>A Lora mainly used for adding details.</p><p>New version 2.5 description</p><p>Positive weights can still increase the details of the image, making it particularly suitable for creating things out of thin air. Negative weights can reduce details. Currently, an interesting phenomenon has emerged that some models with 2D or 2.5d effects are gradually restored to 3D realistic effects after using negative weights. Perhaps this interesting effect can be applied to certain projects with special needs, so this version has been uploaded.</p><p>Old version description:</p><p>The weight range is from - 6 to 3, and both the real style model and the anime animation style model are competent.</p><p>Specifically controlled through Lora's weight.</p><p>There are two versions, the standard version has a strong emphasis on detail reduction, which leads to the development of the screen towards a different style. Because the content in the prompt has been reduced, the screen has changed. Therefore, -6 does not mean that the quality of the screen has decreased, but may have obtained a relatively pure screen style.</p><p>In addition, there is also a Lite version available, which has a relatively small impact and overall controllable changes, making it convenient for fine-tuning numerical values.</p><p>Additionally, different screen contents and models have varying levels of support for Lora. A small amount of themes and content will explode after a weight greater than 3.</p><p>This Lora model is experimental in nature, and testing support is welcome. Thank you all!</p><p></p><p>一款主要用于增加细节的lora。</p><p>新版2.5说明</p><p>正数的权重依然能增加画面细节，特别适合无中生有，负数的权重会减少细节，目前出现了一种有趣的现象，一些2d或者2.5d效果的模型在使用负数权重后模型被逐渐还原成3d真实效果。也许这种有趣的效果能够使用在某些特殊需求的项目上，故此上传了该版本。</p><p>旧版说明：</p><p>权重范围从-6到3都能起效，不管是真实风格模型还是二次元动漫风格模型都能胜任。</p><p>具体通过lora的权重来控制。</p><p>有两个版本，标准版力度较强，削减细节方面使得画面朝另外一个画面风格发展，因为将prompt中的内容削减后使得画面产生了变化，所以-6并不意味着画面质量下降，而是可能获得了比较纯粹的画面风格。</p><p>另外还准备有lite版本，lite版本的影响较小，整体变化可控，方便数值上进行微调。</p><p>另外不同的画面内容和模型对lora的支持程度不同。少量题材和内容将会在大于3的权重后爆炸。</p><p>此lora模型为实验性质，欢迎进行测试支持。谢谢大家！</p><p></p><p></p><p>主にディテールを増やすためのlora。</p><p>新版2.5の説明</p><p>正数の重みは依然として画面の詳細を増やすことができ、特に無中生有に適しており、負の重みは詳細を減らすことができ、現在は興味深い現象が現れており、2 dまたは2.5 d効果のモデルの中には負の重みを使用した後、モデルは徐々に3 d真実効果に還元されている。この興味深い効果は、特定のニーズに特化したアイテムに使用できる可能性があるので、このバージョンをアップロードしました。</p><p>旧バージョンの説明：</p><p>重みの範囲は-6から3まで有効で、リアルスタイルモデルでも二次元アニメスタイルモデルでも適任です。</p><p>具体的にはloraの重みによって制御される。</p><p>2つのバージョンがあり、標準版は力が強く、細部を削減することで画面が別の画面スタイルに発展し、proptの内容を削減して画面が変化したため、-6は画面の品質が低下したことを意味するのではなく、比較的純粋な画面スタイルを獲得した可能性がある。</p><p>また、liteバージョンも用意されており、liteバージョンの影響は小さく、全体の変化は制御可能で、数値的な微調整が容易である。</p><p>また、画面内容やモデルによってloraへのサポート度合いが異なります。少量の題材と内容は3より大きい重みで爆発する。</p><p>このloraモデルは実験的な性質であり、テストサポートを歓迎します。ありがとうございました！</p><p></p><p></p><p>디테일을 더하는 데 주로 사용되는 로라.</p><p>새 버전 2.5 설명</p><p>양수의 가중치는 여전히 화면의 디테일을 증가시킬수 있다. 특히 터무니없이 적합하다. 음수의 가중치는 디테일을 감소시킨다. 현재 재미있는 현상이 나타났다. 일부 2d 또는 2.5d 효과의 모델은 음수의 가중치를 사용한후 모델은 점차 3d의 진실한 효과로 환원되였다.아마도 이런 재미있는 효과는 일부 특수한 수요의 항목에 사용될수 있기에 이 버전을 업로드하였다.</p><p>이전 릴리즈 노트:</p><p>가중치 범위는 -6에서 3까지 모두 효과가 있으며, 실제 스타일 모델이든 2차 애니메이션 스타일 모델이든 모두 감당할 수 있다.</p><p>구체적으로 로라의 권중을 통해 통제한다.</p><p>두 가지 버전이 있는데 표준판의 강도가 비교적 강하고 디테일을 줄이는 데 있어 화면이 다른 화면 스타일로 발전했다. 왜냐하면 prompt의 내용을 줄인 후에 화면에 변화가 생겼기 때문에 -6은 화면의 질이 떨어지는 것을 의미하는 것이 아니라 비교적 순수한 화면 스타일을 얻을 수 있다.</p><p>또한 lite 버전이 준비되어 있으며 lite 버전의 영향이 적고 전체적인 변화를 제어할 수 있어 수치상 미세조정이 용이하다.</p><p>또 화면 내용과 모델에 따라 로라에 대한 지원 정도가 다르다.소량의 소재와 내용은 3보다 큰 가중치 후에 폭발할 것이다.</p><p>이 로라 모델은 실험적인 성질이므로 테스트 지원을 환영합니다.감사합니다!</p><p></p><p></p><p></p>