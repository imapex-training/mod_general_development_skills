
* Log into your newly created environment 

```
vagrant ssh 
	
# this places you into the virtual environment
# follow along with the commands entered at the prompts
[vagrant@localhost ~]$ pwd
/home/vagrant
	
# Vagrant boxes typically use a user called "vagrant"
# In that users's home directory is a folder called "sync" 
[vagrant@localhost ~]$ ls -l
total 4
drwxr-xr-x. 2 vagrant vagrant 4096 Jul 27 14:20 sync
	
[vagrant@localhost ~]$ ls -l sync/
total 4
-rw-r--r--. 1 vagrant vagrant 3020 Jul 27 14:20 Vagrantfile

# The "sync" folder is linked to the project directory on 
# your computer.  This makes development easy because you 
# can develop on your laptop using your local tools, and 
# immediately test and run code inside the enviornment without
# manual coping and transferring code
	
# type exit to return to your local terminal
exit
```

