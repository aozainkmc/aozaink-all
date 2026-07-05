# AozaiInk All

AozaiInk 玩法的整合仓库，用于聚合构建和发布 release。

本仓库引用以下模块：

- [aozaink-core](https://github.com/aozainkmc/aozaink-core)
- [aozaink-input](https://github.com/aozainkmc/aozaink-input)
- [aozaink-sigillum](https://github.com/aozainkmc/aozaink-sigillum)

在父级工程执行聚合构建：

```powershell
.\gradlew.bat :aozaink-all:build
```

Release 使用 `aozaink-all/build/libs/` 下生成的聚合 jar。
