wysiwyg_codefilter
==================

Mirror of http://drupal.org/sandbox/cam8001/1847398 to enable easy download for non-developers.

Usage:

- Install wysiwyg, code_filter, and wysiwyg_codefilter (this module) in the normal way.
- For the input type you are using, make sure that "Code Filter" is at the bottom of the filter
  processing order at admin/config/content/formats
- You will now be able to use <?php tags in WYSIWYG editors. You will NOT be able to see PHP
  code in the "Rich-text" editing mode.