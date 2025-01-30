# Lesson 2: CSS Review Question
### **Question 1: Specificity Challenge**  
You have the following CSS rules applied to an `<h1>` element:  

```css
h1 {
    color: blue;
}
#title {
    color: green;
}
.title {
    color: red;
}
```

The HTML is:  

```html
<h1 id="title" class="title">Hello, World!</h1>
```

What will be the color of the `<h1>` text?  

A. **Blue**  
B. **Green**  
C. **Red**  
D. **It depends on the order of the CSS rules**  
E. **The text will inherit its color from the parent element**  
F. **Error: conflicting CSS rules**  

**Answer**: **B (Green)**  

---

### **Question 2: Z-Index and Positioning**  
Two overlapping `<div>` elements are styled as follows:  

```css
#box1 {
    position: relative;
    z-index: 10;
}
#box2 {
    position: absolute;
    z-index: 5;
}
```

The HTML is:  

```html
<div id="box1">Box 1</div>
<div id="box2">Box 2</div>
```

Which box will appear on top?  

A. **Box 1**  
B. **Box 2**  
C. **Neither, they overlap equally**  
D. **It depends on the order in the DOM**  
E. **Box 2 will be on top because of `absolute` positioning**  
F. **Error: conflicting z-index values**  

**Answer**: **A (Box 1)**  

---

### **Question 3: Flexbox Alignment**  
You have a container and three child items. You want the second child to align to the end of the container while the others stay at the start. The CSS is:  

```css
.container {
    display: flex;
    justify-content: flex-start;
}
.item:nth-child(2) {
    align-self: flex-end;
}
```

The HTML is:  

```html
<div class="container">
    <div class="item">Item 1</div>
    <div class="item">Item 2</div>
    <div class="item">Item 3</div>
</div>
```

What will happen to the alignment of the second item?  

A. **It will move to the end of the container**  
B. **It will stay aligned with the other items at the start**  
C. **It will align to the bottom of the container, independent of the others**  
D. **It will cause all items to align to the end**  
E. **It will align in the center of the container**  
F. **Error: `align-self` cannot override `justify-content`**  

**Answer**: **C (It will align to the bottom of the container, independent of the others)**  

---

### **Question 4: Box Model Trickery**  
A `<div>` has the following CSS:  

```css
div {
    width: 200px;
    padding: 20px;
    border: 10px solid black;
    box-sizing: content-box;
}
```

What will be the total width of the `<div>`?  

A. **200px**  
B. **220px**  
C. **240px**  
D. **260px**  
E. **280px**  
F. **320px**  

**Answer**: **E (280px)**  

*Explanation: `content-box` means the `width` includes only the content. Padding and border are added on top of the specified width.*  

---

### **Question 5: Pseudo-classes and Hover State**  
You have a button styled to change its background color when hovered. The CSS is:  

```css
button:hover {
    background-color: blue;
}
button:active {
    background-color: green;
}
```

What will happen when you click and hold the button?  

A. **The background color will stay blue**  
B. **The background color will change to green**  
C. **The background color will flash blue and then green**  
D. **The background color will remain the same as before hovering**  
E. **The button will ignore both styles**  
F. **It depends on the browser being used**  

**Answer**: **B (The background color will change to green)**  
