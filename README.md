# Blogify App
## Overview

Blogify is a full-stack web application built with Django and ReactJS, offering a seamless experience for users to create, edit, and delete their blog posts. It provides a user-friendly interface and robust backend functionality using Django Rest Framework.

### Features
* Login/Registration
* User-Friendly Design
* Create/Edit/Delete Your Posts
* User Profile
* Blogs Homepage


## Backend Setup
1. Clone this repository: `git clone https://github.com/obula-sai/Django-React-Blogify-App.git`.
2. Change the current directory to `backend` folder: `cd ./Django-React-Blog/backend/`.
3. Create a virutal environment and install all backend dependencies with pipenv: `pipenv install`.
4. Start the virtual environment: `pipenv shell`.
5. Change the working directory to `blog_backend` which contains the `manage.py` file: `cd ./blog_backend`.
6. Run `python manage.py makemigrations`.
7. Run `python manage.py migrate`.
8. Create a superuser: `python manage.py createsuperuser`
9. Run the server: `python manage.py runserver`.

## Frontend Setup
1. Navigate the current working directory to `blog_frontend`: `cd ./Django-React-Blog/frontend/blog_frontend/`.
2.  Install the all frontend dependencies using npm: `npm install`.
3.  Run the server: `npm start`.

### Creating The First Post
1. Make sure that both Backend and Frontend Servers are running.
2. Open your browser and navigate to [localhost:3000](localhost:3000).
3. Go To [http://localhost:3000/login/](http://localhost:3000/login/).
4. Access the login or registration page.
5. Enter your credentials or fill in the registration form.
6. Click the login or register button to proceed.
7. Upon successful login or registration, you'll be redirected to Home Page
8. Look for "Create Post" option, proceed to post creation.
9. Input title, content, and metadata in the provided fields.
10. Publish the post directly.
12. After the post gets published, it will be displayed on the homepage of the blog ([localhost:3000](localhost:3000)).
12. Edit or delete the post later from the dashboard.




## Screenshots
![Screenshot (408)](https://github.com/obula-sai/Django-React-Blog-App/assets/110908237/1f46f7e7-a587-4261-8d0e-718634ab61ff)


![Screenshot (409)](https://github.com/obula-sai/Django-React-Blog-App/assets/110908237/76bb3505-8928-4e7b-b9bc-adf53b2d53a1)


![Screenshot (410)](https://github.com/obula-sai/Django-React-Blog-App/assets/110908237/9f63fd65-94da-479f-9527-056dd44e3550)



![Screenshot (411)](https://github.com/obula-sai/Django-React-Blog-App/assets/110908237/b26a4c6b-6c67-4bfe-af54-649471731e01)

![Screenshot (412)](https://github.com/obula-sai/Django-React-Blog-App/assets/110908237/1ea6efa7-6bbb-4afc-9c40-51f53ab6dc5a)
![Screenshot (413)](https://github.com/obula-sai/Django-React-Blog-App/assets/110908237/3995b86a-727e-42c0-a8fd-709ecd7cc3a4)









=
