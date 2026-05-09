# pomodoro-app

一个简洁的桌面番茄钟应用，纯 HTML/CSS/JS 实现，双击即可在浏览器中运行。

## 项目结构

```
pomodoro-app/
├── pomodoro.html          # 主程序
├── README.md              # 项目说明
├── .gitignore             # Git 忽略规则
├── screenshots/           # 开发过程截图
├── starry-dreaming-sloth.md  # 实施计划
└── .claude/               # Claude Code 配置
    ├── settings.json      # 项目设置
    ├── settings.local.json # 权限配置
    └── CLAUDE.md          # 本文件
```

## 运行方式

```bash
open pomodoro.html
```

## 技术要点

- 纯前端，无依赖
- SVG 圆形进度环
- Web Audio API 提示音
- Notification API 桌面通知
- 玫红主题配色
