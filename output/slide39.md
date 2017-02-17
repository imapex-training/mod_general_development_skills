
* Match lines containing the word 'hello' or 'world'

	```
	grep '(hello)|(world)' hello.txt
	
	# Nothing returned... 
	# Because this qualifies as an "extended" regular expression
	# use grep -E or egrep 
	
	grep -E '(hello)|(world)' hello.txt
	
	hello world
	goodbye world
	```

