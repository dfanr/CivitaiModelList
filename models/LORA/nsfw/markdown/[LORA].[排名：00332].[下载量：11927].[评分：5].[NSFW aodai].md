## NSFW aodai
### 一、模型概述

- 标签：`transparent`, `nudes`, `clothing`, `cute`, `semi-realistic`, `ao dai`, `vietnamese dress`, `aodai`, `nsfw`
- 下载数：11927
- 收藏人数：2169
- 评论人数：9
- 评分人数：17
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] aodaimong_v2

- 统计数据
  - 发布时间：2023-03-26T22:07:50.357Z
  - 原始模型：SD 1.5
  - 下载数：9894
  - 评分人数：6
  - 评分：5
- 下载地址
  - [aodaimong_v2.safetensors](https://civitai.com/api/download/models/29085)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/603fdf16-7286-4fa9-f160-fc44dbe1f200/width=450/328329.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e4f2c680-d337-4a6f-60e8-0417f33e1700/width=450/328328.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e073459b-d2c7-494e-93ab-2887b0688000/width=450/328327.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1de2bcd0-d946-407a-8676-2b2fe0dcc400/width=450/328326.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] aodaimong_v1

- 统计数据
  - 发布时间：2023-03-26T22:07:50.357Z
  - 原始模型：SD 1.5
  - 下载数：2033
  - 评分人数：11
  - 评分：5
- 下载地址
  - [aodaimong_v1.safetensors](https://civitai.com/api/download/models/28312)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a1cd09a2-a06f-4871-efb7-1c61b4381a00/width=450/323186.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c76e0d04-ed1b-4a25-031e-dc81f2ba9d00/width=450/318713.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2d285829-af20-4895-845f-55d9945d8300/width=450/318720.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3a2438b7-e67a-4396-f1c8-8d8fa7339500/width=450/318719.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3><u>For those who can't see more than 2 sample images: Go to your account settings and toggle adult contents off and on again.</u></h3><p></p><h2>This is the nsfw lora version of the aodai, or Vietnamese dress.</h2><p>The difference between this lora and the other aodai models/embeddings out there is that this one has been trained exclusively with over 100 lewd aodai images. You will find these dresses to be a bit more transparent with the occasional visible nipples, or maybe a missing pair of pants. Who knows?</p><p>Another point which drove me into making this lora is that it's hard to get the bottom half of the dress right if your character doesn't stand upright. Half of the time they look like they're wearing the bottom of a swim suit. This lora does a decent job to represent the dress on different postures too. Keyword: a decent job, it's not perfect. I don't think it can ever be perfect. Getting the AI to reliably pick on the two splits is looking like an impossible task to me at this point.</p><p><em>It'll work on some custom character loras to a certain extend. I'm planning to fine-tune this lora to reduce artifacts on the dress in the near future. Also works with latex texture for those of you who are fancy about giving it a go.</em></p><h3>V2 update:</h3><p>Not sure if I can call this version definitely better than V1 but here are some note-worthy things about V2:</p><ul><li><p>Works best around 0.7 - 0.9 weight. Personally I use 0.7 for all of the sample images. Make sure that you have &lt;lora:aodaimong_v2:<strong>x</strong>&gt;, ((<strong>y</strong> aodaimong)) as your prompt, with <strong>x</strong> being the weight and <strong>y</strong> the color. Add "latex" to <strong>y </strong>to get latex texturing on your dress. By default with no <strong>y</strong> it's a white dress.</p></li><li><p>This version distinguishes hair and dress colors much better than V1. In V1, 9 out of 10 times you'll get the same dress color as your hair if you choose to specify what the character's hair color is. That is no longer the case in V2.</p></li><li><p>Fixes some texture issues. I did my best to smooth out the dress so hopefully you won't see as much weird textures as in V1.</p></li><li><p>Works more consistently with other poses.</p></li><li><p>Pants are a lot rarer now. It's virtually impossible to have the pants generated consistently during my testing so I decided to reduce the frequency of it as a result.</p></li><li><p>Added a few more prompts to control a few parameters and provide a more consistent set of images in general. I.e: You have more control of what you want your character to do/look like now instead of leaving it to the randomness of the AI. See below.</p></li><li><p>Added a prompt to consistently showing no bra on your character: khongbra.</p></li><li><p>Added some poses. Try using these prompts: posing for photo, holding a cloth.</p></li><li><p>Latex texture works fairly consistent now. With all colors but white that is.</p></li><li><p>Overall it's an improvement based on what I wanted to do. Feel free to go back and forth between the two versions depending on your needs.</p></li></ul><p></p><h3>Credit</h3><p>I'd like to credit the following creators for I've been using their characters a lot during my testing:</p><p></p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/12327/virtualgirl-aim">Nyaa</a> and their virtual girls series. Absolutely my favorite.</p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/21162/vyvan-le-or-asian-instagram-model">asian_ai</a> and their Vyvan Le character model. Who else is better to model these dresses if not a Viet girl herself?</p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/20096/vietnamese-aodai">lamlnq</a> and their aodai checkpoint. Check them out too, gave me the inspiration to make this lora.</p></li></ul><p></p><p><strong><s>I personally think V2 is going to be the final version of this lora, at least for now. I ran out of new images to add to the dataset and training the AI any further will just end up overcooking it.</s> I got an idea for V3 so currently working on it. No promise it'll ever be done though, very few sample size right now.</strong></p><p><strong>Please do post what you are able to make using this lora, I love seeing them.</strong></p><p></p><p></p>