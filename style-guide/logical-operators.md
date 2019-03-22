---
layout: default
title: Logical Operators
parent: Style Guide
nav_order: 6
---

# Logical Operators

- Double pipes `||` are preferred to `OR`

Incorrect: 

```php 
    if($foo OR $bar) {...}
```

Correct: 

```php 
    if($foo || $bar) {...}
```

---

- Double ampersand `&&` is preferred to `AND`

Incorrect: 

```php 
    if($foo AND $bar)
```

Correct: 

```php 
    if($foo && $bar)
```

---

- No space should precede or proceed an exclamation point `!` before a variable when checking for inverse

Incorrect: 

```php 
    if( ! $foo)
```

Correct: 
```php 
    if(!$foo)
```
