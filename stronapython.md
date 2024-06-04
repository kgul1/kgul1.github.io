---
layout: default
---
# header1
                               strona poświecona python


## lekcja(01)

```py
// porownaniu z c++ instrukcja wejscia w python jest duzo krótza 
                        print("Hello, World!")
```

## lekcja(02)

```py
//  instrukcja inicjalizowania zmiennych jako ze python jest jezykiem
// dynamicznym nie deklarujemy typow danych zmiennych
// robie sie to poprzez przekonwertowanie np print(type(int("7")))
x = 5
y = "John"
print(x)
print(y)
```

## lekcja(03)

```py
//  typy danych w pythonie
Text Type:      str
Numeric Types:	int, float, complex
Sequence Types:	list, tuple, range
Mapping Type:	dict
Set Types:	set, frozenset
Boolean Type:	bool
Binary Types:	bytes, bytearray, memoryview
None Type:	NoneType
```
## lekcja(04)

```py
//  zmienne logiczne w pythonie
print(10 > 9)//true poniewarz 10 jest wieksze od 9
print(10 == 9)//false poniewarz 10 nie jest rowne 9
print(10 < 9)//false poniewarz 10 nie jest mniejsze od 9 
```


## lekcja(05)

```py
a = 33
b = 33
if b > a:
  print("b is greater than a")
elif a == b://elif oznacza w przeciwnym wypadku jezyli if
 //sie nie spelnia
  print("a and b are equal")
```


```py
a = 200
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else://else zachodzi gdy ani if ani elif sie nie spelnily
  print("a is greater than b")
```
[powrot do strony startowej](./index.html)
