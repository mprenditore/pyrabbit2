.. image:: https://travis-ci.org/deslum/pyrabbit2.svg?branch=master

==================
PyRabbit2
==================

This project is fork project pyrabbit https://github.com/bkjones/pyrabbit 

I fork project, because he don't update many years.

Pyrabbit is a module to make it easy to interface w/ RabbitMQ's HTTP Management
API.  It's tested against RabbitMQ 3.6.10 using Python 2.7-3.6. It has
a pretty solid set of tests, and I use tox to test across Python versions.

PyRabbit is on PyPI, which makes it installable using pip or easy_install.

Support:

   - Users (Create, Read, Update, Delete)
   - User acess SHA256 + salt 
   - Permissions
   - Polices
   - Vhosts (Create, Read, Update, Delete)
   - Exchanges (Create, Read, Update, Delete)
   - Bindings (Create, Read, Update, Delete)
   - Queues (Create, Read, Update, Delete)
   - Shovel
   - Work with cluster nodes
   - Many features support RabbitMQ API https://pulse.mozilla.org/api/

Install::

     pip3 install pyrabbit2
     
     
See the documentation at http://pyrabbit.readthedocs.org

Please send pull requests! Pyrabbit doesn't yet provide 100% coverage of
the exposed RabbitMQ API, so dig in! 
