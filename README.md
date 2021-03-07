# Django React Todo
 Cool CRUD Example project from -> https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react

![thingey-under30](https://user-images.githubusercontent.com/7981120/110251135-1f57f700-7f4d-11eb-98f2-333bcd29b0aa.gif)

- 'pipenv shell' will activate a vitrual enviroment from your working powershell directory
- 'django-admin startproject backend' - creates the backend project -> cd backend
   - 'python manage.py startapp todo' - runing this from the backend folder created above will create the app 'todo'
   - 'python manage.py migrate' - runs migration
   - 'python manage.py runserver' - starts the server on http://localhost:8000
   - 'python manage.py makemigrations todo' - creates a migration file for the 'todo' model 
   - 'python manage.py migrate todo' - applies the new model changes to the sqlite database
    
 - 'npx create-react-app frontend' creates new frontend project (do this from root) -> cd frontend
   - 'npm start' starts the react app at http://localhost:3000
   - 'frontend/package.json' contains -> "proxy": "http://localhost:8000", which links app to backend
