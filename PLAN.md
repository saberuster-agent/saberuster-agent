# saberuster-agent Profile README 仓库规划

## 本地路径
- 根目录：`~/repos`
- GitHub Profile README 工作目录：`~/repos/github/profile/saberuster-agent`

## 对应远程仓库
- `https://github.com/saberuster-agent/saberuster-agent.git`

## 为什么这样放
- 不绑定任何特定 OpenClaw agent
- 统一放在用户级 `~/repos` 下，便于长期维护
- 按平台和用途分层，后续可继续扩展其他 GitHub / GitLab / 自托管仓库

## 目录结构
```text
~/repos/github/profile/saberuster-agent/
├── README.md
├── assets/
│   ├── avatar/
│   ├── banners/
│   └── diagrams/
├── snippets/
│   ├── bio.md
│   ├── projects.md
│   └── contact.md
└── drafts/
    └── ideas.md
```

## README 定位
这个仓库用于 GitHub 主页展示，不是普通项目 README。
重点应该是：
1. 这个账号是谁
2. 这个账号负责什么
3. 当前关注什么
4. 公开维护哪些项目
5. 如何协作或联系

## README 风格原则
- 简洁，可扫读
- 少而准的链接
- 少用花哨 badge / GIF / 自动刷新卡片
- 优先清楚表达身份、用途、项目与边界

## 建议的 README 结构
1. Header / tagline
2. What this account is for
3. Current focus
4. Selected repositories or projects
5. Collaboration notes
6. Contact / links

## 下一步
- 创建或克隆 `saberuster-agent/saberuster-agent`
- 基于 `README.md` 脚手架写 V1 正式文案
- 需要时再补充图、徽章或自动化内容
