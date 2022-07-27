# convert a Number to String in JavaScript:

1. toString() 
2. num + "" or  num + ''
3. Using String() 
4. Template Strings ==> string = `${num}`; 
5. Using toFixed() method
6. using split,call and join ==> "".split.call(Num,"").join("")

---



## The below are the methods to convert an Integer to String in JS.

### The methods are arranged in the decreasing order of performance.

<pre>let num = 1</pre>

#### Method 1: <pre>num = `${num}`</pre>

#### Method 2: <pre>num = num + ''</pre>

#### Method 3: <pre>num = String(num)</pre>

#### Method 4: <pre>num = num.toString()</pre>

#### Method 5: <pre>num = num.toFixed()</pre>

#### Method 6: 
<pre>
let num = 108;
"".split.call(num,"").join("");
</pre>
