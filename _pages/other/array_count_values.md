---
title: array_count_values
description: count how many times a value appears in an array
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