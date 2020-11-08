---
title: array_merge
description: add an array to another array
---

```php
    <?php

    $array_1 = ['Winston', 'Venkman'];
    $array_2 = ['Egon', 'Ray'];

    $combined = array_merge($array_1, $array_2); 

    print_r($combined);
```

{% include output_header.html %}

```console
    Array
    (
        [0] => Winston
        [1] => Venkman
        [2] => Egon
        [3] => Ray
    )
```