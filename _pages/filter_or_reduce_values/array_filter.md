---
title: array_filter
description: leave only those elements that meet a given condition
---

```php
    <?php

    $array = ['leaving', 2, 44, 'only', 99, 100, 'strings', 3];

    print_r(array_filter($array, 'is_string'));
```

{% include output_header.html %}

```console
    Array
    (
        [0] => leaving
        [3] => only
        [6] => strings
    )
```