## fking_civitai
### 一、模型概述

- 标签：`concept`, `general purpose`, `civitai`, `community`, `fking`
- 下载数：915
- 收藏人数：139
- 评论人数：9
- 评分人数：2
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v20230318_Lyco

- 统计数据
  - 发布时间：2023-06-01T13:28:22.095Z
  - 原始模型：SD 2.1 768
  - 下载数：249
  - 评分人数：0
  - 评分：0
- 下载地址
  - [fkingCivitai_v20230318Lyco.safetensors](https://civitai.com/api/download/models/86599)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/164366d8-9338-4a44-aad1-3ed4d0977b53/width=450/986870.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/823906ad-aff4-4969-aa91-123ae15529d7/width=450/986787.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fb2fcd90-b057-4a3c-b08f-8ab74320e9a5/width=450/986862.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5d373cd8-b66c-492b-aa9c-01b7c77474a8/width=450/986905.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v20230318

- 统计数据
  - 发布时间：2023-05-31T23:17:54.735Z
  - 原始模型：SD 2.1 768
  - 下载数：264
  - 评分人数：0
  - 评分：0
- 下载地址
  - [fkingCivitai_v20230318.safetensors](https://civitai.com/api/download/models/25299)
  - [fkingCivitai_v20230318_trainingData.zip](https://civitai.com/api/download/models/25299?type=Training%20Data)
  - [fkingCivitai_v20230318.yaml](https://civitai.com/api/download/models/25299?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/644bc606-3c40-4976-f55b-08256a949b00/width=450/277566.jpeg" /> |
| ---- |

#### [版本1/共3个版本] v20230222

- 统计数据
  - 发布时间：2023-05-31T23:17:54.735Z
  - 原始模型：SD 2.1 768
  - 下载数：402
  - 评分人数：2
  - 评分：5
- 下载地址
  - [fkingCivitai_v20230222.safetensors](https://civitai.com/api/download/models/14469)
  - [fkingCivitai_v20230222_trainingData.zip](https://civitai.com/api/download/models/14469?type=Training%20Data)
  - [fkingCivitai_v20230222.yaml](https://civitai.com/api/download/models/14469?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7788bb60-38d5-49c1-8782-c5197fa6d000/width=450/159202.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e0dca45a-9991-4e1d-8651-c5904796fa00/width=450/159201.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/eed6f502-3653-46fc-d339-17ffe8831700/width=450/159200.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c2bf271f-38bc-49f4-78a7-09db8547fc00/width=450/159356.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>fking_civitai</h1><p><strong>A fking StableDiffusion model</strong></p><p>Welcome, all you beautiful Civitai people! This model was created directly from the images given by model/TI/lora/etc uploaders for their model samples. The prompt data given from the uploader or <code>PNG</code> metadata was directly used for training, the only curation done was to limit all images to be at least 320 pixels in width or height and less than 1024 pixel in width or height.</p><p>Furthermore, all weights and most special characters were removed, such as <code>.:()[]</code> and possibly more (<em>or less, whoops)</em>. Any prompt that had a lora, <code>&lt;lora:lora_name:weight&gt;</code> was also stripped. Images were further curated by checking if the remaining tags were <code>&gt; 0</code>.</p><p></p><p><strong>Current Version v20230318</strong></p><p>This version was trained on `42,350 images` for <code>100 epochs</code> or <code>4,235,000 steps</code> on <strong>RunPod A100 Secure Cloud</strong> (<em>ouch, that was expensive</em>).</p><ul><li><p><code>320 &lt;= image size &lt;= 1024</code>, so try different generation dimensions</p></li><li><p><code>by &lt;uploader&gt;</code> added to training caption</p></li><li><p><code>&lt;imagetags&gt;, &lt;triggerwords&gt;</code> added to training caption. (<em>Note: Image tags were scraped on 03/18/2023, and may no longer be accurate, RIP)</em></p></li><li><p>Text encoder was trained, as a result the training captions from the primarily <code>1.x</code> training dataset, you'll need to prompt this model as if it were a <code>1.x</code> model for the best results. If you are not looking for <code>anime</code> be sure to add it to your negative prompts as the training set also contained a large amount of it. (<em>Future version I will be pruning it)</em></p></li></ul><p></p><h2>Usage</h2><p>This model was trained without a trigger word directly with the prompts pulled from previews of models on this site. You can try using it as a general purpose model, or as an experiment. Try and see if you can invoke a certain model's style by using words explicitly in their preview image prompts, likely a trigger word.</p><p></p><h2>Future Updates</h2><p>I do have plans to update the checkpoint with the newly uploaded images to Civitai, perhaps monthly or bi-monthly, it takes a loooooong time for training and I haven't decided if I want to spend money to off-load it. Next updates will also include a <code>txt</code> file of all images and models used for quicker crediting. I apologize that I didn't have the foresight to do that before I got started.</p><p></p><h3>Upcoming Changes</h3><ul><li><p><strong>[DONE]</strong> Include trigger words as caption data as long as they conform to the tag filters</p></li><li><p><strong>[DONE] </strong>Be more precise in caption filter</p></li><li><p><strong>[DONE] </strong>Include a <code>credits.txt</code> with version/dataset to quickly identify which image was sourced from what model</p></li><li><p><strong>[IMPLEMENTED] </strong>CHAD Score images to further prune the dataset of images with low aesthetic scores. (<em>Implemented in scraper, but not in use on this version)</em></p></li><li><p><strong>[WIP] </strong>Continue ignoring requests for <code>NSFW</code> or <code>1.x</code> models</p></li></ul><p></p><h2>StableDiffusion 1.x</h2><p>There will not be a checkpoint trained against a <code>1.x</code> base. You are welcome to train it yourself using the dataset I provided.</p><p></p><h2>Contributions</h2><p>If you are interested in contributing monetarily, please check out the links in my profile, (<em>various charities</em>), or consider donating directly to Civitai. Otherwise, just a thanks is all that is needed.</p><p></p><h2>Additional Notes</h2><p>I will only be scraping models and images flagged <code>SFW</code>, I will not be training a <code>NSFW</code> or <code>18+</code> model, but I also didn't look at each individual picture and some <code>NSFW</code> material may have slipped through.</p><p></p><h2>Remixes/Merges/Extractions</h2><p>This is Civitai's model, by the people, for the people. Please merge and remix away! I only ask that you <strong>DO NOT</strong> mix with a model intended for resale, don't keep from your community.</p><p></p><p><strong><em>Please remember to like or rate model. Happy prompting!</em></strong></p><p></p>