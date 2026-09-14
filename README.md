# 鸡小坤 Chickun

> 我是鸡小坤 Chickun，练习时长两年半，喜欢唱、跳、Rap、篮球。

基于仓库中的 [design.png](design.png) 制作的 Codex 桌面宠物。保留银灰中分头、黄脸红腮、黑上衣白背带裤与橙色篮球的 3D 玩偶造型。

## 动画

- 原地运球、交替抖肩，中分发梢随节奏弹动。
- 带球起跳转身，经过背身姿势后转回落地。
- 左右篮球步伐、招手、待机眨眼、等待回应、失误反应、认真检查。
- 16 个顺时针视线方向。

详细动作设计见 [docs/animation-design.md](docs/animation-design.md)。

## 预览与文件

已完成生成与验收。打开 [preview.html](preview.html) 可切换动作、调速、逐帧检查，以及切换浅色、深色和透明网格背景。

| 文件 | 用途 |
| --- | --- |
| `design.png` | 用户提供的原始参考图 |
| `chickun/pet.json` | 双语名称、介绍与 Codex v2 配置 |
| `chickun/spritesheet.webp` | 1536 × 2288 透明图集，8 × 11 格 |
| `chickun.zip` | 可分发宠物包 |
| `chickun-run/qa/` | 动画预览、方向检查与验收报告 |

每格 192 × 208 像素，配置使用 `spriteVersionNumber: 2`。9 组常规动画共 57 帧，加 16 个视线姿势和 1 个中性静止帧；其余未使用的格保持透明。

## 安装

将宠物包中的 `chickun` 文件夹放入 `~/.codex/pets/`，确保 `pet.json` 和 `spritesheet.webp` 位于同一文件夹。现有同名宠物请先备份，再替换。当前宠物已经安装到本机 `~/.codex/pets/chickun/`，仓库宠物包、压缩包与安装图集的 SHA-256 完全一致。

这是基于用户参考图创作的个人趣味宠物。
