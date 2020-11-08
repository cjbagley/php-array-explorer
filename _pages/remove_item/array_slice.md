---
title: array_slice
description: remove part of an array    
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