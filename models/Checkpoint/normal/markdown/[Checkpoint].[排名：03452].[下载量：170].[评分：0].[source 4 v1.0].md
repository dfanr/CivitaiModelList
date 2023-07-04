## source 4 v1.0
### 一、模型概述

- 标签：`lighting`, `style`
- 下载数：170
- 收藏人数：36
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1 checkpoint

- 统计数据
  - 发布时间：2022-12-27T22:12:11.501Z
  - 原始模型：SD 1.5
  - 下载数：134
  - 评分人数：0
  - 评分：0
- 下载地址
  - [source4V10_v1Checkpoint.ckpt](https://civitai.com/api/download/models/3108)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4f6994c1-b614-4d25-0ffb-1943e6202100/width=450/21563.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/eb37265e-6e7b-4556-fc35-1ff0f469c100/width=450/21564.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1cd99b23-a02f-420e-7957-02fc6510ef00/width=450/21565.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dc5617ce-2e85-497a-682b-9b2251294f00/width=450/21566.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1 safetensors

- 统计数据
  - 发布时间：2022-12-27T21:06:07.938Z
  - 原始模型：SD 1.5
  - 下载数：36
  - 评分人数：0
  - 评分：0
- 下载地址
  - [source4V10_v1Safetensors.safetensors](https://civitai.com/api/download/models/3109)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4f6994c1-b614-4d25-0ffb-1943e6202100/width=450/36392.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/eb37265e-6e7b-4556-fc35-1ff0f469c100/width=450/36393.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1cd99b23-a02f-420e-7957-02fc6510ef00/width=450/36394.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dc5617ce-2e85-497a-682b-9b2251294f00/width=450/36395.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Originally posted to <a target="_blank" rel="ugc" href="https://huggingface.co/jkcarney/source4_v1.0">HuggingFace by jkcarney</a></p><h1>Introduction</h1><p>Source4 is a Stable Diffusion 1.5/Dreambooth model trained on portraits with dramatic, multicolored lighting. These portraits are heavily inspired by modern, multicolored theatrical lighting (hence the name Source4). This model was fine tuned without prior preservation loss for 8000 steps on over 90 high quality 512x512 images.</p><p>In the prompt, use activation token <code>source4 style</code></p><p></p><h1>Recommendations</h1><p>I recommend experimenting with different colors in your prompt. For example, adding <code>teal tones</code> or <code>red tones</code> to your prompt bring those respective colors out. Also try a smaller weight on the <code>source4 style</code> prompt (ie, <code>(source4 style:0.8)</code>), for a slightly less pronounced but more realistic effect.</p><p><code>Euler a</code> and <code>DPM++ 2S a Karras</code> for 25-30 steps have typically given me the highest quality images. Euler a typically gives me more "dreamy" portraits while DPM++ 2S a Karras gives me more realistic portraits.</p><p>If the effect is too pronounced or faces are totally blurred out, I recommend decreasing the weight of the activation token. An alternative is to specify <code>detailed face</code> in the prompt to ensure a face is actually drawn.</p><h1></h1><p>Welcome to the technicolored world.</p>