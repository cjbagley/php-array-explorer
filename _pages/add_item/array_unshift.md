---
title: array_unshift
description: add an element to the beginning
---

```php
    <?php

    $array = ['Quill', 'Gamora', 'Drax'];

    array_unshift($array, 'Rocket', 'Groot'); 

    print_r($array);
```

{% include output_header.html %}

```console
    Array
    (
        [0] => Rocket
        [1] => Groot
        [2] => Quill
        [3] => Gamora
        [4] => Drax
    )
```