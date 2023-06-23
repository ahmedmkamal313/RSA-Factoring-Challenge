# RSA Factoring Challenge

This is a program that factorizes large numbers into a product of two prime numbers. It is based on the RSA Factoring Challenge, a series of cryptographic puzzles that were designed to test the security of the RSA encryption algorithm.

### Motivation
This project was created as an optional challenge for **ALX SE** students. The goal is to factorize as many numbers as possible in less than 5 seconds, using any programming language and without any dependencies. This project demonstrates the skills and knowledge of cryptography, number theory, and algorithm design.

### Features
- Factorizes large numbers into a product of two prime numbers
- Supports multiple numbers in a file
- Outputs the factorization in a simple format
- Runs without any dependencies or installation
- Works on Standard Ubuntu 20.04 LTS

### Installation and Usage
To use this program, you need to clone this repository and run the factors executable.
```
git clone https://github.com/ahmedmkamal313/RSA-Factoring-Challenge.git
cd RSA-Factoring-Challenge
./factors <file>
```
where `<file>` is a file containing natural numbers to factor, one number per line. For example:
```
17976931348623159077293051907890247336179769789423065727343008115
7312675806560849860266523
```
The output will be the factorization of each number in the file, in the format n=p*q, where p and q are prime numbers. For example:
```
17976931348623159077293051907890247336179769789423065727343008115=13407807929942597099574024998205846127479365820592393377723561443*13308776303605232647404302462765558726052776128228214649096256861
7312675806560849860266523=820162525879*8912743431
```
The program will run for at most 5 seconds and then terminate.

### Author
This project was created by [Ahmed Kamal](https://github.com/ahmedmkamal313), a student at ALX SE.

### Disclaimer
This project is for educational purposes only. The author is not responsible for any misuse or damage caused by this program.

### List of files
- factors
  - Factorize as many numbers as possible into a product of two smaller numbers.

- rsa
  - RSA Laboratories states that: for each RSA number `n`, there exist prime numbers `p` and `q` such that `n` = `p` × `q`. The problem is to find these two primes, given only `n`.
