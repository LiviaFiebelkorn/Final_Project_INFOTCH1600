# How to Create Your Own SVG!
## Part 3: Coding the SVG!
In this part, you will learn how to code the SVG!
---
**Step 1:** Create the SVG element. This is what defines what the SVG will look like. Then define the size of the SVG. (For the example, I will be using a 150 by 150 size!)
*Print this:*
```
<!DOCTYPE html>
<html>
<body>
  
<h1>My new SVG</h1>
  
<svg width="150" height="100">
  
</body>
</html>
```

**Step 2:**  Get Creative! This is the fun part. There are many different methods to creating SVGs. Here is a [link](https://www.w3schools.com/graphics/svg_reference.asp) to those methods, I recommend looking into each of the methods for in depth learning! For this tutorial, I will show you how to make a simple flower.
 The order of which the objects appear is from top to bottom, meaning that objects on the bottom will cover object above them. *Lets start with the stem:*
```  
<!DOCTYPE html>
<html>
<body>
  
<h1>My new SVG</h1>
  
<svg width="150" height="100">
   <line x1="75" y1="150" x2="75" y2="90" stroke="green" stroke-width = "4" />

</body>
</html>
 ```
  *Now for the Petals!*
  ```
<!DOCTYPE html>
<html>
<body>
  
<h1>My new SVG</h1>
  
<svg width="150" height="100">
   <line x1="75" y1="150" x2="75" y2="90" stroke="green" stroke-width = "4" />
  <circle cx="60" cy="60" r="15" fill="blue" />
   <circle cx="60" cy="90" r="15" fill="red" />
   <circle cx="90" cy="60" r="15" fill="pink" />
   <circle cx="90" cy="90" r="15" fill="purple" />

</body>
</html>
  ```
*And finally the center of the flower!*
  ```
<!DOCTYPE html>
<html>
<body>
  
<h1>My new SVG</h1>
  
<svg width="150" height="100">
   <line x1="75" y1="150" x2="75" y2="90" stroke="green" stroke-width = "4" />
  <circle cx="60" cy="60" r="15" fill="blue" />
   <circle cx="60" cy="90" r="15" fill="red" />
   <circle cx="90" cy="60" r="15" fill="pink" />
   <circle cx="90" cy="90" r="15" fill="purple" />
    <circle cx="75" cy="75" r="15" fill="yellow" />
</body>
</html>
 ```
 **Step 3:** Close the SVG
  To close the SVG, we do the same statement as on the previous page.
  ```
<!DOCTYPE html>
<html>
<body>
  
<h1>My new SVG</h1>
  
<svg width="150" height="100">
   <line x1="75" y1="150" x2="75" y2="90" stroke="green" stroke-width = "4" />
  <circle cx="60" cy="60" r="15" fill="blue" />
   <circle cx="60" cy="90" r="15" fill="red" />
   <circle cx="90" cy="60" r="15" fill="pink" />
   <circle cx="90" cy="90" r="15" fill="purple" />
    <circle cx="75" cy="75" r="15" fill="yellow" />
  </svg>
</body>
</html>
 ```
 ---
  ## Congrats! You just made an SVG!
---
|[ Previous ](Page5.md) |   [ Table of Contents ](README.md)  |
