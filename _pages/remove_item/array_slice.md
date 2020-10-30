---
title: array_slice
explorer_key: remove_item
explorer_sub_key: remove_part_of_array
php_net_link: https://www.php.net/manual/en/function.array-slice.php
---

```php
    <?php

    $array = ['red', 'orange', 'yellow', 'green', 'blue', 'indigo', 'violet'];

    $slice = array_slice($array, 1, 3); 

    print_r($slice);
```

{% include output_header.html %}

```console
    Array
    (
        [0] => orange
        [1] => yellow
        [2] => green
    )
```