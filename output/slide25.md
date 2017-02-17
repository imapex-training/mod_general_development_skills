
* curl will simply write out the data as returned by the server, and it isn't always in a handy format, particularly when returned as raw JSON.  You can "pipe" JSON data to an included python module to make it more readable.  

	```
	curl -H "Authorization: Bearer $SPARK_TOKEN" \
		https://api.ciscospark.com/v1/teams \
		| python -m json.tool
		
	  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
	                                 Dload  Upload   Total   Spent    Left  Speed
	100   904  100   904    0     0    428      0  0:00:02  0:00:02 --:--:--   428
	{
	    "items": [
	        {
	            "created": "2016-06-29T13:29:05.416Z",
	            "id": "...",
	            "name": "MidW/A imapex"
	        }
	    ]
	}
	```  

