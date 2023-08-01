RSA Factoring Challenge
RSA Laboratories states that: for each RSA number n, there exist prime numbers p and q such that

	n = p × q. The problem is to find these two primes, given only n.

	This task is the same as task 0, except:

	p and q are always prime numbers
	There is only one number in the files
	julien@ubuntu:~/RSA Factoring Challenge$ cat tests/rsa-1
	6
	julien@ubuntu:~/RSA Factoring Challenge$ ./rsa tests/rsa-1
	6=3*2
	julien@ubuntu:~/RSA Factoring Challenge$ cat tests/rsa-2
	77
