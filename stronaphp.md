---
layout: default
---
# Programowanie w PHP
                               strona poświecona php


## lekcja(01)

```php
// prosta instrukcja wejscia w języku php
echo "My first PHP script!";
```

## lekcja(02)

```php
//  instrukcja inicjalizowania zmiennych jak w pythonie nie podajemy typow
//tylko w php zmienne zawsze uprzedza znak $
<?php
  $x = 5;
  $y = "John";
  echo $y . " ma " . $x . " lata";
?>
```

## lekcja(03)

```php
//  typy danych w php
String
Integer
Float 
Boolean
Array
Object
NULL
Resource
```
## lekcja(04)

```php
//  zmienne logiczne w php
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


## lekcja(05)

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
[powrot do strony startowej](./index.html)
