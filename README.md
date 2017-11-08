# django-blog-app
DjangoPractice: A Simple Blog Application using Python's Django Web Framework


## How to run
- First make sure that you have installed Python3 and Django on your system
- After installing : 
~~~~
git clone https://github.com/HassanAzam/django-blog-app.git
cd django-blog-app
python manage.py runserver
~~~~
- go to ````localhost:8000/blog/```` to see blog posts
- go to ````localhost:8000/admin/```` to manage users and blog
* To login at ````localhost:8000/admin/````, first create superuser: (from django-blog-app directory) type:

  ~~~~
  python manage.py createsuperuser
  ~~~~
- Login with the superuser details


### V1.0
- Admin site to manage users and blogposts
- Blog Posts 'list' and 'detail' views
- Posts Pagination


### V2.0 (will update soon)
- Sharing posts by email
- Adding comments
- Tagging posts
- Posts by similarity
