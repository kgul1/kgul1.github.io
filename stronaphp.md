---
layout: default
---
# Programowanie w PHP
                               strona poświecona php


##  prosta instrukcja wejscia w języku php

```php

echo "My first PHP script!";
```

##  instrukcja inicjalizowania zmiennych jak w pythonie

```php

 nie podajemy typow
//tylko w php zmienne zawsze uprzedza znak $
<?php
  $x = 5;
  $y = "John";
  echo $y . " ma " . $x . " lata";
?>
```

##  typy danych w php

```php

String
Integer
Float 
Boolean
Array
Object
NULL
Resource
```
##  zmienne logiczne w php

```php

<?php
  $prawda = true;
  $fałsz = false;

  if ($prawda) {
    echo 'Zmienna $prawda posiada wartość true';
  }

  if (!$fałsz) {
    echo 'Zmienna $fałsz posiada wartość false';
  }
?>
```


## instrukcja warunkowa

```php
if (20 > 18) {
  echo "20 jest wieksze od 18";
}
```


```php
 $x = 20;
 $y = 18;
if (x > y) {
  echo "x jest wiekszy od  y";
}
```
# powrot do strony glównej
[powrot do strony startowej](./index.html)
