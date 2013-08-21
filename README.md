#### [Project Homepage][1]
#### [API Documentation][2] and [Manual][3]

--------------------

About
=====

Adds a queue extension to python-slimta that stores messages and message
metadata to [redis][4] hash keys. This is a storage plugin for the standard
queue engine that uses [redis-py][5] with gevent sockets to asynchronously
communicate with the database.

[![Build Status](http://ci.slimta.org/job/python-slimta-redisstorage/badge/icon)](http://ci.slimta.org/job/python-slimta-redisstorage/)

Getting Started
===============

If you haven't yet installed [`python-slimta`][6], refer to the "Getting
Started" section. Once inside your virtualenv:

    (.venv)$ python setup.py develop

To run the suite of included unit tests:

    (.venv)$ nosetests

Refer to the [API Documentation][2] and [Manual][3] for more information on
using this extension.

[1]: http://slimta.org/
[2]: http://docs.slimta.org/latest/api/extra.redisstorage.html
[3]: http://docs.slimta.org/latest/manual/extensions.html#redis-storage
[4]: http://redis.io/
[5]: https://github.com/andymccurdy/redis-py
[6]: https://github.com/slimta/python-slimta

