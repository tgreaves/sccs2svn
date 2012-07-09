sccs2svn
========

Branch: jobsite-master

This was branched in order to add various updates to support a migration at Jobsite.

Summary of changes:

* Print file that is _about_ to be processed (to help pinpoint errors).
* Set svn --fs-type to bdb  (to avoid 'Too many open files' error)
* Use os.walk instead of deprecated os.path.walk (symlinks were being followed)
