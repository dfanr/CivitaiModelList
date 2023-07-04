## hyperfusion 200k images
### 一、模型概述

- 标签：`anime`, `concept`, `thighs`, `hyperass`, `hyperbreasts`, `belly`, `pregnancy`, `pregnant`, `hyperpreg`, `booty`, `fat`, `chubby`, `boobs`, `tits`, `nipples`, `thick thighs`, `booba`, `breasts`, `ass`, `hyper`, `big boobs`, `huge nipples`, `hyperfusion`, `preg`, `thigh`
- 下载数：11211
- 收藏人数：1315
- 评论人数：59
- 评分人数：18
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v5

- 统计数据
  - 发布时间：2023-06-14T20:48:35.452Z
  - 原始模型：SD 1.4
  - 下载数：5740
  - 评分人数：7
  - 评分：5
- 下载地址
  - [hyperfusion_213k_32dim-LoCon-epoc6-v5.safetensors](https://civitai.com/api/download/models/75230)
  - [hyperfusion-v5-tags.zip](https://civitai.com/api/download/models/75230?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/004c3e93-e835-4589-b52f-e97a6a04d9e9/width=450/840968.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/067f9bc2-43c0-4ae0-bf7f-a5f9c17146cb/width=450/840977.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/58fd441a-41ae-4060-beb5-fc6e1b65633c/width=450/840978.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6743c931-6599-4c8c-9f88-192f3cab1928/width=450/840981.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v4

- 统计数据
  - 发布时间：2023-05-19T19:06:19.891Z
  - 原始模型：SD 1.4
  - 下载数：5471
  - 评分人数：11
  - 评分：5
- 下载地址
  - [hyperfusion_99k-64dim-LoRA_epoc6-v4.safetensors](https://civitai.com/api/download/models/19987)
  - [hyperfusion-v4-tags.zip](https://civitai.com/api/download/models/19987?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/66575ca7-5dcc-496e-b190-c0e55bc57900/width=450/211145.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8cfd95f8-5978-4473-320a-628888a79c00/width=450/211144.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d18fd74e-488e-4cff-40ae-8e320fea5500/width=450/211143.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8b48f728-0b63-4cea-98ac-b7fe3094a100/width=450/211142.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This LoRA model was trained on <s>100k</s> 200k images of normal to hyper sized anime characters. It focus mainly on breasts/ass/belly/thighs but is trained on over 47,000 unique tags.</p><p></p><p>In short, this model is a "fusion" of all of my other models. Hence fusion in the name. However if you really want the absolute largest sizes, it's best to use this model AND one of my specific <a target="_blank" rel="ugc" href="https://civitai.com/user/throwawayjm">hyper models</a>. I've found that specialized models do work really well when they focus on one specific topic. I just wanted to have it all in one, so this is where we are.<br /></p><h2 id="heading-21">v5 ChangeLog</h2><ul><li><p>Doubled the dataset size to 200k+</p></li><li><p>Trained with Kohya's LoCon LoRA, but does not require any additional extensions. &lt;lora:model_name:1&gt; is all you need</p><ul><li><p>There is a bug in A1111 version 1.0 and 1.1 that prevents Kohya's LoCon LoRA from loading. If you are on this version, you can either upgrade to 1.2.x or install the LoRA extension.</p></li></ul></li><li><p>v4 focused on body size, this one focuses more on body shapes. See tag docs for examples. ex :round belly, chubby belly, sagging belly, hanging belly, breasts..., body... etc...</p></li><li><p>Better at belly related tags overall (because a good part of the new data was belly stuff)</p></li><li><p>Better tag accuracy for sizes and shapes, thanks to more accurate image classifiers. Still plenty of room for improvement</p></li><li><p>v5 is trained a bit further than v4 so you may need to reduce the strength for some prompts. It's usually fine at :1 for anime type models, but should be lowered when mixing LoRAs</p></li></ul><h3 id="heading-22"><br />Tag Info (You definitely want to read the tag docs, see :Training Data)</h3><p><br />Because hyperfusion is a conglomeration of multiple tagging schemes, I've included a tag guide "tag-data" in the training data download. It will describe the way the tags work (similar to Danbooru tags) and which tags the model knows best. <br />But for the most part you can use a majority of tags from Danbooru, r-43, e621, related to breasts/ass/belly/thighs/nipples.</p><p></p><p>The best method I have found for tag exploration is going to danbooru/r-34 and copying the tags from any image you like, and use them as a base. Because there are just too many tags trained into this model to test them all.<br /></p><h3 id="heading-23">Tips</h3><ul><li><p>If you are not getting the results you expect from a tag, find other similar tags and include those as well. I've found that this model tends to spread its knowledge of a tag around to other related tags. So including more will increase your chances of getting what you want.</p></li><li><p>Using the negative "3d" does a good job of making the image more anime like if it starts veering too much into a rendered model look.</p></li><li><p><s>AbyssOrange does have a habit of putting nipples on bellies, try to avoid nipple tags when generating big bellies. use "navel" tags instead.</s></p><p>Rarely happens any more. Must have been a data issue</p></li><li><p>Ass related tags have a strong preference for back shots, try a low strength ControlNet pose to correct this, or try one or more of these in the negatives "ass focus, from behind, looking back". The new "ass visible from front" tag can help too.</p></li></ul><p></p><h3 id="heading-24">Extra</h3><p><br />This model took me months of failures and plenty of lessons learned (hence v4)! If LoCon LoRA picks up in popularity, I may retrain it in the near future. I would eventually like to train a few more image classifiers to improve certain tags, but all future dreams for now.</p><p>As usual I have no intention of monetizing any of my models. Enjoy the thickness!</p><p></p><h3 id="heading-25">Training Hurdles</h3><p><strong>-Tagging-</strong></p><p>The key to tagging a 200k dataset is to automate it all. Start with the wd-tagger (or similar danbooru tagger) to append some common tags on top of the tags scraped with the images from their source site. Then I trained a handful of image classifiers like breast size, breasts shape, innie/outie navel, directionality, etc..., and let those do the heavy lifting. Finally convert any similar tags into one single tag as described in the tag docs.</p><p>If only there there were a r-34 or e621 style tagger available.</p><p></p><p>I used this to train my image classifiers<br /><a target="_blank" rel="ugc" href="https://github.com/huggingface/transformers/tree/main/examples/pytorch/image-classification">https://github.com/huggingface/transformers/tree/main/examples/pytorch/image-classification</a></p><p></p><p><strong>-Poor Results-</strong></p><p>For a long time I was plagued with sub par results. I suspected maybe the data was just too low quality, but in the end it just ended up being poorly tagged images. Sites like r-34 tend to have too many tags describing an image like "big breasts, huge breasts, hyper breasts" all on the same image. This is not great for a model where you want to specify specific sizes. Using the classifiers I mentioned above I limited each image to a single size tag for each body part, and the results were night and day.</p><p></p><p><strong>-Tag Bleeding-</strong></p><p>An example of tag bleeding is using the tag "gigantic breasts", but you end up with everything being gigantic, breasts, ass, thighs. It's been an annoying problem, and the only (partial) solution that I have found is to segment the size tags for each body part. Like "huge ass", vs "size 200 breasts". This way they don't share the same "huge" size tag.</p><p>I trained a model earlier with this tagging scheme and it did work a little better, but there was still some tag bleeding. I think this is because you often have images where the character has both large breasts and a large ass in the same image, so both concepts end up bleeding into each other regardless.</p><p>The reason I chose not to segment the size tags was because it would make prompting more difficult since it deviates too much from the danbooru/r-34 tagging schemes.</p><p></p><p><strong>-Testing-</strong></p><p>In order to determine if a new model is better than the last, it's important to have some standard prompts that you can compare with. x/y plot is great for this. Just keep in mind that the seeds between models will be totally different, and you likely need to compare dozens of images at a time and not 1 to 1. It's also important to compare new models against the base model output to make sure what you are training is actually having an overall positive effect compared to the origin model.</p><p></p><p><strong>-Software/Hardware-</strong></p><p>The training was all done on a 3090 in an Ubuntu docker instance. The software was Kohya's trainer using the LoRA network and lots of patience.</p>