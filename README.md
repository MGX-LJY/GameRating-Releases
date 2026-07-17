# GameRating Releases

这里是 GameRating Windows 客户端的官方安装包与自动更新发布源。

## 下载

请从 [Releases](https://github.com/MGX-LJY/GameRating-Releases/releases) 下载最新的 `GameRating-Setup-版本.exe` 安装程序。

## 自动更新

安装 `2.0.0-alpha.2` 或更高版本后，客户端会自动检查 Alpha 通道的新版本、后台下载更新，并在用户确认后重启安装。

每个版本会同时发布：

- Windows NSIS 安装程序；
- Blockmap 增量更新文件；
- Electron Updater 版本清单。

## 安全说明

- 本仓库不包含 GameRating 源代码；
- 本仓库不保存 Steam API Key、GitHub Token 或用户数据；
- 用户的游戏库、评价、收藏夹与 Steam 同步数据保存在本机用户数据目录，应用升级不会主动删除这些数据。