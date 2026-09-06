# Starry Passage · Alpha 情报大厅

《流光 · Starry Passage》的网页试玩版。玩家可以在星月夜村庄中自由探索，并在教堂的 Alpha 情报大厅查看币圈情报站提供的空投日历与稳定性数据。

## 在线试玩

发布完成后访问：`https://grby-nice.github.io/starry-passage-web/`

## 数据节奏

- Alpha 活动：每 17 秒读取一次币圈情报站快照。
- 稳定性：每 5 秒读取一次币圈情报站快照。
- 游戏本身不直接访问 Binance，不会增加采集服务器的上游请求频率。
- 接口异常时保留最后一次成功数据并自动重试。

## 发布方式

项目源码包作为 GitHub Release 附件保存。Release 发布后，GitHub Actions 自动下载源码包、使用 Godot 4.3 导出 Web 版本并部署到 GitHub Pages。

## 字体许可

中文界面使用 Noto Sans SC，字体文件依据 SIL Open Font License 1.1 分发。项目的其他源码与美术资源未授予公共再分发许可。

