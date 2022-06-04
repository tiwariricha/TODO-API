# TODO-API
API to create TODO APP
open the project directory and run the following command

virtualenv project-env
$ source project-env/bin/activate
$ pip install django

$ python manage.py makemigrations
This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command

$ python3 manage.py migrate

now install all the required dependency run command
pip install -r /path/to/requirements.txt

One last step and then todo App will be live.  On the terminal, type the following command 

$ python3 manage.py runserver   
That was pretty simple,  Now all the api of the App live. we can start using our simple todo Apis. 

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

