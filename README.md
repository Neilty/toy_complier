toy_complier

toy compiler is using for a language support only data type 64-bits float
and also support call into standard lib functions
eg.
def fib(x)
	if x < 3 then
	1
	else
		fib(x-1) + fib(x-2)

fib(40)

extern sin(arg)
extern cos(arg)
extern atans(arg1, arg2)

atan2(sin(.4), cos(42))
