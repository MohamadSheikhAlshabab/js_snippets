# Convert String to Character Array in JavaScript:
1. Using split('').
2. Using spread operator inside array literals  [...string]
3. Using Array.from(string).
4. Using Object.assign([], string)

![image](https://user-images.githubusercontent.com/60566868/181222079-35614aba-50c4-4fe6-a5e5-65166b2340e4.png)


---

## example :
<pre>
const string = 'word';
</pre>

#### Option 1:
<pre>
string.split('');
</pre>

/####  Option 2:
<pre>
[...string];
</pre>

####  Option 3:
<pre>
Array.from(string);
</pre>

####  Option 4:
<pre>
Object.assign([], string);
</pre>

####  Result:
<pre>
// ['w', 'o', 'r', 'd']
</pre>
