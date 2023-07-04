## Old Newspaper Style
### 一、模型概述

- 标签：`vintage`, `architecture`, `style`, `newspaper`, `lora`, `oldstyle`
- 下载数：2440
- 收藏人数：591
- 评论人数：11
- 评分人数：6
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-25T11:21:35.443Z
  - 原始模型：SD 1.5
  - 下载数：2440
  - 评分人数：6
  - 评分：5
- 下载地址
  - [npzw-05.safetensors](https://civitai.com/api/download/models/54932)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6408e4a2-6930-448c-50ee-2bf7ba075200/width=450/594366.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6022d208-8110-41ce-ab4b-6ae046eef100/width=450/594373.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c0ccff1c-d54b-44d7-5a78-89a31fdf1700/width=450/594367.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6cb33bb9-e270-4be6-8068-8c575a607800/width=450/594364.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is a style LoRA that will give your images a old newspaper front page look. Header on top, text around the frame, where your object/subject will be inside the frame or with text accurately around your object/subject.</p><p></p><p>I want to thank <span data-type="mention" class="mantine-1yiar0p" data-id="mention:176954" data-label="Hollowstrawberry">@Hollowstrawberry</span> for the collab he made. And also <span data-type="mention" class="mantine-1yiar0p" data-id="mention:15552" data-label="rockerBOO">@rockerBOO</span>, <span data-type="mention" class="mantine-1yiar0p" data-id="mention:270540" data-label="ChameleonAI">@ChameleonAI</span>, <span data-type="mention" class="mantine-1yiar0p" data-id="mention:381188" data-label="zykurv">@zykurv</span>, <span data-type="mention" class="mantine-1yiar0p" data-id="mention:545757" data-label="IndolentCat">@IndolentCat</span> for their tips and tricks! Please check their creations as well!</p><p></p><p><strong>The reviews and feedback will be very valuable for me.</strong></p><p></p><h3><strong>Trigger word:</strong></h3><p></p><p>The main trigger word for style is <code>npzw</code>. You will additionally need to add to prompt the next words: <code>(text)</code>, <code>monochrome</code>, or <code>sepia</code>. Keep in mind that depending on the model you using you may need to adjust weights of those words. Most often for anime models you want like: <code>(npzw:1.1)</code>, <code>(text:1.1)</code> at least. Adjust that depending on your results.</p><p></p><p>And <strong>most important</strong> remove <code>text</code>, <code>monochrome</code>, <code>sepia</code>, <code>greyscale</code> from <strong><u>your negative prompt</u></strong>. Because a lot of people using those words in negative prompt.</p><p></p><ul><li><p><strong>Avoid using <u>colors</u> other than black or white in prompts.</strong></p></li></ul><p></p><p><strong>Red eyes</strong> will give your image a hue that will ruin the purpose of this style in my opinion. However feel free to do so if you want. Also if <code>1girl</code> / <code>1boy</code> doesn't work for your character LoRA try using <code>woman</code> / <code>man</code> instead.</p><p></p><p>Use additional modifiers to frame the body of person: <code>full body</code>, <code>upper body</code>, <code>cowboy shot</code>, <code>portrait</code></p><p></p><h3><strong>Weights:</strong></h3><p></p><p>This LoRA was trained on SD1.5. So it works with weight :1 absolutely fine. Adjust it if needed when combining with other LoRAs.</p><p></p><p>I'm not sure what name LoRA will get on downloading, so please make sure you using <strong>the proper name in prompt of the file that you downloaded</strong> if you going to copy prompts from previews.</p><p></p><h3>Negative embeddings:</h3><p>I think i used only one negative embedding during testing:</p><ul><li><p>AuroraNegative, you can find download link for it in description on this page: <a target="_blank" rel="ugc" href="https://civitai.com/models/40199/aurora">https://civitai.com/models/40199/aurora</a></p></li></ul>