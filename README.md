# Daily_Coding
 Improve programming skills day by day.
===
|Author|Shifeng Song|
|---|---
|Email|a245241964@gmail.com

****
## Day 1

* Language C
```c
void decompose(double x, long *int_part, double *frac_part)
{
  *int_part = (long) x;
  *frac_part = x- *int_part;
}
```

x -->  
int_part --> &i  
frac_part --> &d  

call the method  
 
```c
decompose(3.1415926,&i,&d);
```
x --> 3.1415926  
int_part --> 3  
frac_part --> .1415926  
