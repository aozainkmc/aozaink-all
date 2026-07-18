# Molu / 墨箓

`aozaink-all` 是开发工程名；面向玩家及 Modrinth 的聚合完整版发布名为 `molu`。

官方玩法模块的母义、基础字、尾修字和唯一所有权遵循父工程的 [`GLYPH_OWNERSHIP.md`](../GLYPH_OWNERSHIP.md)。聚合包不会让模块复用彼此拥有的汉字；Input 只统一黄符三格格式。

本仓库引用以下模块：

- [aozaink-core](https://github.com/aozainkmc/aozaink-core)
- [aozaink-input](https://github.com/aozainkmc/aozaink-input)
- [aozaink-sigillum](https://github.com/aozainkmc/aozaink-sigillum)

在父级工程执行聚合构建：

```powershell
.\gradlew.bat :aozaink-all:build
```

Release 使用 `aozaink-all/build/libs/` 下生成的 `molu-<version>.jar`。独立模块分别发布为 `molu-core`、`molu-input`、`molu-sigillum`，源码工程名保持 `aozaink-*`。
