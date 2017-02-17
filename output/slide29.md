
* By default curl sends an HTTP **GET** method.  
* To send other methods, use the `-X` option.  

```
curl -X POST -H "Authorization: Bearer $SPARK_TOKEN" \
	https://api.ciscospark.com/v1/messages 
	
{"message":"Required request body is missing","errors":[{"description":"Required request body is missing"}],"trackingId":"NA_c4d9d517-3617-4b6a-a521-dc2a26334dd6"}
	
# When POSTING, you often have to include data, as the error message indicates
```

