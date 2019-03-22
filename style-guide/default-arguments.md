---
layout: default
title: Default Arguments
parent: Style Guide
nav_order: 9
---

# Default Arguments

- Function declarations should use default values sparingly
- Defaults should be declared without space around the equal sign
- Arguments without defaults can explicitly check for empty values and set 
default value if needed
- Ternary operator is preferred when setting default values

```php
// Incorrect
function myCoolFunction($foo = 'hello', $bar = array(1, 56), $baz = true) { ... }

// Correct
function myCoolFunction($foo, $bar, $baz=true) {
    $foo = $foo ?: 'hello';
}
```
