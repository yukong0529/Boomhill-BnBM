<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/brand/replay-logo-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/brand/replay-logo-light.png">
  <img alt="REPLAY" src="assets/brand/replay-logo-light.png" width="240">
</picture>

# 泡泡堂 M（Crazy Arcade BnB M）

一款手机平台上的水球动作游戏。

> **警告：仅限获准参加 Lab Track 的创作者使用。** 未经批准的使用一律禁止，不因其属于内部制作、学习、研究、个人学习或商业用途而例外。

> 使用条件以仓库根目录中的 [LICENSE](LICENSE) 和 [NOTICE](NOTICE) 为准。查看器：[在查看器中浏览本游戏](https://nexon-replay.github.io/Boomhill/#/g/bnb-mobile)。其他游戏请访问[资源中心](https://nexon-replay.github.io/Boomhill/)。

## 目录

| 目录 | 内容 |
|---|---|
| `2d/` | 2D 图像，按资源包分别存放；图像为 PNG，多帧图像使用精灵图集，并附有图集 JSON |
| `3d/` | 3D 预览模型，按类别分别存放；每个模型包含 `<id>.glb` 模型、`<id>.webp` 缩略图和 `<id>.json` 附加信息 |
| `3d/_shared/` | 多个模型共用的纹理、表情图和组装部件（文件名为原始名称_短哈希） |
| `2d/manifest.json`、`3d/manifest.json` | 记录每个文件的大小和 SHA-256 |

## 2D 图像

| 资源包 | 内容 | 图像数 | 帧数 |
|---|---|---:|---:|
| `010_ui` | UI | 2,198 | 2,198 |
| `020_icon` | 图标 | 1,643 | 1,643 |
| `030_map` | 地图 | 835 | 835 |
| `040_monster` | 怪物模式 | 419 | 419 |
| `050_effect` | 特效 | 477 | 477 |
| | 合计 | 5,572 | 5,572 |

## 3D 预览模型

这些模型可直接在浏览器中预览（压缩后的 GLB、纹理最长边为 512 px，角色仅包含基础动作）。如需用于游戏制作或编辑，请使用下方的原始 ZIP 文件。

| 目录 | 类别 | 模型数 |
|---|---|---:|
| `3d/010_character/` | 角色 | 11 |
| `3d/020_costume/` | 服装 | 221 |
| `3d/030_vehicle/` | 载具 | 10 |
| `3d/040_pet/` | 宠物 | 10 |
| `3d/050_monster/` | 怪物 | 40 |
| `3d/060_accessory/` | 配饰 | 528 |
| | 合计 | 820 |

## 3D 原始 ZIP

原始文件按类别打包，包含未压缩的 GLB、原始分辨率的 PNG 纹理和完整动作。请从仓库的 Releases 下载。

| 类别 | 文件 | 大小 | 模型数 |
|---|---|---:|---:|
| 配饰 | [bnb-mobile-3d-accessory.zip](https://github.com/NEXON-REPLAY/Boomhill-BnBM/releases/download/3d-originals-v1/bnb-mobile-3d-accessory.zip) | 7.7 MB | 528 |
| 角色 | [bnb-mobile-3d-character.zip](https://github.com/NEXON-REPLAY/Boomhill-BnBM/releases/download/3d-originals-v1/bnb-mobile-3d-character.zip) | 10.7 MB | 11 |
| 服装 | [bnb-mobile-3d-costume.zip](https://github.com/NEXON-REPLAY/Boomhill-BnBM/releases/download/3d-originals-v1/bnb-mobile-3d-costume.zip) | 49.5 MB | 221 |
| 怪物 | [bnb-mobile-3d-monster.zip](https://github.com/NEXON-REPLAY/Boomhill-BnBM/releases/download/3d-originals-v1/bnb-mobile-3d-monster.zip) | 3.5 MB | 40 |
| 宠物 | [bnb-mobile-3d-pet.zip](https://github.com/NEXON-REPLAY/Boomhill-BnBM/releases/download/3d-originals-v1/bnb-mobile-3d-pet.zip) | 0.7 MB | 10 |
| 载具 | [bnb-mobile-3d-vehicle.zip](https://github.com/NEXON-REPLAY/Boomhill-BnBM/releases/download/3d-originals-v1/bnb-mobile-3d-vehicle.zip) | 1.1 MB | 10 |

文件格式见[资源中心仓库的 docs/format.md](https://github.com/NEXON-REPLAY/Boomhill/blob/main/docs/format.md)，使用方法见[资料指南](https://nexon-replay.github.io/Boomhill/guide.html)。
