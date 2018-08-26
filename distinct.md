# distinct

> 在表中，可能会包含重复值。这并不成问题，不过，有时您也许希望仅仅列出不同（distinct）的值。关键词 DISTINCT 用于返回唯一不同的值。

SELECT COUNT(name) FROM student_name;  # 所有的name

SELECT COUNT(DISTINCT name) FROM student_name;  # 不同的值