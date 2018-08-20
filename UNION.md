1. UNION

> UNION 操作符用于合并两个或多个 SELECT 语句的结果集。(不允许重复值)
> The union of two or more tables means combing their type-matching rows
> There are two necessary conditions for a `UNION` to be performed
> each union query must have the same number of columns. and each nth column must have the same type in all union queries

```
SELECT id, name FROM student UNION SELECT id, name FROM sportsman;
```

2. UNION ALL

> UNION ALL 命令和 UNION 命令几乎是等效的，不过 UNION ALL 命令会列出所有的值。(允许重复值)
