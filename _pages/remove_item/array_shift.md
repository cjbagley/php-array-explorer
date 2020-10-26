---
title: array_shift
explorer_key: remove_item
explorer_sub_key: remove_element_from_beginning
php_net_link: https://www.php.net/manual/en/function.array-shift.php
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