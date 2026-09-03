# Hex Casting NeoForge 1.21.1 Ports

Hex Casting addon ports for Minecraft `1.21.1`, NeoForge `21.1.234`, and Hex Casting `0.12.0-devel-pre-39`.

这是这些移植仓库的统一入口。每个源码组保留独立仓库和原上游历史，所有公开移植都位于 `pre39` 分支。

| Port repository | Mod IDs | Upstream base |
|---|---|---|
| [Yaha](https://github.com/FluorineUCK/Yaha-NeoForge-1.21.1/tree/pre39) | `yaha` | [master@02ebb9b9](https://github.com/TheRobbie73/yaha.git) |
| [Hex Addons](https://github.com/FluorineUCK/Hex-Addons-NeoForge-1.21.1/tree/pre39) | `phlib`, `iotaworks`, `hexic` | [main@a900aacc](https://tangled.org/pool.net.eu.org/hex-addons) |
| [HexxyTounge](https://github.com/FluorineUCK/HexxyTounge-NeoForge-1.21.1/tree/pre39) | `hexxytounge` | [main@86026d57](https://iris.radicle.network/rad:zChmxddnxPemALy4RuZ7zQgzDxYv) |
| [HexDebug](https://github.com/FluorineUCK/HexDebug-NeoForge-1.21.1/tree/pre39) | `hexdebug` | [main@8fc7e24e](https://github.com/object-Object/HexDebug.git) |
| [HexTweaks](https://github.com/FluorineUCK/HexTweaks-NeoForge-1.21.1/tree/pre39) | `hextweaks` | [upstream-1.20@624ff839](https://github.com/walksanatora/HexTweaks.git) |
| [Hexcessible](https://github.com/FluorineUCK/Hexcessible-NeoForge-1.21.1/tree/pre39) | `hexcessible` | [mc/1.21.1@17048b9c](https://github.com/tizu69/hexcessible.git) |
| [HexResearch](https://github.com/FluorineUCK/HexResearch-NeoForge-1.21.1/tree/pre39) | `hexresearch` | [main@f5ca4b17](https://github.com/dashkal16/HexResearch.git) |
| [Hexal](https://github.com/FluorineUCK/Hexal-NeoForge-1.21.1/tree/pre39) | `hexal` | [main@b0d90daa](https://github.com/FallingColors/Hexal.git) |
| [Hexical](https://github.com/FluorineUCK/Hexical-NeoForge-1.21.1/tree/pre39) | `hexical` | [main@c98ae178](https://github.com/miyucomics/hexical.git) |
| [Hexpose](https://github.com/FluorineUCK/Hexpose-NeoForge-1.21.1/tree/pre39) | `hexpose` | [main@9f97e848](https://github.com/miyucomics/hexpose.git) |
| [Oneironaut](https://github.com/FluorineUCK/Oneironaut-NeoForge-1.21.1/tree/pre39) | `oneironaut` | [1.20.1@d4d3abaf](https://github.com/beholderface/oneironaut.git) |
| [HexKinetics](https://github.com/FluorineUCK/HexKinetics-NeoForge-1.21.1/tree/pre39) | `hexkinetics` | [master@ab7a71b4](https://github.com/Sonunte/HexKinetics.git) |
| [HexCellular](https://github.com/FluorineUCK/HexCellular-NeoForge-1.21.1/tree/pre39) | `hexcellular` | [main@a5d5f635](https://github.com/miyucomics/hexcellular.git) |
| [MoreIotas](https://github.com/FluorineUCK/MoreIotas-NeoForge-1.21.1/tree/pre39) | `moreiotas` | [main@0d96e56c](https://github.com/FallingColors/MoreIotas.git) |
| [HexGuide](https://github.com/FluorineUCK/HexGuide-NeoForge-1.21.1/tree/pre39) | `hexguide` | [main@449d902f](https://github.com/xm1221/HexGuide.git) |
| [HexCassettes](https://github.com/FluorineUCK/HexCassettes-NeoForge-1.21.1/tree/pre39) | `hexcassettes` | [main@241f932c](https://github.com/miyucomics/hexcassettes.git) |
| [Mediaworks](https://github.com/FluorineUCK/Mediaworks-NeoForge-1.21.1/tree/pre39) | `mediaworks` | [main@f7c45ee5](https://github.com/artynova/mediaworks.git) |
| [HexxySable](https://github.com/FluorineUCK/HexxySable-NeoForge-1.21.1/tree/pre39) | `hexxysable` | [master@aa0a3be1](https://github.com/TechTastic/HexxySkies.git) |

## Repository model

- `origin`: the `FluorineUCK` port repository.
- `upstream`: the original project repository.
- Publication/default branch: `pre39`.
- `phlib`, `iotaworks`, and `hexic` remain together in `Hex-Addons-NeoForge-1.21.1`.
- Exact repository and commit mapping: [repositories.json](repositories.json).

## Excluded port

HexOverpowered is intentionally not published because its original author does not permit submission.
