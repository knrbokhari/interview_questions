# interview-

## Features
- [JavaScript](#JavaScript)
- [React](#React)
- [Nodejs](#Nodejs)
- [Express](#Express)
- [MongoDB](#MongoDB)

<!-- ![Power](https://imgLink.png) -->
<!-- 
| 1                             | 2                | 3                                                                     |
|-------------------------------|:----------------:|----------------------------------------------------------------------:|
| 1                             | 2                | 3                                                                     | 
| 1                             | 2                | 3                                                                     | -->

### JavaScript

#### What is javascript?

<details><summary><b>Answer:</b></summary>
<p>

JavaScript is a single-threaded, scripting language that enables us to create dynamically updating content, control multimedia, animate images, and pretty much everything else. JavaScript is used both on the client and server sides, allowing us to make web pages interactive.

</p>
</details>

<details><summary><b>Answer Banglai:</b></summary>
<p>

জাভাস্ক্রিপ্ট হল একটি single-threaded, scripting language যা আমাদেরকে dynamically content আপডেট করতে, মাল্টিমিডিয়া নিয়ন্ত্রণ করতে, ছবিগুলিকে অ্যানিমেট করতে এবং আরও অনেক কিছু করতে সক্ষম করে৷ জাভাস্ক্রিপ্ট ক্লায়েন্ট এবং সার্ভার উভয় দিকেই ব্যবহৃত হয়, যা আমাদের ওয়েব  page গুলিকে ইন্টারেক্টিভ করতে দেয়।

</p>
</details>

#### How .js file executed on the browser ?

<details><summary><b>Answer:</b></summary>
<p>

Every Web browser comes with a JavaScript engine that provides a JavaScript runtime environment. For example, Google Chrome uses the V8 JavaScript engine. V8 is an open-source JavaScript engine developed for Google Chrome and Chromium web browsers. <strong>
The browser’s built-in interpreter searches for `<script>` tag or `.js`  file linked with an HTML file while loading a web page, and then interpretation and execution start.</strong>

</p>
</details>

#### What is a callback function?

<details><summary><b>Answer:</b></summary>
<p>

A callback is a function passed as an argument to another function. 

```
function greeting(name) {
  alert(`Hello, ${name}`);
}

function processUserInput(callback) {
  const name = prompt("Please enter your name.");
  callback(name);
}

processUserInput(greeting);
```

</p>
</details>

#### What is a Closure in JavaScript? How does it work?

<details><summary><b>Answer:</b></summary>
<p>
A closure is a function having access to the parent scope, even after the parent function has closed. A closure gives us access to an outer function's scope from an inner function.

```
function makeFunc() {
  const name = 'Naeem';
  function displayName() {
    console.log(name);
  }
  return displayName;
}

const myFunc = makeFunc();
myFunc();
```
</p>
</details>

#### What is a recursive function?

<details><summary><b>Answer:</b></summary>
<p>
A recursive function solves a particular problem by calling a copy of itself and solving smaller subproblems of the original problems. 

```
function countDownFrom(number) {
	for (let i = number; i > 0; i--) {
		console.log(i);
	}	
}

countDownFrom(5)
```
</p>
</details>

#### Difference between undefined and null?

<details><summary><b>Answer:</b></summary>
<p>
undefined is a type, whereas null is an object. undefined means a variable is declared, but no value has been assigned a value. null in JavaScript is an assignment value. You can assign it to a variable.
</p>
</details>

#### What are the different data types in JavaScript?

<details><summary><b>Answer:</b></summary>
<p>
Data types in JavaScript define the type of data that a variable can store. JavaScript includes primitive and non-primitive data types. The primitive data types in JavaScript include string, number, boolean, undefined, null, and symbol. The non-primitive data type includes the object. A variable of primitive data type can contain only a single value.
</p>
</details>

#### What is DOM?

<details><summary><b>Answer:</b></summary>
<p>
DOM stands for Document Object Model. It is a programming interface that allows us to create, change, or remove elements from the document. 
</p>
</details>

#### Explain hoisting in JavaScript.


<details><summary><b>Answer:</b></summary>
<p>
In JavaScript, hoisting occurs during the creation phase of the execution context that moves the variable and function declarations to the top of the script.

![Power](https://www.tutorialsteacher.com/Content/images/js/hoisting.png)


</p>
</details>

#### Difference between undefined and null?

<details><summary><b>Answer:</b></summary>
<p>
undefined is a type, whereas null is an object. undefined means a variable is declared, but no value has been assigned a value. null in JavaScript is an assignment value. You can assign it to a variable.
</p>
</details>

#### What are the differences between “==” and “===”?

<details><summary><b>Answer:</b></summary>
<p>
== in JavaScript is used for comparing two variables, but it ignores the data type of the variable. === is used for comparing two variables, but this operator also checks the datatype and compares two values.

</p>
</details>

#### What is an event bubbling in JavaScript?

<details><summary><b>Answer:</b></summary>
<p>
Event bubbling is a way of event propagation in the HTML DOM API, when an event occurs in an element inside another element, and both elements have registered a handle for that event. With bubbling, the event is first captured and handled by the innermost element and then propagated to outer elements. The execution starts from that event and goes to its parent element. Then the execution passes to its parent element and so on till the body element.
</p>
</details>

#### What are the ways to define a variable in JavaScript?

<details><summary><b>Answer:</b></summary>
<p>

- <strong> Var </strong> – The JavaScript variables statement is used to declare a variable and, optionally, we can initialize the value of that variable. Example: var a =10; Variable declarations are processed before the execution of the code.
- <strong> Const </strong> – The idea of const functions is not allow them to modify the object on which they are called. When a function is declared as const, it can be called on any type of object.
- <strong> Let </strong> – It is a signal that the variable may be reassigned, such as a counter in a loop, or a value swap in an algorithm. It also signals that the variable will be used only in the block it’s defined in.

</p>
</details>

#### What is the purpose of ‘This’ operator in JavaScript?

<details><summary><b>Answer:</b></summary>
<p>
The JavaScript this keyword refers to the object it belongs to. This has different values depending on where it is used. In a method, this refers to the owner object and in a function, this refers to the global object.
</p>
</details>

#### What are the scopes of a variable in JavaScript?

<details><summary><b>Answer:</b></summary>
<p>
The scope of a variable is the region of your program in which it is defined. JavaScript variable will have only two scopes.
</p>
</details>

#### What is ECMAScript?

<details><summary><b>Answer:</b></summary>
<p>
ECMAScript is a scripting language based on JavaScript.
</p>
</details>

#### What is ES6?

<details><summary><b>Answer:</b></summary>
<p>
ECMAScript 2015 was the second major revision to JavaScript. ECMAScript 2015 is also known as ES6 and ECMAScript 6. ECMAScript provides the specification on how JavaScript programming language should work. ES6 comes with significant changes to the JavaScript language. It brought several new features like, let and const keyword, rest and spread operators, classes, modules, and many other enhancements to make JavaScript programming easier and more fun. 
</p>
</details>

#### Why will you use default parameters?

<details><summary><b>Answer:</b></summary>
<p>
Default function parameters allow named parameters to be initialized with default values if no value or undefined is passed.
</p>
</details>


#### How does the Spread operator work?

<details><summary><b>Answer:</b></summary>
<p>
The spread operator is a new addition to the set of operators in JavaScript ES6. The spread syntax works within array literals, function calls, and initialized property objects to spread the values of iterable objects into separate items.
</p>
</details>



#### What difference between class and object?

<details><summary><b>Answer:</b></summary>
<p>
A class is a template for creating objects in a program whereas the object is an instance of a class. A class is a logical entity while the object is a physical entity. A class does not allocate memory space on the other hand object allocates memory space. You can declare a class only once but you can create more than one object using a class. Classes can’t be manipulated while objects can be manipulated.

</br>

ক্লাস (Class) : অবজেক্ট অরিয়েন্টেড প্রোগ্রমিং এ সবার আগে ক্লাস (class) সম্পর্কে ধারনা নিতে হবে।ক্লাস হচ্ছে অবজেক্টের জন্য টেমপ্লেট।অবজেক্ট তৈরী করার আগে একটা ক্লাস তৈরী করে নিতে হয় এবং এই ক্লাসটিকেই instantiate করলে এটা একটা অবজেক্ট হয়ে যায় (new শব্দ দিয়ে instantiate করতে হয়->নিচে বিস্তারিত আছে)।ক্লাস তৈরীর জন্য প্রথমেই class এই শব্দটি লিখে এরপর যেকোন নাম দিতে হয় আর এরপর দ্বিতীয় বন্ধনির (curly braces) ভিতর সব কোড লিখতে হয়।
অবজেক্ট (Object) : অবজেক্ট হচ্ছে অবজেক্ট অরিয়েন্টেড প্রোগ্রামিং এর মুল মেশিন।একটা ক্লাস তৈরী করে তাকে আগে অবজেক্ট বানিয়ে নিতে হয় এরপর এই অবজেক্ট এর প্রোপার্টিজ এবং মেথডে একসেস নিয়ে কাজ করা হয়।ধরুন উপরে যে ক্লাসটি তৈরী করেছি সেটি যদি অবজেক্ট বানাতে চান তাহলে new শব্দটি দিয়ে নিচের মত করে কোড লিখতে হবে।

</p>
</details>


#### Explain Call by value vs call by reference.

<details><summary><b>Answer:</b></summary>
<p>
In the Call by Value method, there is no modification in the original value. In the Call by Reference method, there is a modification in the original value.
</p>
</details>


#### What is a Prototype chain?

<details><summary><b>Answer:</b></summary>
<p>
Each object has a private property that holds a link to another object called its prototype.  That prototype object has a prototype of its own, and so on until an object is reached with null as its prototype. By definition, null has no prototype, and acts as the final link in this prototype chain.
</p>
</details>

#### What is a Higher-order Function?

<details><summary><b>Answer:</b></summary>
<p>
A higher-order function is a function that takes a function as an argument, or returns a function. A higher-order function is in contrast to first-order functions, which don’t take a function as an argument or return a function as output.
</p>
</details>

#### Difference between Array vs LinkedList.

<details><summary><b>Answer:</b></summary>
<p>
An array is a collection of elements of a similar data type. A LinkedList is an ordered collection of elements of the same type in which each element is connected to the next using pointers.
</p>
</details>

#### What is API? 

<details><summary><b>Answer:</b></summary>
<p>
API is Application Programming Interface. API allows two applications to talk to each other.
</p>
</details>

### React
### Nodejs
### Express
### MongoDB

<!-- #### What is a Closure in JavaScript? How does it work?

<details><summary><b>Answer:</b></summary>
<p>
A closure is a function having access to the parent scope, even after the parent function has closed. A closure gives us access to an outer function's scope from an inner function.

```
function makeFunc() {
  const name = 'Naeem';
  function displayName() {
    console.log(name);
  }
  return displayName;
}

const myFunc = makeFunc();
myFunc();
```
</p>
</details> -->