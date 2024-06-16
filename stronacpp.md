---
layout: default
---
# programowanie w c++
                               strona poświecona c++


## prosta instrukcja wejscia w języku c++

```cpp

#include <iostream>
using namespace std;

int main() {
  cout << "Hello World!";
  return 0;
}
```

## instrukcja inicjalizowania zmiennych

```cpp

#include <iostream>
using namespace std;

int main() {
 int myNum = 15;  // myNum równa sie 15
myNum = 10;  // teraz myNum równa 10
cout << myNum;  // wyjście 10
}
```

##   typy danych w c++

```cpp

int myNum = 5;               // Integer (whole number)
float myFloatNum = 5.99;     // Floating point number
double myDoubleNum = 9.98;   // Floating point number
char myLetter = 'D';         // Character
bool myBoolean = true;       // Boolean
string myText = "Hello";     // String
```
##   zmienne logiczne w c++

```cpp

bool isCodingFun = true;
bool isFishTasty = false;
cout << isCodingFun;  // Outputs 1 (true)
cout << isFishTasty;  // Outputs 0 (false)
```


## instrukcje warunkowe c++

```cpp
if (20 > 18) {
  cout << "20 jest wieksze od 18";
}
```


```cpp
int x = 20;
int y = 18;
if (x > y) {
  cout << "x jest wiekszy od  y";
}
```
# powrot do strony glównej
[powrot do strony startowej](./index.html)
