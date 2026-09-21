# 小乐魂启动器 · Little Ghast Launcher

白色系 Minecraft 启动器（Electron + React）。

## 功能
- 资源中心：Mod / 资源包 / 光影 / 整合包 / 服务器插件下载（Modrinth）+ 本地导入
- 实例管理：模组、资源、光影、存档备份、一键开服
- 全局中文故障报告（中文详细报错 + 解决方案）
- 微软正版登录 / 离线账户、皮肤、自定义域名、本地服务器
- 一键自更新（本仓库 `update.json` 为更新清单）

## 更新清单
`update.json` 格式：
```json
{ "version": "0.1.4", "url": "新版安装包直链", "notes": "更新说明（可选）" }
```
发布新版时：上传新 Release → 修改 `update.json` 里的 version/url/notes → 提交。玩家启动器会自动弹出更新提示。
