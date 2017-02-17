
* What do we know about the code?  In the case of `doubler()` we know from the code that it takes an integer as an input and returns an integer equal to two times the input. Great.. so what? In this simple example, not much can go wrong, but we should test to document what the use case was.  

	```
	python -i
	
	from doubler import doubler
	
	print doubler(2)
	print doubler('2')
	
	```

