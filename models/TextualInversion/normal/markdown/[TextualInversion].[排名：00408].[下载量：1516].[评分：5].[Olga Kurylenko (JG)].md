## Olga Kurylenko (JG)
### 一、模型概述

- 标签：`girl`, `person`, `female`, `french`, `textual inversion`, `model`, `hollywood`, `woman`, `actress`, `celebrity`, `embedding`, `girls`, `real person`, `women`, `james bond`, `007`, `ukranian`
- 下载数：1516
- 收藏人数：141
- 评论人数：4
- 评分人数：8
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2.0

- 统计数据
  - 发布时间：2023-06-25T12:57:37.025Z
  - 原始模型：SD 1.5
  - 下载数：556
  - 评分人数：3
  - 评分：5
- 下载地址
  - [okuryl3nko.pt](https://civitai.com/api/download/models/103753)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f94a8ec4-5e06-44db-b516-b6b3dbf65952/width=450/1283716.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3f47bd49-1119-45bb-b64e-0925bcb8184b/width=450/1283717.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4337af9d-b2f8-4bf5-aa90-2669b330e8b3/width=450/1283740.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2b923279-cc06-4bc2-aa2a-6b1105dd7cd9/width=450/1283718.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-06-25T12:53:53.316Z
  - 原始模型：SD 1.5
  - 下载数：960
  - 评分人数：5
  - 评分：5
- 下载地址
  - [0lg4kury.bin](https://civitai.com/api/download/models/85415)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/40818c47-b960-44c3-af92-3d38f4e181a6/width=450/967129.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/227e78c0-517f-49af-8da0-7ed29a803705/width=450/967132.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4512c87b-f225-4cf2-a865-c24ac94c55b9/width=450/967131.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a1572b53-6baa-4a90-ae5b-6cd49ed13411/width=450/967138.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><a target="_blank" rel="ugc" href="https://www.instagram.com/olgakurylenkoofficial/">Olga Kurylenko</a> is a Ukranian/French actress and model, known for many roles in films such as <em>Hitman </em>or <em>Quantum of Solace</em>.</p><p><strong>Note: </strong>This TI has been updated. Please refer to the "About this version" section for more info on the training process and settings.</p><p>Since I'm on vacation, I've started training TIs on a free colab shared by <span data-type="mention" class="mantine-1yiar0p" data-id="mention:26232" data-label="Scottymac">@Scottymac</span> (who was also kind enough to provide a step-by-step tutorial on how to use it--thanks a bunch, mate!). It allows me to do a full batch size (even without paying Colab Pro, I can run the training process with a batch size of 6 and gradient 3).</p><p>This is kind of an experiment for me too, as I've trained the model without captions for the first time. And I'd say the results are surprisingly good, but I'll need to further test the process to get a clearer idea about its pros and cons.</p><p>I've tested a few steps: 120, 180 and 500. Probably should have tested more, but I liked the results with step 500 so much that I thought it was unnecessary. Training rate, as usual, was a fixed 0.004.</p><p>Appreciate my work? My TIs are free, but you can always <a target="_blank" rel="ugc" href="https://www.buymeacoffee.com/jernaugurgeh">buy me a coffee</a>. :)</p><p>Curious about my (usual) work process? I have summarized it <a target="_blank" rel="ugc" href="https://civitai.com/models/56570/renata-valliulina?commentId=118383&amp;modal=commentThread">here</a>.</p><h2 id="heading-27">How to create a good prompt using my TIs</h2><p>You're obviously free to experiment, but bear in mind that my TIs are trained with a more or less fixed phrasing, that normally starts with:</p><p>"photo of EMBEDDING_NAME, a woman"</p><p>So I recommend always starting your prompt like that and then building the rest of the prompt from there. For instance, "photo of beautiful (0lg4kury:0.99), a woman as a movie star, hair upsweep updo, sweater off-shoulders, trousers, at a movie premiere gala, dark moody ambience (masterpiece:1.2) (photorealistic:1.2) (bokeh) (best quality) (detailed skin:1.2) (intricate details) (nighttime) (8k) (HDR) (cinematic lighting) (sharp focus), (looking at the camera:1.1), (closeup portrait:1.1)"</p>