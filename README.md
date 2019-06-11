Hello! 

This is a recreation of the Coding Challenge done by Daniel Shiffman on the Coding train channel on youtube 

in order to run this code you need the following links in your html head:


the lib file for p5.js
===============


Imaginary Numbers: 

root(4) == 2

root(16) == 4 

root(-1) == ??

imaginary numbers are represented as 'i' 

complext numbers are represented by a real number 'a', and an imaginary number 'b(i)' or ... 

a + b(i)

=============

The Mandelbrot set on Wikipedia is defined as: 

"The Mandelbrot set is the set of complex numbers 'c' for which the function 'Fc(z) = z^2 + c' does not diverge when iterated from z = 0. "

c is a complex number || a + bi 

so the math to understand the Fc() equation would be ordered out like this: 

Given z = 0: 

    Zo = 0 => Z1 = z^2 + c

    Z2 = C^2 + C 

        C^2 == (a + bi)(a + bi)

            a^2 + abi + abi + b^2i^2

            a^2 + 2abi - b^2

            a^2 - b^2 + 2abi 

        this final product being another complex number with '2abi' being the imaginary number and 'a^2 - b^2' being the real number 
================

The objective of the iterative Mandelbrot set is to iterate this equation with all the values being 'bound in absolute value' 
    this means that the numbers that are being generated tend to not go towards infinity 




