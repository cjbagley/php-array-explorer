---
title: array_search
description: get the key of the first instance in an array
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