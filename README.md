
# code-challenge

Instructions:

Given a number, return the next bigger number using the same digits. For example:

```
12 ==> 21
513 ==> 531
2017 ==> 2071
```

```
nextNumber(num: 12)	// returns 21
  
nextNumber(num: 513)	// returns 531
 
nextNumber(num: 2017)	// returns 2071
```

If the digits can't be rearranged to form a bigger number, return -1:
```
9 ==> -1
111 ==> -1
531 ==> -1
```
```
nextNumber(num: 9)	// returns -1
nextNumber(num: 111)	// returns -1
nextNumber(num: 531)	// returns -1
```
