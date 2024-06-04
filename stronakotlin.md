---
layout: default
---
# Programowanie w Kotlinie
                        strona poświecona kotlinowi


## lekcja(01)

```kotlin
// prosta instrukcja wejscia w języku kotlin
fun main() {
  println("Hello World")
}
```

## lekcja(02)

```kotlin
//  instrukcja inicjalizowania zmiennych jak w kotlinie 

var variableName = value
val variableName = value
```
```kotlin
//  instrukcja inicjalizowania i wypisywania  zmiennych jak w kotlinie 

var name = "John"
val birthyear = 1975

println(name)          // Print the value of name
println(birthyear)     // Print the value of birthyear
```
## lekcja(03)

```kotlin
//  typy danych w kotlinie
val myNum = 5             // Int
val myDoubleNum = 5.99    // Double
val myLetter = 'D'        // Char
val myBoolean = true      // Boolean
val myText = "Hello"      // String
```
## lekcja(04)

```kotlin
//  zmienne logiczne w kotlinie
val isKotlinFun: Boolean = true
val isFishTasty: Boolean = false
println(isKotlinFun)   // Outputs true
println(isFishTasty)   // Outputs false 
```
```kotlin
 val x = 10
val y = 9
println(x > y) // zwaraca true, poniewarz 10 jest wieksze od 9
```


## lekcja(05)

```kotlin
if (20 > 18) {
  println("20 is greater than 18")
}
```


```kotlin
 val time = 20
if (time < 18) {
  println("Dzien dobry.")
} else {
  println("Dobry wieczor.")
}
// Outputs "Dobry wieczor."
```
[powrot do strony startowej](./index.html)
