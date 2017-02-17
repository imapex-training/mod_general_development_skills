
* With curl you can send data to a server as part of an API request as well.  The `-d` flag is used, and several options exist for providing the data.  You'll often need to include a `-H "Content-type: application/json"` header as well indicating the type of data being sent.  
	* Inline 

```	
# When sending JSON data, you need to escape inner quotes
curl -X POST -H "Authorization: Bearer $SPARK_TOKEN" \
	-H "Content-type: application/json" \
	https://api.ciscospark.com/v1/messages \
	-d "{\"toPersonEmail\": \"$PARTNER_EMAIL\",\"text\": \"Test message from lab\"}"
	
{"id":"...","roomId":"...","toPersonEmail":"...","roomType":"direct","text":"Test message from lab","personId":"...","personEmail":"...","created":"2016-07-26T21:05:00.330Z"}
		
```

