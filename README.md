OpenBrain Plasmoid Source
-----------------
[![Build Status](https://travis-ci.org/Tiger66639/openbrain.svg)](https://travis-ci.org/Tiger66639/openbrain)
You need Qt4.svn
You also need KDE4.2.x.svn

run:

cmake .
make
sudo make install





If you have an odd kde4 installation you may have to run:
'cmake -DCMAKE_INSTALL_PREFIX=`kde4-config --prefix` .' 
instead of just 'cmake .' Note: the backticks in the cmake command above.
