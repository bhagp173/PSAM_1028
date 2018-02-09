## NOTES

```rudy

// Call Last Element In Array
undefined
var lastElementInArray = ["apple, banana, coconut, figs"]
undefined
var myFruitArray = ["apple", "banana", "coconut", "figs", "grapes"]
undefined
myFruitArray.length
5
myFruitArray.length - 1
4
var myNestedArrayOfFruit = []
undefined
var myNestedArrayOfFruit = ["","",""]
undefined
var myNestedArrayOfFruit = [["","",""],["","",""],["","",""]]
undefined
myNestedArrayOfFruit
(3) [Array(3), Array(3), Array(3)]
0: (3) 
VM552:1 Uncaught SyntaxError: Unexpected token :

```
## PART 2

```ruby

//.push adds Elements to END of Array
var mySimpleFruitArray = []
undefined
mySimpleFruitArray.push()
0
mySimpleFruitArray.push("Apple")
1
mySimpleFruitArray
["Apple"]
mySimpleFruitArray.push("Banana")
mySimpleFruitArray.push("coconut")
mySimpleFruitArray.push("figs")
4
mySimpleFruitArray
(4) ["Apple", "Banana", "coconut", "figs"]

```
## PART 3

```ruby

// ADD Element to Front, Shift it All Down
undefined
var colorArray = ["Red", "Blue", "Green"]
undefined
var colorArray = ["Red", "Blue", "Green"]
colorArray.unshift("Yellow")
4
colorArray
(4) ["Yellow", "Red", "Blue", "Green"]
colorArray.unshift("Purple")
5
colorArray
(5) ["Purple", "Yellow", "Red", "Blue", "Green"]

```
## PART 4

```ruby

// .pop REMOVING ELEMENTS From Array
var colorArray = ["Red", "Blue", "Green"]
undefined
colorArray.pop
ƒ pop() { [native code] }
colorArray.pop()
"Green"
colorArray
(2) ["Red", "Blue"]
colorArray.pop()
"Blue"
colorArray
["Red"]
colorArray.pop()
"Red"
colorArray
[]
colorArray.push("Grey")
1
colorArray.push("Brown")
2
colorArray.pop("White")
"Brown"
colorArray
["Grey"]
colorArray.push("Brown")
2
colorArray
(2) ["Grey", "Brown"]

```
## PART 5

```ruby

// Concatenate, or Attached, 2 Arrays
var ledColorArray = ["Red","Green","Blue"]
var grayscaleArray = ["White","Gray","Black"]
var myLargeColorArray = ledColorArray.concat(grayscaleArray)
undefined
myLargeColorArray
(6) ["Red", "Green", "Blue", "White", "Gray", "Black"]
/get indexOf and Element
myLargeColorArray.indexOf("blue")
VM1279:1 Uncaught SyntaxError: Invalid regular expression: missing /
ledColorArray.indexOf("Red")
0
ledColorArray.indexOf("White")
-1
ledColorArray.indexOf("Blue")
2
