Now let’s explore more about the data type “string”
Strings could be words, numbers, texts and characters inside of single or double quotes (“sum”, “10”, “John”, ‘Merry’, ‘that dog’).
 But if we start to write a word in double quote and end it with a single quote it will give us an error in the console as the quote needs to match. 
You could either use double quote or single quote to define string, but you cannot use both at the same time. 
For example,

>“johny’ // Uncaught SyntaxError: Invalid or unexpected token
>"jhony" // it returns the value "jhony"
>'jhony' // it returns the value 'jhony'


But there are ways to use double quoted string with a single quote inside of it. For example 

"I can’t stop but study JavaScript"// expected output is "I can’t stop but study JavaScript"
Explanation: The reason why this example is valid is because even though there is a single quote in between the n and the t the example ended with a double
 quote on the outside. But if we write the code like the code below we will get an error.

'I don't want' //Uncaught SyntaxError: Unexpected identifier

String Concatenation 

As we have seen before we can use addition operator to add numbers we could do the same for strings and add two or multiple strings together and JavaScript
 will combine them into one string which is called concatenation. For example, in console if we write

>"hello"+"world" // it will return "helloworld"

Even though we wrote them separately JavaScript combined them together and made them one single string using concatenation. But, if we want space between the
 words we could write it like

>" hello " +" world " // the output will be " hello  world " 

Inside the quotes the white space is not ignored and counted as a part of the string. 
We can also have a double quote inside a double quoted string using a space character known as a backlash (\). For example,

>"she is such a  \" beautiful\" girl" // the output is [ she is such a  " beautiful" girl ]

So, by using the backslash (\) or escape character followed by a double quote we tell JavaScript that we want a double quote in the string. 

