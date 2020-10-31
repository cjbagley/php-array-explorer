---
title: array_search
explorer_key: search
explorer_sub_key: to_get_key_of_first_instance
php_net_link: https://www.php.net/manual/en/function.array-search.php
---

```php
    <?php

    $array = ['Nate', 'Pat', 'Dave', 'Taylor', 'Chris', 'Rami'];

    var_dump(array_search('Dave', $array));
```

{% include output_header.html %}

```console
    int(2)
```