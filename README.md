lispkit
=======

A lisp browser using WebKit


Installation
------------

Ensure you have Quicklisp available locally.

System deps
-----------

* libwebkitgtk
* gtk2
* A CL implementation (tested with SBCL so far)

```shell
cd $QUICKLISP_HOME/local-projects
git clone https://github.com/AeroNotix/cl-webkit.git
git clone https://github.com/AeroNotix/lispkit.git
sbcl --noinform --quit --eval \
    "(ql:quickload :lispkit)"
```

Status
------

Very early work

Some videos

* Control via SLIME: https://www.youtube.com/watch?v=9GJcct_FyVw
* Keybinds: https://www.youtube.com/watch?v=NxiYnJ_JfRQ
* Navigation: https://www.youtube.com/watch?v=wXQKZX96QDA
