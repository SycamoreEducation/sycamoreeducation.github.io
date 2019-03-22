---
layout: default
title: Variables
parent: Style Guide
nav_order: 2
---

# Variables

- Should generally contain only lowercase letters, though numbers are occasionally needed (i.e. for semester values)
 - Incorrect: `$Route345 = 345;`
 - Correct: `$route = 345;`

- Should be reasonably named to indicate their purpose and content, using a minimum of three characters
 - Incorrect: `$a = ($n / $d) * 100;`
 - Correct: `$avg = ($num / $dem) * 100;`

- Single letter variables should **only** be used in `for` loops
 - i.e. `for($i = 0; $i < $rsc; $i++)`
