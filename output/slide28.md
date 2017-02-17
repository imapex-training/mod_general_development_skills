
* If you want to capture the Headers to a file, use the `-D <file>` argument. 

	```
	curl -H "Authorization: Bearer $SPARK_TOKEN" \
		https://api.ciscospark.com/v1/teams \
		-D headers.txt
	
	ls -l
	total 16
	-rw-r--r--  1 user123  staff  296 Jul 26 16:10 headers.txt
	```

