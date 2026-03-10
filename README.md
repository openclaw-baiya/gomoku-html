# Gomoku HTML

一个纯前端的五子棋小游戏（双人本地对战），无需安装依赖，打开浏览器即可玩。

## 功能

- 15x15 棋盘
- 黑白双方轮流落子
- 自动判断五子连珠胜负（横/竖/斜）
- 一键重新开始

## 使用方式

1. 克隆仓库

```bash
git clone https://github.com/openclaw-baiya/gomoku-html.git
cd gomoku-html
```

2. 直接用浏览器打开 `index.html`

也可以用任意静态服务器运行，例如：

```bash
python3 -m http.server 8000
```

然后访问：<http://localhost:8000>

## 项目结构

- `index.html`：游戏页面与核心逻辑（Canvas 绘制 + 落子判定）

## 后续可扩展

- 人机对战（简单 AI）
- 悔棋/撤销
- 落子音效与动画
- 移动端手势优化
- 在线对战（WebSocket）

---

如果这个小项目对你有帮助，欢迎 Star ⭐