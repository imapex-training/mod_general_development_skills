
* Count the number of lines containing 'world'

	```
	awk '/world/{++cnt} END {print "Count = ", cnt}' hello.txt
	```

