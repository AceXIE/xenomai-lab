Cross your fingers. That's, like, a basic rule for this sort of thing.

The folder data/xenomailab/ should be copied to ~/.xenomailab/
This is where the blocks are stored.
Remember to build a project before executing it because there are no executables untill you build them :-)

How to:

0.Dependencies

sudo apt-get install libboost-graph-dev qt4-dev-tools build-essential

1.Compile Xenomai Lab:
qmake
make

2.Install
sudo make install

3.Uninstall
sudo make uninstall