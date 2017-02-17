
* You can capture the returned data (not headers, just data) using the `-o <file>` option to curl.  
	* _You can use `-o /dev/null` as a shortcut to drop any returned data if only interested in headers or testing_

	```
	curl -H "Authorization: Bearer $SPARK_TOKEN" \
		https://api.ciscospark.com/v1/teams -o teams.json
	
	ls -l 	
	-rw-r--r--  1 user123  staff  904 Jul 26 15:49 teams.json
	
	```	
	
