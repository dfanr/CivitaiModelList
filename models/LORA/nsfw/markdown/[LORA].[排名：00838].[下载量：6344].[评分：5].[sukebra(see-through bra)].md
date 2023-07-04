## sukebra(see-through bra)
### 一、模型概述

- 标签：`see-through`, `bra`
- 下载数：6344
- 收藏人数：1254
- 评论人数：4
- 评分人数：6
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] sukebra(bsb&fsb)

- 统计数据
  - 发布时间：2023-03-31T05:51:31.997Z
  - 原始模型：Other
  - 下载数：6344
  - 评分人数：6
  - 评分：5
- 下载地址
  - [sukebra(bsb&fsb)-000003.safetensors](https://civitai.com/api/download/models/31852)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a966118e-8a10-40ce-27f8-0cc94bf03f00/width=450/362406.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/71d6bbcd-880b-49e1-c906-b6d882a5b600/width=450/362412.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/17742044-dfe0-4d20-bfdd-989dff547200/width=450/362413.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/01434099-069e-4a4d-2dce-28d0b3c5fc00/width=450/362411.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>服の上からブラが透けるLoRAです。</p><p>Stable Diffusionのおかげで私たちは簡単に下着や裸を見る機会が増えましたが、服の上から見たいときもありますよね？</p><p>This is a LoRA that allows you to see through your bra over your clothes.</p><p>Thanks to Stable Diffusion we have more opportunities to see underwear and nudity directly, but sometimes we want to see it over our clothes, don't we?</p><p>このLoRAはフロント透けブラとバック透けブラのどちらも描写できます。</p><p>This LoRA can describe both front-see-through and back-see-through bras.</p><p>トリガーワードなどサンプルの情報を写すのが一番早いですが、以下解説です。</p><p>It is quickest to look at sample information such as trigger words, but here is an explanation</p><p>バック透けブラのトリガーワードは「bsb」（behind透けブラ）&amp;「behsuke」（behind透け）です。「from behind」も必要。</p><p>フロント透けブラのトリガーワードは「fsb」（front透けブラ）&amp;「frosuke」(front透け）です。</p><p>The trigger words for back see-through bra are "bsb" (behind see-through bra) &amp; "behsuke" (behind see-through ). From behind" is also required.</p><p>The trigger words for front see-through bra are "fsb" (front see-through bra) &amp; frosuke (front see-through).</p><p>weightは1で大丈夫だと思いますが、フロントとバックそれぞれ得意なモデルが違います。</p><p>なので影響を少なくするLoRA階層&lt;NP:1,1,1,1,1,0,0,0,1,1,1,1,1,1,1,0,0&gt;を使ってもいいと思います。</p><p>I think weight 1 is fine, but there are different models that are good at front and back.</p><p>So you can use LoRA hierarchy &lt;NP:1,1,1,1,1,0,0,0,0,1,1,1,1,1,1,1,1,0,0,0&gt; to reduce the influence.</p><p>バック透けブラは実写系モデルが得意です。イラスト系ではリアルに出すぎてしまうため、気になるなら階層適用をおすすめします。</p><p>フロント透けブラはイラスト系モデルが得意です。実写系でも比較的まともですが気になる場合階層適用をおすすめします。</p><p>Live-action models excel at see-through back bras. If you are concerned about it, we recommend applying hierarchy because it comes out too realistic in illustration-type models.</p><p>Illustration-type models are good at see-through bras. Live-action models are also relatively decent, but if you are concerned about it, we recommend applying the hierarchy.</p><p>服が透けすぎたり破れる場合はpromptからsee-throughを外すのが一番効果的です。weightを下げるのもOK。</p><p>If the clothes are too see-through or torn, it is most effective to remove SEE-THROUGH from the PROMPT. lowering the weight is also OK.</p><p>逆に下着が透けないならトリガーワードを強調したりweightを上げてみてください。</p><p>On the other hand, if your underwear is not transparent, try emphasizing the trigger word or increasing the weight.</p>