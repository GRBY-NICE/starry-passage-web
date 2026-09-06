# Starry Passage · 币圈情报世界

《流光 · Starry Passage》的网页试玩版。玩家可以在星月夜村庄中自由探索，把币圈情报站的实时板块变成可进入的建筑与信息墙。

## 在线试玩

- 游戏直达：https://grby-nice.github.io/starry-passage-web/
- 主站入口：https://yuequan123.com/starry-passage

## 当前进度

### 第一阶段 · Alpha 教堂

- 教堂外墙 Alpha 摘要
- 今日活动、预告与稳定性完整面板
- 离线缓存与手机触屏入口

### 第二阶段 · 中央广场与社区大厅

- 热门、最新公开帖子
- 帖子详情与币种社区归类
- “我的帖圈”安全登录桥接
- C 快捷传送与手机社区入口

## 数据节奏

- Alpha 活动：每 17 秒读取一次币圈情报站快照。
- 稳定性：每 5 秒读取一次币圈情报站快照。
- 社区大厅：每 20 秒读取一次公开帖子，进入大厅时立即刷新。
- 游戏不直接访问 Binance，不保存网站密码、Cookie、登录令牌或钱包信息。
- 各数据源独立运行；接口异常时保留最后一次成功数据并自动重试。

## 发布方式

项目源码包作为 GitHub Release 附件保存。GitHub Actions 自动识别源码目录、使用 Godot 4.3 导出 Web 版本并部署到 GitHub Pages。

## 字体许可

中文界面使用 Noto Sans SC，字体文件依据 SIL Open Font License 1.1 分发。项目的其他源码与美术资源未授予公共再分发许可。
