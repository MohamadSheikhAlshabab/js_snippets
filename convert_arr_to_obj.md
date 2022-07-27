# Convert Array of Objects to an Object:
1. Using Reduce Function
2. Using Spread Operator
3. Using Object.assign
4. Using Comma Operator
5. Using forEach Loop

---
## example:

<pre>
const data = {
  1 : { key: 1, name: "A", condition: true },
  4 : { key: 4, name: "B", condition: false },
  7 : { key: 7, name: "C", condition: true },
  11 : { key: 11, name: "D", condition: true },
  12 : { key: 12, name: "E", condition: false }
}
</pre>

#### 1. Using Reduce Function:

<pre>
const arrayToObject1 = (arr, key) => {
     return arr.reduce((obj, item) => {
         obj[item[key]] = item
         return obj
     }, {})
 }
 </pre>
 
 ![](https://codezup.com/wp-content/uploads/2021/03/Screenshot-2021-03-01-at-11.32.01-PM-1536x724.png)
 
 ---
 #### 2. Using Spread Operator:
 
<pre>
const arrayToObject2 = (array, key) =>
     array.reduce(
     (obj, item) => ({
       ...obj, [item[key]]: item
     }),{});
 </pre>
 
 ![](https://codezup.com/wp-content/uploads/2021/03/Screenshot-2021-03-01-at-11.41.38-PM-1536x741.png)
 
 ---
 #### 3. Using Object.assign (One Liner solution)
<pre>
const arrayToObject3 = (arr, key) => Object.assign({}, …arr.map(item => ({[item[key]]: item})))
</pre>
![](https://codezup.com/wp-content/uploads/2021/03/Screenshot-2021-03-01-at-11.48.18-PM-1536x505.png)

---
#### 4. Using Comma Operator

<pre>
const arrayToObject4 = (arr, key) => 
    arr.reduce((obj, item) => ((obj[[item[key]]] = item), obj), {});
</pre>
![](https://codezup.com/wp-content/uploads/2021/03/Screenshot-2021-03-01-at-11.57.22-PM-1536x531.png)

---
### 5. Using forEach Loop

<pre>
const arrayToObject5 = (arr, key) => {
     const res = {};
     arr.forEach(obj => {
         res[obj[key]] = obj;
     })
     return res
 }
</pre>
![](https://codezup.com/wp-content/uploads/2021/03/Screenshot-2021-03-02-at-12.09.05-AM-1536x752.png)
