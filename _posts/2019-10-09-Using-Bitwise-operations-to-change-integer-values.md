---
title: "Modifying integer values with bitwise operations using exercise 2.6 from The C programming language 2nd Edition as an example"
classes: wide
---


Exercise 2-6. Write a function setbits(x,p,n,y) that returns x with the n bits that begin at position p set to the rightmost n bits of y, leaving the other bits unchanged. 

Using the values of P=5 N=3 X=154 Y=170, this problem wants me to replace the 2^1, 2^2, 2^3 bits of X (101) with the 2^0, 2^1, 2^2 bits of Y (010)

```
N values in Y represent the values we want to put in X
N values in X represent the values we need to replace with N values in Y. 
Value of Y = 170 in binary 		Value of X = 154 in binary
	YYYYYNNN				XXXXNNNX
	10101010				10011010
	   	
```




