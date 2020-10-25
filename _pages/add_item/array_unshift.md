---
title: array_unshift
explorer_key: add_item
explorer_sub_key: add_element_to_start
php_net_link: https://www.php.net/manual/en/function.array-unshift.php
---

```php
    <?php

    $array = ['Quill', 'Gamora', 'Drax'];

    array_unshift($array, 'Rocket', 'Groot'); 

    print_r($array);
```

{% include output_header.html %}

```console
    Array
    (
        [0] => Rocket
        [1] => Groot
        [2] => Quill
        [3] => Gamora
        [4] => Drax
    )
```