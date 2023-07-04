## Unusual Angles (openpose)
### 一、模型概述

- 标签：`selfie`, `poses`, `kneeling`, `bent over`, `lying`, `crawling`
- 下载数：6944
- 收藏人数：898
- 评论人数：4
- 评分人数：6
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-03-08T12:47:40.579Z
  - 原始模型：SD 1.5
  - 下载数：6944
  - 评分人数：6
  - 评分：5
- 下载地址
  - [unusualAnglesOpenpose_v10.zip](https://civitai.com/api/download/models/19966)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6ff0236b-b5e1-4f64-6b00-5976db588f00/width=450/210890.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8ced1a46-0f9f-4894-c832-e1ed29d97f00/width=450/210889.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9b742d8a-ffdd-488e-9689-41790e79f900/width=450/210888.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b0be1ce3-1cf5-4011-0a16-2fefde961100/width=450/210887.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Edit: These require controlnet/openpose</p><p></p><p>6 different poses. 3 of these have the same base pose, just minor differences.</p><p></p><p>I attached a batch of images for each pose to avoid cherry-picking. What you see is what you get.</p><p></p><p>Please notice that changing key words in the prompt will change the angle <em>significantly</em>. For example, as the pictures show, pose 3 will produce a completely different angle with "from_above", compared to "from_below" in your prompt. So there is a lot of flexibility to go with these poses. (There is also "from_side" and "from_behind", though I use these less frequently.)</p><p></p><p>Poses:</p><p></p><p>1) This one works well with 512x512. They may be opening a box or something, at least that is what I was going for.</p><p></p><p>2) Works both with 512x640 and 640x512. Also produces some interesting results when you change the angle to "from_below" and use "crawling" instead of "kneeling" in your prompt, though the arms tend to be a little short in those outputs.</p><p></p><p>3) Works better with 512x640 or something similar when you're going for the "from_below" angle. If you go 512x512 or a wider ratio, the hip tends to push past the left arm. Changing the angle to "from_above" also produced some interesting results. This is the least consistent of the 6 poses in producing good results.</p><p></p><p>4) Pretty straight forward. More close-up than anticipated.</p><p></p><p>5) This one only works when you really emphasize in the prompt that you want a lying pose. Pretty consistent when you get there.</p><p></p><p>6) A selfie pose, fairly consistent. You may also go for "from_below" and "crawling" here to get something completely different where they are leaning on something with their arm.</p><p></p><p></p>