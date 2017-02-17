
* If you are making a request to an HTTPs site, but one that lacks a fully verifiable certificate, curl will by default throw an error.  You can use the `-k` option to allow insecure connections.  

	```
	# Example command 
	curl -k https://badsecurity.com
	```  
	
