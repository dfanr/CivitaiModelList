## doge
### 一、模型概述

- 标签：`character`, `animals`, `meme`, `dog`, `shiba inu`, `doge`, `cheems`
- 下载数：990
- 收藏人数：204
- 评论人数：3
- 评分人数：5
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1

- 统计数据
  - 发布时间：2023-03-25T12:05:13.260Z
  - 原始模型：SD 1.5
  - 下载数：990
  - 评分人数：5
  - 评分：5
- 下载地址
  - [doge.safetensors](https://civitai.com/api/download/models/18180)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/200cc97d-43b0-47d7-d0be-7f9618839e00/width=450/186976.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ad60a74-1570-48c0-947d-bde4e948c700/width=450/186987.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/98e72161-f3a5-443f-65dc-581a5559be00/width=450/186986.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/234a76cf-ea84-4a6e-28ba-e189d3d2db00/width=450/186985.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>A multi-concept LORA model trained on ~60 images of <strong>doge</strong> characters and shibas in different styles, which makes it compatible with almost any other 1.5 model.</p><p></p><p>This LORA includes the following characters: doge, cheems, swoledoge, baby-doge + bonus characters and generally improves the ability to generate shiba inu dogs.</p><p></p><p>Optimal CFG Scale 3-6<br />Optimal Lora ranges: 0.55 - 1.1</p><p></p><p>To use this model In a1111 webui, download it, rename it to <u>doge.safetensors</u> place it in models/lora and include <strong>&lt;lora:doge:1&gt;</strong> anywhere in the prompt, where 1 can be any value in lora ranges mentioned above. Click on the images to see the prompts used, if it doesn't work, turn off ublock or refresh the page.</p><p></p><p>The trigger phrases are: <strong>doge</strong> (for the main doge character), <strong>shiba inu</strong> (for more general shibas), <strong>buff Swoledoge</strong> (for bodybuilder doge), <strong>baby-doge</strong> (for a cute mini-doge puppy), <strong>Cheems sitting</strong> (for the Cheems character).<br />For Cheems you might need to add, "puppy p3rr0" to the negative prompt.</p><p></p><p><u>Bonus characters</u>: this lora can also generate two other dogelore characters: <a rel="ugc" href="https://joke-battles.fandom.com/wiki/Perro_(Dogelore)">Perro</a> and <a rel="ugc" href="https://knowyourmeme.com/memes/nelson-the-bull-terrier-walter">Walter</a>.  I found a consistent recipe for Perro for realistic models, which requires a warm-up stage to give the basic shapes and colors. The prompt requires a trigger phrase <strong>[(white) puppy:cute ((p3rr0)):5] sitting</strong> where 5 is ~1/4 of all generation steps; CFG scale 3-4; lora power at 0.7-0.8, and "(doge)" and "(shiba inu)" in negative prompt.</p><p>For Walter, it is a bit more simple: <strong>white (bullterrier) ((walt3r))</strong></p><p></p><p>Why did I use leetspeak in trigger words during training? Because both "perro" and "walter" are very popular words/tokens that do not match the expected concept.</p><p>If you like this lora, feel free to follow me &lt;3<br />Message to community: <a rel="ugc" href="https://civitai.com/questions/148/guideish-for-training-a-stylemultiple-characters-in-a-single-lora-my-tips-and-thoughts-for-creators-on-improving-the-content-on-this-website">STOP</a> making 144mb LORAs for a single character.<br /></p><p>License: use as you wish, excluding usage of this free model for cryptocurrency promotions, it is prohibited under default license and requires a commercial license, which you can obtain by contacting me.</p>