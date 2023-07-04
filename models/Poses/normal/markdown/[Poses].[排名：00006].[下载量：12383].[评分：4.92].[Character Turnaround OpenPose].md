## Character Turnaround OpenPose
### 一、模型概述

- 标签：`poses`, `controlnet`, `pose`, `openpose`
- 下载数：12383
- 收藏人数：2087
- 评论人数：8
- 评分人数：12
- 评分：4.92

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] LekimaTurnaroundV1

- 统计数据
  - 发布时间：2023-03-11T07:13:28.912Z
  - 原始模型：SD 1.5
  - 下载数：12383
  - 评分人数：12
  - 评分：4.92
- 下载地址
  - [characterTurnaround_lekimaturnaroundv1.zip](https://civitai.com/api/download/models/20094)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/102c34de-52fa-46ef-5027-5bd7742db000/width=450/214665.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cc6a8fa1-bfc9-4c8f-e388-6bf4f7ba9900/width=450/212393.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/79eff0f8-5d45-4f4f-d21f-f58ce0b10d00/width=450/212398.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/711c21d9-f582-4398-5fa2-98577d33b200/width=450/212397.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>Disclaimer: This is not made by me.</h1><p>These poses were originally posted on <a target="_blank" rel="ugc" href="https://www.reddit.com/r/StableDiffusion/">r/StableDiffusion</a> by <a target="_blank" rel="ugc" href="https://www.reddit.com/user/lekima/">u/lekima</a>. I reached out to <a target="_blank" rel="ugc" href="https://www.reddit.com/user/lekima/">u/lekima</a> to see if they would post their work on civitai. <s>They were receptive but I believe forgot, and I can't bring myself to urge a stranger online to do something so insignificant. Therefore, let all credit be attributed to </s><a target="_blank" rel="ugc" href="https://www.reddit.com/user/lekima/"><s>u/lekima</s></a><s> and reach out to them if you find this model useful.</s><br /><br /><s>To </s><a target="_blank" rel="ugc" href="https://www.reddit.com/user/lekima/"><s>u/lekima</s></a><s>, if you see this, and want it to be removed and attributed under your own submission, please do let me know. </s><strong><s>Click "show more" for instructions.</s></strong><br /><br /><a target="_blank" rel="ugc" href="https://www.reddit.com/user/lekima/">u/lekima</a> has since given permission for me to keep this file up, but go <a rel="ugc" href="https://civitai.com/user/lekima"><u>check out their profile on CivitAI</u></a> in case they upload any other awesome stuff!</p><p></p><h2>All instructions are compiled from the comments on <a target="_blank" rel="ugc" href="https://www.reddit.com/r/StableDiffusion/comments/1180fls/sharing_my_openpose_template_for_character/">this thread</a>:</h2><h3>Step 1: Set Structure</h3><ul><li><p>In <strong>txt2img</strong> tab</p></li><li><p>Upload the OpenPose template to <strong>ControlNet</strong></p></li><li><p>Check Enable and Low VRAM</p></li><li><p>Preprocessor: None</p></li><li><p>Model: control_sd15_openpose</p></li><li><p>Guidance Strength: 1</p></li><li><p>Weight: 1</p></li></ul><h3>Step 2: Explore</h3><ul><li><p>In <strong>txt2img</strong> tab</p></li><li><p>Enter desired prompts</p></li><li><p>Size: same aspect ratio as the OpenPose template (2:1)</p></li><li><p>Settings: DPM++ 2M Karras, Steps: 20, CFG Scale: 10</p></li><li><p>Batch size: 4 or 8 (depends on your machine)</p></li><li><p>Generate the images</p></li><li><p>Adjust prompts, settings and re-generate until happy 🔁</p></li></ul><h3>Step 3: Upscale / Finalize</h3><ul><li><p>In <strong>txt2img</strong> tab</p></li><li><p>Select the generated image you want to upscale</p></li><li><p>In <strong>Seed</strong> section, click ♻️ button to reuse the seed</p></li><li><p>Enable <strong>Hires.fix</strong> with settings: Denoising: 0.6, Hires upscale: 1.8, Hires upscaler: Latent</p></li><li><p>Batch size: 1</p></li><li><p>Generate the image</p></li><li><p>Adjust prompts, settings and re-generate until happy 🔁</p></li></ul><h3>A few notes:</h3><ul><li><p>You should set the size to be the same as the template (<code>1024x512</code> or <code>2:1 aspect ratio</code>).</p></li><li><p>You can add <code>simple background</code> or <code>reference sheet</code> to the prompts to simplify the background, they work pretty well.</p></li><li><p>It's very difficult to make sure all the details are the same between poses (without inpainting), adding keywords like <code>character turnaround</code>, <code>multiple views</code>, <code>1girl</code> or <code>solo</code> will help keep things a little bit more consistent.</p></li><li><p>If you have any tips and tricks to improve the process/results further, please let me know.</p></li></ul><p></p><p><strong>Question: </strong>Ah, is there a negative prompt you're using at all? or is it just the positive ones?</p><p><strong>Answer: </strong>Yes there is, it's simply <code>EasyNegative, extra fingers, fewer fingers</code><br /><a target="_blank" rel="ugc" href="https://huggingface.co/datasets/gsdf/EasyNegative"><u>You can get EasyNegative here</u></a> btw. Hope this helps!</p><p></p><p><strong>Question: </strong>Very cool! Could you tell me which model you are using? Is this a trained model by you or is it available for download?</p><p><strong>Answer: </strong>Thank you! I used <a target="_blank" rel="ugc" href="https://civitai.com/models/4468/counterfeit-v25"><u>Counterfeit v2.5</u></a> for these examples, you can download it by following the link. Hope this helps!</p>