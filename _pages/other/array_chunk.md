---
title: array_chunk
explorer_key: other
php_net_link: https://www.php.net/manual/en/function.array-chunk.php
---

```php
    <?php

    $input = ['John','Paul','George','Ringo'];

    $chunks = array_chunk($input, 2); 

    print_r($chunks);
```

{% include output_header.html %}

```console
    Array
    (
        [0] => Array
            (
                [0] => John
                [1] => Paul
            )

        [1] => Array
            (
                [0] => George
                [1] => Ringo
            )
    )
```