# 更新日志 (Changelog)

所有针对 FsBlockLibrary 的版本变更、功能更新、Bug 修复等记录都将汇总于此。

## [Unreleased]
- 暂无。

## [v1.0.0] - 2026-07-04
- 明确发布策略：永久免费、无功能限制，不设置试用期、授权码或付费解锁。
- 发布 `FsBlockLibrary-v1.0.0-x64.msi` 正式安装包。
- 发布 `FsBlockLibrary-v1.0.0-portable-x64.zip` 便携包，内含完整 Starter runtime。
- 安装入口统一为“飞思图库启动器”，通过 Starter 选择 AutoCAD 2019-2027。
- 安装包内置 `x64_AC_2019_Release`、`x64_AC_2021_Release`、`x64_AC_2025_Release`、`x64_AC_2027_Release` 四个运行目录。
- 支持 `FsCadLoader.arx -> FsScreenMenu.arx -> FsCadCore.arx -> FsBlockLibrary.arx` 链式加载。
- 普通用户无法写 `%ProgramFiles%` 时，运行配置会复制到 `%APPDATA%\FsBlockLibrary\FsBlockLibrary.ini`。
- 发布 `SHA256SUMS.txt` 和 `release-manifest.json` 用于校验 MSI 与便携包。
