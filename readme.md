# Civitai模型离线数据

## 项目概述

在civitai（C站）找stable diffusion模型的时候，个人感觉筛选的效率太低，所以调用C站官方提供的api，将所有模型数据通过脚本批量保存到了本地，包括json格式（原始数据）和markdown格式（对数据进行了排版和可视化）。文件夹结构和文件命名比较规整，便于快速查找所需模型。

快速链接：

- [Checkpoint模型](./models/Checkpoint/normal/markdown)
- [TextualInversion模型](./models/TextualInversion/normal/markdown)
- [Hypernetwork模型](./models/Hypernetwork/normal/markdown)
- [AestheticGradient模型](./models/AestheticGradient/normal/markdown)
- [LORA模型](./models/LORA/normal/markdown)
- [Controlnet模型](./models/Controlnet/normal/markdown)
- [Poses模型](./models/Poses/normal/markdown)

特点：

- 数据最近更新时间：2023年7月4日
- 包含['Checkpoint', 'TextualInversion', 'Hypernetwork', 'AestheticGradient', 'LORA', 'Controlnet', 'Poses']这七大类的模型
- 每类模型按照nsfw标志位分了两个子文件夹：normal和nsfw
  ![文件夹结构](<images/截屏2023-07-04 23.14.17.png>)
- 每个子文件夹包含两类文件：
  - 第一类json文件，来自api返回的原始数据，大部分人用不到这类数据
  - 第二类markdown文件，按照下载量排序，用于本地可视化查看各个模型的信息，随便打开一个模型对应的markdown文件，排版格式统一，预览图和模型下载地址一目了然
  ![markdown文件命名和排序](<images/截屏2023-07-04 23.14.35.png>)
- 每个markdown均包含：
  - 基本数据：例如标签、下载量和评分等
  - 各个版本的模型的下载地址和预览图（每个版本最多只显示4张图）
  - 原始api返回的模型详情描述
  - 例如：
  ![markdown文件样例](<images/截屏2023-07-04 23.23.56.png>)

## 使用说明

- nsfw文件夹下对应的文件大概率包含敏感数据，请谨慎使用
- 通过markdown文件中的下载链接，下载对应模型，然后放到stable diffusion webui对应的目录下即可正常使用
- markdown文件中的图像可能需要科学上网才能正常显示，打开的markdown文件较多时图像可能加载缓慢

## 声明

- 所有数据全部来自于civitai官方api返回的数据
- 仅供图像生成相关的学习和交流之用
- 此仓库仅包含整理好的数据，不包含数据采集的脚本，原因是：担心运行脚本的人太多，给civitai的服务器带来严重的访问压力