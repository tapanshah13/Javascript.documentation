# Javascript Documentation

## Document for Javascript


  * JavaScript programs can be inserted almost anywhere into an HTML document using the <script> tag.
  
```
<script>
  
1.document.getElementById("demo").innerHTML = "Hello JavaScript";
2.alert ("javascript");

</script>
```



# For external javascript


```
<script src="myScript.js"></script>
```


# Comments

```
//For one line comments
/*For multiple line 
of comment
*/
```

# Variables

## 1 Let

  ####  It is used for 'Name storage' for data
  

```
<script>

let price1 = 5;
let price2 = 6;
var total = price1 + price2;
document.getElementById("demo").innerHTML ="The total is: " + total;

</script>
```


## 2 Var

 #### The main difference between let and var is that scope of a variable defined with let is limited to the block in which it is declared while variable declared with var has the global scope. ... But we can access variable with var from window object if it is defined globally.

## 3 Const

 #### To declare a constant (unchanging) variable, use const instead of let
 

```
<script>

const myBirthday = '18.04.1982';
myBirthday = '01.01.2001';

</script>
```

# Operators

## JavaScript Arithmetic Operators
   #### Arithmetic operators are used to perform arithmetic operations
## JavaScript Assignment Operators
   #### Assign values to JavaScript variables
## Adding String Operators
   #### The + operator can also be used to add (concatenate) strings
## Adding Strings and Numbers
   #### Adding a number and a string will return a string
## Comparison Operators
   #### Compares a difference between variables or values
## Logical Operators
   #### Determine the logic between variables or values.
## Typeof operators
   #### We can use typeof operators to find a data type of variable


# Data Types
## In JavaScript there are 5 different data types that can contain values:
   * string
   * number
   * boolean
   * object
   * function

## There are 6 types of objects:
   * Object
   * Date
   * Array
   * String
   * Number
   * Boolean

## Data types that cannot contain values:
   * null
   * undefined

# alert
 * Give a alert box message and waits for user to press 'OK'
 
 
```
alert("Hello");
```

# prompt
   * It shows a window message with title, text box and buttons OK/Cance
   
```
result = prompt(title, [default]);
```
# confirm
   * It shows a window message with question and buttons OK/Cancel
   * There is result if OK it means True else False

# Functions
   * Javascript function executed when something calls it
   
```
<script>
function myFunction(p1, p2) {
  return p1 * p2;
}
document.getElementById("demo").innerHTML = myFunction(4, 3);
</script>
```

# Object 
   * It is group of specific value
```
let person = {name:"james", age:"35", id:"1234"};
```

# Event

  * Event is when user perform some action like pressing submit button
```
<button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>
```

# Type Conversions

## 1 String Conversion

   * It is used when we need a string value from variable it converts variable to string value
    
```
let value = true;
alert(typeof value); 

value = String(value);
alert(typeof value); 
```

## 2 Numeric Conversion
  
  * Numeric conversion happens in mathematical form and it is used to convert a value to number
  
  ```
  let str = "13";
  alert(typeof str); 

  let num = Number(str); // becomes a number 123

  alert(typeof num); // number
  ```
  
## 3 Boolean Conversion

 * It is used for logical operations to test a condition. If value is null, NaN, undefined, becomes False in this 
  condition and other values are True
  
  ```
alert( Boolean(1) ); 
alert( Boolean(0) ); 

alert( Boolean("hello") );
alert( Boolean("") );
```

# Math Operators with Precedence

### Precedence	Name	Sign

   * 16	     exponentiation	     **
   
   * 15	     multiplication	     *
   
   * 15	     division	           /
   
   * 15      reminder            %
   
   * 13	     addition	           +
   
   * 13	     subtraction         -
   
   
   # Comparisons
   
   
   * In this we will learn about different types of comaparisons in javascript
    
   ## Boolean is the result 
    
   * We get result in True or False after comparison
   
   ## 1 String Comparison
   
   * In this string gets compare with eachother for this javascript use 'Dictionary' order
   
   
   ```
   alert( 'P' > 'D' );  // true
alert( 'Goal' > 'Gold' ); // false
alert( 'Ball' > 'Bee' ); // true
```

## 2 Comparison of different types
  * It is comparison between different data types 
  
  ```
  alert( '2' > 1 ); // true
  alert( '01' == 1 ); // true
  alert( true == 1 ); // true
  alert( false == 0 ); // true
  ```
 
  
  
   
   














