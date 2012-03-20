Description
===========
This is just a simple modification of the 'zero' base project on `pinax <http://pinaxproject.com/>`_
with preconfigured `compass  <http://compass-style.org/>`_
with `blueprint  <http://compass-style.org/reference/blueprint/>`_.
Basically you can use pinax to setup your project based on this template.

You get :
 * Basic directory tree / files for a Django project
 * Deploy scripts for pinax
 * Preconfigured Compass with Bluprint


The following files have been added inside the project:

::

    ├── static
    │   ├── css
    │   │   ├── ie.css
    │   │   ├── print.css
    │   │   └── screen.css
    │   ├── img
    │   │   └── grid.png
    │   ├── js
    │   └── sass
    │       ├── ie.sass
    │       ├── partials
    │       │   └── _base.sass
    │       ├── print.sass
    │       └── screen.sass
    ├── config.rb

Usage
=====

Just download the project folder (``compass_project``) anywhere and run the shell command inside your virtualenv:

::

     $  pinax-admin setup_project -b ../path/to/compass_project yourprojectname