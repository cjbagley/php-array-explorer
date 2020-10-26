---
title: array_pop
explorer_key: remove_item
explorer_sub_key: remove_element_from_end
php_net_link: https://www.php.net/manual/en/function.array-pop.php
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