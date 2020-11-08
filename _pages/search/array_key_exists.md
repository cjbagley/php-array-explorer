---
title: array_key_exists
description: see if a key exists in an array
---

```php
    <?php

    $array = [
        'name' => 'Bob McBobby',
        'age' => 100,
        'home' => 'New York',
    ];

    var_dump(array_key_exists('telephone', $array));
```

{% include output_header.html %}

```console
    bool(false)
```