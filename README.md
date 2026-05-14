# Automation Branch

这个分支是 `AceDuan/obsidian-web` fork 仓库的自动同步控制分支。

它只用于承载 GitHub Actions workflow，用来定时同步上游仓库：

```text
MusiCode1/obsidian-web:main -> AceDuan/obsidian-web:sync/upstream-main
```

这个分支不是项目代码分支。

如需查看或使用最新上游代码，请切换到：

```text
sync/upstream-main
```

如需向上游提交 PR，建议从 `sync/upstream-main` 创建新的 `feature/*` 分支。