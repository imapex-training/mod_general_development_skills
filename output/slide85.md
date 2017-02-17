
* Use pip to read in the requirements and verify the virtualenv meets all needed requirements.  

	```
	pip install -r requirements.txt
	
	Requirement already satisfied (use --upgrade to upgrade): requests==2.10.0 in ./venv/lib/python2.7/site-packages (from -r requirements.txt (line 1))
	Collecting Flask==0.10.1 (from -r requirements.txt (line 2))
	Collecting itsdangerous>=0.21 (from Flask==0.10.1->-r requirements.txt (line 2))
	Collecting Werkzeug>=0.7 (from Flask==0.10.1->-r requirements.txt (line 2))
	  Using cached Werkzeug-0.11.10-py2.py3-none-any.whl
	Collecting Jinja2>=2.4 (from Flask==0.10.1->-r requirements.txt (line 2))
	  Using cached Jinja2-2.8-py2.py3-none-any.whl
	Collecting MarkupSafe (from Jinja2>=2.4->Flask==0.10.1->-r requirements.txt (line 2))
	Installing collected packages: itsdangerous, Werkzeug, MarkupSafe, Jinja2, Flask
	Successfully installed Flask-0.10.1 Jinja2-2.8 MarkupSafe-0.23 Werkzeug-0.11.10 itsdangerous-0.24 
	```

