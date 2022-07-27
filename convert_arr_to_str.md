#  Convert array to string in javascript:

1. [Using join()](https://github.com/MohamadSheikhAlshabab/js_snippets/new/main#1-using-join)
2. [Using + Operator](https://github.com/MohamadSheikhAlshabab/js_snippets/new/main#2-using--operator)
3. [Using toString()](https://github.com/MohamadSheikhAlshabab/js_snippets/new/main#3-using-tostring)
4. [Using concat()](https://github.com/MohamadSheikhAlshabab/js_snippets/new/main#4-using-concat)
5. [Using String()](https://github.com/MohamadSheikhAlshabab/js_snippets/new/main#5-using-string)
6. [Using Template Strings( `${ }` )](https://github.com/MohamadSheikhAlshabab/js_snippets/new/main#6-using-template-strings)

## Example:

<pre>
let array = ["Javascript", "Is", "Popular","Language"];
</pre>

#### 1. Using join():

<pre>
let string  = array.join(",");                             // Javascript,Is,Popular,Language
</pre>

---

#### 2. Using + Operator:

<pre>
let string  = array + "";                                // Javascript,Is,Popular,Language
</pre>

---

#### 3. Using toString():


<pre>
let string  = array.toString();                            // Javascript,Is,Popular,Language
</pre>

---

#### 4. Using concat():

<pre>
let emptyString = "";
let string  = emptyString.concat(array);                     // Javascript,Is,Popular,Language
</pre>

---

#### 5. Using String():

<pre>
let string  = String(array);                     // "Javascript,Is,Popular,Language"
</pre>

---


#### 6. Using Template Strings(${}):

<pre>
let string  = `${array}`;                     // "Javascript,Is,Popular,Language"
</pre>

---
