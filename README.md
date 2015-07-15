lookup-iscroll
========

Based on https://github.com/cubiq/iscroll with some custom changes.

Version History
---------------

+ v5.1.3 - 2015-07-15
  + non-standard (and legacy) DOMMouseScroll and mousewheel events removed, now only 'wheel' is listened
  + new bottomYReached and topYReached events
  + no-bounce optimization (disabling function calls)
  + bower.json