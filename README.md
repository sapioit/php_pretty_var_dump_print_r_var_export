# USAGE
```php
include_once("debug.php");
$var
vd($var);
pr($var);
ve($var);
vd2($var);
pr2($var);
ve2($var);
```

## CONTENT
```php
function pr($data)
{
    echo "<pre>";
    print_r($data);
    echo "</pre>";
}

function vd($data)
{
    echo "<pre>";
    var_dump($data);
    echo "</pre>";
}

function ve($data)
{
    echo "<pre>";
    var_export($data);
    echo "</pre>";
}

function pr2($data)
{
    echo "<pre><code>";
    print_r($data);
    echo "</code></pre>";
}

function vd2($data)
{
    echo "<pre><code>";
    var_dump($data);
    echo "</code></pre>";
}

function ve2($data)
{
    echo "<pre><code>";
    var_export($data);
    echo "</code></pre>";
}

```

## How it works
```php
ve($cuvinte);var_export($cuvinte);
print '<br/><br/>';
pr($cuvinte);print_r($cuvinte);
print '<br/><br/>';
vd($cuvinte);var_dump($cuvinte);
```
#### Returns
```php
array (
  0 => '0',
  1 => '1',
  2 => '2',
  3 => '3',
  4 => '4',
  5 => '5',
  6 => '6',
  7 => '7',
  8 => '8',
  9 => '9',
  10 => 'a',
  11 => 'b',
  12 => 'c',
  13 => 'd',
  14 => 'e',
  15 => 'f',
  16 => 'g',
  17 => 'h',
  18 => 'i',
  19 => 'j',
  20 => 'k',
  21 => 'l',
  22 => 'm',
  23 => 'n',
  24 => 'o',
  25 => 'p',
  26 => 'q',
  27 => 'r',
  28 => 's',
  29 => 't',
  30 => 'u',
  31 => 'v',
  32 => 'w',
  33 => 'x',
  34 => 'y',
  35 => 'z',
  36 => '10',
)
array ( 0 => '0', 1 => '1', 2 => '2', 3 => '3', 4 => '4', 5 => '5', 6 => '6', 7 => '7', 8 => '8', 9 => '9', 10 => 'a', 11 => 'b', 12 => 'c', 13 => 'd', 14 => 'e', 15 => 'f', 16 => 'g', 17 => 'h', 18 => 'i', 19 => 'j', 20 => 'k', 21 => 'l', 22 => 'm', 23 => 'n', 24 => 'o', 25 => 'p', 26 => 'q', 27 => 'r', 28 => 's', 29 => 't', 30 => 'u', 31 => 'v', 32 => 'w', 33 => 'x', 34 => 'y', 35 => 'z', 36 => '10', )

Array
(
    [0] => 0
    [1] => 1
    [2] => 2
    [3] => 3
    [4] => 4
    [5] => 5
    [6] => 6
    [7] => 7
    [8] => 8
    [9] => 9
    [10] => a
    [11] => b
    [12] => c
    [13] => d
    [14] => e
    [15] => f
    [16] => g
    [17] => h
    [18] => i
    [19] => j
    [20] => k
    [21] => l
    [22] => m
    [23] => n
    [24] => o
    [25] => p
    [26] => q
    [27] => r
    [28] => s
    [29] => t
    [30] => u
    [31] => v
    [32] => w
    [33] => x
    [34] => y
    [35] => z
    [36] => 10
)
Array ( [0] => 0 [1] => 1 [2] => 2 [3] => 3 [4] => 4 [5] => 5 [6] => 6 [7] => 7 [8] => 8 [9] => 9 [10] => a [11] => b [12] => c [13] => d [14] => e [15] => f [16] => g [17] => h [18] => i [19] => j [20] => k [21] => l [22] => m [23] => n [24] => o [25] => p [26] => q [27] => r [28] => s [29] => t [30] => u [31] => v [32] => w [33] => x [34] => y [35] => z [36] => 10 ) 

array(37) {
  [0]=>
  string(1) "0"
  [1]=>
  string(1) "1"
  [2]=>
  string(1) "2"
  [3]=>
  string(1) "3"
  [4]=>
  string(1) "4"
  [5]=>
  string(1) "5"
  [6]=>
  string(1) "6"
  [7]=>
  string(1) "7"
  [8]=>
  string(1) "8"
  [9]=>
  string(1) "9"
  [10]=>
  string(1) "a"
  [11]=>
  string(1) "b"
  [12]=>
  string(1) "c"
  [13]=>
  string(1) "d"
  [14]=>
  string(1) "e"
  [15]=>
  string(1) "f"
  [16]=>
  string(1) "g"
  [17]=>
  string(1) "h"
  [18]=>
  string(1) "i"
  [19]=>
  string(1) "j"
  [20]=>
  string(1) "k"
  [21]=>
  string(1) "l"
  [22]=>
  string(1) "m"
  [23]=>
  string(1) "n"
  [24]=>
  string(1) "o"
  [25]=>
  string(1) "p"
  [26]=>
  string(1) "q"
  [27]=>
  string(1) "r"
  [28]=>
  string(1) "s"
  [29]=>
  string(1) "t"
  [30]=>
  string(1) "u"
  [31]=>
  string(1) "v"
  [32]=>
  string(1) "w"
  [33]=>
  string(1) "x"
  [34]=>
  string(1) "y"
  [35]=>
  string(1) "z"
  [36]=>
  string(2) "10"
}
array(37) { [0]=> string(1) "0" [1]=> string(1) "1" [2]=> string(1) "2" [3]=> string(1) "3" [4]=> string(1) "4" [5]=> string(1) "5" [6]=> string(1) "6" [7]=> string(1) "7" [8]=> string(1) "8" [9]=> string(1) "9" [10]=> string(1) "a" [11]=> string(1) "b" [12]=> string(1) "c" [13]=> string(1) "d" [14]=> string(1) "e" [15]=> string(1) "f" [16]=> string(1) "g" [17]=> string(1) "h" [18]=> string(1) "i" [19]=> string(1) "j" [20]=> string(1) "k" [21]=> string(1) "l" [22]=> string(1) "m" [23]=> string(1) "n" [24]=> string(1) "o" [25]=> string(1) "p" [26]=> string(1) "q" [27]=> string(1) "r" [28]=> string(1) "s" [29]=> string(1) "t" [30]=> string(1) "u" [31]=> string(1) "v" [32]=> string(1) "w" [33]=> string(1) "x" [34]=> string(1) "y" [35]=> string(1) "z" [36]=> string(2) "10" }
```
