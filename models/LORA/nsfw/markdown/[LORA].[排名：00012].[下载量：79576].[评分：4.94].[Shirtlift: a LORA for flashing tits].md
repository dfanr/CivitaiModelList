## Shirtlift: a LORA for flashing tits
### 一、模型概述

- 标签：`poses`, `flashing`, `breasts`
- 下载数：79576
- 收藏人数：7909
- 评论人数：74
- 评分人数：127
- 评分：4.94

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Shirtliftv1

- 统计数据
  - 发布时间：2023-02-15T19:15:13.542Z
  - 原始模型：SD 1.5
  - 下载数：79576
  - 评分人数：127
  - 评分：4.94
- 下载地址
  - [shirtliftv1.safetensors](https://civitai.com/api/download/models/7870)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c701137f-096d-4710-8a8e-f175b9624300/width=450/74073.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b5f391c9-34db-4ed7-9e9d-36f8ebb0ad00/width=450/74072.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/88ab1829-f708-49b9-0ac7-4b11d1237a00/width=450/74071.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6f956c16-b86a-4b55-62fa-b0e41d321b00/width=450/74070.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>SEQUEL OUT NOW: <a rel="ugc" href="https://civitai.com/models/8631">Skirtlift</a> </p><p>I was having a hard time prompting a woman lifting her shirt, so I made this LORA. It also works for men.</p><p>Sample images made with the model <a target="_blank" rel="ugc" href="https://civitai.com/models/5935/liberty">Liberty</a>.</p><p></p><p>EDIT: some people asked how I made it. Here's a rough guide:</p><p></p><p><strong>Workflow</strong>:</p><p>1. Scour the interweb for pictures that represent the theme (women pulling their shirts up). Try to get a range of bodytypes/outfits/locations (while keeping in mind that they need to still have enough of a consistent theme for the AI pick up on what's being trained)</p><p>2. Crop and tag images. It's better to crop manually, especially with smaller datasets, but I had over 100 images so I automated it and just deleted the bad crops. (Many tools available for this. I think I used the <a target="_blank" rel="ugc" href="https://github.com/d8ahazard/sd_smartprocess">Smart Process extension for Automatic1111</a>).</p><p>2a. Cut the tags that represent the theme ('flashing,' 'pulling back shirt,' etc.), replace with a universal tag ('shirtlift')</p><p>2b. Fix incorrect tags</p><p>3. Run a first LORA training (I used the <a target="_blank" rel="ugc" href="https://colab.research.google.com/github/Linaqruf/kohya-trainer/blob/main/kohya-LoRA-finetuner.ipynb#scrollTo=gPgBR3KM6E-Z">Kohya LoRA Fine-Tuning Notebook by Linaqruf</a>).</p><p>4. Test it with an uncomplicated prompt and see what's not working:</p><p>4a. Is it not grasping the theme? Cut images that are too much of a variation on the theme (here it was mostly shots where the shirt was too bunched up to for the AI to 'read' it as a shirt, and shots where other things were going on with the person's hands)</p><p>4b. Is it reproducing aspects that aren't essential to the theme? Cut some of the images that over-represent those aspects in the dataset <strong>and/or</strong> describe those aspects in the caption since the AI might be assuming they're part of the universal tag. (Here it was forcing some of the same facial features or bodytypes)</p><p>4c. Is it just being wonky in some indescribable way? Change the training settings. (This is still trial and error for me but there are some guides out there)</p><p>4d. Repeat step 3 with those changes</p><p>5. Repeat step 4 using more complicated prompts to see if it can carry the theme over to different styles and situations that weren't represented in the dataset.</p><p>5a. If it's having trouble reproducing something you really want, try to find examples of that thing to add it to the dataset.</p><p>6. Repeat step 5 until satisfied.</p><p></p><p><strong>Settings</strong></p><p>I ended up with 104 images after a couple rounds of trimming out unhelpful ones.</p><p>The settings were mostly the defaults in <a target="_blank" rel="ugc" href="https://colab.research.google.com/github/Linaqruf/kohya-trainer/blob/main/kohya-LoRA-finetuner.ipynb#scrollTo=gPgBR3KM6E-Z">Linaqruf's Kohya Lora Fine-tuner notebook</a>, but with these changes:</p><p>Model: SD1.5</p><p>mixed_precision: FP16</p><p>Network Dim + Network_Alpha: 64</p><p>LR_Scheduler: cosine_with_restarts</p><p>Dataset_Repeats: 2</p><p>Clip_Skip: 1</p><p>I don't know how important some of them are; I'm still trial-and-erroring this thing.</p><p></p><p>For more info, <a target="_blank" rel="ugc" href="https://rentry.org/59xed3">this is a helpful guide I learned from</a>.</p>