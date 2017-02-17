
* Update the original file (and backup the old data) 

	```
	sed -i '.bak' 's/good /GOOD /' hello.txt 
	
	cat hello.txt
	
	hello world
	goodbye world
	GOOD morning
	GOOD evening
	life is a box of chocolates
	you never know what you're going to get
	
	# Put it back the way it was... 
	sed -i '.bak' 's/GOOD /good /' hello.txt 
	```

