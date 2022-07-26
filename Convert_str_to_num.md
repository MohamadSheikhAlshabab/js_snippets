
# 7 ways to convert a String to Number in JavaScript
1. Using parseInt()
2. Using Number() 
3. Using Unary Operator (+) 
4. Using parseFloat()
5. Using Math.floor() 
6. Multiply with number  (str * 1) 
7. Double tilde (~~) Operator 

----

- example :

## 1. Using parseInt() :

<pre>
 myString = '129' 
console.log(parseInt(myString)) // expected result: 129

a = 12.22
console.log(parseInt(a)) // expected result: 12
 </pre>
---
## 2. Using Number() :

<pre>
Number("10");          // returns 10
Number(" 10  ");       // returns 10
Number("10.33");       // returns 10.33
</pre>
---
## 3. Using Unary Operator (+):

<pre>
const x = 25;
const y = -25;
console.log(+x); // expected output: 25
console.log(+y); // expected output: -25
console.log(+''); // expected output: 0
</pre>
---
## 4. Using parseFloat() :
<pre>
parseFloat("10");        // returns 10
parseFloat("10.33");     // returns 10.33
parseFloat("10 20 30");  // returns 10
parseFloat("10 years");  // returns 10
parseFloat("years 10");  // returns NaN
</pre>
---
## 5. Using Math.floor() :

<pre>
str = '1222'
console.log(Math.floor(str)) // returns 1222

a = 12.22
Math.floor(a) // expected result: 12
</pre>
---
## 6. Multiply with number  (str * 1)  :

<pre>
str = '2344'
console.log(str * 1) // expected result: 2344
</pre>
---
## 7. Double tilde (~~) Operator  :

<pre>
str = '1234'
console.log(~~str) // expected result: 1234
negStr = '-234'
console.log(~~negStr) // expected result: -234
</pre>
