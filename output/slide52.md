
* If you are matching text that contains `/` it can be a pain to escape them all, so you can use `_`, `:`, `|` as alternatives.  Just pick something that isn't in your string.  

	```
	echo 'I am sad.  So very very sad...' | sed 's:sad:happy:g'
	
	I am happy.  So very very happy...
	```

