---
title: array_merge
explorer_key: add_item
explorer_sub_key: add_array_to_another_array
php_net_link: https://www.php.net/manual/en/function.array-merge.php
---

```php
    <?php

    $array_1 = ['Winston', 'Venkman'];
    $array_2 = ['Egon', 'Ray'];

    $combined = array_merge($array_1, $array_2); 

    print_r($combined);
```

{% include output_header.html %}

```console
    Array
    (
        [0] => Winston
        [1] => Venkman
        [2] => Egon
        [3] => Ray
    )
```