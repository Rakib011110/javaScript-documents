# javaScript-documents 


## introduced-to-js-17


### what is javaScript?

- JavaScript is high level, interpreted programming language used to make web pages more interactive. JavaScript is a dynamic programming language that's used for web development, web applications, game development, and lots more. JavaScript language is used both on the client-side and server-side allowing you to make web pages interactive.
- JavaScript হলো একটি scripting অথবা programming language যা সাধারনত কোন ওয়েবসাইটে ব্যবহার করা হয়। এই language কে আবার client-side scripting language ও বলা হয় কারণ এর সোর্স কোড গুলো process হয় Client এর web browser দিয়ে।

### Why use JavaScript?

- Where HTML and CSS are languages that give structure and style to web pages, JavaScript gives web pages interactive elements that engage a user.

List of JavaScript:

- [](#)
- [JavaScript-Array-Condition-18 ](#JavaScript-Array-Condition)
- [](#)
- [](#)
- [](#) 
- [](#)  
- [](#) 


<details>
<summary>
  <h3> How to Work js ? (Click Me)</h3>
</summary>
<br >
 reduce

```js


১। JavaScript Engine প্রথমে আপনার JavaScript Code পড়বে মানে parse করবে।
২। তারপর আপনার JavaScript Code কে পরিবর্তন করে মানে compile করে একটি machine language এ নিয়ে আসবে।
৩। তারপর এই machine language টিই আপনার কাজ করবে।


জাভাস্ক্রিপ্ট মূলত ব্রাউজারে বিভিন্ন ইভেন্ট দ্বারা পরিচালিত হয় । যেমন :

1-ক্লিক - যখন কোন ইউজার কোন বাটন বা অবজেক্টের উপরে ক্লিক করতে তখন জাভাস্ক্রিপ্ট কাজ করবে ।
2-ডাবল ক্লিক - ইউজার যখন কোন বাটন বা অবজেক্টের উপরে ডাবল ক্লিক করবে ।
3-রাইট ক্লিক - যখন ওয়েব পেজে রাইট ক্লিক করবে তখন কাজ শুরু হবে ।
-4লোড - ওয়েব পেজটি যখন ব্রাউজারে লোড হবে তখন কাজ করবে ।
-5আনলোড - যখন ওয়েব পেজ থেকে ইউজার বেরিয়ে যাবে তখন কাজ করানো যাবে ।
6-স্ক্রল - ওয়েব পেজ স্ক্রল করলে কাজ করবে ।
7-মাউস হভার - কোন ছবি বা অবজেক্টের উপরে যখন মাউস রাখা হবে তখন ও 8-জাভাস্ক্রিপ্টকে কাজ করাতে পারি ।
9-উইন্ডো রিসাইজ - ব্রাউজারের এর উইন্ডো যখন রিসাইজ করে ছোট বা বড় 10-করা হবে তখন ও কাজ করানো যায় ।
11-কীবোর্ড কী প্রেস - কোন কারনে ইউজার কীবোর্ড থেকে যখন কোন কী প্রেস করবে তখন ও জাভাস্কিপ্ট কাজ করতে পারে ।


```

</details>

<details>
<summary>
  <h3>JavaScript version? (Click Me)</h3>
</summary>
<br >

- সর্বপ্রথ JavaScript ১৯৯৫ সালে Brendan Eich নামে একজন ব্যক্তি আবিষ্কার করেছিল।

- ECMAScript হলো JavaScript এর অফিসিয়াল নাম এবং এই ECMAScript কে আবার ES ও বলা হয়ে থাকে।

```js

```

</details>

<details>
<summary>
  <h3>জাভাস্ক্রিপ্ট ভ্যারিয়বেল কি? (Click Me)</h3>
</summary>
<br >

- ভ্যারিয়বেল (variable) এর অর্থ - পরিবর্তনশীল । প্রোগ্রামে কোন তথ্য বা ডাটাকে বার বার ব্যবহার করার জন্য নির্দিষ্ট Keyword এর মাধ্যমে কম্পিউটারের মেমরি ( Ram memory) ভিতরে স্টোর করে রাখা হয় । এই স্টোর করে রাখা ডাটাকে Variable এর মাধ্যমে যেখানে প্রয়োজন হবে সেখানে ডিক্লিয়ার করা হয় ।

```js
-example;
var price = 11;
var age = 17;
var temperature = 38;

// string
var person = "sodor uddin";
var location = "andork killa bandorbon";
var special = "alia bhatt";

// Boolean
var serious = true;
var isFullMarks = true;
var isSingle = false;
```

</details>

### write-variable

<details>
<summary>
  <h3> How to write variable ? (Click Me)</h3>
</summary>
<br >

- ভ্যারিয়েবল এ letters(a-z), digits(0-9), underscores(\_), and dollar signs($) এই চারটি জিনিস ব‍্যবহার করতে পারেন।
- ভ্যারিয়েবল এর নাম ডিজিট বা নম্বর দিয়ে শুরু করা যাবে না। তবে মাঝে কিংবা শেষে ডিজিট ব‍্যবহার করা যাবে। উদাহরণ: var name7 = rakib islam ';
- ভ্যারিয়েবল নামের মধ‍্যে স্পেস বা ফাঁকা রাখা যাবে না।
- ভ্যারিয়েবল এর নামে কোন কিওয়ার্ড ব‍্যবহার করা যাবে।
- ভেরিয়েবলের নাম কেজ সেন্সিটিভ তাই এ ব্যাপারে সতর্ক থাকতে হবে। যেমন A এবং a এক নয়।
- ভেরিয়েবলের নামের মাঝে কোন চিহ্ন যেমন – কমা, ফুলস্টপ ব্যবহার করা যাবে না।
- ভেরিয়েবলের নাম হিসেবে জাভাস্ক্রিপ্টের সংরক্ষিত শব্দ বা Reserved Word গুলো ব্যবহার করা যাবে না।
- চাইলে একসাথে একাধিক ভ‍্যালিয়েবল লেখা যায়। তবে সেক্ষেত্রে প্রতিটি ভ‍্যালিয়েবলের পরে কমা দিতে হবে। উদাহরণ: var name, age, location;

- 3 টি উপায়ের ভ্যারিয়েবল ব্যবহার করা যায়:
  ১. var 2. let = পরবর্তীতে কোন ভ্যারিয়েবলের মান পরিবর্তন করা যায়। বেশিভাগ সময় এটি ব্যবহার করা হয়।
  ৩. const = এটি কোন ভ্যারিয়েবল দিলে ভ্যারিয়েবলের মান পরিবর্তন করা যায়।

```js
// good variable
var price = 29;
/* 
vaR price = 29;
Var price = 29;
VAR price = 29; */

/*
1. variable name can not be any keywords
var false = 96;
var return = true;
 */

// 2. variable name has to be in one work. No space
// var my home address = "New California";

/*  3. variable name can not have quotation
var "name" = "Tom Hanks"; */

/* 
 4. variable name can not starts with a number but can ends with a number
var 99Club = 1964;
var club25 = 2025;
 */
/* 
 5. How to use long names
 can not use dash
var user-name = "raj bappa";
 */
var user_name = "bappa raj";
var usercurrenthomeaddress = "andor killa bandor ban";
var user_home_address = "andor killa bandor ban"; // snake case
var userHomeAddress = "andor killa bandor ban"; // camel case: we will use this one
var UserHomeAddress = "andor killa bandor ban"; // pascal case

// variable name is case senstive
var person = 25;
var Person = 35;
```

</details>

</details>

### Arithmetic-Operators

<details>
<summary>
  <h3>Arithmetic-Operators(Click Me)</h3>
</summary>
<br >

JavaScript Arithmetic Operators
Arithmetic operators perform arithmetic on numbers (literals or variables).

- +Addition
- -Subtraction
- \*Multiplication
- \*\* Exponentiation (ES2016)
- / Division
- % Modulus (Remainder)
- ++ Increment
- -- Decrement

```js
var onionPrice = 20;
var eggPrice = 10;
// console.log(onionPrice)

// addition, subtraction
/* var totalPrice = onionPrice + eggPrice;
console.log(totalPrice)
var priceDifference = onionPrice - eggPrice;
console.log(priceDifference);
 */

// console.log(totalPrice);
// console.log(onionPrice);
// console.log(eggPrice);
// console.log(onionPrice + eggPrice);

/* multplication
var orangePrice = 20;
var quantiy = 7;
var totalCost = orangePrice * quantiy;
console.log(totalCost); */

// division
var money = 500;
var player = 10;
var eachPlayer = money / player;
console.log(eachPlayer);
```

</details>

<details>
<summary>
  <h3> JavaScript Type(Click Me)</h3>
</summary>
<br >

- In JavaScript there are 5 different data types that can contain values:

- string
- number
- boolean
- object
- function

- There are 6 types of objects:
- Object
- Date
- Array
- String
- Number
- Boolean

- And 2 data types that cannot contain values:
- null
- undefined

```js
var price = 100;
//  console.log(typeof price);
var price = "100";
// console.log(typeof price);
var isHappy = true;
// console.log(typeof isHappy);
var romantic;
// console.log(typeof romantic);

// advanced
var num1 = 0.1;
var num2 = 0.2;
var sum = num1 + num2;
sum = sum.toFixed(1);
sum = parseFloat(sum);
console.log(sum);
```
</details> 


## JavaScript-Array-Condition-18 

### JavaScript-Array-Condition-18 

</details>


<details>
<summary>
  <h3>What is js Array ? (Click Me)</h3>
</summary>
<br >

- অ্যারে হল একটি বিশেষ ধরনের জাভাস্ক্রিপ্ট ভেরিয়েবল যা একই কাজে ব্যবহৃত একই ধরেনর তথ্য বা data কে একটি একক জাভাস্ক্রিপ্ট ভেরিয়েবলের মাধ্যমে ধারন করতে পারে। এক্ষেত্রে এই অ্যারে অবজেক্ট গুলোকে তাদের সাবস্ক্রিপ্টের মাধ্যমে access করা যায়।
- অ্যারের প্রথম এলিমেন্টটির অবস্থান অবস্থান হয় 0,
- এলিমেন্টটির এলিমেন্টের অবস্থান হয় 1,
- তৃতীয় এলিমেন্টটির অবস্থান হয় 2, এভাবে অন্যগুলো হবে।

```js
var friendsAge = [11, 21, 45, 17, 14, 105, 6];

var picnicFee = [5000, 2000, 4000, 150];

var nayikas = ["mahi", "opu", "sabnoor", "sabana"];
var vowels = ["a", "e", "i", "o", "u"];

console.log(friendsAge.length);
```

- অ্যারের প্রথম এলিমেন্টটির অবস্থান অবস্থান হয় 0,
- এলিমেন্টটির এলিমেন্টের অবস্থান হয় 1,
- তৃতীয় এলিমেন্টটির অবস্থান হয় 2, এভাবে অন্যগুলো হবে।

```js
var numbers = [45, 68, 78, 56, 89, 98];

var num = numbers.indexOf(56);

// 1. get element value by index
var element = numbers[1];
// console.log(element);

// 2. set element value by index
numbers[1] = 77;
numbers[3] = 44;
// console.log(numbers);

// 3. find index of an element
var positionIndex = numbers.indexOf(89);
console.log(positionIndex);
```

</details>


<details>
<summary>
  <h3>JavaScript Array Methods ? (Click Me)</h3>
</summary>
<br >
 - const fruits = ["Banana", "Orange", "Apple", "Mango"];

- JavaScript Array pop()
- The pop() method removes the last element from an array:
- fruits.pop();
  -The pop() method returns the value that was "popped out":
- let fruit = fruits.pop();
-
-

```js
The pop() method removes the last element from an array:
 fruits.pop();
const fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.pop();


The pop() method returns the value that was "popped out":
const fruits = ["Banana", "Orange", "Apple", "Mango"];
let fruit = fruits.pop();

JavaScript Array push()
The push() method adds a new element to an array (at the end):
const fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.push("tomato");
```

```js
var numbers = [78, 45, 98, 45];
//use push to add element to an array as the last element array
// numbers.push(63);
// console.log(numbers);
var friends = ["balam", "kalam", "salam"];
friends.push("gelam");
friends.push("pailam");
// console.log(friends);

// use pop to get last element
console.log(numbers);
// numbers.pop();
var element = numbers.pop();
console.log(numbers);
console.log(element);
```

</details>

### perators

<details>
<summary>
  <h3>JavaScript comparison operators ? (Click Me)</h3>
</summary>
<br >

- JavaScript comparison operators
  To compare two values, you use a comparison operator. The following table shows the comparison operators in JavaScript:

- Operator Meaning
- <less than
- > greater than
- <=less than or equal to
- > =greater than or equal to
- ==equal to
- !=not equal to

```js
// console.log(5 < 6);
// console.log(5 > 6);
// console.log(5 == 6);
// console.log(6 == 6);
// console.log(5 != 6);
// console.log(15 != 15);
// less than or equal
// console.log(5 <= 6)
// console.log( 6 <= 6 )
// console.log( 16 <= 6 )

// greater than or equal
// console.log(5 >= 6)
// console.log(5 >= 2)
// console.log(2 >= 2)

var num1 = 56;
var num2 = 89;

// console.log(num1 < num2);
// console.log(num1 > num2);
// console.log(num1 === num2);
// console.log(num1 !== num2);
// console.log(num1 >= num2);
// console.log(num1 <= num2);

// multiple conditions
// money1 > money2 && result1 > result2 && height1 > height2
// money1 > money2 || result1 > result2 || height1 > height2

/* 

- Introduction to JavaScript comparison operators
To compare two values, you use a comparison operator. The following table shows the comparison operators in JavaScript:

- Operator	Meaning
- <	less than
- >	greater than
- <=	less than or equal to
- >=	greater than or equal to
- ==	equal to
!=	not equal to   


*/
```

</details>

### if-else-conditons

<details>
<summary>
  <h3>if-else-conditons? (Click Me)</h3>
</summary>
<br >

- যে সকল ক্ষেত্রে কোন বিশেষ একটা শর্ত বা condition, সত্য বা true হলে তার ওপর নির্ভর করে সুনির্দিষ্ট কোন বিশেষ কার্য অর্থাৎ কোড execute করে এবং মিথ্যা বা false হলে অপর একাধিক শর্ত বা condition এর উপর নির্ভর করে কোন বিশেষ কার্য সম্পাদন করা জন্য অর্থাৎ কোড execute করার জন্য জাভাস্ক্রিপ্ট এর else . . if স্টেটমেন্ট ব্যবহার করা হয়।

- যখন কোন নির্দিষ্ট একটা শর্ত বা condition সত্য অর্থাৎ true হয়, তখন কিছু কোড execute করবে এবং যদি মিথ্যা বা false হয় তবে ভিন্ন একটি শর্ত বা condition কাজ করবে অর্থাৎ execute করবে এবং এই শর্ত বা condition মিথ্যা বা false হলে, ভিন্ন কিছু কোড কাজ করবে অর্থাৎ execute করবে, এ রকম ক্ষেত্রে জাভাস্ক্রিপ্ট এর else . . if স্টেটমেন্ট ব্যবহার করা হয়।

- বিষয়টি একটি উদাহরণ এর মাধ্যমে দেখা যাক। মনে করি বিস্কুট কেনার জন্য আমরা 100 টাকা নিয়ে একটি দোকানে গেলাম। দোকানে আমাদের 300 টাকা মূল্যের এক প্যাকেট বিস্কুট পছন্দ হল, কিন্তু আমাদের কাছে 300 টাকা না থাকায় আমরা 200 টাকা মূল্যের অন্য এক প্যাকেট বিস্কুট পছন্দ করলাম, কিন্তু 200 টাকা না থাকায় আমরা অন্য 100 টাকা মূল্যের অন্য এক প্যাকেট বিস্কুট কিনলাম।
- এক্ষেত্রে আমাদের প্রথম পছন্দ হল 300 টাকা মূল্যের বিস্কুট, দ্বিতীয় পছন্দ হল 200 টাকা মূল্যের বিস্কুট এবং তৃতীয় পছন্দ হল 100 টাকা মূল্যের বিস্কুট। এই কাজটিই হল জাভাস্ক্রিপ্ট এর else . . if স্টেটমেন্ট।

```js
var iphonePrice = 79000;
var myBudget = 95000;
// if iphone price is less than my budget. I will buy the iphone
/**
 *  if iphone price is less than my budget
 *      i will buy the iphone
 *
 *
 * if (condition) {
 *      // will execute if the condition is true
 * }
 *
 * */

if (iphonePrice < myBudget) {
  console.log("i phone kine futani marbo");
}

var chickenPrice = 500;
var myMoney = 50;
// if (chickenPrice <= myMoney){
//     console.log('Murgir raan khamu and haddi chibamu!!!');
// }
// if (chickenPrice > myMoney){
//     console.log('Smashed potato and lentils soup');
// }

/**
 * if chiken er price is less than my budget
 * i will eat chiken
 * na hoi: else
 * */

if (chickenPrice < myMoney) {
  console.log("I will eat Chicken");
} else {
  console.log("I will eat potato");
}
```

#### multiple-condtion

```js
// var isGraduated = true;
// var salary = 75000;
// var cars = 1;

// if(isGraduated == true){
//     console.log('Eso biye kore feli')
// }
// else{
//     console.log('tor Kopale Biya nai')
// }

// if(isGraduated == true && salary > 50000){
//     console.log('Eso biye kore feli')
// }
// else{
//     console.log('tor Kopale Biya nai')
// }

// if(isGraduated == true && salary > 50000 && cars >= 1){
//     console.log('Eso biye kore feli')
// }
// else{
//     console.log('tor Kopale Biya nai')
// }

var isGraduated = false;
var salary = 61000;
var cars = 0;

if (isGraduated === true || salary > 50000 || cars >= 1) {
  console.log("Eso Prem kori");
} else {
  console.log("tomar friend er mobile number dao");
}

if (isGraduated === true && (salary > 50000 || cars >= 1)) {
}
```

### Multi-Stage-condition

```js
var money = 68;
var danishPrice = 45;
var butterBread = 35;
var toastBiscuit = 20;

if (danishPrice < money) {
  console.log("Dan Dan danish khamu");
} else if (butterBread < money) {
  console.log("Butter bon khamu");
} else if (toastBiscuit < money) {
  console.log("chubai chubai toast biscuit khamu");
} else {
  console.log("Khali cha e sasther jonno valo");
}
```

```js
var straightLint = false;

if (math == true) {
  if (geometry == true) {
    if (straightLint == true) {
    } else {
      console.log("baka pothe cholba na");
    }
  } else {
    console.log("pithagorous hoite parba na");
  }
} else {
}
```

</details>


