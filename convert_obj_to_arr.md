# Converting Object to Array in javascript:

1. [Using Object.keys()](https://github.com/MohamadSheikhAlshabab/js_snippets/new/main#1-using-objectkeys)
2. [Using Object.values()](https://github.com/MohamadSheikhAlshabab/js_snippets/new/main#2-using-objectvalues)
3. [Using Object.entries()](https://github.com/MohamadSheikhAlshabab/js_snippets/new/main#3-using-objectentries)
4. [Using an empty array and push property to add to it.](https://github.com/MohamadSheikhAlshabab/js_snippets/new/main#4-using-an-empty-array-and-push-property-to-add-to-it)
5. [Using map](https://github.com/MohamadSheikhAlshabab/js_snippets/new/main#5-using-map)

## example:

<pre>
let objList = {'a':1,'b':2,'c':3,'d':4}
</pre>

#### 1. Using Object.keys():
<pre>
Object.keys(objList)                                // ['a','b','c','d']
</pre>
---

#### 2. Using Object.values():

<pre>
Object.values(objList)                              // [1,2,3,4]
</pre>

---
#### 3. Using Object.entries()

<pre>
Object.entries(objList)                             // ['a',1,'b',2,'c',3,'d',4]
</pre>

---
#### 4. Using an empty array and push property to add to it.

<pre>
let arrList = []
for (let key in objList){
    arrList.push([key , objList[key]])              // [['a',1],['b',2],['c',3],['d',4]]
</pre>
---
#### 5. Using map:

<pre>
let arrList = Object.keys(objList).map(key => {
  return [key , objList[key]])                     // [['a',1],['b',2],['c',3],['d',4]]
})
</pre>

