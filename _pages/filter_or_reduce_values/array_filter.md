---
title: array_filter
explorer_key: filter_or_reduce_values
explorer_sub_key: leaving_only_those_that_meet_a_given_condition
php_net_link: https://www.php.net/manual/en/function.array-filter.php
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