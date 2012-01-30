thornhill 0.3
=============

thornhill is a Small but Useful(tm) utility to test Alias (and, in the
future, other) directives it finds in an Apache config file.  It's
meant to be useful for ensuring that content on one server is the same
as on another (ie, when migrating servers).

Note my assumption: that Apache directives are important enough to be
worth testing on their own.  IOW, thornhill will *not* test everything
about your site; it will simply allow you to work through a long list
of directives, making sure things work as you go along.

Other assumptions:

- you have an old site where everything is working, and a new site
  you wish to eventually make live
- DNS has not yet been changed
- the VirtualHost config is the same on both machines (in particular,
  ServerAlias/ServerName and Alias directives)
- Alias and other Apache directives are sufficiently important to be
  worth testing on their own

The directives tested are:

- Alias
- RedirectMatch

More to come...

Dependencies
------------

Perl modules:

- Test::More
- Apache::Admin::Config
- Test::WWW::Mechanize

Bugs
----

- Assumes ServerAlias; you'll need to adjust that below

ChangeLog
---------

0.1: Initial release
0.2: README, license, cleanup.
0.3: Use Test::WWW::Mechanize; test for RedirectMatch.

TODO
----

- better tests
- better documentation (POD?)
- Save tests to file for running later
- Allow tests to be specified (eg: find "this sentence" in both
  pages, rather than worry about whether they're both identical;
  should catch things like different dates, session ids, etc)

Named after
-----------

Lisa Thornhill (http://www.imdb.com/title/tt0221728/)

License
-------

thornhill is released under version 3 of the GPL; see COPYING for details.

Homepage
--------

http://saintaardvarkthecarpeted.com/software/thornhill

Hugh Brown
January 2012

