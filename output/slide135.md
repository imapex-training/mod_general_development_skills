
* 	Sometimes you may want to check the status of vagrant environments on your entire computer, not just the current directory

```	
vagrant global-status
	
id       name    provider   state   directory
-----------------------------------------------------------------------------------------------
43c5018  default virtualbox saved   /Users/hapresto/coding/myhero_app
24f2e19  default virtualbox saved   /Users/hapresto/coding/myhero_web
20f794d  default virtualbox saved   /Users/hapresto/coding/mantl_cicd_sampleapp
26aa5b7  default docker     running /Users/hapresto/coding/mantl_cicd_sampleapp
9608b2f  default docker     running /Users/hapresto/coding/myhero_app
2ce0ff0  default virtualbox running /Users/hapresto/coding/myhero_data
8f444c4  default docker     running /Users/hapresto/coding/myhero_data
01874c0  default virtualbox running /Users/hapresto/coding/imapex101/examples/imapex101vagrant
	
The above shows information about all known Vagrant environments
on this machine. This data is cached and may not be completely
up-to-date. To interact with any of the machines, you can go to
that directory and run Vagrant, or you can use the ID directly
with Vagrant commands from any directory. For example:
"vagrant destroy 1a2b3c4d"
	
```
	
