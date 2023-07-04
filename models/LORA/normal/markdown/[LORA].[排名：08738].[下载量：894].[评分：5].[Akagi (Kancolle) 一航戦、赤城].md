## Akagi (Kancolle) 一航戦、赤城
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `cosplay`, `kancolle`, `realistic`, `akagi`
- 下载数：894
- 收藏人数：176
- 评论人数：0
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] AkagiKancolle_v1.0

- 统计数据
  - 发布时间：2023-05-02T10:21:10.973Z
  - 原始模型：SD 1.5
  - 下载数：894
  - 评分人数：2
  - 评分：5
- 下载地址
  - [AkagiKancolle_V10.safetensors](https://civitai.com/api/download/models/60462)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2fc78318-56a4-4465-705c-e6b814b02f00/width=450/660850.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f244f176-bcdf-458b-f9f6-42ed0ad18700/width=450/660858.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1ad15e23-4976-44f4-008a-3479af519400/width=450/660863.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e1015ca2-bf17-4da9-feb8-a668d5cf5c00/width=450/660864.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>『一航戦赤城、第一次攻撃隊、発艦してください！』</h1><p></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/hanafuusen2001/AkagiKancolle">Akagi (Kancolle) HuggingFace Model Card</a></p><p></p><p>⬇️ Instructions in English are below. ⬇️</p><p></p><h2><strong>關於</strong></h2><p>AkagiKancolle 是『艦隊これくしょん -艦これ-』中『赤城』角色的 LoRA 模型。</p><p>本 LoRA 的泛化性不錯，可以用在寫實類模型和動漫類模型中，諸如：ChilloutMix、BeautyProMix、ChikMix、AOM2、ReVAnimated 等。</p><p></p><h2><strong>使用説明</strong></h2><h3>觸發詞</h3><p>本 LoRA 的觸發詞是 iks_akagi, 1girl。IKS 來自『第一航空戰隊（Dai Ichi Kōkū sentai, Ichikō-sen）』的首字母。</p><p></p><h3>提示詞</h3><p>必要時，可加入以下提示詞，以便强化赤城的官方服裝（袴、襷、弓掛、胸当て、弓道、着物）：</p><ul><li><p>hakama, hakama_short_skirt, hakama_skirt, red_hakama</p></li><li><p>japanese_clothes, kimono, tasuki, yugake, muneate, kyuudou</p></li><li><p>thighhighs, white_legwear</p></li></ul><p></p><ol><li><p>在一些模型中，加入提示詞 <strong>akagi_\(kancolle\)</strong> 能加强角色效果。</p></li><li><p>使用不同大模型時，需要額外增加的提示詞以達到理想效果，要多嘗試。</p></li><li><p>只在正面提示詞中加入 <strong>iks_akagi, 1girl</strong> 也能產生赤城角色效果，但通常在動漫類模型更容易出現。</p></li></ol><p></p><h3><strong>存在的問題</strong></h3><ol><li><p>在這個版本的模型中，赤城服裝中的 muneate（胸当て）和 tasuki（襷）有時較難呈現出來，計劃在下個版本中解決。</p></li><li><p>赤城袴裙前面的飛行甲板挂飾無法穩定顯示，而且飛行甲板上的『ア』字往往無法正確出現。</p></li><li><p>角色人物可能會手持一些奇怪的物件，例如棍子、竹筒，可能是由於訓練圖集中包含了赤城手持弓的原因。</p></li></ol><p></p><h3><strong>參數</strong></h3><ul><li><p>LoRA Weight：建議在 0.5 ~ 1.0，其中 0.8 是較好的選擇，使用 BeautyProMix 模型時 LoRA 權重要適當降低。</p></li><li><p>Sampling method：DPM++ SDE Karras （選其他都可能導致畫面出現奇怪的紋理）</p></li><li><p>Sampling steps：20 ~ 30</p></li><li><p>CFG Scale：7 ~ 10</p></li><li><p>Restore faces：建議選擇</p></li><li><p>Clip skip：2 比 1 更好</p></li></ul><p></p><p></p><h2><strong>About</strong></h2><p>AkagiKancolle is the LoRA model of the character "Akagi" from "Kantai Collection -KanColle-".</p><p>The generalization of this LoRA is good. It can be used in realistic models and animation models, such as: ChilloutMix, BeautyProMix, ChikMix, AOM2, ReVAnimated, etc.</p><p></p><h2>Instructions</h2><h3>Activation Word</h3><p>The activation word for this LoRA is <strong>"iks_akagi, 1girl"</strong>. IKS comes from the initials of "First Carrier Division (Dai Ichi Kōkū sentai, Ichikō-sen)".</p><p></p><h3>Prompt</h3><p>If necessary, the following prompts can be added to enhance Akagi's official costumes (袴, 襷, 弓掛, 胸当て, 弓道, 着物):</p><ul><li><p>hakama, hakama_short_skirt, hakama_skirt, red_hakama</p></li><li><p>japanese_clothes, kimono, tasuki, yugake, muneate, kyuudou</p></li><li><p>thighhighs, white_legwear</p></li></ul><p></p><ol><li><p>In some models, adding the prompt <strong>"akagi_\(kancolle\)"</strong> can strengthen the role effect.</p></li><li><p>When using different models, additional prompts are needed to achieve the desired effect, so try more.</p></li><li><p>Only adding <strong>iks_akagi, 1girl</strong> to the prompt can also appear Akagi character effect, but usually it is more likely to appear on anime models.</p></li></ol><p></p><h3>Existing Problems</h3><ol><li><p>In this version of the LoRA, the muneate (胸当て) and tasuki (襷) in the Akagi costume are sometimes difficult to render, and it is planned to be resolved in the next version.</p></li><li><p>The flight deck ornaments on the front of the Akagi hakama skirt cannot be displayed stably, and the word "ア" on the flight deck often does not appear correctly.</p></li><li><p>The character may hold some strange objects, such as sticks and bamboo tubes, which may be due to the fact that Akagi is holding a bow in the training images.</p></li></ol><p></p><h3>Parameters</h3><ul><li><p>LoRA Weight: It is recommended to be 0.5 ~ 1.0, among which 0.8 is a better choice, and the LoRA weight should be appropriately reduced when using the BeautyProMix model.</p></li><li><p>Sampling method: DPM++ SDE Karras (choosing others may cause strange textures in the picture)</p></li><li><p>Sampling steps: 20 ~ 30</p></li><li><p>CFG Scale: 7 ~ 10</p></li><li><p>Restore faces: recommended choice</p></li><li><p>Clip skip: 2 is better than 1</p></li></ul><p></p><h2>about me</h2><ul><li><p><a target="_blank" rel="ugc" href="https://twitter.com/HanaFuusenAI">Twitter @HanaFuusenAI</a></p></li><li><p><a target="_blank" rel="ugc" href="https://space.bilibili.com/2828614">Bilibili @はな風船HanaFuusen</a></p></li></ul>