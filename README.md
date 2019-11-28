#### How to run project:

1. Set the env variables
	
	`export FLASK_APP=First-Flask-App`
	
	`export FLASK_DEBUG=1`
	
2. You need to be in ../First-Flask-App NOT in the root file and run command
	
	`flask run`

#### To create the DATABASE:

	from project import db, create_app
	
	db.create_all(app.create_app())
