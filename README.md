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
- [javaScript-ES6](#javaScript-ES6)  
- [optional-chaining](#optional-chaining)   

- [JavaScript-Api-practice](#JavaScript-Api-practice)  
- [explore-Javascript-object](#explore-Javascript-object)  
- [more-Javascript-concept](#more-Javascript-concept) 
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
