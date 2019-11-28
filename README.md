How to run project:
	1. Set the env variables
		export FLASK_APP=project
		export FLASK_DEBUG=1
	2. You need to be in ../your-project NOT in the root file and run command
	flask run

To create the DATABASE:
	from project import db, create_app
	db.create_all(app.create_app())
