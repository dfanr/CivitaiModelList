## Gun2Head Pose
### 一、模型概述

- 标签：`anime`, `gun`, `poses`, `pose`, `gun to head`
- 下载数：4004
- 收藏人数：814
- 评论人数：9
- 评分人数：10
- 评分：4.5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] Gun2HeadV4ActualFinal

- 统计数据
  - 发布时间：2023-06-08T16:06:20.170Z
  - 原始模型：SD 1.5
  - 下载数：1930
  - 评分人数：5
  - 评分：4
- 下载地址
  - [Gun2HeadV4.safetensors](https://civitai.com/api/download/models/91841)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2c0f2489-d74d-4e11-94cb-151f0604efe4/width=450/1074669.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2311cfbf-f9d2-4537-8bc3-054b1c2eea8a/width=450/1074696.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d89dd40e-aa35-4ff0-a1af-1d92288f9aea/width=450/1077050.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7e81e096-cb43-4d1e-ae24-fbde4fe16445/width=450/1074694.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] Gun2HeadV3Final

- 统计数据
  - 发布时间：2023-06-08T15:59:03.390Z
  - 原始模型：SD 1.5
  - 下载数：2074
  - 评分人数：5
  - 评分：5
- 下载地址
  - [Gun2HeadV3.safetensors](https://civitai.com/api/download/models/7907)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/911d617a-9459-4734-1624-837582c32000/width=450/74424.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/687fe055-c19b-4152-4627-c13a824fdb00/width=450/74423.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/95f36c4d-9594-42ee-82d1-c5f1ae679900/width=450/74422.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/10654bf2-e549-4620-52bc-5e165b509900/width=450/74421.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3 id="heading-1809"><u><span style="color:#228be6">V4 SUMMARY</span></u></h3><p>In the attempt to revisit this and make it better, V4 of this concept has now attained better functionality when generating handguns. It also no longer has the issue of switching hands or using both hands; it will always generate the pose on the righthand side.</p><p></p><p>Unfortunately, it was a consistently unavoidable price I had to pay that the fingergun only mode became more scuffed than the gun mode, unlike the previous version. It's trained to do two fingers instead of just one, yet still prefers to do one anyway.</p><p>Note that the images it generates are almost always a bit too detailed, and most outputs you will get look semireal.</p><p></p><p>It does relatively well without controlnet, though that is not to say controlnet cannot help make it better, especially when trying for fingerguns, where it often lowers the hand or places it in front of the forehead. If it isn't giving you the pose, it's fine to increase the weight past one a bit.</p><p></p><p></p><h3 id="heading-1015"><u><span style="color:#fa5252">V3 SUMMARY</span></u></h3><p>Well, I<em> t</em>ried to make this work, but I won't lie, you <strong>WILL</strong> have to wrestle with this to get what you want. This lora is designed to work with both guns and finger guns, all you have to do is prompt as such. However, I've tried everything, but it will, no matter what and whenever it wants to, give two guns to the head instead of just one. You can use as many negative prompts as you'd like but it won't get rid of it forever. I've retrained it multiple times, but that didn't work either. So in the end, since it still technically does what it's meant to, I'm still gonna post it anyway.</p><p></p><p>If you manage to find a way to prevent the issue completely, please do let me know. Also, this doesn't seem to mix well with other loras, but take that with a grain of salt, because that happens no matter what loras I use, so it's maybe just a personal problem. Another thing is that getting two fingers instead of one is also difficult, though sometimes increasing the weight just slightly fixes that.</p><p></p><p>A negative prompt you can try:</p><p><em>(gun, holding gun, weapon, holding weapon:1.4), dual wielding, double finger guns</em></p><p></p><p>Keep in mind the previews may look good, but are cherry-picked results over a wide range of tests. Therefore...<strong>Do not expect full replication!</strong></p><p>At the end I've provided examples as to what<strong> </strong><em>can</em><strong> </strong>go wrong.</p><p></p><p>66 images, trained on NAI. Tested across multiple models.</p>