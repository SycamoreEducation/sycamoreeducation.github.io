---
layout: default
title: General Guidelines
parent: Style Guide
nav_order: 1
---

# General Guidelines

## File Format
- Files should be saved with Unicode (UTF-8) encoding.
- The [BOM](https://en.wikipedia.org/wiki/Byte_order_mark) should not be used.
- Unix line endings should be used (LF).

## One Statement Per line

- Never combine statements on one line

```php
// Incorrect
$foo = 'this'; $bar = 'that'; $baz = str_replace($foo, $bar, $baz);

// Correct
$foo = 'this';
$bar = 'that';
$baz = str_replace($foo, $bar, $baz);
```
