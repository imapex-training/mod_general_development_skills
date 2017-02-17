
* Let's lifecycle the environment
* Run this command to get a glimpse at the different lifecycle actions	

```
vagrant ? | grep "up\|destroy\|halt\|reload\|resume\|suspend"
	
     destroy         stops and deletes all traces of the vagrant machine
     halt            stops the vagrant machine
     plugin          manages plugins: install, uninstall, update, etc.
     reload          restarts vagrant machine, loads new Vagrantfile configuration
     resume          resume a suspended vagrant machine
     suspend         suspends the machine
     up              starts and provisions the vagrant environment
```

