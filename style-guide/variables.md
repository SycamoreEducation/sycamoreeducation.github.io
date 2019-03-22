---
layout: default
title: Variables
parent: Style Guide
nav_order: 2
---

# Variables

- Should generally contain only lowercase letters, though numbers are occasionally needed (i.e. for semester values)

Incorrect: 
```php
    $Route345 = 345;
```

Correct: 
```php
    $route = 345;
```


- Should be reasonably named to indicate their purpose and content, using a minimum of three characters

Incorrect: 
```php 
    $a = ($n / $d) * 100;
```
Correct: 
```php 
$avg = ($num / $dem) * 100;
```


- Single letter variables should **only** be used in `for` loops

i.e. 
 ```php 
    for($i = 0; $i < $rsc; $i++) {...}
```
