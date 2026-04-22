# 本地行渠联动作战大本营 · 使用手册

这是"本地行渠联动作战大本营"系统的对外使用手册（静态网页版本）。

- 🌐 在线访问：启用 GitHub Pages 后自动生成
- 🔒 数据安全：所有业务敏感数字已模糊脱敏，人名已化名处理
- 📅 最后更新：2026-04-22（对应系统 v171）

## 目录结构

```
├── index.html                    # 手册主文件（打开即浏览）
├── manual_assets_public/         # 已脱敏的界面截图
│   ├── 20_home.png               # 大盘数据
│   ├── 21_cases.png              # 案例库
│   ├── 22_knowledge.png          # 知识库
│   ├── 23_plan.png               # 拓客方案
│   ├── 24_news.png               # 重要动态
│   └── 25_admin.png              # 管理后台
└── README.md                     # 本文件
```

## 如何启用 GitHub Pages

仓库创建后：
1. 进入仓库 `Settings → Pages`
2. `Source` 选 `Deploy from a branch`
3. `Branch` 选 `main` + 根目录 `/ (root)`，保存
4. 约 30 秒后，页面顶部会出现公开访问链接

## 如何后续更新

后续系统代码迭代时，重新生成手册的流程：

1. 登录 With 平台访问项目页面
2. 抓取最新源代码
3. 重新批量截图并脱敏
4. 覆盖本仓库的 `index.html` + `manual_assets_public/` 并 push

更新流程已封装为 WorkBuddy Skill（`with-manual-updater`），一句话即可触发。

## 许可

内部资料，仅限内部人员访问参考。数据/案例已脱敏，不代表真实业务数字。
