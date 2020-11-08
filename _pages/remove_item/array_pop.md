---
title: array_pop
description: remove an element from the end
---

```php
    <?php

    $array = ['Bronze', 'Silver', 'Gold', 'Paper'];

    $last = array_pop($array); 

    print_r($array);
    print_r($last);
```

{% include output_header.html %}

```console
    Array
    (
        [0] => Bronze
        [1] => Silver
        [2] => Gold
    )

    Paper
```