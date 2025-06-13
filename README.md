# 程序员做饭指南

[![build](https://github.com/Anduin2017/HowToCook/actions/workflows/build.yml/badge.svg)](https://github.com/Anduin2017/HowToCook/actions/workflows/build.yml)
[![License](https://img.shields.io/github/license/Anduin2017/HowToCook)](./LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/Anduin2017/HowToCook)](https://github.com/Anduin2017/HowToCook/graphs/contributors)
[![npm](https://img.shields.io/npm/v/how-to-cook)](https://www.npmjs.com/package/how-to-cook)
![Man hours](https://manhours.aiursoft.cn/r/github.com/anduin2017/howtocook.svg)
[![Docker](https://img.shields.io/badge/docker-latest-blue?logo=docker)](https://github.com/Anduin2017/HowToCook/pkgs/container/how-to-cook)
[![Join the AnduinOS Community on Revolt](https://img.shields.io/badge/Revolt-Join-fd6671?style=flat-square)](https://rvlt.gg/ndApqZEs)

最近宅在家做饭，作为程序员，我偶尔在网上找找菜谱和做法。但是这些菜谱往往写法千奇百怪，经常中间莫名出来一些材料。对于习惯了形式语言的程序员来说极其不友好。

所以，我计划自己搜寻菜谱并结合实际做菜的经验，准备用更清晰精准的描述来整理常见菜的做法，以方便程序员在家做饭。

同样，我希望它是一个由社区驱动和维护的开源项目，使更多人能够一起做一个有趣的仓库。所以非常欢迎大家贡献它~

## 本地部署

如果需要在本地部署菜谱 Web 服务，可以在安装 Docker 后运行下面命令：

```bash
docker pull ghcr.io/anduin2017/how-to-cook:latest
docker run -d -p 5000:5000 ghcr.io/anduin2017/how-to-cook:latest
```

如需下载 PDF 版本，可以在浏览器中访问 [/document.pdf](https://cook.aiursoft.cn/document.pdf)

## 如何贡献

针对发现的问题，直接修改并提交 Pull request 即可。

在写新菜谱时，请复制并修改已有的菜谱模板: [示例菜](https://github.com/Anduin2017/HowToCook/blob/master/dishes/template/%E7%A4%BA%E4%BE%8B%E8%8F%9C/%E7%A4%BA%E4%BE%8B%E8%8F%9C.md?plain=1)。

## 搭建环境

- [厨房准备](tips/厨房准备.md)
- [如何选择现在吃什么](tips/如何选择现在吃什么.md)
- [高压力锅](tips/learn/高压力锅.md)
- [空气炸锅](tips/learn/空气炸锅.md)
- [去腥](tips/learn/去腥.md)
- [食品安全](tips/learn/食品安全.md)
- [微波炉](tips/learn/微波炉.md)
- [学习焯水](tips/learn/学习焯水.md)
- [学习炒与煎](tips/learn/学习炒与煎.md)
- [学习凉拌](tips/learn/学习凉拌.md)
- [学习腌](tips/learn/学习腌.md)
- [学习蒸](tips/learn/学习蒸.md)
- [学习煮](tips/learn/学习煮.md)

## 菜谱

### 按难度索引

- [1 星难度](starsystem/1Star.md)
- [2 星难度](starsystem/2Star.md)
- [3 星难度](starsystem/3Star.md)
- [4 星难度](starsystem/4Star.md)
- [5 星难度](starsystem/5Star.md)

### 素菜

- [蚝油生菜](dishes/vegetable_dish/蚝油生菜.md)
- [红烧冬瓜](dishes/vegetable_dish/红烧冬瓜.md)
- [蒜蓉蚝油西兰花](dishes/vegetable_dish/蒜蓉蚝油西兰花.md)

### 荤菜

- [蒸肉沫](dishes/meat_dish/蒸肉沫.md)

### 水产


### 早餐


### 主食


### 半成品加工


### 汤与粥


### 饮料


### 酱料和其它材料

- [油泼辣子](dishes/condiment/油泼辣子/油泼辣子.md)

### 甜品


## 进阶知识学习

如果你已经做了许多上面的菜，对于厨艺已经入门，并且想学习更加高深的烹饪技巧，请继续阅读下面的内容：

- [辅料技巧](tips/advanced/辅料技巧.md)
- [高级专业术语](tips/advanced/高级专业术语.md)
- [糖色的炒制](tips/advanced/糖色的炒制.md)
- [油温判断技巧](tips/advanced/油温判断技巧.md)

## 衍生作品推荐

- [HowToCook-mcp 让 AI 助手变身私人大厨，为你的一日三餐出谋划策](https://github.com/worryzyy/HowToCook-mcp)
- [HowToCook-py-mcp 让 AI 助手变身私人大厨，为你的一日三餐出谋划策 (Python)](https://github.com/DusKing1/howtocook-py-mcp)
