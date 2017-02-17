
* Inspect the HTTP Headers with `-v` to find out what happened... 
  
  ```
  curl -v https://api.ciscospark.com/v1/teams
  
	*   Trying 104.239.247.152...
	* Connected to api.ciscospark.com (104.239.247.152) port 443 (#0)
	* TLS 1.2 connection using TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384
	* Server certificate: *.ciscospark.com
	* Server certificate: Go Daddy Secure Certificate Authority - G2
	* Server certificate: Go Daddy Root Certificate Authority - G2
	> GET /v1/teams HTTP/1.1
	> Host: api.ciscospark.com
	> User-Agent: curl/7.43.0
	> Accept: */*
	>
	< HTTP/1.1 401 Unauthorized
	< Content-Length: 0
	< Date: Tue, 26 Jul 2016 20:32:26 GMT
	< Server: Redacted
	< Trackingid: NA_69b0048b-3bab-4175-a2c0-f9272ba99c2d
	< X-Cf-Requestid: 9b78f835-9d29-46a9-5211-27c5cf34f59e
	< Content-Type: text/plain; charset=utf-8
	<
	* Connection #0 to host api.ciscospark.com left intact  
  ```  

