So, lets get ready to learn some JavaScript and understand its syntax.
Let’s start with the basic built in primitive data types.

Primitive Data Types

Explanation: One of the most essential part of every programming language is the languages ability to differentiate between different categories of data. 
For example, every programming language can differentiate between a number and a string or a word. It could also differentiate between a whole number and a 
fractional number. The language could also differentiate a positive number from a negative number. These differentiations vary from language to language depending 
on the language the user is using. In JavaScript there are 6 Primitive Data Types which are  string, number, boolean, null, undefined, symbol (new in ECMAScript 2015).

Understand Primitive Data Types by Example

 //Strings

 “Hello World!”
 “25”
 “Jhony”

Explanation: Strings are nothing but plain texts inside quotation marks. From the “Hello World” example you can count them as one string even though there are

multiple words because they are inside quotes JavaScript counts them as one string. Also, even though 25 is a number but because it is inside double quotes 
JavaScript counts it as a string instead of a number as we can have any character or number inside of a string. 

  //Numbers
  2 // A whole number
 2.3 // A fractional or Decimal number
 -50 // A negative number

Explanation: From the 3 example of numbers it is clear that JavaScript does not care if a number is whole, decimal or negative and they are all treated as just 

numbers. Other languages do differentiate but JavaScript is more generous in this case and whether a number is whole, fractional or negative it counts them under 
a broad category. 

 //Booleans
  true
  false

Explanation: Booleans only have two options, they are either true or false. They do not use of numbers or quotes. 

 //null and undefined
  null
 undefined
Explanation: null and undefined are values. There is only one null and one undefined. There’s no such thing as multiple types of null or undefined like numbers and
 strings. 

  //symbol
 const key_name = Symbol();
 const user = {};
 user [key_name] = "JavaScript";
 console.log(user[key_name]);

 //expected output “JavaScript”


Explanation: Symbols provide a unique identifier. Once a symbol has been used as a key to an object they cannot be overwritten except by the same symbol. To access 
the properties of objects they have to be referred with the right symbol. 
Please visit the official MDN page for a better understanding on ES6 Symbols
•	 https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol

To get a better understanding of Primitive Data Types please visit the official MDN document page
•	https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures
•	https://developer.mozilla.org/en-US/docs/Glossary/Primitive

