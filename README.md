# USAGE
```php
include_once("debug.php");
vd($array);
pr($array);
ve($array);
```
## CONTENT
```php
function pr($data)
{
    echo "<pre>";
    print_r($data); // or var_dump($data);
    echo "</pre>";
}

function vd($data)
{
    echo "<pre>";
    var_dump($data); // or var_dump($data);
    echo "</pre>";
}

function ve($data)
{
    echo "<pre>";
    var_export($data); // or var_dump($data);
    echo "</pre>";
}
```
