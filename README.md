# javaScript-documents 


## introduced-to-js-17


### what is javaScript?

- JavaScript is high level, interpreted programming language used to make web pages more interactive. JavaScript is a dynamic programming language that's used for web development, web applications, game development, and lots more. JavaScript language is used both on the client-side and server-side allowing you to make web pages interactive.
- JavaScript হলো একটি scripting অথবা programming language যা সাধারনত কোন ওয়েবসাইটে ব্যবহার করা হয়। এই language কে আবার client-side scripting language ও বলা হয় কারণ এর সোর্স কোড গুলো process হয় Client এর web browser দিয়ে।

### Why use JavaScript?

- Where HTML and CSS are languages that give structure and style to web pages, JavaScript gives web pages interactive elements that engage a user.

List of JavaScript:

- [](#)
- [Array-Condition](#JavaScript-Array-Condition)
- [JavaScript-loop](#JavaScript-loop)
- [js-function-object](#js-function-object) 
- [JavaScript-dom](#JavaScript-dom)  
- [#javaScript-ES6](#javaScript-ES6)  
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


## JavaScript-Array-Condition


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

# JavaScript-loop 

<details>
<summary>
  <h3> JavaScript loop (Click Me)</h3>
</summary>
<br >

- কোন স্টেটমেন্টকে ধারাবাহিক ভাবে বার বার দেখানোর জন্য Loop ব্যবহার করা হয় প্রোগ্রামিং ভাষার ক্ষেত্রে । প্রতিটি কম্পিউটার ভাষায় Loop বর্তমান ঠিক জাভাস্কিপ্টের ন্যায় ।

- কল্পনা করুন আমার প্রয়োজন ১ থেকে ১০০ সংখ্যা । এক্ষেত্রে আমরা Loop ব্যবহার করে সহজে আমাদের চাহিদা পূরণ করতে পারি । লুপ ব্যবহার করার ফলে কোডটি জটিল হয় না ।

- কটি লুপ (Loop) এর তিনটি অংশ থাকে :
- Initialization - Initialization হিসাবে ভ্যারিয়বেল ও তার ভ্যালু লেখা হয় ।
- Condition - কতবার লুপ চলবে সেটি Condition এর মধ্যে লিখতে হয় ।
- Increment / Decrement - লুপের ধাপ সৃষ্টি হয় ।

- Loop এর প্রকারভেদ :
- Loop সাধারণত পাঁচ প্রকারের নিচে লিস্ট দেওয়া হল -

- While Loop
- Do / Whlie Loop
- For Loop
- For / inloop এটি object এর জন্য
- Foreach এটি Array জন্য

```js

```

</details>

</details>

### while-loop

<details>
<summary>
  <h3>JavaScript while loop? (Click Me)</h3>
</summary>
<br >
  - কোন একটি শর্ত বা condition পুরন না হওয়া পর্যন্ত কোন কাজ চালিয়ে যেতে জাভাস্ক্রিপ্ট এর while লুপ ব্যবহার করা হয়। এক্ষেত্রে নির্ধারিত শর্ত বা condition টি মিথ্যা অর্থাৎ false না হওয়া পর্যন্ত while লুপ টি চলতেই থাকবে।

- উদাহরণ স্বরূপ বলা যায়, একজন শিক্ষক আপনাকে একটি অংক করতে দিল। আপনি যত বার অংকটি ভুল করছেন, ততবার শিক্ষক আপনাকে অংক টি করতে বলছে, অর্থাৎ কেবল মাত্র অংকটি করতে পারলেই আপনি এই কাজ থেকে মুক্তি পাবেন। জাভাস্ক্রিপ্ট এর while লুপ টি পুরোপুরি এই রকম।

- প্রথমত একটি ভ্যারিয়বেল নেওয়া হয় এবং তার ভ্যালু অ্যাসাইন করা হয় initialization ।
- দ্বিতীয়ত While নামে একটি কীওয়ার্ড লেখা হয় while loop ব্যবহারের জন্য এবং প্রথম বন্ধনীর ভিতরে কন্ডিশান দেওয়া হয় লুপটি কত বার চলবে ।
- Loop কে পুনরায় সচল করার জন্য অ্যারিথমেটিক অ্যাসাইনমেন্ট অপারেটর ব্যাবহার করা হয় ।

- যখন While লুপের কাজ শুরু হয় তখন জাভাস্কিপ্ট চেক করে দেখে যে ভ্যারিয়বেলের ভ্যালু অনুযায়ী কন্ডিশান স্টেটমেন্ট টি সত্য কি না । যদি সত্য হয় তাহলে সেকেন্ড ব্রাকেট { } এর মধ্যের কোড গুলো এক্সিকিউট হয় ।

- এরপর Increment / Decrement স্টেটমেন্ট ভ্যারিয়বেল এর ভ্যালুতে 1+ বা 1- করে । পুনরায় প্রোগ্রামকে আবার কন্ডিশান স্টেটমেন্টে নিয়ে গিয়ে কন্ডিশান চেক করা হয় । যদি কন্ডিশান সত্য হয় তাহলে সেকেন্ড ব্রাকেটএর মধ্যে কোড গুলো পুনরায় এক্সিকিউট হয় ।

- এভাবে লুপটি চলতে থাকবে যতক্ষণ না কন্ডিশান মিথ্যা হবে । কন্ডিশান মিথ্যা হলেই প্রোগ্রাম লুপ থেকে বের হয়ে আসবে । কন্তু সর্বদা স্মরণ রাখবেন কন্ডিশান স্টেটমেন্ট টি যদি সব সময় সত্য হয় তবে আপনি কখনও While Loop থেকে বের হয়ে আসতে পারবেন না । আপনার কম্পিউটার এর ক্ষতি ও হতে পারে । তাই While Loop ব্যবহারের সময় সতর্ক হওয়া আবশ্যক ।

### While

```js
// if(condition){

// }

// roastGiven = roastGiven + 1;
// roastGiven += 1;
/* 
1. Loop variable
2. condition inside while
3. Loop body
4. Change the loop variable
*/

// var roastGiven = 0;
// while (roastGiven < 10) {
//     console.log('Roast Den, Please !!')
//     console.log(roastGiven);
//     roastGiven++
// }


```

### even

```js
// target: 1 to 20 all event numbers
var number = 0;
while (number <= 20) {
  console.log(number);
  // number++;
  number = number + 2;
}
```

### number

```js
// Target: Display 1 to 10
var number = 1;
while (number <= 20) {
  console.log(number);
  number++;
}
```

### odd

```js
// target: 1 to 100 all odd number
var number = 1;
while (number <= 100) {
  console.log(number);
  number = number + 2;
}
```

</details>

### javascript-for-Loop

<details>
<summary>
  <h3> javascript for Loop? (Click Me)</h3>
</summary>
<br >

- ফর লুপ দিয়েও while লুপের কাজ করা যায়। ফর লুপ দিয়ে যেসব কাজ হয় while দিয়েও ঐ কাজ করা যাবে। ফর লুপ while এর মতই pretest লুপ, মানে আগে কন্ডিশন চেক করবে এরপর true হলে লুপের অভ্যন্তরের কোড এক্সিকিউট হবে। ফর লুপে ৩ টি এক্সপ্রেশন থাকতে পারে

- ১. ভেরিয়েবল initialization : প্রথম এক্সপ্রেশন দিয়ে ভেরিয়েবল initialize করা হয় এবং এই এক্সপ্রেশন লুপ এক্সিকিউট হওয়ার আগেই এক্সিকিউট বা চেক হবে।

- ২. কন্ডিশন : এরপর একটা কন্ডিশন দেয়া হয় যেটা চেক করে true রিটার্ন করলে লুপ এক্সিকিউট হবে, তবে এটিও ঐচ্ছিক যদি এই্ কন্ডিশন না দেয়া হয় তাহলে ফর লুপ বাই ডিফল্ট true রিটার্ন করে।

- ৩. শেষ এক্সপ্রেশন : এটা দিয়ে ভেরিয়েবলটি আপডেট করা হয় (বাড়ানো কিংবা কমানো হয়)। এটা সবার শেষে এক্সিকিউট হয়। প্রতিবার লুপ ঘুরে আসার পর এটি এক্সিকিউট হয়।

```js
// var roastGiven = 0;
// while(roastGiven < 7 ){
//     console.log('Roast Den, Please !!')
//     roastGiven++;
// }

// for loop
// for(var roastGiven = 0; roastGiven < 7 ; roastGiven++){
//     console.log('Roast Den, Please !!');
// }

// simple version of for loop

/* console.log('simple For loop');
for (var i = 0; i < 7; i++) {
    console.log(i);
}
 */

// for (var i = 1; i <= 10; i++) {
//     console.log(i);
// }

// i = i + 2;
// i += 2;
// for (var i = 0; i <= 20; i += 2) {
//     console.log(i);
// }

for (var i = 1; i <= 20; i += 2) {
  console.log(i);
}
```

### Array loops

```js
// for (var i = 0; i < 10; i++) {
//     console.log(i);
// }

// target: display every elements of an array
// var numbers = [45, 87, 89, 56, 32, 51, 25, 188, 41, 25, 98];

// for (i = 0; i < 7; i++) {
//     var number = numbers[i]
//     console.log(number);
// }

// for (var i = 0; i < numbers.length; i++) {
//     var number = numbers[i];
//     console.log(number);
// }

var items = ["bottle", "mouse", "sunglass", "pen", "notebook"];

for (var i = 0; i < items.length; i++) {
  var item = items[i];
  console.log(item);
}
```

</details>

# js-function-object 

<details>

<summary>
  <h3>What js Funtion ? (Click Me)</h3>
</summary>
<br >

- Functions
- JavaScript provides functions similar to most of the scripting and programming languages.

- In JavaScript, a function allows you to define a block of code, give it a name and then execute it as many times as you wan

- javaScript Function Syntax
- A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().
- Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

- The parentheses may include parameter names separated by commas:
  (parameter1, parameter2, ...)
- The code to be executed, by the function, is placed inside curly brackets: {}

- জাভাস্ক্রিপ্ট ফাংশন হল কিছু জাভাস্ক্রিপ্ট কোড যা সুপ্ত অবস্থায় থাকে, যতক্ষণ পর্যন্ত না তাকে কাজ করতে বা execute করতে বলা হয়। একটি জাভাস্ক্রিপ্ট ফাংশন তখনই কাজ করে যখন কোন জাভাস্ক্রিপ্ট ইভেন্ট সংঘটিত হয় বা অন্য কোন জাভাস্ক্রিপ্ট ফাংশন তাকে call করে। প্রায়শই কোন জাভাস্ক্রিপ্ট প্রোগ্রামে আমাদের কিছু কিছু কাজের পুনরাবৃত্তি করতে হয়, এ রকম ক্ষেত্রে ফাংশন ব্যাবহারের ফলে অনেক সময় বাঁচে। জাভাস্ক্রিপ্ট ফাংশন ব্যবহার করে একই কোড প্রোগ্রামে বার বার না লিখেও বার বার কাজ করানো যায়।

- একটি জাভাস্ক্রিপ্ট ফাংশন ব্যবহার করার জন্য নিচের 2টি কাজ করতে হয়।

- ফাংশন definie করা এবং
- ফাংশন ডাকা বা call করা।

- ফাংশন definie করা : একটি জাভাস্ক্রিপ্ট ফাংশন কি কাজ করবে, তা ফাংশন definie করার সময় অর্থাৎ ফাংশনটি যখন তৈরি করা হয় তখন নির্ধারণ করে দেয়া হয়।

- ফাংশন ডাকা বা call করা: জাভাস্ক্রিপ্ট ফাংশনটি কখন কাজ করবে অর্থাৎ কি ইভেন্ট এর ফলে কাজ করবে, তা নির্ধারণ করাই হল ফাংশন ডাকা অর্থাৎ ফাংশন call করা। উদাহরণ স্বরূপ বলা যায়, কোন এইচটিএমএল বাটন ক্লিক করার ফলে ওয়েব পেজে একটি ফলাফল প্রদর্শিত হবে। এটাই হল ফাংশন ডাকা বা জাভাস্ক্রিপ্ট ফাংশন call করা।

```js
// function declaration
function startFan() {
  console.log("Stand up");
  console.log("walk towards the switch");
  console.log("Press the switch");
}

// call the function
startFan();
console.log("Waking up in the morning");
startFan();
console.log("Eating lunch");
console.log("Watching JS tutorial");
startFan();
```
</details>


<details>
<summary>
  <h3>function  parameters ? (Click Me)</h3>
</summary>
<br >

- A function can have one or more parameters, which will be supplied by the calling code and can be used inside a function. JavaScript is a dynamic type scripting language, so a function parameter can have value of any data type.

```js
function bringSingara(money) {
  console.log("taka disen: ", money);
  console.log("ai nen singara");
}

var taka = 300;
// bringSingara(taka);

function add(num1, num2) {
  console.log("going to add:", num1, num2);
}

// add(125, 96);

function sum(a, b, c, d, e) {
  console.log(a, b, c, d, e);
  var sum = a + b + c + d + e;
  console.log(sum);
}

sum(15, 98, 56, 5, 9);
```
</details>

### javaScript return
 <details>

<summary>
  <h3>javaScript return
? (Click Me)</h3>
</summary>
<br >
The return statement ends function execution and specifies a value to be returned to the function caller

```js
function add(number1, number2) {
  console.log(number1, number2);
  var sum = number1 + number2;
  // console.log(sum);
  return sum;
  console.log("I need more code");
  return 15;
  return "hello done";
  return "I am hungry";
}

// add(45, 15);

var total = add(80, 20);
// console.log('total', total)

function bringSingra(money) {
  singraPrice = 10;
  var quantity = money / singraPrice;
  return quantity;
}
var myTaka = 150;

var singaras = bringSingra(myTaka);
console.log(singaras);
```

</details>

### demo

<details>

<summary>
  <h3>What is  Object? (Click Me)</h3>
</summary>
<br >
  - জাভাস্ক্রিপ্ট হল একটি অবজেক্ট নির্ভর ওয়েব প্রোগ্রামিং ভাষা। জাভাস্ক্রিপ্ট এর সকল কিছুই হল অবজেক্ট। ইংরেজি " Object " শব্দটির আক্ষরিক অর্থ হল " বস্তু ", জাভাস্ক্রিপ্টে অবজেক্ট অর্থ হল একটি বিশেষ ধরনের ডাটা যার প্রোপার্টি এবং মেথড রয়েছে। সকল জাভাস্ক্রিপ্ট অবজেক্ট এরই প্রোপার্টি এবং মেথড রয়েছে। জাভাস্ক্রিপ্টে আমরা প্রয়োজন অনুযায়ী অবজেক্ট এবং ভেরিয়েবল টাইপ তৈরি করতে পারি। প্রোগ্রামিং এর কাজ গুলো জাভাস্ক্রিপ্ট অবজেক্ট এর প্রোপার্টি এবং মেথড ব্যবহার করে করে করা হয়।

- অবজেক্ট তৈরি
- জাভাস্ক্রিপ্টে 3টি পদ্ধতিতে কোন অবজেক্ট তৈরি করা যায়, এগুলো - হল নিম্নরূপ -

- সরাসরি অবজেক্ট তৈরি,
- অবজেক্ট constructor অর্থাৎ নতুন কিওয়ার্ড ব্যবহার করে এবং
- অবজেক্ট literal ব্যবহার করে।

```js

```
</details> 

# JavaScript-dom


<details>

<summary>
  <h3>What is Dom ? (Click Me)</h3>
</summary>
<br >

The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

```js

```

</details>

<details>

<summary>
  <h3>What is the HTML DOM?
? (Click Me)</h3>
</summary>
<br >

- The HTML DOM is a standard object model and programming interface for HTML. It defines:

- The HTML elements as objects
- The properties of all HTML elements
- The methods to access all HTML elements
- The events for all HTML elements
- In other words: The HTML DOM is a standard for how to get, change, add, or delete HTML elements.

```js

```

</details>

<details>

<summary>
  <h3>The HTML DOM Tree of Objects
? (Click Me)</h3>
</summary>
<br >

- With the object model, JavaScript gets all the power it needs to create dynamic HTML:

- JavaScript can change all the HTML elements in the page
- JavaScript can change all the HTML attributes in the page
- JavaScript can change all the CSS styles in the page
- JavaScript can remove existing HTML elements and attributes
- JavaScript can add new HTML elements and attributes
- JavaScript can react to all existing HTML events in the page
- JavaScript can create new HTML events in the page

```js

```

</details> 

# javaScript-ES6-31
<details>
<summary>
  <h3>What is ES6 ? (Click Me)</h3>
</summary>
<br >

- javaScript ES6 (ECMAScript 6) is the 6th major release of the ECMAScript language specification. It is also referred to as ES2015 as it was released in 2015.

- ES6 introduced several new features and syntax improvements to the JavaScript language, including:

- let and const keywords for declaring variables with block scope
- Arrow functions for concise and readable function syntax
- Template literals for string interpolation
- Classes for object-oriented programming in JavaScript
- Promises for handling asynchronous code
- Destructuring for easy assignment of array and object properties
- Spread operator for copying and concatenating arrays and objects
- Modules for organizing code and sharing functionality between files
- Default function parameters and rest parameters
- ES6 made writing modern and maintainable JavaScript code much easier and more efficient, and its features are widely used in modern web development today.

```js

```

</details>

<details>
<summary>
  <h3>difference between, var, Let and const in  Javascript ? (Click Me)</h3>
</summary>
<br >

- 1: In JavaScript, var, let, and const are used to declare variables, but they have some important differences:

var:
var is the oldest way to declare variables in JavaScript. It has function scope, which means that if a variable is declared inside a function, it can only be accessed within that function. If it is declared outside a function, it becomes a global variable and can be accessed throughout the code. var can be redeclared and reassigned.
Example:

```js
var a = 10;
function example() {
  var b = 20;
}
```

- 2: let:
  let was introduced in ES6 and it has block scope, which means that if a variable is declared inside a block (within curly braces), it can only be accessed within that block. let cannot be redeclared, but it can be reassigned.

```js
const a = 10;
const obj = { prop: "value" };
obj.prop = "new value"; // valid
```

- 3: const:
  const is also introduced in ES6 and it also has block scope. A variable declared with const cannot be reassigned or redeclared. However, if the variable is an object or an array, its properties or elements can be changed.

```js
const a = 10;
const obj = { prop: "value" };
obj.prop = "new value"; // valid
```

- বাংলা ঃ

- var দিয়ে ভ্যারিয়েবল ডিক্লেয়ার করলে সেইটা re-declare এবং re-assign দুইটাই করা যায় ।
- let দিয়ে ভ্যারিয়েবল ডিক্লেয়ার করলে সেইটা re-assign করা যায় কিন্ত re-declare করা যায় নাহ

- এবং const দিয়ে ভ্যারিয়েবল ডিক্লেয়ার করলে সেইটা re-declare এবং re-assign কোনোটাই করা যায় নাহ।

</details>

<details>
<summary>
  <h3>What is Default function parameters ? (Click Me)</h3>
</summary>
<br >

- In this example, if you call addNumbers() with no arguments, it will return 0 (the default value for both x and y). If you call addNumbers(5) with only one argument, it will use 5 for x and 0 for y, and return 5. If you call addNumbers(5, 3) with both arguments, it will use 5 for x and 3 for y, and return 8.

Default function parameters can also be used with other parameter types, such as objects and arrays. For example:

```js
function addNumbers(x = 0, y = 0) {
  return x + y;
}
```

```js
function greetUser(name = "Anonymous", greeting = "Hello") {
  console.log(`${greeting}, ${name}!`);
}

greetUser(); // logs "Hello, Anonymous!"
greetUser("John"); // logs "Hello, John!"
greetUser("Mary", "Hi"); // logs "Hi, Mary!"
```

</details>

<details>
<summary>
  <h3>what is Template string in js ? (Click Me)</h3>
</summary>
<br >

- Template strings, also known as template literals, are a feature in JavaScript that allows for more expressive and flexible string formatting. Template strings are enclosed in backticks (``) instead of single quotes or double quotes.

- One of the key features of template strings is the ability to embed expressions directly into the string, using the ${expression} syntax. This allows for more dynamic string formatting, where the value of the expression is automatically converted to a string and inserted into the string.

```js
const name = "Rakib";
const age = 25;
const message = `Hello, my name is ${name} and I am ${age} years old.`;
```

```js
const person = "Adam Sand";
const person2 = "Ben White";
const person3 = `Donald Trump`;

const multiLine =
  "First Line text \n" +
  "second line of code \n" +
  "Third line of text \n" +
  "Fourth line of string";
// console.log(multiLine)

const newMultiLine = `First Line of text
Second LIner of text
third line of string
fourth line of code 
fifth line of code
`;
// console.log(newMultiLine);

const a = 2;
const b = 2;
const num = [43, 33, 4, 4, 4, 3, 3];
const summary = "sum of:" + a + "sum of :" + b + "is" + (a + b);
// console.log(summary);
const newSummary = ` sum of a ${a} and b ${num.length} is: ${a + b}  `;
console.log(newSummary);
```

</details>

<details>
<summary>
  <h3>What is Arrow Funtion in js ? (Click Me)</h3>
</summary>
<br >

- Arrow functions are a shorthand syntax for writing function expressions in JavaScript. They were introduced in ECMAScript 6 (ES6) and have become a popular way to write functions in modern JavaScript code.

- Arrow functions have a more concise syntax compared to traditional function expressions, and also have some differences in the way they handle the "this" keyword.

Here's an example of a traditional function expression:

```js
const double = function (x) {
  return x * 2;
};
```

- The same function can be expressed as an arrow function like this:

```js
const double = (x) => {
  return x * 2;
};
```

- As you can see, the arrow function uses the => syntax instead of the function keyword. The function parameter x is enclosed in parentheses, and the function body is enclosed in curly braces.

- Arrow functions also have a more concise syntax when the function body is a single expression. In this case, the curly braces and return keyword can be omitted:

```js
const double = (x) => x * 2;
```

- This is equivalent to the previous arrow function, but with the function body expressed as a single expression.

- One important difference between arrow functions and traditional function - expressions is how they handle the "this" keyword. Arrow functions do not bind their own "this" value, but instead inherit the "this" value from the surrounding scope. This can be useful in certain situations, but can also cause unexpected behavior if the surrounding scope changes.

- Overall, arrow functions provide a more concise syntax for writing function expressions in JavaScript, and are widely used in modern JavaScript code.

- bangla: Arrow function কে সহজভাবে সংজ্ঞায়িত করতে গেলে বলা যায় আমরা জাভাস্ক্রিপ্ট এ রেগুলার যে ফাংশন লিখি তার সংক্ষিপ্ত রূপ। এর মাধ্যমে আমরা ফাংশন এর সিনট্যাক্স কে আরো ছোট করে ফেলতে পারি। এতে আমাদের বয়লারপ্লেট কোড অনেক কমে যায়।

- more example:

```js
// function declaration
/* function add(first, second){
    const total =  first + second;
    return total;
} */

// function expression
const add1 = function add1(first, second) {
  const total = first + second;
  return total;
};
// function expression with anonymous function
const add2 = function (first, second) {
  const total = first + second;
  return total;
};

function add3(first, second) {
  const total = first + second;
  return total;
}

function add4(first, second) {
  return first + second;
}

const add5 = function (first, second) {
  return first + second;
};
const add6 = (frist, second) => frist + second;
const result = add6(10, 20);
console.log(result);

const add = (frist, second) => {
  const total = frist + second;
  return total;
};

const num = add(323, 44);
console.log(num);

// interview question: differences between
// function declaration, function expression and arrow function
```

```js
const add = (frist, second) => frist + second;

const getFullName = (frist, last) => frist + " " + last;

const multiply = (a, b) => a * b;

const result = multiply(7, 8);
console.log(result);

const addAlll = (a, b, c, d, e, f) => a + b + c + d + e + f;

//  no peraMeter
const getPie = () => 3.12;

//  one perameter
const doubleIt = (num) => num * 2;

const fivTime = (num) => num * 5;

//  multiline Arrow funtion,
const doMath = (z, y, z) => {
  const firstSum = x + y;
  const secondSum = y + z;
  const multiplyResult = firstSum + secondSum;
  const result = multiplyResult / 2;
  return result;
};
```

</details>

<details>
<summary>
  <h3>spread operator ? (Click Me)</h3>
</summary>
<br >

- The spread operator is a feature introduced in ECMAScript 6 (ES6) that allows an iterable (such as an array or a string) to be expanded into individual elements. In the context of arrays, the spread operator can be used to copy an array, concatenate arrays, and pass arrays as arguments to functions.

- Here are some examples of using the spread operator with arrays:

- 1 Copy an array:

```js
const arr1 = [1, 2, 3];
const arr2 = [...arr1]; // create a copy of arr1
console.log(arr2); // Output: [1, 2, 3]
```

- In this example, the spread operator is used to create a new array arr2 that contains all the elements of arr1.

- 2. Concatenate arrays:

```js
const arr1 = [1, 2];
const arr2 = [3, 4];
const arr3 = [...arr1, ...arr2]; // concatenate arr1 and arr2
console.log(arr3); // Output: [1, 2, 3, 4]
```

- In this example, the spread operator is used to create a new array arr3 that contains all the elements of arr1 and arr2.

- 3.Pass arrays as arguments to a function

```js
const arr1 = [1, 2, 3];
const max = Math.max(...arr1); // find the maximum element in arr1
console.log(max); // Output: 3
```

- In this example, the spread operator is used to pass the elements of arr1 as individual arguments to the Math.max function, which returns the maximum value in the array.

more example:

```js
const max = Math.max(12, 45, 54, 56);

// console.log(max);
const numbers = [44, 43, 42, 21, 24, 65];
const largest = Math.max(...numbers);

// console.log(...numbers);
// console.log(largest);

const numbers2 = [...numbers];
numbers.push(43);
// console.log(numbers);
// console.log(numbers2);

const number3 = [...numbers];

const numbers4 = [434, 5, 45, ...number3, 434];
console.log(numbers4);
```

</details>


