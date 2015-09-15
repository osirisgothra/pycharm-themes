TextMate themes for PyCharm
===========================

Current PyCharm version: 3, 4, and, 4.5 (at 4.5.4)

This is a fork of a fork:

* The current author at this time is not affiliated with the original authors, for stuff that is not
  modified here, please ask the respective author(s)
* The fork is here: https://github.com/benbovy/pycharm-themes
* The fork's fork (original author) is here: https://github.com/d1ffuz0r/pycharm-themes

Themes for older versions check at [Releases](https://github.com/d1ffuz0r/pycharm-themes/releases) page

Themes list
-----------

* All Hallow's Eve
* Amy
* Blackboard
* Cobalt
* Dawn
* Eiffel
* Espresso Libre
* GitHub
* IDLE
* LAZY
* Mac Classic
* MagicWB (Amiga)
* Monokai Bright
* Pastels on Dark
* PyDev
* Solarized (Dark)
* Solarized (Light)
* SpaceCadet
* Sunburst
* Zenburnesque
* Django
* iPlastic

Installation
============
This section has been slightly modified for your cut-copy-paste convience and now includes
the installation instructions for Windows users as well. The instructions are bit-width
agnostic, so it will work regardless of 32-bit or 64-bit installations. Unless you are
using a heavily customized system, these locations are standard across the mentioned
systems. 

If you require instructions or think a platform is missing, please let me know and I'll put it up here.

Installation for Windows
------------------------

PyCharm 3.0
```
cd /d c:\temp
git clone git://github.com/osirisgothra/pycharm-themes.git
cd pycharm-themes/colors
xcopy *.icls "C:\Documents and Settings\<User name>\.PyCharm30\Config\Colors"
```

PyCharm 4.0 and 4.5 (including 4.5.4)
```
cd /d c:\temp
git clone git://github.com/osirisgothra/pycharm-themes.git
cd pycharm-themes/colors
xcopy *.icls "C:\Documents and Settings\<User name>\.PyCharm30\Config\Colors"
```


Installation for Mac OS X
-------------------------

PyCharm 3.0
```
git clone git://github.com/osirisgothra/pycharm-themes.git
cd pycharm-themes/colors
cp *.icls ~/Library/Preferences/PyCharm30/colors
```

PyCharm 4.0 and 4.5 (including 4.5.4)
```
git clone git://github.com/osirisgothra/pycharm-themes.git
cd pycharm-themes/colors
cp *.icls ~/Library/Preferences/PyCharm40/colors
```


Installation for Linux
----------------------

PyCharm 3.0
```
git clone git://github.com/osirisgothra/pycharm-themes.git
cd pycharm-themes/colors
cp *.icls ~/.PyCharm30/config/colors/
```

PyCharm 4.0 and 4.5 (including 4.5.4)
```
git clone git://github.com/osirisgothra/pycharm-themes.git
cd pycharm-themes/colors
cp *.icls ~/.PyCharm40/config/colors/
```
