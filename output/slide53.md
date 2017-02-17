
* sed much more useful working with files.  Let's emphasize 'good' to 'GOOD'

	```
	sed 's/good/GOOD/' hello.txt
	
	hello world
	GOODbye world
	GOOD morning
	GOOD evening
	life is a box of chocolates
	you never know what you're going to get
	
	# Whoops... didn't want to chagne goodbye, indicate word breaks
	sed 's/good /GOOD /' hello.txt
	
	hello world
	goodbye world
	GOOD morning
	GOOD evening
	life is a box of chocolates
	you never know what you're going to get
	```

