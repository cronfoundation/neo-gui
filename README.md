Project Setup
=============

On Linux:
=========
`yum install leveldb-devel`

On Windows:
===========

To build and run locally, you need to clone and build https://github.com/neo-project/leveldb first, 
then copy `libleveldb.dll` to the working directory (i.e. /bin/Debug, /bin/Release)

Note: When building, the project file settings must be changed from static library (lib) to dynamic linked library (dll).

Running Binaries on Windows:
===========

To run precompiled binaries, execute

x86: \neo-gui\bin\Release\x86\cron-gui.exe

x64: \neo-gui\bin\Release\x64\cron-gui.exe
