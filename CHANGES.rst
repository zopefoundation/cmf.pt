Changelog
=========

In next release...


1.0 - 2010-05-12
----------------

- Correct binding of templates. This fixes problems handling args when
  renderingn templates. [malthe]

0.6 - 2009-10-25
----------------

- Added a ``z3c.autoinclude.plugin`` entry point to avoid the need for a ZCML
  slug in Plone.
  [hannosch]

0.5 - 2009-07-24
----------------

- Extend the ignore_re list of CMFCore.DirectoryView to ignore our cache
  files named `.<original extension>.py`. [hannosch]

0.4 - 2009-05-18
----------------

- Avoid a deprecation warning for Globals.InitializeClass. [hannosch]

0.3 - 2009-02-13
----------------

- Added ``_exec`` method to the file-system based skin template class, largely
  carried over from `Products.PageTemplates`. [malthe]

0.2 - 2008-12-17
----------------

- The ``func_code`` attribute of file-system page templates should simulate a
  function taking no arguments. [malthe]

0.1 - 2008-11-29
----------------

- Initial release. [malthe]
