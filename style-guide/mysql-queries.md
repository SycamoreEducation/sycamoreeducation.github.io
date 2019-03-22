---
layout: default
title: MySQL Queries
parent: Style Guide
nav_order: 10
---

# MySQL Queries
- MySQL keywords should always be capitalized 
 - `SELECT`, `INSERT`, `DATE`, `DATE_FORMAT`, `WHERE`, `AS`, `JOIN`, `ON`, `IN`, etc

```php
// Incorrect
$sql = "select value1, value2, value3, value4, value5, value6 as cool where SchoolID = 1" ...

// Correct
$sql  = "SELECT value1, value2, value3, value4, ";
$sql .= "value5, value6 AS cool ";
$sql .= "WHERE id = 1" ...
```
