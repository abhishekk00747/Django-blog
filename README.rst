=====
Django HLRS Blog
=====

It is a simple Django app to where authors can post there blogs. 

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "blog" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'blog',
    ]

2. Include the polls URLconf in your project urls.py like this::

    path('', include('blog.urls')),

3. Run `python manage.py migrate` to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a blogs (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/ to see all the blogs.