## MaiMix
### 一、模型概述

- 标签：`anime`, `sexy`, `female`, `art`, `mix`, `base model`, `portrait`, `model`, `illustration`, `girls`
- 下载数：32
- 收藏人数：45
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] MaiMixHard

- 统计数据
  - 发布时间：2023-07-03T10:46:17.385Z
  - 原始模型：SD 1.5
  - 下载数：2
  - 评分人数：0
  - 评分：0
- 下载地址
  - [maimix_hard.safetensors](https://civitai.com/api/download/models/109331)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6c2ae51e-6443-4c16-8add-9489a935d2f4/width=450/1388047.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f3d31849-50e9-4d8f-bcce-1347c57f6a08/width=450/1388048.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e1358d18-5fc5-485a-915f-c345333e1763/width=450/1388051.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/695c78b0-55fd-41ed-b7c5-e62f385da6e7/width=450/1388049.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] MaiMixSoft

- 统计数据
  - 发布时间：2023-07-03T09:52:47.167Z
  - 原始模型：SD 1.5
  - 下载数：3
  - 评分人数：0
  - 评分：0
- 下载地址
  - [maimix_soft.safetensors](https://civitai.com/api/download/models/109206)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/45322bf1-3c36-4e51-99d3-835b0b3c6532/width=450/1385647.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/915433ea-ab88-4ff2-9fd6-22979c7746c3/width=450/1403085.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6a1d460c-78b1-4fb5-91b0-8a6936e41f51/width=450/1385650.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/038d172c-a9ea-43e9-a633-3c7ab642fd59/width=450/1385649.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] MaiMixBeta

- 统计数据
  - 发布时间：2023-07-03T09:52:47.167Z
  - 原始模型：SD 1.5
  - 下载数：27
  - 评分人数：0
  - 评分：0
- 下载地址
  - [maimix_beta.safetensors](https://civitai.com/api/download/models/109091)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/312c5e36-f289-4db6-b590-d0e08e752b23/width=450/1383384.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e7acbd29-7ab4-4aea-ae76-f8e7cd5d249f/width=450/1383383.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d45a6ef8-72ea-4551-bf93-9f18a68cf41a/width=450/1383387.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5a423b7f-f6ac-4f41-bced-78b1928755eb/width=450/1383386.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>MaiMix</strong> is an anime illustration style model which aims to produce high quality art with little prompting at low steps but even greater results with more complex prompts.</p><p></p><p>All sample images have been generated without the use of textual inversion/negative embeddings and VAE at 512x768 resolution (no upscaling) with no extra features to display the strength of the model. <strong>For real world use</strong> it is recommended that <strong>ClearVAE</strong> and <strong>EasyNegative</strong> is used for even higher quality results. Hires.fix and/or <a target="_blank" rel="ugc" href="https://github.com/Bing-su/adetailer">Adetailer</a> is recommended for images where the character is more distant for better results.</p><p></p><p><strong>MaiMixHard</strong> is an updated version based on a line art illustration style.</p><p><strong>MaiMixSoft</strong> is an updated version based on a brush stroke illustration style.</p><p><strong>MaiMixBeta</strong> is the original generalist MaiMix with an illustration style closer to the base model used.</p><p></p><p>NSFW is supported but NSFW LoRA's may be needed for better results.</p><p></p><p><strong>Recommended Settings (VAE Not Baked):</strong></p><p><strong>Sampler:</strong> Euler or DPM++ 2M Karras (25-50 steps)<br /><strong>CFG Scale:</strong> 4 to 11 (7.5 preferred for balanced outputs)<br /><strong>Clip Skip:</strong> 2 for more variation but model works well with 1 as well.<br /><strong>Negatives (if not using EasyNegative):</strong> <span style="color:rgba(255, 255, 255, 0.9)">((low quality!!, worst quality!!, monochrome noir)), AND bad anatomy, AND hideous extra bad hands, AND auxiliary missing malformed fingers, AND unrefined duplicate body parts, AND fused overlap unseparated conjoined, AND (strabismus, (red eyes)), AND fused merged additional arms, AND baby face, AND child, AND loli, AND childlike, AND young, AND (((corner text!, watermark!, logo!, signature!, words!, letters!, content!, artist name!, trademark!, inscription!, symbol!, hieroglyph!, glyphs!, type!, scribble!))), face tattoos, face paint, scars, misplaced multiple boobs, inaccurate nipples, Asian face, transsexual, hermaphrodite, deformed malformed, twisted, mutilated, blur, haze, censor</span></p><p></p><p><strong>Extreme Wildcard Prompt Example (Over-Prompting):</strong></p><p><span style="color:rgba(255, 255, 255, 0.9)">professional|commercial|finished colorful|pristine|dark|saintly reflective|iridescent|crystalline|textured polychromatic|immersive|transcendent|cinematic|surreal|phantasmagoria intricate|delicate|exquisite detail floral|snowflake|sunset tattooed fashionista|executive|goth|student|swordswoman|punk|seraph angled|dynamic|focused full portrait masterpiece CGI by wlop|WENJR|ufotable AND attractive|seductive|trendy|beautiful|mature and womanly|alluring|proportional|motherly|subservient|homely|casual|erotic with jewel-like color contacts and ((((salon dyed complex hair wearing a sleeveless|simple low-cut sportswear belt kimono|dress uniform jacket)))) AND contemporary|Desi|Arabian|Oriental|European|multinational|cybernetic traditional|elegant|sophisticated fractal|endless|entrancing|infinite|perpetual|abstract mural natural|ambient|moody ancient|opulent|fancy cityscape|dusk fantasy beauty showpiece outline BREAK aesthetic|pleasing|artistic|tasteful official 8K HDR anime|photorealistic outdoors|oceanic|scenic|picteresque depth|layered|dimensional landscape|background|theme|scenery|silhouette original film grain polaroid style AND enhanced|featured|complete|final|enriched rainbow|pastel|neon|psychedelic continuous|flowing|curvaceous|diffuse|eternal encased|juxtaposed|overlap underwater bubble jellyfish butterfly bloom concept AND absurdres ultra high quality sharp|extravagant|defined|precise|crisp resolution|clarity magical|cryptic|arcane mystic|majestic|dramatic|action cosmic energy modern|excessivism|analytical perfect|fantastic|breathtaking award|prize winning digital movie|blockbuster game release coverart wallpaper poster illustration image with hand-drawn thick|distinct brush|ink|watercolor stroke|impasto edge line shift|shimmering volumetric lighting using Unity|Unreal|Octane Engine|Render trending on Pixiv|Instagram|Artstation</span></p><p></p><p><strong>Model Design Aim:</strong></p><p>MaiMix is designed as a proof-of-concept weight merge model using LoRA's only to further train and fine-tune models to produce new model characteristics and improvements over base models. This newer model is also likely to produce better results when checkpoint merged with other models - although this was not tested.</p><p></p><p><strong>Special Thanks To The Creators of:</strong></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/Lucetepolis/MareColoris">MareColoris</a> (used as the base model) and the creators of the following LoRA that are part of the Civitai community:</p><p>Japanese scene_20230609163753-000018.safetensors, [LoRa] Shoal 錦鱗 Concept (With multires noise version).safetensors, BG2_dpep4+silicon29dim64.safetensors, butterfly.safetensors, Concept_scenery_background.safetensors, crystal_v1.safetensors, improve_backgrounds.safetensors, Pyramid lora_Ghibli_n3.safetensors, AMechaSSS[color_theme,mecha musume, mechanical parts,robot joints,headgear].safetensors, bigeye.safetensors, Cube-10.safetensors, detailed_eye-10.safetensors, fate_kyrielight-10.safetensors, FBH3-000005.safetensors, kitagawa_marin_v1-1.safetensors, Loraeyes_V1.safetensors, LR-000007BB.safetensors, mathayom_uniform16.safetensors, matWomen_v2.safetensors, minamoto_no_raikou_v1.safetensors, QuickHandV2.safetensors, tattoo_lora01.safetensors, 眼睛双eyes.safetensors, add_detail.safetensors, bad_pic.safetensors, loraH(DiffLoRA)_FaceShadowTweaker_v1_dim4.safetensors, more_details.safetensors, SilvermoonMix2.safetensors, tangbohu-detailmaker_v2.5.safetensors, XenoDetailer.safetensors, AI_Lora-05.safetensors, colorful world_20230606112956-000017.safetensors, Cutesy4-10.safetensors, doukou.safetensors, midjourney_20230624181825.safetensors, style_Aobeni.safetensors, style_TOKKYU.safetensors, tachi-e.safetensors, wlop_offset.safetensors, Yoneyama Mai_v2.safetensors, 3DMM_V11.safetensors, add_sharpness.safetensors, epiNoiseoffset_v2-pynoise.safetensors, FilmVelvia2.safetensors, flat2.safetensors, hipoly_3dcg_v7-epoch-000012.safetensors, saturation.safetensors, tangbohu-line_1.0.safetensors, thickline_fp16.safetensors, LAS.safetensors, GachaSplash4.safetensors, vibrantProj-07.safetensors</p><p></p>