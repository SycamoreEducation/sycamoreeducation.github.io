---
layout: default
title: true, false, and null
parent: Style Guide
nav_order: 5
---

# true, false, and null

- Booleans (true and false) are to be used when possible, rather than numeric equivalents

Incorrect: 
```php 
    if($foo) $bar = 1;
```

Correct: 
```php 
    if($foo) $bar = true;
```

---

- `!` should be used when possible vs function calls

Incorrect: 
```php 
    if(empty($str)) $str = 'stuff';
```

Correct: 
```php
    if(!$str) $str = 'stuff';
```
