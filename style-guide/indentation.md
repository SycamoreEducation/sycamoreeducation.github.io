---
layout: default
title: Indentation
parent: Style Guide
nav_order: 8
---

# Indentation

- All functions or control statements have their opening brace on the same line 
as they're declared on

```php
// Incorrect
function main()
{
}

if($foo)
{
}

// Correct
function main() {
}

if($foo) {
}
```

---

- All code blocks inside of a function or control statement are indented 1 level
to signify they are a part of the parent block

```php
// Incorrect
if($foo){
$bar = $baz;
}

// Correct
if($foo) {
    $bar = $baz;
}
```

---

- All control blocks that span multiple lines must have curly braces surrounding them

```php
// Incorrect
if($foo)
    $bar = $baz;

// Correct
if($foo) {
    $bar = $baz;
}
```

---

- For one line control blocks, braces should not be used

```php
    if($foo) $bar = $baz;
```
