---
title: array_unique
description: remove duplicates
---

```php
    <?php

    $original_array = [1, 2, 3, 4, 4, 5, 6, 7, 7, 8, 9];

    $filtered_array = array_unique($original_array);

    print_r($filtered_array);
```

{% include output_header.html %}

```console
    Array
    (
        [0] => 1
        [1] => 2
        [2] => 3
        [3] => 4
        [5] => 5
        [6] => 6
        [7] => 7
        [9] => 8
        [10] => 9
    )
```