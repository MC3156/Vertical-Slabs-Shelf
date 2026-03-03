# Vertical Slabs Shelf

**Resourcepack for Java 1.21.9+**.

**LINK👉** [![Github](https://img.shields.io/badge/github-VSS-purple?logo=github)](https://github.com/MC3156/Vertical-Slabs-Shelf "Visit this resourcepack on Github (*OvO*)") [![Modrinth](https://img.shields.io/badge/Modrinth-dark_green)](https://modrinth.com/resourcepack/vertical-slabs-shelf "Visit this resourcepack on Modtinth (*OvO*)") [![CurseForge](https://img.shields.io/badge/CurseForge-orange)](https://www.curseforge.com/minecraft/texture-packs/vertical-slabs-shelf "Visit this resourcepack on CurseForge (*OvO*)") [![PlanetMinecraft](https://img.shields.io/badge/PlanetMinecraft-blue)](https://www.planetminecraft.com/texture-pack/vertical-slabs-shelf/ "Visit this resourcepack on PlanetMinecraft (*OvO*)")


## Using & 使用方法

![VerticalSlabsShelfGIF](https://cdn.modrinth.com/data/cached_images/e90b65e7a8f183b24a627355930be96c37cbe242.gif)

**1** Place half slabs into shelves to simulate vertical half slabs.

**2** In Creative mode, use the `Ctrl + Select`(The default is the middle mouse button) shortcut to get shelves with half slab data, making it easier to place vertical half slabs.

**3** This **resourcepack** is compatible with half slabs from other resourcepacks and mods. It's recommended to set this resource pack’s priority to the highest.

**1** 将台阶方块嵌入展示架中实现模拟竖半砖；

**2** 在创造模式使用"Ctrl+选中"按键获得含有半砖数据的展示架，可以更方便的放置竖半砖；

**3** 该资源包兼容其他资源包和模组的半砖，请尽量将该资源包的优先级调到最高。

### 实现原理

@.物品在展示架的模型可以修改参数调整，相比于基于实体的方案，该方案优势在于方块数据便于保存，性能开销小，相比mod类作品，资源包可随时装卸，且兼容性好，适用于Java 1.21.9+；

1.为台阶类方块的父模型添加调整展示架display参数；

2.修改elements参数和其uv解决问题叠加闪烁问题。

### 灵感来源

刷小破站视频和去主流模组网站获取相关资源学习。AwA~
