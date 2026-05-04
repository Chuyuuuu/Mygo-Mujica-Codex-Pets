# MyGO!!!!! / Ave Mujica Codex Pets

这是一组给 Codex 使用的 BanG Dream! 角色宠物合集，角色来自《BanG Dream! It's MyGO!!!!!》和《BanG Dream! Ave Mujica》。

仓库里的 `Release/` 目录放的是可以直接安装的版本，每个角色目录都包含：

- `pet.json`
- `spritesheet.webp`

## 角色

| 作品 | 角色 | 宠物目录 |
| --- | --- | --- |
| BanG Dream! It's MyGO!!!!! | Anon | `Release/anon` |
| BanG Dream! It's MyGO!!!!! | Tomori | `Release/tomori` |
| BanG Dream! It's MyGO!!!!! | Taki | `Release/taki` |
| BanG Dream! It's MyGO!!!!! | Soyo | `Release/soyo` |
| BanG Dream! It's MyGO!!!!! | Rana | `Release/rana` |
| BanG Dream! Ave Mujica | Saki | `Release/saki` |
| BanG Dream! Ave Mujica | Mutsumi | `Release/mutsumi` |
| BanG Dream! Ave Mujica | Uika | `Release/uika` |
| BanG Dream! Ave Mujica | Umiri | `Release/umiri` |
| BanG Dream! Ave Mujica | Nyamu | `Release/nyamu` |

## 安装方式一：手动安装

1. 从本仓库的 `Release/` 目录下载你想要的角色文件夹。
2. 把整个角色文件夹放到你的 Codex 宠物目录下。

目录结构应类似：

```text
<Codex 宠物目录>/<pet-id>
```

常见的 Codex 宠物目录位置：

```text
Unix/macOS/Linux: ~/.codex/pets
Windows: %USERPROFILE%\.codex\pets
```

如果你的 Codex 配置使用了自定义目录，请以实际配置为准。

例如安装 Tomori 后，目录结构应类似：

```text
<Codex 宠物目录>/tomori/pet.json
<Codex 宠物目录>/tomori/spritesheet.webp
```

然后重启 Codex，或在 Codex 里重新选择宠物。

## 安装方式二：让 Codex 帮你安装

把下面对应角色的 prompt 复制给 Codex 即可。

### Anon

```text
请在临时目录 git clone https://github.com/Chuyuuuu/Mygo-Mujica-Codex-Pets.git，然后把 Release/anon 放进 Codex 宠物目录（Unix/macOS/Linux 通常是 ~/.codex/pets，Windows 通常是 %USERPROFILE%\.codex\pets）。
```

### Tomori

```text
请在临时目录 git clone https://github.com/Chuyuuuu/Mygo-Mujica-Codex-Pets.git，然后把 Release/tomori 放进 Codex 宠物目录（Unix/macOS/Linux 通常是 ~/.codex/pets，Windows 通常是 %USERPROFILE%\.codex\pets）。
```

### Taki

```text
请在临时目录 git clone https://github.com/Chuyuuuu/Mygo-Mujica-Codex-Pets.git，然后把 Release/taki 放进 Codex 宠物目录（Unix/macOS/Linux 通常是 ~/.codex/pets，Windows 通常是 %USERPROFILE%\.codex\pets）。
```

### Soyo

```text
请在临时目录 git clone https://github.com/Chuyuuuu/Mygo-Mujica-Codex-Pets.git，然后把 Release/soyo 放进 Codex 宠物目录（Unix/macOS/Linux 通常是 ~/.codex/pets，Windows 通常是 %USERPROFILE%\.codex\pets）。
```

### Rana

```text
请在临时目录 git clone https://github.com/Chuyuuuu/Mygo-Mujica-Codex-Pets.git，然后把 Release/rana 放进 Codex 宠物目录（Unix/macOS/Linux 通常是 ~/.codex/pets，Windows 通常是 %USERPROFILE%\.codex\pets）。
```

### Saki

```text
请在临时目录 git clone https://github.com/Chuyuuuu/Mygo-Mujica-Codex-Pets.git，然后把 Release/saki 放进 Codex 宠物目录（Unix/macOS/Linux 通常是 ~/.codex/pets，Windows 通常是 %USERPROFILE%\.codex\pets）。
```

### Mutsumi

```text
请在临时目录 git clone https://github.com/Chuyuuuu/Mygo-Mujica-Codex-Pets.git，然后把 Release/mutsumi 放进 Codex 宠物目录（Unix/macOS/Linux 通常是 ~/.codex/pets，Windows 通常是 %USERPROFILE%\.codex\pets）。
```

### Uika

```text
请在临时目录 git clone https://github.com/Chuyuuuu/Mygo-Mujica-Codex-Pets.git，然后把 Release/uika 放进 Codex 宠物目录（Unix/macOS/Linux 通常是 ~/.codex/pets，Windows 通常是 %USERPROFILE%\.codex\pets）。
```

### Umiri

```text
请在临时目录 git clone https://github.com/Chuyuuuu/Mygo-Mujica-Codex-Pets.git，然后把 Release/umiri 放进 Codex 宠物目录（Unix/macOS/Linux 通常是 ~/.codex/pets，Windows 通常是 %USERPROFILE%\.codex\pets）。
```

### Nyamu

```text
请在临时目录 git clone https://github.com/Chuyuuuu/Mygo-Mujica-Codex-Pets.git，然后把 Release/nyamu 放进 Codex 宠物目录（Unix/macOS/Linux 通常是 ~/.codex/pets，Windows 通常是 %USERPROFILE%\.codex\pets）。
```

## 视频预览

每个角色的动作预览视频都在对应角色目录下：

```text
<角色目录>/qa/videos
```

例如：

```text
tomori/qa/videos
saki/qa/videos
```

## 已知问题

跳跃动作会有一些局限。Codex 宠物本身没有太多可用于跳跃表现的高度，所以这些宠物的跳跃动作基本不会出现明显高度变化，看起来可能会有点奇怪，还请见谅。

## 制作说明

这些宠物不是非常精细的手工像素资产，而是使用 Codex 的 hatch pets skill 顺手生成的，比较适合想开箱即用、节省自己 tokens 的朋友。

部分角色或部分动作可能会有瑕疵。仓库中保留了所有过程文件，包括参考图、生成帧、prompt、QA 文件和最终 spritesheet。如果你不想从头重做喜欢的角色，可以把仓库拉下来，只修改局部动作或局部帧。

## License

本仓库作者贡献的内容采用 [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) 授权。你可以自由复制、修改、分发、再创作或用于任何用途，署名不是强制要求。

请注意：本授权只适用于本仓库作者贡献或生成整理的文件，不代表放弃、转让或重新授权 BanG Dream!、MyGO!!!!!、Ave Mujica、相关角色、商标、设定、美术风格或其他原始 IP 权利。BanG Dream! 及相关内容版权归 Bushiroad 及其相关权利方所有。本项目是非官方粉丝制作项目，与 Bushiroad 没有关联、授权或背书。
