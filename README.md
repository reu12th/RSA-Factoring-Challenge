# RSA Factoring Challenge
### `Algorithm` `Scripting` `Python`

## 0. Factorize all the things!
Factorization of many numbers as possible into a product of two smaller numbers.   
### Usage
* Usage: factors <file>
	* where <file> is a file containing natural numbers to factor.
	* One number per line
	* All lines will be valid natural numbers greater than 1
	* There will be no empty line, and no space before and after the valid number
	* The file  always end with a new line
* Output format: n=p*q
	* one factorization per line
	* p and q don’t have to be prime numbers
	* See Example:   
```python
reuben@ubuntu:~/RSA-Factoring-Challenge$ cat tests/test00 
4
12
34
128
1024
4958
1718944270642558716715
9
99
999
9999
9797973
49
239809320265259
reuben@ubuntu:~/RSA-Factoring-Challenge$ time ./factors tests/test00
4=2*2
12=6*2
34=17*2
128=64*2
1024=512*2
4958=2479*2
1718944270642558716715=343788854128511743343*5
9=3*3
99=33*3
999=333*3
9999=3333*3
9797973=3265991*3
49=7*7
239809320265259=15485783*15485773

real    0m0.009s
user    0m0.008s
sys 0m0.001s
reuben@ubuntu:~/RSA-Factoring-Challenge$ 
```   
* File: factors

## 1. RSA Factoring Challenge

