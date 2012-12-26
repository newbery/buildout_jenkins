
Requirements
============

1) A working java in the system path ...

2) ?


Bootstrap
=========

$ git ...
$ python virtualenv.py

Check the python paths in the [pythons] section of 'config/base.cfg'.
Do not edit 'base.cfg' directly.  If necessary, make a 'local.cfg'
in the buildout root with any local overrides.

Example:
$ echo -e "[pythons]\npaths=/path/to/python2.4 /path/to/python2.6" > local.cfg


Buildout
========

$ bin/buildout

or to apply local overrides...

$ bin/buildout -c local.cfg


Jenkins
=======

To start,

$ bin/jenkins start

To stop,

$ bin/jenkins stop

To start in foreground mode,

$ bin/jenkins fg

Visit at http://localhost:8081/jenkins/


