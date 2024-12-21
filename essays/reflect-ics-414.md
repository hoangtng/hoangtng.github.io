---
layout: essay
type: essay
title: "Reflect my experience in ICS 414"
# All dates must be YYYY-MM-DD format!
date: 2024-12-20
published: true
labels:
  - Website Developer
  - Learning
  - Javascript
---
<p><img height="50%" 
     style="display: block;
  margin-left: auto;
  margin-right: auto;
  width: 70%" 
     src="https://www.workato.com/product-hub/wp-content/uploads/2020/12/workato-blog-JavaScript-20201208-bl-01.jpg"></p>

<h3>function introduction(student, programmingLanguage) {</h3>
<p style="display: inline-block;
    margin-left: 40px;">return “I came on a journey to JavaScript because I needed it for projects in my ICS 314 (Software Engineering I) class. Prior to joining the ICS 314 class, I had learned some programming languages such as C++, Java, and Python. Learning these languages in previous classes was initially challenging, but then it provided me with a solid foundation. Consequently, when I transitioned to learning JavaScript, I found it relatively easier and quickly adapted to it. This was because the syntax and structure of JavaScript are similar to Java programming, but somewhat simpler, syntax is more concise, and execution is also faster.”;</p>
<h3>}</h3>

<h3>function compare(javascript, others) {</h3>
<p style="display: inline-block;
    margin-left: 40px;">return “Compared to other programming languages, although JavaScript has many similarities with other programming languages, but also there are also many notable differences. First, variable declaration in JavaScript is much more convenient than in Java. While Java variables must be declared using specific data types before they can be used, JavaScript is more flexible. Simply using 'let,' 'var,' or 'const' is sufficient, without having to consider which data type is suitable for declaration. </p>

<p style="display: inline-block;
    margin-left: 40px;">Then, JavaScript is an object-oriented language that is prototype-based, that does not use classes to define objects. Instead, it uses prototypes, which are existing objects. In addition, JavaScript has the concept of “JavaScript treat function as a first-class”, this means that functions can be assigned to any other variable, passed as an argument, or returned by another function. </p>
```
function sayHello() {
  return "Hello, ";
}
function greeting(helloMessage, name) {
  console.log(helloMessage() + name);
}
// Pass 'sayHello' as an argument to 'greeting' function
greeting(sayHello, "JavaScript!");
// Hello, JavaScript!
```
<p style="display: inline-block;
    margin-left: 40px;">One of the most interesting things about JavaScript that I experienced while learning is how JavaScript handles concurrency issues. To deal with concurrency issues, JavaScript also has the concept of asynchronous programming with “Promise”, which allows the code to run in the background without blocking the execution of other code. For example, we can execute parallel queries to the database or run API calls in the background while the main thread (website) continues to function normally. Even if a database query fails, the main thread will remain uninterrupted. I believe these differences contribute to bringing more convenience, creativity, and productivity to JavaScript developers.”; </p>
<h3>}</h3>

<h3>function athletic_software_engineering() {</h3>
<p style="display: inline-block;
    margin-left: 40px;">return “I find that WODs (Workout of the Day) are highly effective for me. Although WODs are a bit of a pressure because it requires us to quickly find solutions within a limited time, but I believe that when we are forced to do something, we discover ways to overcome it. This has motivated me to spend time persistently learning programming and solving problems almost every day of the week to be able to pass the tests. I believe that after this semester, I will improve my programming skills and critical thinking skills so that I can confidently apply for an internship or have a solid foundation for future subjects.” </p>
<h3>}</h3>

<h3>introduction(“Hoang Nguyen”,”JavaScript”);</h3>
<h3>compare (”JavaScript”, ”Java”);</h3>
<h3>athletic_software_engineering();</h3>



