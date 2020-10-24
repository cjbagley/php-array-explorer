---
title: array_push
explorer_key: add_item
explorer_sub_key: add_element_to_end
---

If you just want to add a single element to an array, the PHP recommended method is:

```php
    <?php

    $array[] = $variable;
```
The array_push() function can be used for adding just one element, however it is best used for adding multiple elements:

```php
    <?php

    $array = ['one','two','three','four'];

    array_push($array, 'five', 'six', 'seven'); 

    print_r($array);
```

{% include output_header.html %}

```console
    Array
    (
        [0] => one
        [1] => two
        [2] => three
        [3] => four
        [4] => five
        [5] => six
        [6] => seven
    )
```