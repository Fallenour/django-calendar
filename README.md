===================================   Fork Notes Begin   ===================================

Currently, the application, while well developed, shows a potential for signs of modestly formed coding design, which is to be expected for an application designed for basic function. The application shows signs of non-modular design, and so therefore these capacities will be added to remediate this issue.

Tasks to be completed:

1. Make the application fully modular, so it can be easily integrated into any django application.
2. Make the application tiered, so any layer can be modified without substantial amounts of effort, as well as fully customizable.
3. As always, Credit the original author for a job well done.


===================================   Fork Notes End   ===================================

Django-Calendar
=======================================
Full view calendar with year, month, week and day views based on templates with Twitter Bootstrap. 


Requirements
------------
- [Django 1.6](https://www.djangoproject.com/).
- [Django 1.6](http://www.makotemplates.org/).
- [jquery 1.11.3](https://jquery.com/).
- [Boostrap 2.3.1](http://getbootstrap.com/).
- [Underscore 1.8.3](http://underscorejs.org/).
- [Moment 2.x](http://momentjs.com/).


Main Stack
----------
   * Python 
   * Django 
   * Mako
   * jQuery
   * Bootstrap


Installation
------------
    * CENTOS
	   $ yum install python-pip
      $ pip install django==1.6
      $ pip install mako
      $ pip install django-mako
      $ yum install npm
      $ npm install -g bower
      $ pip install django-bower
      $ django-admin.py startproject djangocalendar
      $ ./manage.py bower install -- --allow-root


License
-------
Apache License, Version 2.0
http://www.apache.org/licenses/LICENSE-2.0

-- Forked From:
Jose Juan Martínez <jjmartinez@keedio.com>
