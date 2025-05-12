## Constant Objects and Arrays

Constant Objects and Arrays

```javascrypt
// You can create a constant array:
const cars = ["Saab", "Volvo", "BMW"];

// You can change an element:
cars[0] = "Toyota";

// You can add an element:
cars.push("Audi");
```


 ## Variables are Containers for Storing Data
 Variables are Containers for Storing Data

```javascript
// JavaScript Variables can be declared in 4 ways:

// Automatically
// Using var
// Using let
// Using const

// var
// if (true) {
//    var x = 10;
// }
// console.log(x);  // ✅ 10

// let 
// if (true) {
//    let y = 20;
// }
// console.log(y);  // ❌ Error: y is not defined

// const
// const z = 30;
// z = 40;  // ❌ Error

// const obj = { a: 1 };
// obj.a = 2;  // ✅ Boleh

```


````javascript
// JavaScript Data Types
// JavaScript has 8 Datatypes
// String, Number, Bigint, Boolean, Undefined, Null, Symbol, Object

// The Object Datatype
// The object data type can contain both built-in objects, and user defined objects:

// Built-in object types can be:

// objects, arrays, dates, maps, sets, intarrays, floatarrays, promises, and more.

// Numbers:
// let length = 16;
// let weight = 7.5;

// Strings:
// let color = "Yellow";
//let lastName = "Johnson";

// Booleans
// let x = true;
// let y = false;

// Object:
// const person = {firstName:"John", lastName:"Doe"};

// Array object:
// const cars = ["Saab", "Volvo", "BMW"];

// Date object:
// const date = new Date("2022-03-25");

````

```` Javascript
// JavaScript Data Types
// The Object Datatype
// The object data type can contain both built-in objects, and user defined objects:

// Built-in object types can be:

// objects, arrays, dates, maps, sets, intarrays, floatarrays, promises, and more.

// Numbers:
let length = 16;
let weight = 7.5;

// Strings:
let color = "Yellow";
let lastName = "Johnson";

// Booleans
let x = true;
let y = false;

// Object:
const person = {firstName:"John", lastName:"Doe"};

// Array object:
const cars = ["Saab", "Volvo", "BMW"];

// Date object:
const date = new Date("2022-03-25");

````

````javascript

// Tipe data BigInt
// MAX SAFE INTERGER
// Biasa nya digunakan hal2 transaksi seperti dibank hal ini karna presisi perhitungan nya
<!DOCTYPE html>
<html>
<body>

<h2>Number Object Properties</h2>

<p>MAX_SAFE_INTEGER</p>

<p id="demo"></p>

<script>
let  x = Number.MAX_SAFE_INTEGER;
document.getElementById("demo").innerHTML = x;
</script>

</body>
</html>

````

````javascript
// ECMAScript 2015 (ES6)
// In 2015, JavaScript introduced an important new keyword: const.

// It has become a common practice to declare arrays using const:

const cars = ["Volvo", "BMW"];   // Allowed
const cars = ["Volvo", "BMW"];   // Not allowed
var cars = ["Volvo", "BMW"];     // Not allowed
cars = ["Volvo", "BMW"];         // Not allowed

{
  const cars = ["Volvo", "BMW"]; // Allowed
  const cars = ["Volvo", "BMW"]; // Not allowed
  var cars = ["Volvo", "BMW"];   // Not allowed
  cars = ["Volvo", "BMW"];       // Not allowed
}

`````

````javascript
// JavaScript Set Date Methods
// Set Date Methods
// Set Date methods are used for setting a part of a date:

//Method	Description
setDate()	Set the day as a number (1-31)
setFullYear()	Set the year (yyyy)
setHours()	Set the hour (0-23)
setMilliseconds()	Set the milliseconds (0-999)
setMinutes()	Set the minutes (0-59)
setMonth()	Set the month (0-11)
setSeconds()	Set the seconds (0-59)
setTime()	Set the time (milliseconds since January 1, 1970)

````


## Boolean
```` Javascript
Boolean(100)             // true → karena 100 adalah angka bukan nol
Boolean(3.14)            // true → angka pecahan positif, tetap true
Boolean(-15)             // true → angka negatif juga dianggap true
Boolean("Hello")         // true → string tidak kosong dianggap true
Boolean("false")         // true → meskipun tulisannya "false", ini tetap string, bukan nilai boolean, jadi dianggap true
Boolean(1 + 7 + 3.14)    // true → hasilnya 11.14, angka bukan nol, maka true

````