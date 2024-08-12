### **Set 2: Medium (20 Questions)**

1. **Which of the following keywords is used to declare a constant in JavaScript?**
    - a) var
    - b) let
    - c) const
    - d) static
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> c) const <br/>
  <b>Explanation:</b> The `const` keyword is used to declare a constant, a variable that cannot be reassigned.
</details>

2. **What is the output of the following code?**
   ```javascript
   var x = "5" - 3;
   console.log(x);
   ```
   - a) 2
   - b) "2"
   - c) 8
   - d) NaN
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> a) 2 <br/>
  <b>Explanation:</b> JavaScript converts the string `"5"` to a number and then subtracts `3`, resulting in `2`.
</details>

3. **How do you declare a function in JavaScript?**
   - a) function = myFunction() {}
   - b) myFunction function() {}
   - c) function myFunction() {}
   - d) function: myFunction() {}
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> c) function myFunction() {} <br/>
  <b>Explanation:</b> A function is declared using the `function` keyword followed by the function name and parentheses.
</details>

4. **Which method is used to convert a JSON object into a string?**
   - a) JSON.stringify()
   - b) JSON.parse()
   - c) JSON.toString()
   - d) JSON.convert()
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> a) JSON.stringify() <br/>
  <b>Explanation:</b> The `JSON.stringify()` method converts a JavaScript object or value to a JSON string.
</details>

5. **What will be the output of the following code?**
   ```javascript
   var fruits = ["Apple", "Banana", "Mango"];
   console.log(fruits[2]);
   ```
   - a) Apple
   - b) Banana
   - c) Mango
   - d) undefined
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> c) Mango <br/>
  <b>Explanation:</b> The array index `2` refers to the third element, which is `"Mango"`.
</details>

6. **Which of the following is the correct way to create an object in JavaScript?**
   - a) var obj = new Object();
   - b) var obj = Object();
   - c) var obj = {};
   - d) All of the above
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> d) All of the above <br/>
  <b>Explanation:</b> Objects can be created in multiple ways in JavaScript, including using `new Object()`, `Object()`, and object literals `{}`.
</details>

7. **What is the purpose of the `this` keyword in JavaScript?**
   - a) Refers to the current function
   - b) Refers to the global object
   - c) Refers to the current object
   - d) Refers to a new object
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> c) Refers to the current object <br/>
  <b>Explanation:</b> The `this` keyword refers to the object from which it was called.
</details>

8. **Which array method adds one or more elements to the end of an array and returns the new length of the array?**
   - a) push()
   - b) pop()
   - c) shift()
   - d) unshift()
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> a) push() <br/>
  <b>Explanation:</b> The `push()` method adds one or more elements to the end of an array and returns the new length.
</details>

9. **What will be the output of the following code?**
   ```javascript
   var text = "Hello, World!";
   console.log(text.length);
   ```
   - a) 12
   - b) 13
   - c) 14
   - d) 15
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> b) 13 <br/>
  <b>Explanation:</b> The `length` property counts the number of characters in the string, including spaces and punctuation.
</details>

10. **How do you round the number 4.6 to the nearest integer in JavaScript?**
    - a) Math.floor(4.6)
    - b) Math.ceil(4.6)
    - c) Math.round(4.6)
    - d) Math.trunc(4.6)
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> c) Math.round(4.6) <br/>
  <b>Explanation:</b> The `Math.round()` method rounds the number to the nearest integer.
</details>

11. **Which of the following will return `true`?**
    - a) "5" === 5
    - b) "5" == 5
    - c) "5" !== 5
    - d) "5" != 5
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> b) "5" == 5 <br/>
  <b>Explanation:</b> The `==` operator compares only the values, not the types, so `"5"` is considered equal to `5`.
</details>

12. **What does the `Array.prototype.map()` method do?**
    - a) Creates a new array with the results of calling a provided function on every element in the calling array
    - b) Returns a new array with all elements that pass a test implemented by the provided function
    - c) Removes the last element from an array and returns that element
    - d) Adds one or more elements to the end of an array
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> a) Creates a new array with the results of calling a provided function on every element in the calling array <br/>
  <b>Explanation:</b> The `map()` method creates a new array populated with the results of calling a provided function on every element in the array.
</details>

13. **Which of the following is the correct way to write an arrow function in JavaScript?**
    - a) `let myFunction = () => { return "Hello"; }`
    - b) `let myFunction => () { return "Hello"; }`
    - c) `let myFunction = () => return "Hello";`
    - d) `let myFunction = () { => return "Hello"; }`
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> a) `let myFunction = () => { return "Hello"; }` <br/>
  <b>Explanation:</b> The arrow function syntax uses `=>` to define a function.
</details>

14. **What is the output of the following code?**
    ```javascript
    var x = 1;
    if (x) {
        console.log("True");
    } else {
        console.log("False");
    }
    ```
    - a) True
    - b) False
    - c) Error
    - d) undefined
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> a) True <br/>
  <b>Explanation:</b> In JavaScript, `1` is considered a truthy value, so the condition is true.
</details>

15. **What will be the output of the following code?**
    ```javascript
    var arr = [1, 2, 3];
    arr.pop();
    console.log(arr);
    ```
    - a) [1, 2, 3]
    - b) [2, 3]
    - c) [1, 2]
    - d) [1, 2, 3, undefined]
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> c) [1, 2] <br/>
  <b>Explanation:</b> The `pop()` method removes the last element from the array, leaving `[1, 2]`.
</details>

16. **Which of the following is a way to create a promise in JavaScript?**
    - a) `new Promise((resolve, reject) => { ... })`
    - b) `Promise.create(resolve, reject) => { ... }`
    - c) `Promise.then(resolve, reject) => { ... }`
    - d) `Promise.resolve((resolve, reject) => { ... })`


<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> a) `new Promise((resolve, reject) => { ... })` <br/>
  <b>Explanation:</b> The correct way to create a promise is using the `Promise` constructor with a function that has `resolve` and `reject` parameters.
</details>

17. **How do you remove the first element from an array in JavaScript?**
    - a) `arr.pop()`
    - b) `arr.shift()`
    - c) `arr.unshift()`
    - d) `arr.splice(0, 1)`
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> b) `arr.shift()` <br/>
  <b>Explanation:</b> The `shift()` method removes the first element from an array and returns it.
</details>

18. **What will be the output of the following code?**
    ```javascript
    console.log(typeof null);
    ```
    - a) "null"
    - b) "undefined"
    - c) "object"
    - d) "boolean"
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> c) "object" <br/>
  <b>Explanation:</b> In JavaScript, `typeof null` returns `"object"`, which is considered a bug but has been retained for legacy reasons.
</details>

19. **Which of the following is an example of an object literal in JavaScript?**
    - a) `var obj = {name: "John", age: 30};`
    - b) `var arr = [1, 2, 3];`
    - c) `var str = "Hello";`
    - d) `var num = 123;`
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> a) `var obj = {name: "John", age: 30};` <br/>
  <b>Explanation:</b> An object literal is defined using curly braces `{}` and contains key-value pairs.
</details>

20. **What will be the output of the following code?**
    ```javascript
    var x = 10;
    x += 5;
    console.log(x);
    ```
    - a) 10
    - b) 5
    - c) 15
    - d) undefined
<details>
  <summary>Click to show answer</summary>
  <b>Answer:</b> c) 15 <br/>
  <b>Explanation:</b> The `+=` operator adds `5` to `x`, resulting in `15`.
</details>
