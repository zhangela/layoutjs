Layout.js
===============

**Layout.js**, because laying out a website should not be hard (looking at you, CSS!).

## Problem

Laying out UI should be intuitive. We have been drawing squares on paper ever since we were children. Why, then, is frontend web so tedious?

We think the issue has to do with CSS.

Consider this layout ([source](http://learnlayout.com/)):

![image](https://github.com/zhangela/layoutjs/blob/master/sample_layout.png?raw=true)

**With CSS, here are the several ways you can make that layout:**

### Relative Position

```
.container {
  position: relative;
}
nav {
  position: absolute;
  left: 0px;
  width: 200px;
}
section {
  /* position is static by default */
  margin-left: 200px;
}
footer {
  position: fixed;
  bottom: 0;
  left: 0;
  height: 70px;
  background-color: white;
  width: 100%;
}
body {
  margin-bottom: 120px;
}
```

This is terribly unintuitive. Why is .container positioned relatively and nav absolutely? Also, if the container is taller than the nav, then nav would overflow outside its container. 

### Percent Width 

```
nav {
  float: left;
  width: 25%;
}
section {
  margin-left: 25%;
}
```
When the window is too narrow, the navbar will be so narrow that not all the text fit on the screen.

![image](https://github.com/zhangela/layoutjs/blob/master/percent_width.png?raw=true)

### 

## Requirements

## Previous Solutions


## Interested?

Email [zhangela](mailto:zhangela@mit.edu) if you have thoughts, suggestions, bug reports, etc.