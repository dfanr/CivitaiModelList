## PixelNet
### 一、模型概述

- 标签：`pixel art`, `pixel`, `controlnet`, `pixelart`, `tool`
- 下载数：0
- 收藏人数：0
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v0.0-experimental

- 统计数据
  - 发布时间：2023-07-03T21:17:54.385Z
  - 原始模型：SD 1.5
  - 下载数：0
  - 评分人数：0
  - 评分：0
- 下载地址
  - [pixelnet_v00Experimental.yaml](https://civitai.com/api/download/models/109652?type=Config&format=Other)
  - [pixelnet_v00Experimental.safetensors](https://civitai.com/api/download/models/109652)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6a82fde4-22ce-474c-a80d-25894d5faaee/width=450/1395519.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e4d7cbc6-58c5-4c9d-8ee2-a48266617bc0/width=450/1395524.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c25db53c-1d01-467c-a2d7-6bb5e06fe47b/width=450/1395522.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d0c98800-336c-4fe1-acb0-7838d6da72fa/width=450/1395527.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<pre><code>https://huggingface.co/thomaseding/pixelnet

--- license: creativeml-openrail-m ---

# PixelNet (Thomas Eding)

### About:

PixelNet is a ControlNet model for Stable Diffusion.

It takes a checkerboard image as input, which is used to control where logical pixels are to be placed.

This is currently an experimental proof of concept. I trained this using on around 2000 pixel-art/pixelated images that I generated using Stable Diffusion (with a lot of cleanup and manual curation). The model is not very good, but it does work on grid sizes of about a max of 64 checker "pixels" for square generations. I did find that using 128x64 pattern still seemed to work moderately well for a 1024x512 image.

The model works best with the "Balanced" ControlNet setting. Try using a "Control Weight" of 1 or a little higher.

"ControlNet Is More Important" seems to require a heavy "Control Weight" setting to have an effect. Try using a "Control Weight" of 2.

Smaller checker grids tend to perform worse (e.g. 5x5 vs a 32x32)

### Usage:

To install, copy the `.safetensors` and `.yaml` files to your Automatic1111 ControlNet extension's model directory (e.g. `stable-diffusion-webui.extensions/sd-webui-controlnet/models`). Completely restart the Automatic1111 server after doing this and then refresh the web page.

There is no preprocessor. Instead, supply a black and white checkerboard image as the control input. Examples are in the `example-control-images` directory of this repository. (https://huggingface.co/thomaseding/pixelnet/tree/main/example-control-images)

The script `gen_checker.py` can be used to generate checkerboard images of arbitrary sizes. (https://huggingface.co/thomaseding/pixelnet/blob/main/gen_checker.py) Example: `python gen_checker.py --upscale-dims 512x512 --output-file 70x70.png --dims 70x70`

![grid5x5](https://huggingface.co/thomaseding/pixelnet/resolve/main/example-control-images/5x5.png)

![grid16x16](https://huggingface.co/thomaseding/pixelnet/resolve/main/example-control-images/16x16.png)

### FAQ:

Q: Why is this needed? Can't I use a post-processor to downscale the image?

A: From my experience SD has a hard time creating genuine pixel art (even with dedicated base models and loras), where it has a mismatch of logical pixel sizes, smooth curves, etc. What appears to be a straight line at a glance, might bend around. This can cause post-processors to create artifacts based on quantization rounding a pixel to a position one pixel off in some direction. This model is intended to help fix that.

Q: Should I use this model with a post-processor?

A: Yes, I still recommend you do post-processing to clean up the image. This model is not perfect and will still have artifacts. Note that none of the sample output images are post-processed; they are raw outputs from the model.

Q: Will there be a better trained model of this in the future?

A: I hope so. I will need to curate a much larger and higher-quality dataset, which might take me a long time. Regardless, I plan on making the control more faithful to the control image and to generalize to more than just checkerboards.

### Sample Outputs:

![sample1](https://huggingface.co/thomaseding/pixelnet/resolve/main/example-outputs/20230703102437-64a98cdc-3566720748-1259.png)

![sample2](https://huggingface.co/thomaseding/pixelnet/resolve/main/example-outputs/20230703091940-d7d11138-2383291623-524.png

![sample3](https://huggingface.co/thomaseding/pixelnet/resolve/main/example-outputs/20230703083502-89f714b7-2908299568-164.png)</code></pre>