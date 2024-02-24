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
9. Input title and content in the provided fields.
10. Publish the post directly.
12. After the post gets published, it will be displayed on the homepage of the blog ([localhost:3000](localhost:3000)).
12. Edit or delete the post later from the dashboard.




## Screenshots

![Screenshot (414)](https://github.com/obula-sai/Django-React-Blogify-App/assets/110908237/2a2396e2-b840-410b-9b76-baeb8aa0fe9a)


![Screenshot (419)](https://github.com/obula-sai/Django-React-Blogify-App/assets/110908237/c65fc105-34ac-48d4-8bca-b339c0a290dc)


![Screenshot (420)](https://github.com/obula-sai/Django-React-Blogify-App/assets/110908237/a732b8a2-057d-4dfd-8cbb-a1ecb8a2fe5b)

![Screenshot (417)](https://github.com/obula-sai/Django-React-Blogify-App/assets/110908237/291510cb-a298-4202-acc9-0ef3aec2d507)

![Screenshot (423)](https://github.com/obula-sai/Django-React-Blogify-App/assets/110908237/e37a1120-296e-4ff3-b53a-46e856d40b99)

![Screenshot (425)](https://github.com/obula-sai/Django-React-Blogify-App/assets/110908237/ec0f04a6-c150-4cf8-87ec-2418f2978340)



=
