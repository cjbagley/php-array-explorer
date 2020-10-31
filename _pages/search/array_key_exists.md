---
title: in_array
explorer_key: search
explorer_sub_key: to_see_if_key_exists_in_array
php_net_link: https://www.php.net/manual/en/function.array-key-exists.php
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