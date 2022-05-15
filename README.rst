feed2mail
---------
rss2email done simple.

Delivers news from feeds (RSS, Atom, ...) to your mail box.

Required Env
~~~~~~~~~~~~~~
**Required**::

   pip install html2text feedparser

How to use it?
~~~~~~~~~~~~~~
1. ``cp example_config.py config.py``.
2. Edit ``config.py``.
3. Run feed2mail every *N* seconds/hours/decades. For Docker setup::

     docker run -v /path/to/your/seen/file:/seen feed2mail
    
   For manual virtualenv setup, simply run ``feed2mail.py``.

I've found a bug!
~~~~~~~~~~~~~~~~~
Great! `Please open a ticket`_.

.. _Please open a ticket: http://github.com/jonashaag/feed2mail/issues/

License?
~~~~~~~~
ISC
