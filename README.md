gitslave may be better for your purposes
http://gitslave.sourceforge.net/

how I created this repo:
for each subdirectory (e.g., front-end, back-end)
   change to that directory
      for k in [repo]... ; do git submodule add $k ; done
   return to the parent/meta repo directory
