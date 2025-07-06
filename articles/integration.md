---
title: 'Reimann Integration'
author: Vaishnav Sudarshan
---
# Integration
Suppose we want to find the area bounded by under a function and the $x$ axis, from $x = a$ to $x = b$. 

The shape between the function and the $x$ axis isn't a shape that you can find the area of using geometry. So, we have to find a way to split the area into infinite small pieces, similar to how the formula for the area of a circle is derived. 

An easy way to split this area is to divide the $x$ axis from $a$ to $b$ into some number of widths. Each width will be the width of a rectangle, and the height of the rectangle is just the value of the function evaluated at the start of that width. Adding up the areas of all these rectangles is a good approximation for the true area. 
We can write this mathematically as:

If these widths get smaller and smaller, which also means there are more rectangles, this approximation becomes better and better. This means that the exact area under the curve is the sum of the areas of all the rectangles as the widths approach 0. Since each width approaches 0, and each is also a change in x, we can write it as dx. To write this mathematically, 
$$
A = \int\limits_{a}^{b} f(x) dx
$$ 
The weird symbol that looks like an $s$ is the integral symbol. Just like how d is like delta but infinitely small, the integral symbol is like sigma except the values being added up are infinitely small. 