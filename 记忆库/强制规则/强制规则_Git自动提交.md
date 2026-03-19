# 强制规则：Git 自动提交

## 触发时机

- 重要任务完成后
- 系统规则或模板明显迭代后
- 用户明确说“commit”时

## 提交规范

```bash
git add [具体文件]
git commit -m "[类型]: [简短描述]"
```

建议类型：

- `content`
- `system`
- `memory`
- `task`
- `iteration`

## 禁止事项

- 不使用 `git add -A`
- 不 `force push`
- 不擅自提交
- 不修改不是自己的历史提交

