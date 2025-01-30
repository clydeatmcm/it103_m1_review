# Lesson 3: JS Review Question

### **Question 1: Variables and Scope**  
**Scenario:** You are developing a web application where a user can input their name. You need to store the user's name so it can be accessed throughout different functions but should not be reassigned accidentally. Which of the following is the best way to declare the variable?  

A. `var userName = "Alice";`  
B. `let userName = "Alice";`  
C. `const userName = "Alice";`  
D. `userName = "Alice";`  
E. `function userName() { return "Alice"; }`  
F. `const userName; userName = "Alice";`  

**Answer:** C  

---

### **Question 2: Functions and Return Values**  
**Scenario:** You are building a program that calculates the total price of an order. The function should take the price of an item and the quantity, then return the total cost. Which function correctly implements this logic?  

A.  
```js
function getTotal(price, quantity) { 
    console.log(price * quantity); 
}
```  
B.  
```js
function getTotal(price, quantity) { 
    return price * quantity; 
}
```  
C.  
```js
function getTotal() { 
    return price * quantity; 
}
```  
D.  
```js
const getTotal = (price, quantity) => price * quantity;  
```  
E.  
```js
const getTotal = function(price, quantity) {  
    console.log(price * quantity); 
};
```  
F.  
```js
let getTotal = price, quantity => { price * quantity };  
```  

**Answer:** B, D  

---

### **Question 3: Conditionals and Logic**  
**Scenario:** You are developing a login system where users must enter a correct password. If the password is `"admin123"`, they should see "Access Granted", otherwise, they should see "Access Denied". Which of the following correctly implements this logic?  

A.  
```js
if (password = "admin123") { 
    console.log("Access Granted"); 
} else { 
    console.log("Access Denied"); 
}
```  
B.  
```js
if (password == "admin123") { 
    console.log("Access Granted"); 
} else { 
    console.log("Access Denied"); 
}
```  
C.  
```js
if (password === "admin123") { 
    console.log("Access Granted"); 
} else { 
    console.log("Access Denied"); 
}
```  
D.  
```js
if (password != "admin123") { 
    console.log("Access Granted"); 
} else { 
    console.log("Access Denied"); 
}
```  
E.  
```js
if (password === "admin123") { 
    return "Access Granted"; 
} else { 
    return "Access Denied"; 
}
```  
F.  
```js
password === "admin123" ? console.log("Access Granted") : console.log("Access Denied");
```  

**Answer:** C, F  

---

### **Question 4: Loops and Iteration**  
**Scenario:** You are writing a program to display numbers from 1 to 5 in the console. Which loop correctly implements this?  

A.  
```js
for (let i = 0; i < 5; i++) {  
    console.log(i);  
}
```  
B.  
```js
for (let i = 1; i <= 5; i++) {  
    console.log(i);  
}
```  
C.  
```js
let i = 1;  
while (i <= 5) {  
    console.log(i);  
    i++;  
}
```  
D.  
```js
let i = 1;  
do {  
    console.log(i);  
    i++;  
} while (i < 5);
```  
E.  
```js
for (let i = 5; i > 0; i--) {  
    console.log(i);  
}
```  
F.  
```js
for (let i = 1; i < 5; i++) {  
    console.log(i);  
}
```  

**Answer:** B, C  

---

### **Question 5: Arrays and Objects**  
**Scenario:** You are creating an array to store a list of students' names and a separate object to store details of a single student. Which of the following correctly represents this data?  

A.  
```js
let students = ["Alice", "Bob", "Charlie"];  
let student = { name: "Alice", age: 20, grade: "A" };  
```  
B.  
```js
let students = { "Alice", "Bob", "Charlie" };  
let student = ["Alice", 20, "A"];  
```  
C.  
```js
let students = ["Alice", "Bob", "Charlie"];  
let student = { "name": "Alice", "age": 20, "grade": "A" };  
```  
D.  
```js
let students = ["Alice", "Bob", "Charlie"];  
let student = [ name = "Alice", age = 20, grade = "A" ];  
```  
E.  
```js
let students = ["Alice", "Bob", "Charlie"];  
let student = { name: "Alice"; age: 20; grade: "A" };  
```  
F.  
```js
let students = ["Alice", "Bob", "Charlie"];  
let student = { name: "Alice", age: "20", grade: "A" };  
```  

**Answer:** A, C 
