====================
cav-django-fernet-fields
====================

`Fernet`_ symmetric encryption for Django model fields, using the
`cryptography`_ library.

``django-fernet-fields`` supports `Django`_ 1.11 and later on Python 2.7, 3.5, 3.6, 3.7, pypy, and pypy3.

Only PostgreSQL, SQLite, and MySQL are tested, but any Django database backend
with support for ``BinaryField`` should work.

.. _Django: http://www.djangoproject.com/
.. _Fernet: https://cryptography.io/en/latest/fernet/
.. _cryptography: https://cryptography.io/en/latest/
