---
title: array_push
description: add an element to the end
---

<p>If you just want to add a single element to an array, the PHP recommended method is:</p>

```php
    <?php

    $array[] = $variable;
```
<p>The array_push() function can be used for adding just one element, however it is best used for adding multiple elements:</p>

```php
    <?php

    $array = ['one', 'two', 'three', 'four'];

    array_push($array, 'five', 'six', 'seven'); 

    print_r($array);
```

{% include output_header.html %}

```console
    Array
    (
        [0] => one
        [1] => two
        [2] => three
        [3] => four
        [4] => five
        [5] => six
        [6] => seven
    )
```