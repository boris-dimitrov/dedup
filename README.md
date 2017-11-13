# dedup
Help identify duplicate files that can be profitably replaced with hardlinks.

# caution

Replacing duplicates with hardlinks is generally unsafe.  Don't do
it for files under version control, files that are subject to automatic
updates, or files whose attributes (like the time of last access) are
just as important as their contents.  There may be many more exceptions
on your system.

# usage

This is only a bandaid for sorely missing Mac OS filesystem functionality.
It requires manual tweaks for each individual application, with extremely
careful reviews to minimize the possiblity of harming important files.

Read dedup.py for usage.
