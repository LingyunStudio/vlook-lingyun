# VLOOK-Lingyun — Typora 主题

基于 [VLOOK™](https://github.com/MadMaxChow/VLOOK) 的 Typora 自定义主题，使用 Lingyun 风格。

## 修改

以 VLOOK thinking 主题为基础，做了以下定制：

- **字体**：中文 → 宋体/SimSun，英文 → Times New Roman
- **字号**：基础字号 18px
- **样式**：仅保留 Lingyun 主题，删除了其余 5 个主题及对应字体文件，减小体积

## 安装

1. 将本仓库克隆到 Typora 主题目录：
   ```
   git clone https://github.com/LingyunStudio/vlook-lingyun.git "%APPDATA%\Typora\themes\vlook"
   ```
2. 将 `vlook-Lingyun.css` 复制到主题目录上级：
   ```
   copy "%APPDATA%\Typora\themes\vlook\vlook-Lingyun.css" "%APPDATA%\Typora\themes\"
   ```
3. 重启 Typora，在「主题」菜单中选择 `Vlook-Lingyun`

## 目录结构

```
├── vlook-Lingyun.css         # 主题入口文件（需复制到 themes/ 目录）
├── plugin/                   # VLOOK 插件（导出 HTML 用）
├── plugin-live/              # VLOOK Live 插件
├── themes/                   # 主题及其字体依赖
│   └── vlook/
│       ├── pages-dev/        # 开发模式字体
│       └── github-io/        # 发布模式字体
├── themes-live/              # Live 部署用主题
└── samples/                  # VLOOK 示例文档
```

## 许可

主题基于 [VLOOK](https://github.com/MadMaxChow/VLOOK)（MIT License）二次修改。

本仓库 [Apache-2.0](LICENSE)
