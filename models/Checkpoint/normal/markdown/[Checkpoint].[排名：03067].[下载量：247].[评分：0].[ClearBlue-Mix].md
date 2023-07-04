## ClearBlue-Mix
### 一、模型概述

- 标签：`style`
- 下载数：247
- 收藏人数：76
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] ClearBlue-Mix-Anime v1.0

- 统计数据
  - 发布时间：2023-07-01T12:28:08.738Z
  - 原始模型：SD 1.5
  - 下载数：192
  - 评分人数：0
  - 评分：0
- 下载地址
  - [clearblueMix_clearblueMixAnimeV10.safetensors](https://civitai.com/api/download/models/107932)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da046d98-e57c-490a-8a65-4d55d07dc853/width=450/1359642.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/30a28e35-f2cc-4aa4-8f56-ef3b0cc8e840/width=450/1359636.jpeg" /> |
| ---- | ---- |

#### [版本1/共2个版本] ClearBlue-Mix-Real.v1.0

- 统计数据
  - 发布时间：2023-07-01T13:05:24.612Z
  - 原始模型：SD 1.5
  - 下载数：55
  - 评分人数：0
  - 评分：0
- 下载地址
  - [clearblueMix_clearblueMixRealV10.safetensors](https://civitai.com/api/download/models/107927)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d988e059-974b-4aee-8df8-2e6d3628788f/width=450/1357849.jpeg" /> |
| ---- |


### 三、详情
<p><span style="color:rgb(209, 213, 219)">ClearBlue-Mix-Animeは、流出したNovel AIモデルを組み込むことなく、審美的に優れたものにすることを目指した実験的なアニメモデルです。</span></p><p></p><h1 id="heading-19">マージ利用モデル</h1><ul><li><p>epicrealism_pureEvolutionV3</p><p>(<a target="_blank" rel="ugc" href="https://civitai.com/models/25694">https://civitai.com/models/25694</a>) by <a target="_blank" rel="ugc" href="https://civitai.com/user/epinikion">@epinikion</a></p></li><li><p>dreamshaper_631BakedVae</p><p>(<a target="_blank" rel="ugc" href="https://civitai.com/models/4384">https://civitai.com/models/4384</a>) by <a target="_blank" rel="ugc" href="https://civitai.com/user/Lykon">@Lykon</a></p></li><li><p>sdhk_v40</p><p>(<a target="_blank" rel="ugc" href="https://civitai.com/models/82813/sdhk">https://civitai.com/models/82813/sdhk</a>) by <a target="_blank" rel="ugc" href="https://civitai.com/user/hakoniwa/models">@8co28</a></p></li><li><p>FlexWaifu1.3.1</p><p>(<a target="_blank" rel="ugc" href="https://huggingface.co/Ai-tensa/FlexWaifu">https://huggingface.co/Ai-tensa/FlexWaifu</a>) by <a target="_blank" rel="ugc" href="https://twitter.com/Ai_tensa">@Ai_tensa</a></p></li></ul><p></p><h2 id="heading-15992">マージレシピ</h2><p><span style="color:rgb(209, 213, 219)">全ての表記はSuperMergerの表記に準じます。</span></p><p></p><ol><li><p>epicrealism_pureEvolutionV3 + (sdhk_v40 - v1-5-pruned-emaonly) x 0.08 = RealTemp1</p></li><li><p>RealTemp1 + (dreamshaper_631BakedVae - v1-5-pruned-emaonly) x 0.1 = RealTemp2</p></li><li><p>sdhk_v40 + RealTemp2 = ClearBlue-Mix-Real</p><p>alpha = 0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,1,1,1,1,1,1,1,1,1,1,1</p></li><li><p>sdhk_v40 + (FlexWaifu1.3.1 - v1-5-pruned-emaonly 0.5) = AnimeTemp1</p></li><li><p>AnimeTemp1 + ClearBlue-Mix-Real = ClearBlue-Mix-Anime</p><p>alpha = 0,1,0.9,0.7,0.5,0.3,0.1,0,0,0,0,0,0,0,0,0,0,0,0,0,0.1,0.3,0.5,0.7,0.9,1</p></li></ol><p></p><p><span style="color:rgb(209, 213, 219)">このマージレシピ及びモデルの選定基準は</span><span data-type="mention" class="mantine-1yiar0p" data-id="mention:172854" data-label="sazyou_roukaku">@sazyou_roukaku</span><span style="color:rgb(209, 213, 219)">,</span><a target="_blank" rel="ugc" href="https://civitai.com/user/mixboy/models">@mixboy</a>, <a target="_blank" rel="ugc" href="https://twitter.com/nuigurumi1_KR">@nuigurumi1_KR</a>, <a target="_blank" rel="ugc" href="https://huggingface.co/WarriorMama777">@WarriorMama777</a><span style="color:rgb(209, 213, 219)">が公開したものを大いに参考にしています。これらのモデルの制作者やマージレシピの先駆者たちに感謝します。</span></p>