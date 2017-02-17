
* Print the second word in all lines containing the word 'good'

	```
	awk '/good/ { print $2 }' hello.txt
	
	world
	morning
	evening
	
	# what if we don't want "goodbye" to match 
	awk '/good / { print $2 }' hello.txt
	
	morning
	evening
	```

