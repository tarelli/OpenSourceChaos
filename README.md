OpenSourceChaos
===============

Classical nonlinear systems described using LEMS. At the moment, in order to simulate anything you will need to install 
[jLEMS]([https://github.com/LEMS/jLEMS/).


Example:
----------------
$ git clone git@github.com:LEMS/jLEMS.git
$ git clone git@github.com:borismarin/OpenSourceChaos.git
$ cd jLEMS
$ mvn install
$ ./lems ../OpenSourceChaos/butterfly.xml
