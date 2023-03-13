# javaScript-documents 


## introduced-to-js-17


### what is javaScript?

- JavaScript is high level, interpreted programming language used to make web pages more interactive. JavaScript is a dynamic programming language that's used for web development, web applications, game development, and lots more. JavaScript language is used both on the client-side and server-side allowing you to make web pages interactive.
- JavaScript হলো একটি scripting অথবা programming language যা সাধারনত কোন ওয়েবসাইটে ব্যবহার করা হয়। এই language কে আবার client-side scripting language ও বলা হয় কারণ এর সোর্স কোড গুলো process হয় Client এর web browser দিয়ে।

### Why use JavaScript?

- Where HTML and CSS are languages that give structure and style to web pages, JavaScript gives web pages interactive elements that engage a user.

List of JavaScript:

- [Array-Condition](#JavaScript-Array-Condition)
- [JavaScript-loop](#JavaScript-loop)
- [js-function-object](#js-function-object) 
- [JavaScript-dom](#JavaScript-dom)  
- [javaScript-ES6](#javaScript-ES6)  
- [optional-chaining](#optional-chaining)   

- [JavaScript-Api-practice](#JavaScript-Api-practice)  
- [explore-Javascript-object](#explore-Javascript-object)  
- [more-Javascript-concept](#more-Javascript-concept) 
- [debugging-practice](#debugging-practice)  
- [all-about-browsers](#all-about-browsers) 
- [Javascript-Problem-Solved](#Javascript-Problem-Solved)

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

# javaScript-ES6
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

# optional-chaining

<details>
<summary>
  <h3>What is optional chaining  ? (Click Me)</h3>
</summary>
<br >

The optional chaining (?.) operator accesses an object's property or calls a function. If the object accessed or function called using this operator is undefined or null, the expression short circuits and evaluates to undefined instead of throwing an error.

```js
const users = [
  {
    id: 1,
    name: "abul",
    job: "doctor",
  },
];

// console.log(users[0].name);

const data = {
  count: 5000,
  data: [
    {
      id: 1,
      name: "abul",
      job: "doctor",
    },
    {
      id: 2,
      name: "dabul",
      job: "leader",
    },
  ],
};

const firstJob = data.data[0].job;
// console.log(firstJob);

const user = {
  id: 5001,
  name: "thomas alba edison",
  address: {
    street: {
      first: "32/A pabna ",

      second: "third flor",
      third: "fourth flor",
    },
  },
  postOfice: "cantontement",
  city: "dhakaa",
};

const userFloor = user.address.street?.second;
console.log(userFloor);
```

</details>

<details>
<summary>
  <h3> What is Javascript map? (Click Me)</h3>
</summary>
<br >

- In JavaScript, the map() method is used to create a new array from an existing array by transforming each element of the original array. The map() method takes a callback function as an argument, which is applied to each element of the original array. The callback function should return a new value that will be used as the corresponding element of the new array.

- The syntax for using the map() method is as follows:

```js
const newArray = originalArray.map(callbackFunction);
```

- Here, originalArray is the array you want to transform, and callbackFunction is the function that will transform each element of the original array. The map() method will return a new array, newArray, which will contain the transformed elements.

- For example, let's say we have an array of numbers that we want to double:

```js
const numbers = [1, 2, 3, 4, 5];

const doubledNumbers = numbers.map((num) => num * 2);

console.log(doubledNumbers); // Output: [2, 4, 6, 8, 10]
```

- In this example, the map() method is used to create a new array, doubledNumbers, by multiplying each element of the numbers array by 2. The resulting array, doubledNumbers, will contain the transformed elements [2, 4, 6, 8, 10].

The map() method is a useful tool for transforming arrays and is commonly used in JavaScript applications.

</details>

<details>
<summary>
  <h3>What is class ? (Click Me)</h3>
</summary>
<br >

- ক্লাস একটি টেমপ্লেট যা একটি অবজেক্ট তৈরি করতে ব্যবহৃত হয়। একটি ক্লাস শুরু করতে হলে, আমাদের ক্লাস ডিফিনেশন লিখতে হবে। এরপর ক্লাস এর নাম লিখে তৈরি করতে হবে। ক্লাস এর নাম এবং অন্য ক্লাস প্রপার্টি গুলো সব সময় প্রথম অক্ষর বড় হয়।

- কনসট্রাক্টর হল ক্লাস থেকে অবজেক্ট তৈরি করার সময় কল হওয়া একটি স্পেশাল মেথড। কনসট্রাক্টর ব্যবহার করে আমরা ক্লাস থেকে অবজেক্ট তৈরি করতে পারি।

- মেথড হল ক্লাসের ফাংশন। ক্লাস এর মেথড সব সময় ক্লাসের অবজেক্টের সাথে কল হতে হয়।

- ক্লাস থেকে অবজেক্ট তৈরি করার জন্য new অপারেটর ব্যবহার করা হয়। new অপারেটর এর মাধ্যমে অবজেক্ট তৈরি করা হয়।

- উদাহরণ :

```js
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  sayHello() {
    console.log(`Hello, my name is ${this.name} and I am ${this.age} years old.`);
  }
}

const person1 = new Person('John', 30);
const person2

```

```js
class Instructor {
  name;
  designation = " We Couse Instructor";
  team = "Web Team";
  location;

  constructor(name, location) {
    this.name = name;
    this.location = location;
  }
  startSuportSession(time) {
    ` start the support session at ${time}`;
  }

  createQuiz(module) {
    console.log(` Please create quiz for module ${module} `);
  }
}
```



</details>


# JavaScript-Api-practice  


<details>
<summary>
  <h3>What is internet ? (Click Me)</h3>
</summary>
<br >

- The Internet is a global network of interconnected computers and devices that communicate with each other using a standardized set of protocols. It enables the exchange of information and data across vast distances, connecting people, organizations, and communities from all over the world.

```js

```

```js

```

</details>

<details>
<summary>
  <h3>What is IP addresses ? (Click Me)</h3>
</summary>
<br >

- IP addresses (Internet Protocol addresses) are unique numerical identifiers assigned to every device connected to a computer network that uses the Internet Protocol for communication. In other words, it is a numerical label assigned to each device, such as a computer or smartphone, that connects to the internet. IP addresses serve two primary functions: identifying the host or network interface and providing a location of the device in the network. IP addresses can be either static, which means they remain the same over time, or dynamic, which means they change periodically. IP addresses are essential for communication between devices on the internet, as they enable devices to send and receive data packets to the correct destination.

```js

```

```js

```

</details>

<details>
<summary>
  <h3>What is class ? (Click Me)</h3>
</summary>
<br >

- The Domain Name System (DNS) is the phonebook of the Internet
- human acces online throgh domain Name like rakib.com or espn.com
- web browser Interact throgh Internet protocol (IP) address
- DNS translates domain names to ip address so browsers can load internet resources

#### how to work dns

- DNS works by translating human-readable domain names, such as www.example.com, into machine-readable IP addresses, such as 192.0.2.1, which are used to identify devices on the internet. The process typically involves several steps:

- 1. When a user types a domain name into their web browser or other application, the application sends a request to a DNS resolver to obtain the corresponding IP address.

- 2. The DNS resolver first checks its local cache to see if it has a record of the IP address for the requested domain name. If the record is found, the resolver returns the IP address to the application.

- 3. If the record is not found in the local cache, the resolver sends a request to one or more DNS servers to find the IP address for the domain name.

- 4. The DNS servers work together in a hierarchical system to locate the IP address. If the requested domain name is a top-level domain (TLD), such as .com or .org, the resolver sends the request to a root DNS server, which responds with the IP addresses of the TLD DNS servers.

- 5. The resolver then sends the request to the appropriate TLD DNS server, which responds with the IP address of the DNS server responsible for the next level of the domain name hierarchy.

- 6. This process continues until the resolver receives the IP address of the DNS server responsible for the requested domain name.

- 7. The resolver then sends a request to the DNS server for the IP address of the domain name.

- 8. The DNS server responds with the IP address, and the resolver caches the record for future use.

- 9. Finally, the resolver returns the IP address to the application, which uses it to establish a connection with the server hosting the requested website.

- 10. This entire process is usually completed within a few milliseconds, allowing users to access websites and other resources on the internet quickly and easily.

```js

```

```js

```

</details>

<details>
<summary>
  <h3>What is HTTP?  ? (Click Me)</h3>
</summary>
<br >

- HTTP stands for Hypertext Transfer Protocol. It is an application protocol that governs how data is transmitted between clients and servers over the internet. Specifically, it is the protocol that enables communication between web browsers and web servers, allowing users to access websites and other online resources.

- HTTP operates by establishing a connection between a client, such as a web browser, and a server, which hosts the requested resource. The client sends an HTTP request to the server, specifying the resource it wants to access, such as a webpage or a file. The server then responds with an HTTP response, which includes the requested resource, along with other information, such as headers and metadata.

- HTTP is a stateless protocol, which means that each request/response transaction is independent of all others. This allows for efficient and scalable communication over the internet, as multiple clients can send requests to a server simultaneously without interfering with each other.

- HTTP is also extensible, allowing for the development of new features and functionality to be added over time. For example, HTTPS (HTTP Secure) is an extension of HTTP that adds encryption and authentication to enhance security.

- Overall, HTTP is a fundamental protocol of the internet, enabling users to access a vast array of online resources quickly and easily.

- Bangla :
- HTTP অর্থ হলো Hyper Text Transfer Protocol। ইন্টারনেটে টিসিপি/আইপি প্রটোকলের মাধ্যমে যে প্রটোকল ওয়েব সার্ভার ও ওয়েব ক্লায়েন্ট-এর মধ্যে ডেটা আদান-প্রদান করে তাকে এইচটিটিপি (HTTP) বলে। ক্লায়েন্ট বিভিন্ন ব্রাউজারের মাধ্যমে ওয়েবপেইজের জন্য সার্ভারকে অনুরোধ পাঠাতে থাকে। সার্ভার ক্লায়েন্টের অনুরোধে সাড়া দিয়ে ওয়েবপেইজকে ক্লায়েন্টের কাছে পাঠিয়ে দেয়। ক্লায়েন্ট বিভিন্ন ব্রাউজারের মাধ্যমে তা দেখতে পায়। আর যার মাধ্যমে ডেটা আদান-প্রদান হয় তা হলো এইচটিটিপি (HTTP)। সুতরাং এইচটিটিপি (HTTP) এর কাজ হচ্ছে– সার্ভারের সাথে ব্রাউজারের সংযোগ তৈরি করা, ব্রাউজারের যেকোনো অনুরোধ সার্ভারে পৌছে দেওয়া, ব্রাউজারের অনুরোধে সার্ভারের সাড়া মোতাবেক ওয়েবপেইজকে ব্রাউজারে নিয়ে আসা, ব্রাউজার এবং সার্ভারের সংযোগ বিচ্ছিন্ন করা।

```js

```

```js

```

</details>

<details>
<summary>
  <h3>What is API ? (Click Me)</h3>
</summary>
<br >

- In JavaScript, an API (Application Programming Interface) is a set of protocols, routines, and tools for building software applications. Specifically, an API allows developers to access the functionality of an existing system, such as a web service, database, or operating system, and use it to build new applications.

- APIs can be used in a variety of ways in JavaScript, such as:

- Web APIs: These are APIs built into web browsers that provide JavaScript developers with access to a variety of features and functionality, such as the Document Object Model (DOM), XMLHttpRequest (XHR), and Web Storage.

- T- hird-party APIs: These are APIs developed by third-party organizations that provide developers with access to their services, such as social media platforms, weather data, or financial data.

- Custom APIs: These are APIs developed by individual developers or organizations to provide access to their own systems or services.

- In JavaScript, developers typically interact with APIs by making requests using HTTP (or HTTPS) protocols and receiving responses in a standardized format, such as JSON (JavaScript Object Notation) or XML (Extensible Markup Language). This allows developers to easily integrate different systems and services into their applications, making them more powerful and versatile.

```js

```

```js

```


</details>


<details>
<summary>
  <h3>What is JSON ? (Click Me)</h3>
</summary>
<br >

- JSON (JavaScript Object Notation) is a lightweight data-interchange format that is used to transmit data between applications. It is based on a subset of the JavaScript programming language and is both human-readable and machine-readable. JSON is widely used for data serialization, which is the process of converting data objects into a format that can be easily transmitted over a network or stored in a file.

- JSON consists of two primary data structures: objects and arrays. An object is an unordered collection of name/value pairs, while an array is an ordered list of values. Both objects and arrays can be nested within each other to create complex data structures.

- Here is an example of a simple JSON object:

```js
{
  "name": "John Smith",
  "age": 32,
  "email": "john.smith@example.com"
}

```

- Bangla : JSON (JavaScript Object Notation) হল একটি লাইটওয়েট ডেটা-ইন্টারচেঞ্জ ফরম্যাট যা একটি জাভাস্ক্রিপ্ট অবজেক্টের মতো ডেটা স্ট্রাকচার বা ডেটা ফরম্যাট। এর উদ্দেশ্য অ্যাপ্লিকেশনগুলির মধ্যে ডেটা পাঠানোর জন্য একটি লাইটওয়েট ফরম্যাট উপস্থাপন করা। এটি জাভাস্ক্রিপ্টের একটি সাধারণ ডেটা ফরম্যাট হিসাবে ব্যবহৃত হয়।

JSON তিনটি প্রাথমিক ডেটা স্ট্রাকচার ব্যবহার করে: অবজেক্ট, অ্যারে, এবং স্ট্রিং। অবজেক্ট হল নেম/ভ্যালু পেয়ারের অসংখ্য সংগ্রহণ, অ্যারে হল মূলত নম্বরিত একটি সংগ্রহণ এবং স্ট্রিং হল টেক্সট স্ট্রিং বা বর্ণমালা। এই তিনটি স্ট্রাকচার একটি JSON ডেটা স্ট্রাকচার তৈরি করতে ব্যবহৃত হয়।

JSON ব্যবহার করা হয় ডেটা সিরিয়ালাইজেশনের জন্য, যা ডেটা অবজেক্টগুলি নেটওয়ার্কে পাঠান

example :

```js
const user = { id: 1, name: "Gorib Aamir", job: "Actor" };
//  javaScript object notation

const stringify = JSON.stringify(user);
console.log(user);
console.log(stringify);

/* { id: 1, name: 'Gorib Aamir', job: 'Actor' }
{"id":1,"name":"Gorib Aamir","job":"Actor"} */

const shop = {
  owner: "Alia",
  address: {
    street: "kochukhet voot er goli",
    city: "ranbir",
    country: "BD",
  },
  products: ["laptop", "mic", "monitor", "keyboard"],
  revenue: 45000,
  isOpen: true,
  isNew: false,
};

console.log(shop);
const shopJson = JSON.stringify(shop);
console.log(shopJson);
const shopObj = JSON.parse(shopJson);
console.log(shopObj);
```

</details>
 
# explore-Javascript-object
 

<details>
<summary>
  <h3> Way to create js Obejct ? (Click Me)</h3>
</summary>
<br >

- 1: Object literal notation: This is the most common way to create a JavaScript object. You define the object using curly braces {} and add properties and methods inside it.

```js
const person = {
  name: "John",
  age: 30,
  address: {
    city: "New York",
    country: "USA",
  },
  sayHello: function () {
    console.log("Hello!");
  },
};
```

- 2 : Constructor function: You can also create an object using a constructor function. You define a function and use the new keyword to create an instance of the object.

```js
function Person(name, age, address) {
  this.name = name;
  this.age = age;
  this.address = address;
  this.sayHello = function () {
    console.log("Hello!");
  };
}

const person = new Person("John", 30, { city: "New York", country: "USA" });
```

- 3: Object.create() method: You can use the Object.create() method to create a new object with a specified prototype object.

```js
const personPrototype = {
  sayHello: function () {
    console.log("Hello!");
  },
};

const person = Object.create(personPrototype, {
  name: { value: "John" },
  age: { value: 30 },
  address: { value: { city: "New York", country: "USA" } },
});
```

- 4 : ES6 class syntax: You can also create an object using the class syntax introduced in ES6.

```js
class Person {
  constructor(name, age, address) {
    this.name = name;
    this.age = age;
    this.address = address;
  }

  sayHello() {
    console.log("Hello!");
  }
}

const person = new Person("John", 30, { city: "New York", country: "USA" });
```

</details>











# more-Javascript-concept 

<details>
<summary>
  <h3> JavaScript Engine V8 Internal mechanism
? (Click Me)</h3>
</summary>
<br >

- JavaScript Engine V8 is an open-source JavaScript engine developed by Google for use in Google Chrome and other Chromium-based web browsers. It is also used in other environments like Node.js, MongoDB, and Deno.

- V8 is written in C++ and is designed to compile JavaScript code into machine code at runtime, which allows it to execute JavaScript much faster than traditional interpreters. V8's internal mechanism includes several components:

- Parser: It parses the JavaScript code and converts it into an abstract syntax tree (AST) representation.

- Compiler: It compiles the AST into an optimized machine code that can be executed by the CPU.

- Garbage Collector: It automatically manages the memory used by JavaScript objects and releases it when it is no longer needed.

- Execution engine: It executes the compiled machine code and generates the output.

- Profiler: It collects data on how the JavaScript code is executed and provides performance analysis.

- Just-In-Time (JIT) Compiler: It optimizes the execution of frequently used code by dynamically generating machine code at runtime.

- Overall, V8's internal mechanism is designed to provide fast and efficient execution of JavaScript code while managing memory usage and optimizing performance.

- বাংলা ঃ জাভাস্ক্রিপ্ট ইঞ্জিন V8 হল গুগল ক্রোম ও অন্যান্য ওয়েব ব্রাউজার এবং সার্ভার সাইড জাভাস্ক্রিপ্ট এপ্লিকেশনগুলির জন্য উপযোগী একটি ইঞ্জিন। এটি জাভাস্ক্রিপ্ট কোডকে রান করানোর জন্য ব্যবহৃত হয়। V8 একটি কম্পাইলার এবং ইন্টারপ্রেটার দুটির মধ্যে একটি সমন্বয় সিস্টেম ব্যবহার করে কোড রান করে। এটি হাই-পারফরম্যান্স সরঞ্জাম যা জাভাস্ক্রিপ্ট কোডকে সবচেয়ে দ্রুত চলার জন্য উন্নয়ন করে।

V8 এর মূল কাজ হল জাভাস্ক্রিপ্ট সোর্স কোডকে মেশিন কোডে কম্পাইল করা এবং সেটি রান করা। এই ইঞ্জিনের কম্পাইলারটি সোর্স কোডকে স্ট্রিং অবজেক্ট এবং টোকেন এরে এ কনভার্ট করে এবং একটি স্ট্রিং অবজেক্ট তৈরি করে যা কম্পাইলার তারপর পার্স করে। কম্পাইলার কোডটি রান করার জন্য একটি অ

```js

```

</details>
<details>
<summary>
  <h3> what is JavaScript Execution Context and Call stack

? (Click Me)</h3>

</summary>
<br >

- javaScript Execution Context is a conceptual wrapper around the code which contains information about the environment where the code is being executed. It includes the variables, functions, and the scope chain. Whenever the JavaScript engine runs the code, it creates an execution context for that code.

- The Call Stack is a mechanism used by the JavaScript engine to keep track of the execution context while executing the code. Whenever the JavaScript engine enters a function, it creates a new execution context for that function and pushes it onto the top of the call stack. And when the function completes its execution, the engine pops the execution context off the top of the call stack and moves to the context below it.

- The call stack follows the Last-In-First-Out (LIFO) principle which means that the last function that is pushed into the stack will be the first function to come out of the stack. The call stack helps to maintain the order of execution of the JavaScript code and ensures that the function calls are executed in the correct order.

- জাভাস্ক্রিপ্টে একটি Execution Context হল একটি এলাকা বা কনটেক্সট যেখানে জাভাস্ক্রিপ্ট ইন্টারপ্রেটার সম্পর্কিত তথ্য সংরক্ষণ করে। প্রতিটি Execution Context এ সংরক্ষিত হতে পারে নিচের তথ্যগুলি:

- Variable Object (VO) বা একটি ভ্যারিয়েবল সম্পর্কিত তথ্যের অবজেক্ট, যেখানে সমস্ত ভ্যারিয়েবল, ফাংশন এবং আরো অন্যান্য তথ্যগুলি থাকে।
- Scope Chain, যেটি স্কোপ চেইন প্রস্তুত করে তার সাহায্যে বিভিন্ন ভ্যারিয়েবলের এক্সেস করা যায়।

- this কীওয়ার্ড বা কোথাও কোন ফাংশন কল করা হলে যা সেট করা হয়।

- যখন একটি ফাংশন কল করা হয়, তখন একটি Execution Context তৈরি করা হয় এবং তারপর এটি Call Stack এ স্ট্যাক হিসেবে রাখা হয়। Call Stack এ সেটা একটি স্ট্যাক পরিচালিত করা হয়, যা প্রথমে আগে কল করা হল সেটা পরে হতে থাকে। যখন কোন ফাংশন শেষ হয় তখন সেটি Call Stack থেকে রিমুভ হয় এবং তারপর সে

```js

```

</details>
<details>
<summary>
  <h3> What is Single-threaded

? (Click Me)</h3>

</summary>
<br >

- In computing, single-threaded refers to a system or process that can only execute one task or process at a time. In other words, there is only one execution context or call stack. In a single-threaded system, if a task or process is currently being executed, any other task or process that needs to be executed will have to wait until the previous task is completed. This can lead to performance issues in some cases, particularly when dealing with complex or time-consuming tasks. However, single-threaded systems are often simpler and easier to manage than multi-threaded systems, which require more complex synchronization mechanisms to manage multiple threads executing concurrently.

- সিঙ্গল-থ্রেডেড মানে হলো একটি থ্রেড ব্যবহার করে কোন কাজ করা। এর মানে হলো কোন প্রোগ্রাম বা একটি অংশ সিঙ্গল থ্রেড মডেলে চলবে অর্থাৎ একটি সময়ে কেবল একটি টাস্ক নির্দিষ্ট করা থাকে। একটি সিঙ্গল থ্রেডেড এনভায়রনমেন্টে কোন কাজ করতে পারলে অন্য কাজ শুরু হতে হবে না এবং না শেষ হওয়া না পর্যন্ত অন্য কোন কাজ চলতে পারে।

```js

```

</details>
<details>
<summary>
  <h3> JavaScript  Asynchronous vs Synchronous

? (Click Me)</h3>

</summary>
<br >

- JavaScript is a single-threaded language, which means it can only perform one task at a time. However, it can handle both synchronous and asynchronous operations.

- Synchronous operations block the execution of the program until they are completed. This means that the program will not move on to the next line of code until the current operation is finished. For example, when using the alert() method in JavaScript, the program will pause until the user clicks the "OK" button.

- Asynchronous operations, on the other hand, allow the program to continue running while waiting for an operation to complete. This is achieved through the use of callbacks, promises, and async/await functions. Asynchronous operations are commonly used when making network requests or performing I/O operations, as these operations can take a long time to complete and would otherwise block the execution of the program.

- By using asynchronous operations, JavaScript programs can be more efficient and responsive, as they can continue running while waiting for time-consuming operations to complete.

- বাংলা ঃ
- JavaScript একটি সিঙ্গেল থ্রেডেড ভাষা এবং সিঙ্গেল থ্রেড মানে হল একটি সিঙ্গেল কমান্ড লাইনে কোড একবারে একটি কাজ করতে পারে। এটি মানে হল একটি কমান্ড লাইন একবারে শুধুমাত্র একটি কাজ সম্পন্ন করে এবং এরপর একটি নতুন কাজ শুরু করে।
- জাভাস্ক্রিপ্ট এসিঙ্ক্রোনাস এবং সিঙ্ক্রোনাস কি সেটা বুঝাতে গেলে, এসিঙ্ক্রোনাস অপারেশনগুলি লাইন বাই লাইন একটি করে সম্পাদিত হয়। অর্থাৎ, একটি অপারেশনের সম্পাদনা শেষ হওয়া পর্যন্ত সেটির পরবর্তী লাইনের কোন অপারেশন শুরু হবে না। অন্যদিকে, সিঙ্ক্রোনাস অপারেশনগুলি পূর্বে শেষ হওয়া পর্যন্ত অপেক্ষা করতে হয়।
- একটি সিঙ্ক্রোনাস অপারেশন একটি ব্লকিং অপারেশন, অর্থাৎ যখন একটি অপারেশন সম্পন্ন হয় তখন পরবর্তী কোন অপারেশন শুরু হবে না এবং প্রোগ্রাম ব্লক করা থাকে একটি লক করে। সিঙ্ক্রোনাস অপারেশনগুলি আমাদের অনেকটা সিস্টেমের কাছে কম স্কেলেবল। অতএব এই ধরনের অপারেশনগুলি ব্যবহার করা উচিত না যদি প্রোগ্রামের কাজ যথেষ্ট ব্যবধান সৃষ্টি করে এবং প্রোগ্র

```js
console.log(1);
console.log(2);
const timeoutId = setTimeout(() => {
  console.log("lazy logged");
}, 4000);
console.log(4);
console.log(5);
console.log(6);

function doSomething() {
  console.log(3);
}
let num = 0;
const intervalId = setInterval(() => {
  console.log(num++);
}, 1000);
```

</details>

<details>
<summary>
  <h3> JavaScript Promise
? (Click Me)</h3>
</summary>
<br >

- A Promise is a built-in JavaScript object that represents the eventual completion or failure of an asynchronous operation and its resulting value. It is a way to handle asynchronous code and provide a structure for organizing complex async code.

- A Promise can have three states:

- Pending: The initial state, neither fulfilled nor rejected.
- Fulfilled: The operation completed successfully, and the resulting value is available.
- Rejected: The operation failed, and the reason for the failure is available.
- Promises allow us to attach callbacks to handle the eventual success or failure of an asynchronous operation. It makes it easier to reason about and compose asynchronous code.

- The Promise API also provides methods like Promise.all() and Promise.race() that allow us to run multiple asynchronous operations in parallel and handle their results.

- বাংলা : Promise হল JavaScript এর একটি স্পেশাল অবজেক্ট। Promise হল এমন একটি অবজেক্ট যা কোন একটি নির্দিষ্ট কাজ সম্পন্ন হলে কোন একটি রেজাল্ট বা এরর দিয়ে জবাব দেয়। Promise দুটি স্টেট রাখে, একটি হল "Pending" এবং অন্যটি হল "Fulfilled" বা "Rejected"। একবার Promise ফাংশন কল করা হলে তার স্টেট পরিবর্তন করা সম্ভব না। পরবর্তী কোন সময়ে তার স্টেট পরিবর্তন হতে পারে।

- প্রমিসের সাথে কাজ করতে হলে তার then() বা catch() মেথডগুলি ব্যবহার করতে হয়। then() মেথডটি সফলভাবে একটি প্রমিস ফাঁকা হলে কাজ করে। যদি একটি প্রমিস রিজেক্টেড হয় তবে প্রথম রিজেক্ট করা হয়েছে এবং ফাঁকা হয়ে যাবে catch() মেথডটি।

- Promise এর উপযোগী সময় হল সমস্ত অপারেশন asynchronous বা কোড ব্লকিং না করে চালানোর জন্য। Promise এর মাধ্যমে কোডটি নন-ব্লকিং থাকে এবং একটি বিশ্বাসযোগ্য জবাব প্রদ

```js
const getData = new Promise((resolve, reject) => {
  const num = Math.random() * 10;
  if (num < 5) {
    resolve(4343434);
  }
  // resolve(545454)
  else {
    reject("No date Available");
  }
});
getData.then((data) => console.log(data + 22)).catch((err) => console.log(err));
```

</details>

<details>
<summary>
  <h3> JavaScript Async/Await
? (Click Me)</h3>
</summary>
<br >

- Async/Await is a modern syntax in JavaScript for handling asynchronous operations. It allows you to write asynchronous code that looks like synchronous code, making it easier to understand and maintain.

- The async keyword is used to mark a function as asynchronous, and the await keyword is used to wait for a Promise to resolve. When an async function is called, it returns a Promise that resolves with the return value of the function or rejects with an error.

- Here's an example of using async/await to fetch data from a server:

- বাংলা ঃ Async/Await হল জাভাস্ক্রিপ্ট এর একটি ফিচার যা এসিংক্রোনাস কোড লিখতে সহায়তা করে। এটি সাধারণত প্রমিসের উপর নির্ভর করে এবং প্রমিস রিটার্ন করতে পারে। Async কীওয়ার্ডটি ফাংশন সম্পর্কিত বুঝায় এবং Await কীওয়ার্ডটি একটি প্রমিসের রেসপন্সের জন্য অপেক্ষা করতে সাহায্য করে। এটি সহজে বললে, Async/Await ব্যবহার করে সমস্ত নেটওয়ার্ক কল এবং ফাংশনগুলো একটি ব্লকিং সিস্টেম থেকে স্বতন্ত্রভাবে করা যায়। এটি প্রমিসের চেইনিং সহ প্রমিস ভিত্তিক কোড লিখার সময় প্রয়োজনীয় বিভিন্ন ফাংশন কল করার সময় প্রোমিসের রেসপন্সের জন্য অপেক্ষা করতে হয় না।

```js
async function fetchData() {
  try {
    const response = await fetch("https://example.com/data");
    const data = await response.json();
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}
// In this example, the fetchData function is marked as async. It uses the await keyword to wait for the response from the server, and then waits for the response body to be parsed as JSON. If there's an error, it's caught and logged to the console.
```

</details>

<details>
<summary>
  <h3>  what is JavaScript event loop

? (Click Me)</h3>

</summary>
<br >

- JavaScript event loop is a mechanism that allows JavaScript to handle concurrency by executing multiple code blocks without blocking the main execution thread. It is responsible for managing the execution of asynchronous tasks and callbacks, ensuring that they are executed in a specific order and at the appropriate time.

- The event loop works by constantly checking the event queue and executing tasks as they are added to the queue. When an asynchronous task is started, it is added to the event queue with a callback function to be executed once the task is completed. The event loop continues to check the event queue and executes tasks in a first-in-first-out order.

- This allows JavaScript to execute multiple tasks simultaneously, without blocking the main execution thread or causing the program to freeze. It is essential for handling user input and other asynchronous events that require immediate attention while allowing other parts of the program to continue executing in the background.

- JavaScript এর event loop হল এমন একটি প্রক্রিয়া যা জাভাস্ক্রিপ্ট এর রানটাইম এনভায়রনমেন্টে চলতে থাকে। এটি একটি অসংখ্য জাভাস্ক্রিপ্ট কোডের অগ্রগতি বা রান টাইম প্রসেসিং পর্যবেক্ষণ করে সেগুলোকে সঠিক ক্রমানুসারে প্রদর্শিত করে। event loop এর মূল উদ্দেশ্য হল স্বচ্ছতার সাথে কোড রান করার জন্য বিভিন্ন জাভাস্ক্রিপ্ট অপারেশনের মধ্যে স্থানান্তর করা যায়। এটি জাভাস্ক্রিপ্ট রানটাইমের সবচেয়ে গুরুত্বপূর্ণ কাজের মধ্যে একটি। আমরা এক্সেকিউশন কনটেক্স্ট এবং কল স্ট্যাক সম্পর্কে ইতিমধ্যে আলোচনা করেছি, কিন্তু event loop ব্যবহার করে জাভাস্ক্রিপ্ট সিস্টেমের পেছনের দিকে কাজ করে যাওয়া হয়।

```js
function a() {
  console.log("a");
  b();
  console.log("aa");
}
function b() {
  console.log("b");
  d();

  console.log("bb");
}

function d() {
  console.log("dd");
  console.log("dddd");
}

function x() {
  console.log("x");
  y();
  console.log("xx");
}
function y() {
  console.log("y");
  z();
  console.log("yy");
}
function z() {
  console.log("z");
  console.log("zz");
}
setTimeout(() => {
  console.log("inside the timeout");
}, 2000);
a();
```

</details>

<details>
<summary>
  <h3> JavaScript Engine V8 Internal mechanism
? (Click Me)</h3>
</summary>
<br >

- In JavaScript, error handling can be done using try, catch, throw, and finally statements. These statements are used to handle exceptions or errors that occur during the execution of a program.

- try: The try block contains the code that might throw an exception. The code is executed normally unless an exception occurs.

- catch: The catch block is executed when an exception is thrown in the try block. It catches the exception and handles it. The catch block takes an argument that is the error object that contains information about the exception.

- throw: The throw statement is used to throw an exception. When an exception is thrown, the program execution is stopped and the control is transferred to the nearest catch block.

- finally: The finally block is executed after the try and catch blocks, regardless of whether an exception was thrown or not. It is used to execute code that needs to be executed regardless of the outcome of the try block.

Here's an example of how to use these statements together:

```js
try {
  // code that might throw an exception
  const num = 10 / 0; // throws an exception
} catch (error) {
  // handle the exception
  console.log("An error occurred: ", error.message);
} finally {
  // execute code that needs to be executed regardless of the outcome
  console.log("Finally block executed.");
}
```

```js
function checkAge() {
  const ageField = document.getElementById("age");
  const textAge = ageField.value;

  const errorTag = document.getElementById("error");

  try {
    const age = parseInt(textAge);
    if (isNaN(age)) {
      throw "Please enter a number";
    } else if (age < 18) {
      throw "Baccha kaccha not allow";
    } else if (age > 30) {
      throw " murrubi ra ekhane aisen nah";
    }
    errorTag.innerHTML = "";
  } catch (err) {
    // console.log("ERRRO", err);
    errorTag.innerHTML = "Error :" + err;
  } finally {
    console.log("All Done inside try catch");
  }
}
```

</details>

<details>
<summary>
  <h3> JavaScript  synchronous and asynchronous 
? (Click Me)</h3>
</summary>
<br >
- জাভাস্ক্রিপ্টে সিঙ্ক্রোনাস এবং অ্যাসিঙ্ক্রোনাস কোড এক্সিকিউশনের মধ্যে পার্থক্য কি তা হলো সিঙ্ক্রোনাস কোড লাইন বাই লাইন একটা একটা সম্পূর্ণ হওয়ার পর নিষ্পত্তি নেয় যে একটি কাজ শেষ হয়ে গেছে আর এরপর একটি কাজ শুরু হবে। অন্যদিকে অ্যাসিঙ্ক্রোনাস কোড অনেক ক্ষেত্রে লাইন বাই লাইন একটা সম্পূর্ণ না হওয়ায় প্রথম কাজ নিষ্পত্তি নেয়া হয় না। এটি ব্যবহৃত হয় যখন নেটওয়ার্ক কল, ফাইল রিডিং, অ্যাপি কল, টাইমাউট এর মতো অপারেশন এর জন্য অপেক্ষা করতে হয়। এই অপারেশন এর প্রতিরোধ করা যায় যেন একটি অপারেশন চলমান থাকতে পারে অন্য অপারেশন চালু হওয়ার আগে। এর ফলে অ্যাসিঙ্ক্রোনাস কোড বেশ কমপ্লেক্স হয় সিঙ্ক্রোনাস কোড এর তুলনায়।

```js

```

</details>

<details>
<summary>
  <h3> 
? instruction (Click Me)</h3> 
</summary>
<br >

- ১) এই টেক্সট instruction এর পরে দেওয়া ভিডিও টা দেখে আসুন, তারপর আবার এখানে back করবেন।

- ২) নিচের লিঙ্ক দুইটার কোনোটাতে চলে যান। নিজের মত করে কিছু practise করে ফেলুন google/ chatgpt থেকে example নিয়ে event loop এর, আমি একটা example এখানে video তে দেখিয়েছি। আপনিও কাছাকাছি টাইপের কিছু example নিজে নিজে ট্রাই করলে event loop এর পুরো flow টা বুঝে যাবেন।Link-1:http://latentflip.com/loupe/

- Link-2: https://www.jsv9000.app/

- ৩) এবার ইউটিউব এ যান। js event loop লিখে সার্চ করুন। Bangla/ hindi/ english etc. যেই language এর যেই youtuber এর playlist আপনার পছন্দ তার ভিডিও টা মনযোগ দিয়ে দেখে ফেলুন দুইবার।

- ৪) এখন আপনার task শেষ। মনে মনে পুরো process টা একবার ভাবুন।

```js

``` 
</details>  

# debugging-practice

<details>
<summary>
  <h3> What is Debugging
? (Click Me)</h3>
</summary>
<br >

- Debugging is the process of identifying and resolving errors, bugs, and issues in software code. It is an essential step in the software development life cycle to ensure that the code functions as intended and delivers the expected results. Debugging involves using various tools, techniques, and methods to isolate and diagnose the source of a problem in the code, such as using a debugger, logging, breakpoints, and testing. Once the issue is identified, it can be fixed, and the code can be tested again to ensure that it works as intended.

- ডিবাগিং কি জানার চেষ্টা করা হয় একটি প্রোগ্রাম বুঝতে কতটা সঠিকভাবে কাজ করছে কিংবা কোথায় এরর হচ্ছে তা জানতে। সহজ কথায়, প্রোগ্রামিং এরর সমাধান করার পদক্ষেপ হল ডিবাগিং। এটি কোডে সমস্যার কারণ সনাক্ত করা এবং সমস্যার সমাধানের জন্য কোড সম্পাদনা করার মাধ্যমে কাজ করে। ডিবাগিং টুল সহজে একটি প্রোগ্রাম ক্রমানুসারে চালনা করতে এবং সমস্যার স্থান ও সময় নির্দিষ্ট করতে সহায়তা করে।

```js

```

</details>

<details>
<summary>
  <h3> error in js 
? (Click Me)</h3>
</summary>
<br >

- Syntax errors: These errors occur when the code violates the syntax rules of JavaScript. For example, missing a closing bracket or semicolon, using a reserved keyword as a variable name, or using an invalid character in a variable name.
- Runtime errors: These errors occur during the execution of the code. Some common examples include trying to access an undefined variable, passing the wrong type of argument to a function, or attempting to execute code on a null object.
- Logical errors: These errors occur when the code is syntactically correct and runs without errors, but the output is not what was expected. Logical errors are often caused by a mistake in the algorithm or a wrong assumption about the data. They can be the hardest type of error to debug, as the code may appear to be working correctly, but the output is incorrect.
- Network Errors: These occur when there is a problem with network connectivity, such as a failed HTTP request or a DNS lookup failure.
- System Errors: These occur when there is a problem with the system, such as running out of memory or exceeding the maximum call stack size.

- When an error occurs, it is important to identify the type of error and the cause so that it can be fixed. This can be done by using debugging tools such as console.log statements, breakpoints, and error handling code.

```js

```

</details>


# all-about-browsers 




  <details>
<summary>
  <h3> যে জিনিস তোমাকে জানতে হবে 
? (Click Me)</h3>
</summary>
<br >

১. ব্রাউজার কিভাবে কাজ করে। কিভাবে DOM tree, Render Tree বানায় সেটা ছোট করে হলেও নামগুলো জানতে হবে

২. alert, confirm, prompt এই গুলা কোনটা দিয়ে কী কাজ করে। এবং এইগুলার মধ্যে পার্থক্য কি?

৩. URL এর মধ্যে মেজর যে যে অংশ থাকে যেমন query string, href, hash, port এইগুলা জানতে হবে।

৪. location এর মধ্যে href দিয়ে যে যে ওয়েবসাইট দেখতেছো সেটা চেইঞ্জ করে ফেলা যায় সেটা জানতে হবে।

৫. History api এর মধ্যে যে go দিয়ে সামনে পিছনে যেতে পারো সেটা একটু খেয়াল করতে হবে।

৬. Cookies কি জিনিস। এইটা দিয়ে কি করা হয়। সেটা সম্পর্কে হালকা করে জানতে হবে।

৭. local storage আর session storage কখন কোনটা ইউজ করতে হয় সেটা জানতে হবে

৮. Cookies, local storage, session storage এর মধ্যে পার্থক্য কি সেটা জানতে হবে।

-

```js

```

</details>

<details>
<summary>
  <h3> ব্রাউজার কিভাবে কাজ কর
? (Click Me)</h3>
</summary>
<br >

- একটি ওয়েব ব্রাউজার সম্প্রদায়ক সফটওয়্যার যা ইন্টারনেটে সংযুক্ত হয় এবং ওয়েব পেজগুলি প্রদর্শন করে। ব্রাউজার কিভাবে কাজ করে তা নিম্নোক্ত ধাপগুলি মোটামুটি অনুসরণ করে:

- ব্রাউজার ইউজারের রিকোয়েস্ট গ্রহণ করে। ইউজার যখন একটি URL টাইপ করে বা একটি লিঙ্কে ক্লিক করে একটি ওয়েব পেজ লোড করতে চায়, ব্রাউজার একটি রিকোয়েস্ট তৈরি করে।

- ডিএনএস সার্ভার থেকে ইউআরএল এর হোস্টের আইপি ঠিকানা সংগ্রহ করে। সার্ভারটি একটি রিসপন্স প্রেরণ করে যা ইউআরএল-এর হোস্টের আইপি ঠিকানা সহ থাকে।

- সার্ভারটি রিকোয়েস্ট পেতে পারে এমন পুরোটাই থাকলে সেটি সরাসরি রিসপন্স করে এবং ব্রাউজার ডাটা পাঠায়। আরও কমন হয় যে সার্ভারটি ডাটা বিল্ড করতে পারে এবং তারপর র

- A web browser is a software application that connects to the internet and displays web pages. Here is a general overview of how a web browser works:

- The user enters a URL or clicks on a link to access a web page. The browser sends a request to the server for the page.

- The server returns an HTML file with CSS and JavaScript files attached. The browser starts to parse the HTML and construct a Document Object Model (DOM) tree.

- As the browser parses the HTML, it creates a DOM tree, which is a hierarchical structure of HTML elements and their relationships.

- The browser requests additional resources like images, stylesheets, and JavaScript files.

- Once all the resources are downloaded, the browser renders the page by applying the CSS styles to the HTML elements and executing the JavaScript code.

- The browser displays the final rendered page on the screen, allowing the user to interact with the page.

- The user can then interact with the page by clicking on links, filling out forms, or performing other actions that cause the browser to send requests to the server and update the page.

- The browser continues to run JavaScript code and listen for user input, repeating the process of requesting and rendering pages as needed.

- In summary, a web browser works by fetching and rendering web pages, executing JavaScript code, and allowing users to interact with the page. It does this by parsing HTML, creating a DOM tree, and applying CSS styles to the elements. The browser also requests additional resources like images and JavaScript files, and updates the page as users interact with it.

```js

```

</details>
<details>
<summary>
  <h3> BOM (Browser Object Model) and DOM (Document Object Model)
? (Click Me)</h3>
</summary>
<br >

- BOM (Browser Object Model) and DOM (Document Object Model) are two distinct but related APIs in web development. Here are the main differences between BOM and DOM:

- Definition: The BOM is a set of objects and methods provided by the browser to allow developers to manipulate the browser window and its properties, while the DOM is a set of objects and methods that represent the HTML or XML document and allow developers to access and manipulate its content and structure.

- Scope: The BOM provides objects and methods for manipulating the browser window, such as opening and closing windows, resizing, and scrolling, whereas the DOM provides objects and methods for manipulating the HTML or XML document, such as accessing and changing the content of elements, adding or removing elements, and handling events.

- Object hierarchy: The BOM objects are not hierarchical, while the DOM objects are hierarchical, forming a tree-like structure with the document element at the top.

- Standardization: The DOM is a standard defined by the W3C (World Wide Web Consortium), while the BOM is not a standardized API and varies between different browsers.

- Compatibility: The DOM is more widely supported and compatible across different browsers than the BOM.

- In summary, BOM provides access to browser-specific functionalities, while the DOM provides access to the document content and structure. The DOM is a standardized API and is widely supported, while the BOM is not standardized and varies across different browsers

-

```js

```

</details>
<details>
<summary>
  <h3> Location API is a browser
? (Click Me)</h3>
</summary>
<br >

###### - The Location API is a browser API that provides access to the current location and URL of the browser. It allows developers to obtain information about the current location of the user and to change the location of the current document. The Location API is a part of the BOM (Browser Object Model) and provides access to the location object, which has properties and methods that allow developers to manipulate the location of the current document.

###### - The most commonly used properties of the location object include:

- href - returns the entire URL of the current page.
- protocol - returns the protocol (http, https, ftp, etc.) of the current page.
- host - returns the domain name and port number of the current page.
- hostname - returns the domain name of the current page.
- port - returns the port number of the current page.
- pathname - returns the path and filename of the current page.
- search - returns the query string of the current page.
- hash - returns the anchor part of the current page URL.

###### - The most commonly used methods of the location object include:

- assign(url) - loads a new document with the specified URL.
- replace(url) - replaces the current document with the specified URL.
- reload() - reloads the current document.
  Overall, the Location API is a powerful tool for developers to manipulate the URL of the current page and to provide location-based functionality in web applications.

- লোকেশন এপিআই হল ব্রাউজার এপিআই এর একটি যা ব্যবহারকারীর ব্রাউজারের বর্তমান লোকেশন এবং ইউআরএল এর বিষয়বস্তু প্রদান করে। এটি ডেভেলপারদের জন্য সুযোগ সৃষ্টি করে ব্যবহারকারীর বর্তমান লোকেশন সম্পর্কিত তথ্য পেতে এবং বর্তমান ডকুমেন্টের লোকেশন পরিবর্তন করতে। লোকেশন এপিআই ব্রাউজার অবজেক্ট মডেল (BOM) এর একটি অংশ এবং লোকেশন অবজেক্ট অ্যাক্সেস প্রদান করে, যা বর্তমান ডকুমেন্টের লোকেশন এবং এর প্রপার্টি এবং মেথডগুলি পরিবর্তন করতে সক্ষম করে।

- লোকেশন অবজেক্টের সবচেয়ে ব্যবহৃত প্রপার্টিগুলি হল:

- href - বর্তমান পৃষ্ঠার সম্পূর্ণ URL পেতে।
- protocol - বর্তমান পৃষ্ঠার প্রোটোকল (http, https, ftp, ইত্যাদি) পেতে।
- host - বর্তমান পৃষ্ঠার ডোমেইন নাম এবং পোর্ট ন

```js

```

</details>

<details>
<summary>
  <h3> What is cookie

? (Click Me)</h3>


</summary>
<br >
 
- A cookie is a small text file created by a web server and stored on a user's computer by their web browser. Cookies are commonly used by websites to track and store information about their users, such as their preferences, login status, and browsing history.

- Cookies are typically used to identify a user across multiple visits to a website, allowing the website to personalize the user's experience and remember their preferences. For example, a shopping website might use cookies to remember a user's shopping cart contents, so that they can continue shopping where they left off during a previous visit.

- Cookies can store a wide variety of information, such as user IDs, timestamps, and browsing history. When a website uses a cookie, the cookie is sent from the web server to the user's browser, which stores the cookie on the user's computer. The next time the user visits the website, their browser sends the cookie back to the web server, allowing the website to access the stored information.

- While cookies are a useful tool for many websites, they can also be used for tracking and advertising purposes, which has led to concerns about user privacy. Many web browsers allow users to disable or restrict cookies, or to clear their cookies and browsing history to protect their privacy

- কুকিজ হল একটি ছোট টেক্সট ফাইল যা ওয়েব সার্ভার দ্বারা তৈরি এবং ব্যবহারকারীর ওয়েব ব্রাউজার দ্বারা স্টোর করা হয়। কুকিজ সাধারণত ওয়েবসাইট ব্যবহারকারীদের ট্র্যাক করতে এবং তাদের সংজ্ঞায়িত করতে ব্যবহৃত হয়।

- কুকিজ সাধারণত বহুল ব্যবহৃত হয় ওয়েবসাইট ব্যবহারকারীদের পছন্দ, লগইন স্ট্যাটাস এবং ব্রাউজিং হিস্ট্রি সম্পর্কে তথ্য সংরক্ষণ করতে। কুকিজ সাধারণত ব্যবহারকারীকে একই ওয়েবসাইটে পুনরায় প্রবেশ করলে তাদের অভিজ্ঞতা ব্যক্তিগত করে এবং তাদের পছন্দ মুলতুবি সংরক্ষিত থাকে।

- কুকিজ বিভিন্ন ধরণের তথ্য সংরক্ষণ করতে পারে, যেমন ব্যবহারকারী আইডি, টাইমস্ট্যাম্প এবং ব্রাউজিং হিস্ট্রি। যখন একটি ওয়েবসাইট কুকি ব্যবহার কর

-

```js

```

</details>
<details>
<summary>
  <h3> parts of cookie

? (Click Me)</h3>

</summary>
<br >


- A cookie typically consists of four parts:

- 1. Name: The name of the cookie.
- 2. Value: The value associated with the cookie.
- 4. Expiration Date/Time: The date and time when the cookie should expire and be deleted.
- 5. Path and Domain: The domain and path for which the cookie is valid.

  - The "name" and "value" are the only required parts of a cookie. The "expiration date/time" and "path/domain" are optional.

- The "name" is a string that identifies the cookie, and the "value" is the data associated with the cookie. Both the name and value can be up to 4KB in size.

- The "expiration date/time" specifies when the cookie should expire. Once the expiration time has passed, the cookie will be deleted by the browser.

- The "path" and "domain" specify the domain and path for which the cookie is valid. If no domain is specified, the cookie is valid for the domain that set the cookie. If no path is specified, the cookie is valid for the entire domain.

- কুকির পার্টস হলঃ

- নাম (Name): এটি কুকির নাম নির্দেশ করে। এটি কুকি সেট করার সময় ব্যবহৃত হয়।

- মান (Value): এটি কুকির মান নির্দেশ করে। এটি কুকি সেট করার সময় ব্যবহৃত হয়।

- এক্সপায়ার টাইম (Expires Time): এটি নির্দেশ করে কুকি কতক্ষন পরে মেয়াদ উত্তীর্ণ হবে। এটি কুকি সেট করার সময় ব্যবহৃত হয়।

- ডোমেইন (Domain): এটি নির্দেশ করে কুকি যে ডোমেন এপ্লাই হবে। এটি কুকি সেট করার সময় ব্যবহৃত হয়।

- পাথ (Path): এটি নির্দেশ করে কুকি কোন পাথ এপ্লাই হবে। এটি কুকি সেট করার সময় ব্যবহৃত হয়।

- সিকিউর (Secure): এটি নির্দেশ করে কুকি কেবল সিকিউর কানেকশনসহ পাঠানো হবে কিনা।

```js

```

</details>
<details>
<summary>
  <h3>What is loacal storage


? (Click Me)</h3>
</summary>
<br >

- লোকাল স্টোরেজ (Local Storage) হল ওয়েব ব্রাউজারের একটি ফিচার যা ব্যবহারকারীর ডেটা স্থায়ীভাবে সেভ করে রাখে। এটি একটি ব্রাউজার স্টোরেজ ইঞ্জিন যা ক্লায়েন্ট সাইড স্টোরেজ সেট করে।

- লোকাল স্টোরেজ একটি জাভাস্ক্রিপ্ট API এবং এটি ওয়েব স্টোরেজ এপিআইর একটি অংশ। এটি সিধান্তগুলি ব্যবহার করে ব্রাউজারের মধ্যে স্থায়ী ডেটা সেভ করতে পারে। এটি সংগ্রহকারী আকারে ব্যবহার করা যেতে পারে যা সেশন কুকির সাথে তুলনায় অনেকটা মিল করে, কিন্তু সেশন কুকির থেকে কোনও উদ্দেশ্যে ব্যবহার করা যায় না।

- লোকাল স্টোরেজ এর সুবিধা হল এটি স্থায়ীভাবে ডেটা সেভ করে রাখতে পারে যা সেশন শেষ হওয়ার পরে ওয়েবসাইট বা এপ্লিকেশনে সেট করা ডেটার উপর নির্ভর করে না। এছাড়াও লোকাল স্টোরেজ ডে

```js

```

</details> 









# Javascript-Problem-Solved

<details>
<summary>
  <h3>js Problem Solved (Click Me)</h3>
</summary>
<br >

```js

### Number 1 
//Number 1 => Example 1
// charecter forword way of String (string  টা কে  সোজা দিক থেকে console.log করা)
// text = myString কারণ  parametar যেইটাই পাঠাই না কেন অন্য নামে recive kore 
// যেমন myString হিসাবে পাঠাইছে  text হিসাবে recived করছে
function reverseString(text){
    for(let i = 0; i < text.length; i++){
        const element = text[i];
        console.log(element)
        
        
    }
}
//Number 1 => Example 2
// charecter reverse way of String (string টা কে উল্টা দিক থেকে console.log করা)
function reverseString(text){
    for(let i = text.length; i >= 0; i--){
        const element = text[i];
        console.log(element)
    }
}

const myString = 'i am a good boy';
const reversed = reverseString(myString);
console.log(reversed)

//Number 1 => Example 3
// Word reverse way of String (string টা কে উল্টা দিক থেকে console.log করা)
function reverseWord(str){
    //split kore potita word ke alada alada kor hoisa
    const words = str.split(' ');
    const result = [];
    //-1 last element er index 1 kom (undifiend jate na dekhai) 
    for(let i =  words.length - 1; i >= 0; i--){
        const element = words[i];
        
        result.push(element)
    }
    // word gulo ek sentens anar jonno join kora hoisa
    const reversed = result.join(' ');
    return reversed;
}
const myString = 'i am a good boy';
const reversed = reverseWord(myString);
console.log(reversed)

//Number 1 => Example 4
// আগের দুটা মান যোগ করে পরের মান সেট করা
//const fibonacci = [0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144]
/* 
    fibo[3] = fibo[2] + fibo[1]
    fibo[4] = fibo[3] + fibo[2]
    fibo[n] = fibo[n-1] + fibo[n-2]
    fibo[3] = fibo[i-1] + fibo[i-2]
*/
const fibo  = [0, 1];
// 0, 1 already define(0 ,1  value diyai dici tai 2 theke start korta hobe)
for(let i = 2; i <= 25; i++){
    fibo[i] = fibo[i - 1] + fibo[i - 2]
}
console.log(fibo)

//Number 1 => Example 5
//Remobe name duplicate From An Array
const  names = ['abul', 'babul', 'kable', 'dabul', 'ebul', 'babul', 'abul', 'kabul', 'gabul', 'cabul', 'babul', 'abul', 'abul', 'cabul'];
function removeDuplicate(names){
    const unique = [];
    for(let i = 0; i < names.length; i++){
        if(unique.includes(name) === false){
            unique.push(name)
        }
    }
    return unique;
}
const uniqueName = removeDuplicate(names);
console.log(uniqueName)
//Remobe Number duplicate From An Array
const friends = [12, 45, 32, 22, 44, 62, 29, 23, 22, 12, 45, 44, 69, 87];
function removeDuplicateNumber(friends) {
    const uniqueNumber = [];
    for (const friend of friends) {
        if (uniqueNumber.includes(friend) === false) {
            uniqueNumber.push(friend)
        }
    }
    return uniqueNumber
}
console.log(removeDuplicateNumber(friends))


<--Number 2-->
//Number 2 => Example 1
/* 
// Show output from 1-100
1. if the number is divisible by 3 then insted of the show 'foo', is number 5 then show 'bar'
2. if the number divisible by both 3and 5 then instead of the number show 'footbar'
*/
for (let i = 1; i <= 50; i++) {
    if (i % 3 === 0 && i % 5 === 0) {
        console.log('foobar')
    }else if (i % 3 === 0) {
        console.log('foo')

    } else if (i % 5 === 0) {
        console.log('bar')

    } else {
        console.log(i)
    }
}

//Number 2 => Example 2
/* 
Fixed: per item wood requirments
Vary: quantity
1. chair --> 3 cft
2. table --> 10 cft
3. bed --> 50 cft
*/
function woodCalculator(chairQuantity, tableQuantity, bedQuantity){
    const perChariWood =  3;
    const perTableWood = 10;
    const perBedWood = 50;

    const chairWood = chairQuantity * perChariWood;
    const tableWood = tableQuantity * perTableWood;
    const bedWood = bedQuantity * perBedWood;

    const total = chairWood + tableWood + bedWood;
    return total;
}
const totalWood = woodCalculator(2, 1, 1);
console.log('total wood required', totalWood)

//Number 2 => Example 3
// find cheapest price in array of object
const phones = [
    { name: 'Samsung', camera: 12, storage: '32gb', price: 36000, color: 'silver' },
    { name: 'Waltor', camera: 10, storage: '32gb', price: 22000, color: 'silver' },
    { name: 'Iphone', camera: 10, storage: '32gb', price: 82000, color: 'silver' },
    { name: 'Xiomi', camera: 10, storage: '32gb', price: 52000, color: 'silver' },
    { name: 'Oppo', camera: 10, storage: '32gb', price: 20000, color: 'silver' },
    { name: 'Nokia', camera: 10, storage: '32gb', price: 44000, color: 'silver' },
    { name: 'HTC', camera: 10, storage: '32gb', price: 62000, color: 'silver' },
    { name: 'Techno', camera: 10, storage: '32gb', price: 12000, color: 'silver' }
];
function cheapestPhone(phones) {
    let cheapest = phones[0]
    for (const phone of phones) {
        if (phone.price < cheapest.price) {
            cheapest = phone;
        }
    }
    return cheapest;
}

const mySelection = cheapestPhone(phones);
console.log(mySelection)

//Number 2 => Example 4

/* 
1.if ticket numbers is less then 100, per ticket price: 100
2.if tikcket numbers is more than 100, but less than 200. first 100  ticket price will be 100. rest tickets will be 900 taka per ticket.
    first 100 --> 100 tk
    rest ---> 90 tk
3. if you perchase more than tickets
first 100 ---> 100 tk
101-200 ---> 90 tk
200 + ---> 70 tk
*/
function ticketPrice(ticketQuantity){
    const first100Ticket = 100;
    const second100Ticket = 90;
    const restTicket = 70;
    if(ticketQuantity <= 100){
        const price = ticketQuantity * first100Ticket;
        return price;
    }
    else if(ticketQuantity <= 200){
        const first100Price = 100 * first100Ticket;
        const restTicketQuantity  = ticketQuantity - 100;
        const restTicketPrice  = restTicketQuantity * second100Ticket;
        const totalPrice = first100Price + restTicketPrice;
        return totalPrice;
    }
    else{
        const first100Price = 100 * first100Ticket;
        const second100Price = 100 * second100Ticket;
        const restTicketPrict = ticketQuantity - 200;
        const restTicketPrice = restTicketPrict * restTicket;
        const totalPrice = first100Price + second100Price + restTicketPrice;
        return totalPrice;
    }
}
const price = ticketPrice(101);
console.log(price)

//Number 2 => Example 5

// array এর ভিতর কোন কোন কিছু খুঁজে বের করা
const products = [
    {id: 1, name: 'walton Phone', price: 1900, color: 'silver'},
    {id: 2, name: 'mac book air', price: 1900, color: 'green'},
    {id: 3, name: 'Samsung Phone', price: 1900, color: 'yellow'},
    {id: 4, name: 'lenovo yoga lapTOP 2025', price: 1900, color: 'black'},
    {id: 5, name: 'I phone Phone', price: 1900, color: 'red'},
    {id: 6, name: 'dell inspiron laptop', price: 1900, color: 'blue'},
    {id: 7, name: 'nokia old age phone gone', price: 1900, color: 'pink'},
    {id: 8, name: 'htc phone', price: 1900, color: 'white'},
];
//search parameter diya products এর ভিতর যে কোন কিছু খুঁজবো
function matchedProducts(products, search){
    //খুজে যেইটা পাবো তার জন্য array declare (matched) করতে হবে।
    const matched = [];
    
    for(const product of products){
        if(product.name.toLowerCase().includes(search.toLowerCase())){
            matched.push(product)
        }
    }
    return matched;
}
//যেই object a phone  আছে সেই object খুজে দাউ
const result = matchedProducts(products, 'laptop');
console.log(result)



<--Number 3-->
//Number 1 => Example 1

//find largest number
let arr = [3,5, 6, 7, 8, 34, 6,5, 76, 126]
let largest = arr[0]
for(let i = 0; i < arr.length; i++){
    const element = arr[i];
    if(element > largest){
        largest = element;
    }
}
console.log(largest)

//Number 3 => Example 2

// calculate Electricity bill
//for first 100 unit - 5 tk
//for more than 100 unit 6 tk for every unit more than 100
//for more than 200 unit 7 tk for every unit more than 200
// 250 unit
//100 * 5 = 500
//(200 - 100) * 6
//(250 - 200) * 7

function electricity(unit) {
    let bill;
    if (unit <= 100) {
        bill = unit * 5
    } else if (unit <= 200) {
        const first100 = 100 * 5;
        const remaining = unit - 100;
        const remainingCost = remaining * 6;
        bill = first100 + remainingCost;
    } else if(unit > 200){
        const first100 = 100 * 5;
        const second100 = 100 * 6;
        const remaining = unit - 200;
        const remainingBill = remaining * 7;
        bill = first100 + second100 + remainingBill
    }
    return bill;
}

const result = electricity(150);
console.log(result)

//Number 3 => Example 3
// find if anybody got A+ from your friends
// marks = [78, 82, 69]
function checkGPA(arr){
    for(const mark of arr){
        if(mark >= 80){
            return true
        }
    }
    return false;
}
const result = checkGPA([78, 62, 69]);
console.log(result)

//Number 3 => Example 4
//check if a number is Prime
//1 number 11
//2 => number-1
function isPrime(number){
    for(let i = 2; i < number; i ++){
        if(number % i == 0){
            return false
        }
    }
    return true;
}
const result = isPrime(19);
console.log(result)

//Number 3 => Example 5

	
	

```
</details>


### jsProblemQuestions

<details>
<summary>
  <h3> js Problem questions</h3>
</summary>
<br >

```js
  
  
1) Harry’s mom gave him tk 1000 and asked him to buy some oranges and
apples. Write a program to help Harry calculate how much money the
shopkeeper will return. The total cost of 1 kg of oranges and 1 kg of
apples is tk 700.
2) Write a program to calculate the average marks of Mathematics,
Biology, Chemistry, Physics, and Bangla of a student.
3) John’s teacher gave him two variables. Each variable contains a string.
John’s teacher asked him to combine these two strings(‘I am going to
be’ and ‘an awesome web developer’) and print them in one line. Help
John write the program.
4) Sarah’s mother is teaching her mathematics. She gave Sarah the number
119 and asked her what the remainder would be if she divided the number
by 5. Help Sarah write the program.
  
5) নি চে র ভে রি য়ে বল ডি ক্লে য়ার এ ক োনটার মধ্যে কি কি সমস্যা আছে । দে খত ো বে র করতে
পার ো কি না?
Var price = 33
var name - Shabana
var boxName = ‘Cocola;
var 88_price = 34;
var enum = -1;
var _$box’78 = ‘Monika’;
var home-address = “kochu khet”;
  
6) You are given an array:
var fruits = ['Apple', 'Banana', 'Orange'];
  a) Find the index of ‘Banana’ and replace ‘Banana’ with ‘Mango’.
  b) Remove ‘Orange’ and add ‘Watermelon
  
 7) You and your friends Tom, Jane, Peter and John got their final exam
results. Your total score is 85, Tom’s total score is 66, Jane’s total score is
95, Peter’s total score is 56 and John’s total score is 40. The grading
chart is
80 or above A grade
60 or above B grade
50 or above C grade
40 or above D grade
39 or less => F grade
Write a program to find your and your friends’ grades using
if-else.

 8) You are given three numbers 13, 79, and 45. Write a program that will
print the largest number using if-else.
9) You are given a triangle with the sides 9, 8, 9. Write a program to check
whether a triangle is Isosceles or not using if-else.
Isosceles => two sides are equal
10) ক্লাস সে ভে র এর ফাইনাল এক্সাম এ তুমি ফার্স্ট হয়ে ছ। ত োমার বন্ধুআলি য়া, ডালি য়া,
সালি য়া, মালি য়া, লি লি য়া আর জ্বালাইয়া - তাদে র grade তুমি জান ো না। তবে তাদে র নম্বর
জান ো. আলি য়া 95 পে য়ে ছে , ডালি য়া 66 পে য়ে ছে , সালি য়া 80 পে য়ে ছে , মালি য়া পে য়ে ছে 59,
লি লি য়া পে য়ে ছে 47, জ্বালাইয়া পে য়ে ছে 77। তুমি JS code দি য়ে তাদে র grade বে র করে
দি তে পারবে ?
১) যারা ৫০ এর নি চে পে য়ে ছে , তাদে র grade F.
২) যারা ৫০ বা তার উপরে পে য়ে ছে , অথবা ৬০ এর নি চে পে য়ে ছে , তাদে র grade D.
৩) যারা ৬০ বা তার উপরে পে য়ে ছে , অথবা ৭০ এর নি চে পে য়ে ছে , তাদে র grade C.
৪) যারা ৭০ বা তার উপরে পে য়ে ছে , অথবা ৮০ এর নি চে পে য়ে ছে , তাদে র grade B.
৫) যারা ৮০ বা তার উপরে পে য়ে ছে , অথবা ৯০ এর নি চে পে য়ে ছে , তাদে র grade A.
৬) যারা ৯০ বা তার উপরে পে য়ে ছে , তাদে র grade A+.
  
11) তাড়াহুড়া করে স্কুলে র জন্য বে র হচ্ছ কি ন্তু রাস্তা পার হওয়ার সময় দে খলে , ট্রাফি ক
সি গন্যাল লাল রং। এই অবস্থায় যদি তুমি রাস্তা পার হওয়ার চে ষ্টা কর, তাহলে ডে ঞ্জার হতে
পারে । যদি হলদু রং হয় তাহলে ত োমার থে মে যাওয়া উচি ত। আর যদি ট্রাফি ক সি গন্যাল গ্রি ন
হয় তাহলে ত োমার রাস্তা পার হওয়া উচি ত। তাই একটা ক োড লি খে ফে ল ো। যে খানে আমরা
signal নামে একটা ভে রি য়ে বল থাকবে । সে টার মান green, yellow বা red হতে পারে ।
সে ই অনসুারে ডি ফারে ন্ট ডি ফারে ন্ট কাজ হবে । ত ো, সে ই ক োড ফটাফট লি খে ফে ল ো।
12) প্রতি দি ন ত োমার কাজ কি ?
১) রাত ৮ টা বাজে মডি উল আনলক কর ো
২) ফটাফট ভি ডি ও দে খে দে খে প্রাকটিস কর ো
৩) ভি ডি ও দে খতে দে খতে ন োটস নাও
৪) মডি উল শে ষ হলে পুরা মডি উল নি জে নি জে প্রাকটিস কর ো
৫) ক োন কি ছুবঝু তে না পারলে (চি ন্তা করে দে খ ো এইখানে কি ন্তু একটা শর্ত আছে ), সাপ োর্ট সে শনে
জয়ে ন কর ো
এখন ত োমার কাজ হচ্ছে একটা for লপু ১০ বার চালি য়ে উপরে র জি নি সগুলা আউটপুট হি সে বে
দে খান ো।
13) আবার একই জি নি স while লপু চালি য়ে ১০ বার দে খান ো।
14) উপরে র প্রব্লে মটাই while লপু রি ভার্স ওয়ে তে (decremental হি সে বে )করে দে খাও
15) উপরে র প্রব্লে মটাই for লপু রি ভার্স ওয়ে তে (decremental হি সে বে )করে দে খাও
16) ত োমার কাছে : ৮০০০০ টাকার বে শি হলে তুমি mac কি নবে , ৬০ টাকার বে শি হলে gaming ল্যাপটপ
কি নবে , ৪০ হাজার টাকার বে শি হলে lenovo yoga কম্পি উটার কি নবে , ২০ হাজার টাকার বে শি হলে পুরান
ল্যাপটপ কি নবে । না হয় তুমি ম োবাইল দি য়ে কাজ চালাবে ।
17) আসকে আমার মন ভাল ো নে ই এই কথা ৩৯ বার আউটপুট হি সে বে দে খাও।
18) while লপু কি ভাবে কাজ কর
  19) একটা ক োড লি খে ৫৮ থে কে ৯৮ পর্যন্ত যত সংখ্যা আছে সে গুলাকে দে খাও
20) একটা ক োড লি খে ৪১২ থে কে ৪৫৬ পর্যন্ত যত জ োর সংখ্যা আছে সে গুলাকে
দে খাও
21) একটা ক োড লি খে ৫৮১ থে কে ৬২৩ পর্যন্ত যত বি জ োড় সংখ্যা আছে সে গুলাকে দে খাও
22) তুমি এতদি ন যা যা জি নি স শি খছ ো সে গুলার নাম দি য়ে একটা array বানাও। তারপর একটা
for লপু দি য়ে সে ই array এর সব উপাদান কে আউটপুট হি সে বে দে খাও।
23) তুমি এতদি ন পর্যন্ত যে যে মডে লে র ম োবাইল ফ োন ইউজ করে ছ ো সে গুলার নাম দি য়ে একটা
array বানাও। তারপর একটা while লপু দি য়ে সে ই array এর উপাদান গুলা একটা একটা করে
আউটপুট হি সে বে দে খাও
24) একটা ফর লপু চালাও। ৩০ থে কে ৮৬ পর্যন্ত। আর এই লপু ৪৪ এ গে লে ব্রে ক করবে । সে ই
জি নি স ক োড করে দে খাও
25) ত োমার যত বই আছে সে গুলার দাম নি য়ে একটা array লি খে ফে ল ো। যে বই গুল োর দাম ২০০
টাকার উপরে সে গুলাকে স্কি প করবে । অর্থাৎ সে গুলাকে আউটপুট হি সে বে দে খাবে না। বাকি দে র কে
আউটপুট হি সে বে দে খাবে । দে খ ো করতে পার ো কি না।
26) Write a function called foo() which prints “foo” and a function called bar()
which prints “bar”. Call function bar() in the foo() function after printing. What
will be the output? Now call the foo() to see the output.
27) Write a function called make_avg() which will take an three integers and
return the average of those values.
28) Challenging: Write a function called make_avg() which will take an array of
integers and the size of that array and return the average of those values.
29) Write a function called odd_even() which takes an integer value and tells
whether this value is even or odd. You need to do it in 4 ways:
● Has return + Has parameter
● No return + Has parameter
 30) You are in a hurry to go to your school on time. But when you are crossing
the road, the traffic signal is red coloured. In this situation, if you try to cross the
road, you may be in danger.If you notice a yellow coloured traffic signal, you
should stop. If you notice a green coloured traffic signal, you should cross the
road. So write a JS code, where there is a variable called signal. Its value can
be green, yellow or red & we will get different activities as output depending on
the variable. So, hurry up.
31) একটা ফাংশন লি খবা যে টা ১৩ এর নামতা (multiplication table) আউটপুট হি সে বে
দে খাবে ।
32) একটা ফাংশন লি খবা যে টা যে ক োন নামকে uppercase বা রে গুলার কে ইস হি সে বে নি বে আর
আউটপুট হি সে বে সে ই নাম lowercase করে রি টার্ন করবে ।
33) fullName নামে একটা ফাংশন তৈ রী কর যে টা ত োমার নামে র প্রথম অংশ এবং ত োমার
নামে র শে ষে র অংশ প্যারামি টার হি সে বে নি বে । আর ত োমার নামে র দইু অংশ জ োড়া দি য়ে আউটপুট
হি সে বে ত োমার পূর্ন নাম রি টার্ন করে দি বে । যে মন ধর ো, hablu এবং kanto ইনপুট প্যারামি টার
হি সে বে দি লে আউটপুট হি সে বে hablu kanto রি টার্ন করবে ।
34) একটা ফাংশন লি খবা যে টাকে তুমি ক োন সংখ্যাকে ইনপুট হি সে বে দি লে সে সে ই সংখ্যার
square করে সে ই square কে রি টার্ন করবে ।
অর্থাৎ তুমি ইনপুট হি সে বে 5 দি লে সে টাতে স্কয়ারে হি সে বে 25 আউটপুট হি সে বে পাবে ।
35) Write a function that will take hour as the input parameter and will convert it
into minutes and will return the result in minutes.
36) Write a function findLeapYear() that will take the array [2023, 2024, 2025,
2028, 2030] as the input parameter and will check if each year is a leap year. If
a year is a leap year insert that year in a new array, return the new array and
print the result.
37) Write a function findOddSum() that will take the array [ 5, 7, 8, 10, 45, 30 ]
as the input parameter and will return the sum of the odd numbers.
38) leapYear() নামে ফাংশন লি খ ো এবং নে ক্সট ইয়ার অর্থাৎ ২০২৩ কি leap year নাকি সে টা
চে ক কর ো। Leap year হলে ফাংশন true রি টার্ন করবে আর leap year না হলে false রি টার
 করবে ।
39) ত োমার বয়স কি odd নাকি even সংখ্যা সে টা চে ক কর একটা ফাংশন দি য়ে । সে ই
ফাংশনকে ক োন সংখ্যা প্যারামি টার হি সে বে দি লে , সে ই সংখ্যা Even হলে ফাংশন true রি টার্ন
করবে আর Odd হলে false রি টার্ন করবে ।
40) এমন একটা ফ্যাংশনা লি খ ো যে টাকে তুমি ঘন্টাকে ইনপুট প্যারামি টার হি সে বে দি বে । আর সে
সে ই ঘন্টাকে মি নি টে কনভার্ট করে মি নি ট রি টার্ন করবে ।
41) একটা লপু লি খতে হবে যে টা ১ থে কে ১০০ পর্যন্ত যত সংখ্যা আছে সে টা দে খাবে
42) ৫০ থে কে ৮০ এর মধ্যে যত ো বি জ োড় সংখ্যা আছে সে গুলাকে দে খাবে ।
43) তি নটা সংখ্যা এর য োগ করতে পারবে এমন একটা ফাংশন লি খ ো
44) ত োমাকে ফাংশনে র ইনপুট হি সে বে সে লসি য়াস দি বে । তুমি ক্যালকুলে শন করে তাপমাত্রা
ফারে নহাইট এ কনভার্ট করে সে টার আউটপুট রি টার্ন করবে
45) একইভাবে উল্টা হি সাব করবে । যাতে ত োমাকে ফারে নহাইট হি সে বে তাপমাত্রা দি লে সে টাকে
সে লসি য়াস এ কনভার্ট করে আউটপুট দি বে ।
46) কে উ ১০০ এর মধ্যে কত মার্ক্স্ পে য়ে ছে সে টা ত োমাকে বলে দি বে । তুমি একটা ফাংশন দি য়ে বলে
দি বে সে এ+ পাবে নাকি অন্য ক োন গ্রে ড পাবে ।
47) সুদে র হি সাব করবে । জাস্ট হি সাব কে মনে করতে হয়। সে ই চি ন্তায় করবে । সুদ ভাল ো না খারাপ
সে টা এখন চি ন্তা করার দরকার নাই। জাস্ট একটা ফর্মুলর্মু া থাকলে সে টা কি ভাবে ক োড এ লি খতে হয়
সে ই এঙ্গে ল থে কে করার চে ষ্টা কর ো।
48) Suppose, you have an array with 8 elements. Find the smallest element of
that array.
Now for the previous array, try to find the second largest element.
49) Write a function and take an array as a parameter. Find the average of all
the elements of that array and return this average.
50) Write a function which takes the height and width of a rectangle as
parameters. Find out the area of that rectangle and print the result.
  51) একটা ক োড লি খ ো। যে টা দি য়ে ক োন একটা array এর মধ্যে সবচে য়ে ছ োট
সংখ্যা বে র করে দি তে পারবে ।
52) একটা ক োড লি খ ো যে টা দি য়ে তি নটা সংখ্যার মধ্যে সবচে য়ে ছ োট সংখ্যা বে র
করে দি বে ।
53) একটা ফাংশন লি খ ো। সে ই ফাংশনে র মধ্যে ইনপুট হি সে বে একটা array নি বে ।
সে ই array এর মধ্যে অনে কগুলা সংখ্যা থাকবে । ত োমার কাজ হবে ইনপুট নে য়া
array এর মধ্যে যতগুলা সংখ্যা আছে । সে ই সংখ্যা গুলার গড় বে র করবে ।
তারপর সে ই গড় ফাংশনে র রি টার্ন হি সে বে দি য়ে দি বে । একটুচি ন্তা কর ো। বঝু ার
চে ষ্টা কর ো। ট্রাই কর ো। দে খ ো পার ো কি না।
54) একটা ফাংশন লি খ ো। যে টা ইনপুট প্যারামি টার হি সে বে একটা আয়তক্ষে ত্রে র
দৈ র্ঘ্য আর উচ্চতাকে নি বে । তারপর সে ই আয়তক্ষে ত্র এর area (আয়তন) কে
রে জাল্ট হি সে বে রি টার্ন করবে ।
55) (ট্রি কি ) ক োন একটা array এর মধ্যে অনে কগুলা সংখ্যা আছে । সে ই সংখ্যাগুল ো
থে কে second largest সংখ্যা বে র করার একটা প্র োগ্রাম লি খ ো। দরকার হলে
গুগলে সার্চ দাও। তারপর সার্চ রে জাল্ট দে খে বঝেুঝে বঝেুঝে করার চে ষ্টা কর ো।
56) একটা ফাংশন লি খ ো। সে টার মধ্যে তি নটা প্যারামি টার নি বে । এই তি নটা
প্যারামি টার হবে ক োন একটা ত্রি ভুজে র তি নটা বাহু এর দৈ র্য্য। এখন ত োমার কাজ
হচ্ছে ফাংশনে র ভি তরে কি ছুহি সাব নি কাশ করে ত্রি ভুজে র area (আয়তন) বে র
করা। ক োন একটা ত্রি ভুজে র তি নটা বাহুর দৈ র্য্য দে য়া থাকলে সে টা থে কে কি ভাবে
আয়তন বে র করতে হয় সে ই ফর্মুলর্মু া গুগল থে কে খুজেঁজে বে র কর ো।
57) ক োন একটা সংখ্যা প্রাইম সংখ্যা (prime number) কি না। সে টা চে ক করার একটা
ফাংশন লি খ ো।
58) দইুটা ভে রি য়ে বল এর মধ্যে য োগ, বি য় োগ, গুণ, ভাগ কি ভাবে করতে হয় সে টা কি জান ো।
অর্থাৎ তুমি কি +, -, *, /, %এইগুলার ব্যবহার জান ো। তাহলে নাম্বার টাইপে র দইুটা ভে রি য়ে বল
লি খ ো তারপর তাদে র য োগ করে সে টার মান আরে কটা ভে রি য়ে বল এ রাখ ো। একইভাবে ওই দইুটা
ভে রি য়ে বল এর মধ্যে বি য় োগ, গুন, ভাগ এবং ভাগশে ষ বে র কর ো।
59) তুমি কি দইুটা ভে রি য়ে বল এরমধ্যে তুলনা করতে পার ো। কম্পারি জন করতে পার ো। যে দইুটা
ভে রি য়ে বল এর মধ্যে প্রথমটা সে কে ন্ডটা এর চাইতে ছ োট, বড়, অসমান, সমান , ছ োট বা সমান,
  বড় বা সমান। এইগুলা চে ক করতে পার ো। অর্থাৎ <, >, ==, !=, <=, >= চি হ্নগুলা ব্যবহার করতে
পার ো। তাহলে দইুটা সংখ্যা টাইপে র ভে রি য়ে বল ডি ক্লে য়ার করে তাদে রকে এই ছয়ভাবে তুলনা করে
ক োড লি খে ফে ল ো।
.
60) ত োমার যদি দইুটা শর্ত পূরণ করতে বলে । এবং দইুটা শর্তে র মধ্যে দইুটাই পূরণ করতে হবে ।
তাহলে তুমি কি সে টা চে ক করতে পারবে ? একইভাবে যদি বলে তুমি দইুটা শর্তে র যে ক োন একটা
পূরণ করতে পারবে । অর্থাৎ তুমি && এবং || এর ব্যবহার করতে পার ো কি না। যদি পার ো তাহলে
নি জে নি জে এই রকমে র ক োড লি খে ফে ল ো।
61) তুমি কি একটা শর্ত পালন করলে একটা কি ছুকরবে । শর্ত পূরণ না করলে অন্য কি ছুএকটা
করবে এমন ক োড লি খতে পারবে । অর্থাৎ তুমি কি if-else এর ক োড লি খতে পারবে । পারলে একটা
ক োড লি খে ফে ল ো
.
62) ত োমাকে যদি বলে একটা while লপু দি য়ে ৭ থে কে ১৯ পর্যন্ত যতগুলা বি জ োড় সংখ্যা আছে
সে গুলা দে খাতে । তুমি কি সে টা দে খাতে পারবে ? পারলে সে ই ক োড লি খে ফে ল ো।
63) ত োমাকে যদি বলা হয় তুমি একটা array ডি ক্লে য়ার করবে । এবং সে টার মধ্যে কয়টা উপাদান
আছে সে টা বে র করবে হবে । সে ই array এর এর মধ্যে চতুর্থ পজি শন এর উপাদান চে ইঞ্জ করতে
হবে । array এর মধ্যে দইুটা উপাদান য োগ করতে হবে । এবং একটা উপাদান কে বে র করে দি তে
হবে । তুমি কি সে টা করতে পারবে ।
.
64) তুমি কি একটা ফর লপু দি য়ে ক োন একটা array এর সবগুলা উপাদানকে দে খাতে পারবে । সে টা
রে গুলার for লপু হ োক বা for of হ োক। হলে সে ই স্টাইলে একটা ক োড লি খে ফে ল ো।
65) ত োমাকে যদি বলা হয়। একটা array এর মধ্যে ৮০ এর চাইতে বড় সংখ্যা থাকলে সে গুলাকে
console log করে দে খাতে সে টা কি তুমি পারবে ? তাহলে তুমি সে ই ক োড করে ফে ল ো
.
66) তি নটা সংখ্যার গুনফল বে র করে ফাইনাল রে জাল্ট আউটপুট হি সে বে রি টার্ন করতে হবে । তুমি
কি সে ই ক োড লি খতে পারবে । যদি পার ো তাহলে সে ই ক োড লি খে ফে ল ো।
67) একটা অবজে ক্ট ডি ক্লে য়ার করবে । সে টাতে তি নটা প্রপার্টি থাকবে । এবং ক োন একটা প্র োপার্টি
এর মান চে ইঞ্জ করবা।
68) সি ম্পল একটা ফাংশন লি খতে হবে । যে টার নাম হবে feetToInch এবং এই ফাংশন
ইনপুট হি সে বে নি বে feet আর রি টার্ন করবে inch । অর্থাৎ এই ফাংশনকে ক োন
একটা ফি ট বলে দি লে সে রি টার্ন হি সে বে বলে দি বে কত ইঞ্চি হয়।
  69) একদম ফাংশন এর নাম হুবহু centimeterToMeter নাম দি য়ে একটা ফাংশন
লি খবে । এই ফাংশনে ইনপুট হি সাবে কে উ সে ন্টি মি টার দি বে আর সে ই সে ন্টি মি টার
কে মি টার এ কনভার্ট করে রে জাল্ট রি টার্ন করবে ।
.
70) আরে কটা ফাংশন লি খবে যে টার নাম লি খবে । যে ই ফাংশনে র নাম হবে paperRequirements
এই ফাংশনে র প্যারামি টার হি সে বে তি নটা প্যারামি টার হবে । প্রথম প্যারামি টার হবে তুমি প্রথম বই
কত কপি ছাপাতে চাও। সে কে ন্ড প্যারামি টার হবে তুমি সে কে ন্ড বই কত কপি ছাপাতে চাও। আর
থার্ড প্যারামি টার হবে তুমি থার্ড বই কত কপি ছাপাতে চাও। অর্থাৎ ক োন বই এর কত কপি ছাপান ো
হবে সে টাই প্যারামি টার হি সে বে নি বে ।
এইবার ভাল ো করে খে য়াল কর ো।
প্রথম বই ছাপান োর জন্য পৃষ্ঠা লাগবে ১০০ টা
সে কে ন্ড বই ছাপান োর জন্য পৃষ্ঠা লাগবে ২০০ টা
তৃতীয় বই ছাপান োর জন্য পৃষ্ঠা লাগবে ৩০০ টা
এখন ত োমার কাজ হচ্ছে paperRequirements নামক ফাংশন লি খে ফে লা যাতে । সে ই ফাংশনকে
কল করে ক োন বই এর কত কপি লাগবে বলে দি বে প্যারামি টার হি সে বে । আর ফাংশন হি সাব করে
বলে দি বে ত োমার সর্বম োট কতপৃষ্ঠা কাগজ লাগবে ।
উত্তর হি সে বে সংখ্যা রি টার্ন করবে ।
.
71) একটা ফাংশন লি খবে । এই ফাংশনে র নাম হবে bestFriend তারপর সে ই ফাংশনে
ইনপুট প্যারামি টার হি সে বে একটা array নি বে । সে ই array এর মধ্যে ত োমার সব
ফ্রে ন্ডে র নাম থাকবে । এখন ত োমার কাজ হচ্ছে যে ফ্রে ন্ড এর নাম সবচে য়ে বড় সে ই ফ্রে ন্ড এর
নাম রি টার্ন করে দে য়া। এই ক্ষে ত্রে তুমি নামটা অর্থাৎ ফ্রে ন্ডে র নাম (স্ট্রি ং) রি টার্ন করতে হবে ।
.
72) এইটা একটুট্রি কি হতে পারে । একটা array এর মধ্যে অনে কগুলা সংখ্যা থাকবে ।
ত োমার কাজ হচ্ছে সংখ্যা গুলা একটার পর একটা করে চে ক করা। এবং সংখ্যা
গুলা যদি পজি টিভ সংখ্যা হয়। অর্থাৎ শনূ্য বা শন্যেূন্যে র চাইতে বড় হয় তাহলে
সে গুলাকে ক োন একটা array এর মধ্যে রাখবে । আর যদি নে গে টিভ সংখ্যা হয়।
তাহলে লপুটা স্টপ করে দি বে । এবং লপু বন্ধ করার আগ পর্যন্ত যতগুলা পজি টিভ
সংখ্যা পাওয়া গে ছে । সে গুলা রি টার্ন করে দি বে ।
  
``` 
</details>


### Output
  
<details>
<summary>
  <h3>Check Output (Click Me)</h3>
</summary>
<br >
  
```js

বেসিক জাভাস্ক্রিপ্ট (ভেরিয়েবল, এরে, কন্ডিশন, লুপ) এর চেকলিস্ট। 
ভালো করে মনোযোগ দিয়ে একটার পর একটা চেকলিস্ট ধরে ধরে চেক করবে। একটাও বাদ দিবে। বাদ দিলেই তোমার আব্বার কাছে বিচার দিবো। 
১. জাভাস্ক্রিপ্ট কি জিনিস এইটা কি জানো?
২. জাভাস্ক্রিপ্ট কিভাবে কাজ করে সেটা কি জানো?
৩. ভেরিয়েবল কি জিনিস?
৪. ভেরিয়েবল কিভাবে ডিক্লেয়ার করে 
৫. ভেরিয়েবল এর মান কিভাবে চেইঞ্জ করে বা আপডেট করে। 
৬. কি কি ধরণের ভেরিয়েবল হয়। সেগুলা কি কি (হিন্টস: Numeric, String, Boolean)
৭. জাভাস্ক্রিপ এ primitive and non primitive data types কি কি ? উদাহরণ হিসেবে বলো। 
৮. ভেরিয়েবল এর নাম কিভাবে কিভাবে ডিক্লেয়ার করতে হয়। কোন কোন জিনিস নাম এ লেখা যাবে না। অর্থাৎ Variable এর naming convention সম্পর্কে বলো। 
৯. দুইটা ভেরিয়েবল এর মধ্যে =, -, *, /, % কিভাবে করে? 
১০. শর্টহ্যান্ড গুলো জানতে হবে। বিশেষ করে +=, -=, *=, /= জানতে হবে। 
১১.. ++ এবং -- এর কাজ কি ? এইটা কি জানো। 
১২ parseInt, parseFloat, toFixed এইগুলা কি করে? 
--------------
১৩. Array কি জিনিস। এইটা কিভাবে কাজ করে? কিভাবে Array ডিক্লেয়ার করতে হয় 
১৪. array এর মধ্যে কয়টা উপাদান (element) আছে সেটা কিভাবে বের করে 
১৫. array এর উপাদান গুলা এর পজিশন ( index) কিভাবে কাজ করে। কত দিয়ে শুরু হয়। এবং মান কিভাবে চেইঞ্জ হয়। 
১৬. কোন একটা উপাদানের index এর মান  -১ বলতে কি বুঝায় 
১৭. কিভাবে index দিয়ে কোন একটা array এর মধ্যে উপাদান এর মান খুঁজে বের করতে পারো 
১৮. কিভাবে কোন একটা index পজিশন এ array এর উপাদান এর মান চেইঞ্জ করতে পারবে 
১৯. একটা Array এর মধ্যে কোন একটা উপাদান এর মান তোমাকে দেয়া আছে এখন সেটার index তুমি কিভাবে খুঁজে বের করতে পারো?
২০. ধরো, কোন একটা ইনডেক্স দিয়ে উপাদান খুঁজতে গেছো। কিন্তু সেটার মান না দিয়ে তোমাকে undefined দেখাচ্ছে। সেটা দেখে তুমি কি বুঝবে? (একটু গুগলে সার্চ দাও। আমরা কোর্স এ এইটা আলোচনা করিনি। তারপরেও চেষ্টা করে দেখো)
২১. কোন একটা Array এর মধ্যে লাস্ট উপাদান হিসেবে কোন উপাদান হিসেবে যোগ করতে চাইলে কিভাৱে যোগ করবে। আবার Array থেকে শেষের উপাদান টা বের করে দিতে চাইলে কিভাবে বের করে দিবে
২২. কোন একটা Array এর মধ্যে প্রথম উপাদান হিসেবে কোন উপাদান হিসেবে যোগ করতে চাইলে কিভাৱে যোগ করবে। আবার Array থেকে প্রথম উপাদান টা বের করে দিতে চাইলে কিভাবে বের করে দিবে
২৩. তুলনা কিভাবে করতে হয়। এইগুলার মানে কি:  >, <, ==, !=, <=, >=, ===, !==, &&, ।। 
২৪. তোমার কাছে:  ৮০০০০ টাকার বেশি হলে তুমি mac কিনবে, ৬০ টাকার বেশি হলে gaming ল্যাপটপ কিনবে, ৪০ হাজার টাকার বেশি হলে lenovo yoga কম্পিউটার কিনবে , ২০ হাজার টাকার বেশি হলে পুরান ল্যাপটপ কিনবে। না হয় তুমি মোবাইল দিয়ে কাজ চালাবে। 
---------------------
২৫. আসকে আমার মন ভালো নেই এই কথা ৩৯ বার আউটপুট  হিসেবে দেখাও। 
২৬. while লুপ কিভাবে কাজ করে 
২৭. for লুপ কিভাবে কাজ করে 
২৮. while লুপ এর মধ্যে লুপ ভেরিয়েবল চেইঞ্জ না করলে কি সমস্যা হয়। 
২৯. একটা কোড লিখে ৫৮ থেকে ৯৮ পর্যন্ত যত সংখ্যা আছে সেগুলাকে দেখাও 
৩০.একটা কোড লিখে ৪১২ থেকে ৪৫৬ পর্যন্ত যত জোর সংখ্যা আছে সেগুলাকে দেখাও  
৩১. একটা কোড লিখে ৫৮১ থেকে ৬২৩ পর্যন্ত যত বিজোড় সংখ্যা আছে সেগুলাকে দেখাও 
৩২.while আর for loop এর মধ্যে পার্থক্য কি 
৩৩ তুমি এতদিন যা যা জিনিস শিখছো সেগুলার নাম দিয়ে একটা array বানাও। তারপর একটা for লুপ দিয়ে সেই array এর সব উপাদান কে আউটপুট হিসেবে দেখাও। 
৩৪. তুমি এতদিন পর্যন্ত যে যে মডেলের মোবাইল ফোন ইউজ করেছো সেগুলার নাম দিয়ে একটা array বানাও। তারপর একটা while লুপ দিয়ে সেই array এর উপাদান গুলা একটা একটা করে আউটপুট হিসেবে দেখাও 
৩৫. একটা ফর লুপ চালাও। ৩০ থেকে ৮৬ পর্যন্ত। আর এই লুপ ৪৪ এ গেলে ব্রেক করবে। সেই জিনিস কোড করে দেখাও 
৩৬. তোমার যত বই আছে সেগুলার দাম নিয়ে একটা array লিখে ফেলো। যে বই গুলোর দাম ২০০ টাকার উপরে সেগুলাকে স্কিপ করবে। অর্থাৎ সেগুলাকে আউটপুট হিসেবে দেখাবে না। বাকিদের কে আউটপুট হিসেবে দেখাবে। দেখো করতে পারো কিনা। 
------
উপরের ৩৬ এর মধ্যে যদি তুমি ৩০-৩৬ টা করে ফেলতে পারো তাহলে তুমি ভালোই অবস্থানে আছো। এইটা চালাতে থাকো। এখনো কিছু হয়ে যায়নি। তাই ওভার কনফিডেন্ট হওয়ার কিছু নাই এখনো তো বলতে গেলে তেমন কিছুই শুরু হয়নি। । জাস্ট চালাতে থাকো। 
.
যদি তুমি ২০-২৯ টা করে ফেলতে পারো তাহলে তুমি মোটামুটি চলে টাইপের অবস্থানে আছো। হালকা আরেকটু সিরিয়াস হলে বা সামনে করতে করতে লাইনে চলে আসবে। তোমার দ্বারা পসিবল। তবে এইটা ধরে রাখতে হবে। এবং সম্ভব হলে আরেকটু ভালো চেষ্টা করতে হবে। 
.
যদি তুমি ১০-১৯ টা করে ফেলতে পারো তাহলে তুমি টাইট সিচুয়েশন এ আছো। এফোর্ট ভালো দিতে হবে। চেষ্টার পরিমান বাড়াতে হবে। বুঝে নেয়ার চেষ্টা করতে হবে। মডিউল দেখার সাথে সাথে মনোযোগ বাড়াতে হবে। মডিউল বুঝতে না পারলে আমাদের হেল্প নিতে হবে। তাহলে লাইনে নিয়ে আসতে পারবে। একটু বেশি হার্ডওয়ার্ক করলে। 
.
আর যদি ০-৯ টা পারো। তাহলে সত্যি কথা হচ্ছে-- তোমার অবস্থা ভালো না। এইটাই বাস্তবতা। এবং এই কন্ডিশন চলতে থাকলে তোমাকে দিয়ে বেশি কিছু আশা করা যাবে না। এই অবস্থা থেকে উতরাতে হলে অনেক অনেক বেশি সময় দিতে হবে। অনেক অনেক অনেক বেশি এফোর্ট দিতে হবে।  এইটার পিছনে অনেক বেশি লেগে থাকতে হবে।

অনেকগুলো যদি বাটন থাকে এবং সেই বাটনের উপর বেইজ করে যদি কিছু ডিসপ্লে করতে হয় তাহলে নিচের কোন এপ্রোচ এ আগানো ওয়াইজ হবে?
১। প্রতিটা বাটনের জন্য আলাদা ইভেন্ট হ্যান্ডেলার অ্যাড করা এবং প্রতিটি ফাংশন থেকে ডিসপ্লে করা।
২। ইভেন্ট বাবল/ডেলিগেট করে একটি ইভেন্ট হ্যান্ডেলার অ্যাড করা এবং প্রাপ্ত ভ্যালুর উপর ইফ এলস কন্ডিশন (সুইচ কেইস বা স্ট্যাটিক অবজেক্ট ও ইউজ করা যেতে) ইউজ করে ডিসপ্লে করা।
৩। ইভেন্ট বাবল/ডেলিগেট করে একটি ইভেন্ট হ্যান্ডেলার অ্যাড করা এবং previousElementSibling /nextElementSibling.innerText এইভাবে খুজে খুজে তথ্য বের করে ডিসপ্লে করা।

```
</details>







