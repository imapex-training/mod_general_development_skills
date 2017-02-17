
* Cisco Spark, and many other services, use Request Headers to provide authenticaiton information.  
	* Set a Request Header with `-H "<Header-Name>: <Value>` argument.  Multiple `-H` arguments are supported.
	* OAUTH2 is a common mechanism used for authentication, and is used by Cisco Spark.  It leverages a Request Header called **Authorization** with a value of _Bearer \<TOKEN\>_

	```
	curl -H "Authorization: Bearer $SPARK_TOKEN" \
		https://api.ciscospark.com/v1/teams	
	
	{"items":[{"id":"...","name":"MidW/A imapex","created":"2016-06-29T13:29:05.416Z"}]}
	```

