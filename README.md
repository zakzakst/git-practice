# git-practice

## 新しくブランチを作成して、そのブランチでworktreeを作成する
```
git worktree add ../feature-login -b feature/login
```

## すでにあるブランチを worktree 化する
```
git worktree add ../review-fix-123 review/fix-123
```

## 現在の worktree 一覧
```
git worktree list
```

## worktree を削除
```
git worktree remove ../feature-login
```
