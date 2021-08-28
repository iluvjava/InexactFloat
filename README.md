# InexactFloat
About
A floating point number embeded into Julia that can keep track of errors propagations

### **Intro**

The same exact algorithm, run using rational number with infinite precision and running with floating points will produce different results. 

For some numeriacl algorithms, the relative error keeps the same, some magnifies them, other reduce them. This number is made to keep track of all the errors involved. 

To do that, some amount of analysis into the matter will be needed. And we would also need a lot of experiments on it. 