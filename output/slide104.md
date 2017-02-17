
* So we've verified the condition we are attempting to correct though the use of a test case. 
* Now let's modify our function, and add some input validation.  Update `doubler.py` 

	```
	def doubler(n):
	    """
	    A slightly more robust doubler function
	    :param n: int
	    :return: int
	    """
	    
	    if isinstance(n, int):
	        return 2 * n
	    else:
	        raise TypeError('n must be of type integer')
	
	```

