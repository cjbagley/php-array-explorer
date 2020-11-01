---
title: array_unique
explorer_key: filter_or_reduce_values
explorer_sub_key: remove_duplicates
php_net_link: https://www.php.net/manual/en/function.array-unique.php
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