# 我的第一个 GitHub 仓库

这是跟着课程视频做练习用的第一个仓库，用来走通完整的 Git 流程。

## 我在这台电脑上配置好的东西

| 项目 | 内容 |
| --- | --- |
| Git 版本 | 2.56.0（Windows） |
| Git 身份 | luminosity0612 |
| 认证方式 | SSH 密钥（ed25519），走 ssh.github.com 的 443 端口 |
| 默认分支 | main |

## 这次练习学到的命令

```bash
git status          # 看当前状态
git add .           # 把改动放进暂存区
git commit -m "说明" # 提交，写清楚改了什么
git push            # 推到 GitHub
```

## 笔记

- 提交信息（commit message）要写"这次改了什么"，不是写"更新"这种没信息量的词
- 推送前先 `git status` 确认改了哪些文件
- 分支：新功能用 `git checkout -b feature/xxx`，改完发 Pull Request 合并
