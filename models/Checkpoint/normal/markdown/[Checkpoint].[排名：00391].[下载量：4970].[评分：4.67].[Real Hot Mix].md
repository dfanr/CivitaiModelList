## Real Hot Mix
### 一、模型概述

- 标签：`style`
- 下载数：4970
- 收藏人数：612
- 评论人数：2
- 评分人数：6
- 评分：4.67

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1

- 统计数据
  - 发布时间：2023-06-20T14:48:03.459Z
  - 原始模型：SD 1.5
  - 下载数：4970
  - 评分人数：6
  - 评分：4.67
- 下载地址
  - [realHotMix_v1.safetensors](https://civitai.com/api/download/models/68036)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cd16a524-4a5a-4626-90d6-e8c8620d294d/width=450/1335239.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6ca973c1-601f-40d5-9f49-e52a21d1da74/width=450/799099.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/67ca1e28-8f25-4424-ba7f-bedd4c1605b3/width=450/799100.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/44fdf6db-1b62-4983-82ac-48f46911733c/width=450/1335353.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Join my new Discord here! <a target="_blank" rel="ugc" href="https://discord.gg/cnVvnkgtPb">https://discord.gg/cnVvnkgtPb</a></p><p><strong>Real Hot Mix</strong> - a model that looks like real life; no uber contrast &amp; oversaturated colors, no fake plastic skin when generated or upscaled, just normal real life images with:</p><ul><li><p>realistic skin textures!!!!!!!</p><ul><li><p>(dimples, bumps, freckles, imperfections)</p></li></ul></li><li><p>realistic lighting</p></li><li><p>flexible prompting (poses, anatomy, backgrounds)</p></li><li><p>easy to prompt for large OR small breasts</p></li></ul><p>This model is a mix, so no new content was trained. I just wanted a model that was easy to work with and a good base to train future LoRAs on. Enjoy!</p><p><em>(All images &amp; models are prompted with 18+ descriptions &amp; trained with 18+ models!)</em></p><p></p><h2 id="model-details">Model Details</h2><p><strong>Mixing (what I believe to be) the best qualities from several photo-real models:</strong></p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/10961/lazymix-real-amateur-nudes">LazyMix+ (Real Amateur Nudes)</a> v2</p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/21813/edge-of-realism">Edge of Realism</a> v2</p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/4201/realistic-vision-v20">Realistic Vision</a> v2</p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/8030/analog-madness-realistic-model">Analog Madness</a> v4</p></li></ul><p></p><p>Without getting into too much detail, I think LazyMix is one of the best to prompt with (especially for NSFW women), but has a plastic/flat look when upscaling and going for a photorealistic look (vs. analog/grainy/selfie quality). Meanwhile, Edge of Realism and Realistic Vision are very photoreal, and Analog Madness is sort of a hybrid. My intention was to blend LazyMix and Edge of Realism as the primary models, and then add flavors of Realistic and Analog. Real Hot Mix should capture prompt flexibility, NSFW bits, lighting, and skin textures all in 1 model.</p><p></p><p><strong>Mix Formula:</strong></p><p>0.9(0.85(0.5(lazymixRealAmateur_v20) + 0.5(edgeOfRealism_eorV20Fp16BakedVAE)) + 0.15(realisticVisionV20_v20)) + 0.1(analogMadness_v40)</p><p></p><p>Respective Weights:</p><ul><li><p>0.3825 LazyMix+</p></li><li><p>0.3825 Edge of Realism</p></li><li><p>0.1350 Realistic Vision</p></li><li><p>0.1000 Analog Madness</p></li></ul><p></p><h2 id="how-to-use-sample-workflow"><strong>How to use (sample workflow)</strong></h2><ul><li><p>I find that generating txt2img (with ControlNet 'softedge' or 'openpose' if desired) with height/width &lt;=768px and then upscaling (hires fix or img2img) with Nickelback (or maybe NMKD) upscalers works well</p><ul><li><p><a target="_blank" rel="ugc" href="https://upscale.wiki/wiki/Model_Database">https://upscale.wiki/wiki/Model_Database</a></p></li></ul></li><li><p>For upscaling, check out this vid by Sebastian Kamph</p><div data-youtube-video><iframe width="640" height="480" allowfullscreen="true" autoplay="false" disablekbcontrols="false" enableiframeapi="false" endtime="0" ivloadpolicy="0" loop="false" modestbranding="false" origin playlist src="https://www.youtube.com/embed/EmA0RwWv-os" start="0"></iframe></div></li><li><p>For inpainting, set masked content = original</p><ul><li><p>inpaint initial txt2img at either whole picture or only masked</p></li><li><p>inpaint upscaled image with only masked</p></li><li><p>large padding - idk exactly, but I usually like something larger than the default</p></li><li><p>modify prompt as needed depending on what is/isn't masked</p></li><li><p>helps if you know photoshop, edit, then reupload to img2img inpainting</p><ul><li><p>can draw in parts with brush tool</p></li><li><p>can fix parts with content aware/liquify (ex. iris)</p></li></ul></li><li><p>experiment with ControlNet</p></li></ul></li></ul><p></p><p>Contact me at <a target="_blank" rel="ugc" href="mailto:aihotgirls@proton.me">aihotgirls@proton.me</a></p>