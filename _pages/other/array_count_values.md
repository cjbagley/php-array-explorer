---
title: array_count_values
explorer_key: other
explorer_sub_key: count_how_many_times_a_value_occurs
php_net_link: https://www.php.net/manual/en/function.array-count-values.php
---

```php
    <?php

    $array = ['red', 'green', 'yellow', 'red', 'purple', 'green', 'red'];

    print_r($array);
```

{% include output_header.html %}

```console
    Array
    (
        [red] => 3
        [green] => 2
        [yellow] => 1
        [purple] => 1
    )
```