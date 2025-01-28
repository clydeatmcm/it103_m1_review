# Lesson 1: HTML Review Questions
### Question 1:  
**Scenario**: You are tasked with creating a table that includes both a header and footer, as well as some descriptive text for screen readers. Which HTML structure is correct for achieving this?  

A.
```html
   <table>
       <caption>Description</caption>
       <thead>
           <tr><th>Header</th></tr>
       </thead>
       <tfoot>
           <tr><td>Footer</td></tr>
       </tfoot>
   </table>
```
B. 
```html
   <table>
       <thead>
           <tr><td>Header</td></tr>
       </thead>
       <tfoot>
           <tr><td>Footer</td></tr>
       </tfoot>
   </table>
   ```  
C. 
```html
   <table>
       <caption>Description</caption>
       <tr><th>Header</th></tr>
       <tfoot>
           <tr><td>Footer</td></tr>
       </tfoot>
   </table>
   ```  
D. 
```html
   <table>
       <caption>Description</caption>
       <tr>
           <thead><th>Header</th></thead>
       </tr>
       <tr>
           <tfoot><td>Footer</td></tfoot>
       </tr>
   </table>
   ```  
E. 
```html
   <table>
       <tr><th>Header</th></tr>
       <tfoot>
           <tr><td>Footer</td></tr>
       </tfoot>
   </table>
   ```  
F. 
```html
   <table>
       <thead>
           <tr><th>Header</th></tr>
       </thead>
       <caption>Description</caption>
       <tfoot>
           <tr><td>Footer</td></tr>
       </tfoot>
   </table>
   ```  

**Answer**: **D**  

---

### Question 2:  
**Scenario**: You want to embed a video on your webpage that allows users to play it but does not preload it or show playback controls. Which is the correct HTML?  

A. 
```html
   <video src="video.mp4" autoplay></video>
   ```  
B. 
```html
   <video src="video.mp4" preload="none" controls></video>
   ```  
C. 
```html
   <video src="video.mp4" autoplay preload="none"></video>
   ```  
D. 
```html
   <video src="video.mp4" preload="none"></video>
   ```  
E. 
```html
   <video src="video.mp4" autoplay muted preload="none"></video>
   ```  
F. 
```html
   <video src="video.mp4" preload="metadata" autoplay></video>
   ```  

**Answer**: **D**  

---

### Question 3:  
**Scenario**: You are building a webpage for a scientific article that includes a lot of formulas. To ensure semantic markup, which element should you use for mathematical expressions?  

A. `<formula>`  
B. `<math>`  
C. `<expression>`  
D. `<m>`  
E. `<var>`  
F. `<equation>`  

**Answer**: **B**  

---

### Question 4:  
**Scenario**: You need to display a quotation on your webpage, and it must include the source of the quote. Which HTML element combination should you use?  

A. 
```html 
<blockquote>Quote</blockquote>
```
B. 
```html
   <q cite="source">Quote</q>
```  
C. 
```html
   <cite>Quote</cite>
```  
D. 
```html
   <blockquote cite="source">Quote</blockquote>
```  
E. 
```html
   <p cite="source">Quote</p>
```  
F. 
```html
   <quote cite="source">Quote</quote>
```  

**Answer**: **D**  

---

### Question 5:  
**Scenario**: You want to create a form with a dropdown menu that allows users to select a single option, but one option should be pre-selected when the page loads. How would you write this?  

A.  
   ```html
   <select>
       <option>Option 1</option>
       <option selected>Option 2</option>
       <option>Option 3</option>
   </select>
   ```  
B.  
   ```html
   <select>
       <option>Option 1</option>
       <option default>Option 2</option>
       <option>Option 3</option>
   </select>
   ```  
C.  
   ```html
   <select>
       <option value="1">Option 1</option>
       <option value="2" selected>Option 2</option>
       <option value="3">Option 3</option>
   </select>
   ```  
D.  
   ```html
   <select selected>
       <option>Option 1</option>
       <option>Option 2</option>
       <option>Option 3</option>
   </select>
   ```  
E.  
   ```html
   <select>
       <option selected="true">Option 2</option>
       <option>Option 1</option>
       <option>Option 3</option>
   </select>
   ```  
F.  
   ```html
   <select>
       <option value="1">Option 1</option>
       <option value="2" default>Option 2</option>
       <option value="3">Option 3</option>
   </select>
   ```  

**Answer**: **C**  

---  

