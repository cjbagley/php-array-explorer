---
title: array_shift
description: remove an element from the beginning
---

```php
    <?php

    $array = ['Tin', 'Bronze', 'Silver', 'Gold'];

    $first = array_shift($array); 

    print_r($array);
    print_r($first);
```

{% include output_header.html %}

```console
    Array
    (
        [0] => Bronze
        [1] => Silver
        [2] => Gold
    )

    Tin
```