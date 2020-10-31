---
title: in_array
explorer_key: search
explorer_sub_key: to_see_if_value_exists_in_array
php_net_link: https://www.php.net/manual/en/function.in-array.php
---

```php
    <?php

    $array = ['Mario', 'Luigi', 'Peach', 'Toad'];

    var_dump(in_array('Sonic', $array));
```

{% include output_header.html %}

```console
    bool(false)
```