## chengxiaoCC 程潇
### 一、模型概述

- 标签：`celebrity`
- 下载数：4312
- 收藏人数：874
- 评论人数：44
- 评分人数：8
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] chengxiaoCC：V1.0

- 统计数据
  - 发布时间：2023-02-15T14:55:53.193Z
  - 原始模型：SD 1.5
  - 下载数：4312
  - 评分人数：8
  - 评分：5
- 下载地址
  - [chengxiaoCC.safetensors](https://civitai.com/api/download/models/10747)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2343f46b-f6fe-4d9e-214b-fe2f42569800/width=450/104055.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/924737c5-8342-4341-f6d7-3f5db3ca5800/width=450/104058.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/65c5ff18-f3dd-4a39-b091-b106efbe6a00/width=450/104057.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/706575ad-ac90-4672-2303-8c294d505700/width=450/104056.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>基本参数</h1><p>训练素材：78张头像，训练步数：7800，训练载体：kohya，基础模型：SD1.5</p><h1>LORA用法（很重要）</h1><p>lora的<strong>主要用法</strong>是在<strong>img2img的inpaint</strong>里，去修改原图像的头。</p><p><strong>不要在txt2img</strong>里面直接用lora。</p><p>因为人物肖像的lora，<strong>训练素材</strong>都是<strong>怼脸的大头照</strong>，你直接在txt2img里面用，所生成的图片都是<strong>大头照</strong>。哪怕你在prompt里面输入了 full body，出来的图片还是<strong>大头照</strong>。当然，你可以降低LORA的权重，就能生成带身体的图片，但是，这样一来，<strong>人物的样貌就变了</strong>，这不是我们想要的结果。</p><p><strong>下面是简单的教程。</strong></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7b74d270-71c7-41d5-5dd0-41d925334600/width=525" /><p>这是一张AI生成的正常比例的人物肖像，我们把这张图转到img2img里，在inpaint里给人物的脸部画上蒙版，输入chengxiaoCC的LORA</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d1078dc8-e60f-4f22-be76-d039566fe900/width=525" /><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bc915e2c-4973-47b5-04ad-6f9abe2fc500/width=525" /><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1de3c8b2-f11b-4d82-3cb4-07c4fda34b00/width=525" /><p>这样，我们就得到了一张带有程潇脸部的半身照。</p><p>这么做的好处是，你可以在txt2img里面，专心制作人物的<strong>衣服，动作，场景。</strong></p><p>最后，再单独用肖像lora，在img2img里的inpaint里进行<strong>最后的加工</strong>。更加灵活，成品率更高。</p><p>值得注意的是，img2img里面的prompt，和Sampling method,要保持和txt2txt里的一样，这样做，可以保证替换的人物脸部跟原图光影统一。</p><h1>声明</h1><ol><li><p>本人提供的训练素材，仅仅用于学习和交流，分享AI绘画经验。</p></li><li><p>不要用于商业用途，不要用于色情制作，不要大规模传播。</p></li><li><p>如果某些人执意要将公众人物的肖像用于情色素材，请不要著名此LORA的出处，非常感谢。</p></li></ol>