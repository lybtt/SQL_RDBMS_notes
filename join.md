1. JOIN: 如果表中有至少一个匹配，则返回行

```
SELECT p.id, title, body, created, author_id, username, likenumber, tag, photo
FROM article p JOIN user u ON p.author_id = u.id
ORDER BY created DESC
```

2. LEFT JOIN: 即使右表中没有匹配，也从左表返回所有的行

3. RIGHT JOIN: 即使左表中没有匹配，也从右表返回所有的行

4. FULL JOIN(full outer join): 只要其中一个表中存在匹配，就返回行

```
SELECT move.id, move.name,
  type.id, type.name AS type_name
FROM move
FULL OUTER JOIN type ON
move.type_id = type.id;
```




