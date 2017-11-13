# dedup
Help identify duplicate files that can be profitably replaced with hardlinks.

# caution

Replacing duplicates with hardlinks is generally unsafe.

It can be particularly harmful to

  * files under version control
  
  * files that are subject to automatic updates
  
  * files whose attributes (e.g., last access time) are
just as important as their contents


# usage

This is a bandaid for sorely missing Mac OS functionality.
Each application requires extremely careful reviews and manual
adjustments to the code in order to minimize the possiblity of
harming important files.

Read dedup.py for usage.
