# Daily_Coding
 Improve programming skills day by day.
===
|Author|Shifeng Song|
|---|---
|Email|a245241964@gmail.com

****
## Day 1

Language C

* decompse a number

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

* find max and min value in an array
 ```c
 void max_min(int a [],int size, int *max, int *min)
{
  *max = *min = a[0];
  for(int i = 1, i < size; i++){
    if(a[i] < *main){
      *min = a[i];
    }else{
      *max = a[i];
    }
  }  
}
 ```
