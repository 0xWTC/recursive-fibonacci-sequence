# recursive-fibonacci-sequence
 
## Description
 
The Fibonacci sequence is defined by the following recursive formula:
 
Fn = Fn−1 + Fn−2
 
The first two terms are 1 and 1, and the third term, F3, is the sum of the first two terms, F1 and F2, which are 1. The fourth term, F4, is the sum of the first three terms, F1, F2 and F3, which are 1, 2 and 1, and so on.
 
The first three terms are 1, 1 and 2, and the 12th term, F12, is the sum of the first 10 terms, F1 through F10.
 
The 12th term, F12, is the first term to contain three digits.
 
## Solution

The solution to this problem is to use recursion to compute the sequence.
 
The recursive function is given the current index and the current value of the sequence.
 
If the current index is less than or equal to the current value of the sequence, then we return the current value of the sequence.
 
Otherwise, we compute the next value of the sequence by adding the previous two values of the sequence.
 
The recursive function is then called with the next index and the next value of the sequence.

## Requirements

* Python

To run:
   
   python fib.py
 
## Reference
 
[Wikipedia](https://en.wikipedia.org/wiki/Fibonacci_number)
 

## Example output
 
```
1
1
2
3
5
8
13
21
34
55
89
144
233
377
610
987
1597
2584
4181
6765
10946
17711
28657
46368
75025
121393
196418
317811
514229
832040
1346269
2178309
3524578
5702887
9227465
14930352
24157817
39088169
63245986
102334155
165580141
267914296
433494437
701408733
1134903170
1836311903
2971215073
4807526976
7778742049
12586269025
20365011074
32951280099
53316291173
86267571272
139583862445
225851433717
365435296162
591286729879
956722026041
1548008755920
2504730781961
4052739537881
6557470319842
10610209857723
17167680177565
```