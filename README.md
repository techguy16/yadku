Yet Another Dialog (for Haiku)
====================

Haiku port of v1cont's [yad](https://github.com/v1cont/yad).

Download: [x86_64](https://github.com/techguy16/yadku/releases/download/1.0-haiku1/yad-1.0-haiku1.hpkg)

Building
----------------------

Before building, make sure you have `gtk3_devel` and `glib2_devel` packages installed from HaikuDepot.

```bash
git clone https://github.com/techguy16/yadku && cd yadku
autoreconf -ivf
./configure
make
```

Known issues
----------------------
*Please don't create issues if they're listed here.*

* Notebook and Paned don't exist, they were just being painful.
* In some instances, the window won't close.