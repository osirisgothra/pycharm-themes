TextMate themes for PyCharm
===========================

Current Supported PyCharm versions: 3 and 4&nbsp;:sparkle:

This secondary fork of the original:

* The first fork is here: https://github.com/benbovy/pycharm-themes
* The original is here: https://github.com/d1ffuz0r/pycharm-themes
* The current Author is not affiliated with the above Authors
* Please direct questions about any file(set) to the appropriate Author(s)!
* Themes for older versions check at [Releases](https://github.com/d1ffuz0r/pycharm-themes/releases) page

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

The step to create the "colors" directory is *only* required if you have never customized
your colors with the user in question. You can safely ignore the error that the directory
already exists. Furthermore, you should <b>run PyCharm at least once before attempting to
install these colors or else you will need to create the entire directory tree yourself</b>.

If you require instructions or think a platform is missing, please let me know and I'll put it up here.

Installation for Windows
------------------------

PyCharm 3.0
```bat
cd /d c:\temp
git clone git://github.com/osirisgothra/pycharm-themes.git
cd pycharm-themes/colors
md "C:\Documents and Settings\<User name>\.PyCharm30\Config\Colors"
xcopy *.icls "C:\Documents and Settings\<User name>\.PyCharm30\Config\Colors"
```

PyCharm 4.0 and 4.5 (including 4.5.4)
```bat
cd /d c:\temp
git clone git://github.com/osirisgothra/pycharm-themes.git
cd pycharm-themes/colors
md "C:\Documents and Settings\<User name>\.PyCharm40\Config\Colors"
xcopy *.icls "C:\Documents and Settings\<User name>\.PyCharm40\Config\Colors"
```


Installation for Mac OS X
-------------------------

PyCharm 3.0
```sh
git clone git://github.com/osirisgothra/pycharm-themes.git
cd pycharm-themes/colors
mkdir ~/Library/Preferences/PyCharm30/colors
cp *.icls ~/Library/Preferences/PyCharm30/colors
```

PyCharm 4.0 and 4.5 (including 4.5.4)
```sh
git clone git://github.com/osirisgothra/pycharm-themes.git
cd pycharm-themes/colors
mkdir ~/Library/Preferences/PyCharm40/colors
cp *.icls ~/Library/Preferences/PyCharm40/colors
```


Installation for Linux
----------------------

PyCharm 3.0
```sh
git clone git://github.com/osirisgothra/pycharm-themes.git
cd pycharm-themes/colors
mkdir ~/.PyCharm30/config/colors
cp *.icls ~/.PyCharm30/config/colors/
```

PyCharm 4.0 and 4.5 (including 4.5.4)
```sh
git clone git://github.com/osirisgothra/pycharm-themes.git
cd pycharm-themes/colors
mkdir ~/.PyCharm40/config/colors
cp *.icls ~/.PyCharm40/config/colors/
```

:sparkle:&nbsp; Latest version 4.5.4 as of September 15, 2015
