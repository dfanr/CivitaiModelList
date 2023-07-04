## Noise Offset for True Darkness in SD
### 一、模型概述

- 标签：`landscapes`, `dark`, `base model`, `shadow`, `darkness`, `portraits`
- 下载数：2001
- 收藏人数：556
- 评论人数：88
- 评分人数：10
- 评分：4.9

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] V1.0

- 统计数据
  - 发布时间：2023-02-28T06:09:40.374Z
  - 原始模型：SD 1.5
  - 下载数：2001
  - 评分人数：10
  - 评分：4.9
- 下载地址
  - [noiseOffsetForTrue_v10.safetensors](https://civitai.com/api/download/models/12354)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2f385e83-16ee-488b-2e55-b13952432d00/width=450/119785.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f2725cb8-2269-4f64-baed-07915fe7a900/width=450/120167.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/37f97d06-db2b-4d24-25b7-f58a142ae700/width=450/120166.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ea5faa04-9cc0-4a70-fea3-6222de58bc00/width=450/120101.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>Note: 2/27/2023</strong> - I have removed the <strong>ckpt</strong> version of this upload out of an abundance of caution after Bitdefender software reported a Trojan. Spybot Search and Destroy, Malwarebytes, Avast (lol), and Windows Defender (lolol) didn't report any threats. The safetensor version is threat-free in all programs.<br /><br />This model is specially fine-tuned to create good shadowy, dark, scenes. It's created by <a target="_blank" rel="ugc" href="https://www.crosslabs.org/team">Nicholas Guttenberg at Crosslabs</a> and the <a target="_blank" rel="ugc" href="https://www.crosslabs.org/blog/diffusion-with-offset-noise">concept is explained here</a>.<br /><br />Nicholas explains: "not only does SD not have the ability to produce overly dark or light images out of the box, but it also <strong>can’t even learn to do it</strong> - not without changing one thing about it"<br /><br />The article goes on to explain how to finetune your own models with their "darkness" technique, or you can<strong> merge the attached file into your own models with a SD 1.5 diff.</strong> <br /><br />The attached images showcase the difference between their Noise Offset trained 1.5 model and the original 1.5 model, and the results are striking - true darkness and good contrast is possible with this model/method. I've also included examples of the model merged into my <a target="_blank" rel="ugc" href="https://civitai.com/models/3848/theallys-mix-ii-churned">Churned Mix</a> - producing true black/dark images.<br /><br /><a target="_blank" rel="ugc" href="https://civitai.com/models/8765/theovercomer8s-contrast-fix-sd15sd21-768">This amazing LoRA</a> has implemented the technique described in Crosslab's paper.<br /><br /><strong>Please consider joining my Patreon</strong>! Advanced SD tutorials, settings explanations, adult-art, from a female content creator (me!) <a target="_blank" rel="ugc" href="http://patreon.com/theally">patreon.com/theally</a></p>