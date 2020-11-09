---
title: array_change_key_case
description: change the case of the array keys
---

```php
    <?php

    $array = [
        'KeY' => 22,
        'Value' => 'Cheese',
    ];

    print_r(array_change_key_case($array, CASE_UPPER));
```

{% include output_header.html %}

```console
    Array
    (
        [KEY] => 22
        [VALUE] => Cheese
    )
```