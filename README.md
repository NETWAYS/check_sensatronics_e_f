check_sensatronics_e_f
======================

This archive contains two Nagios plugin for monitoring the temperature
of probes attached to TempTrax Model E and Model F devices.

The check_temptraxe plugin is used to monitor probes attached to a 4-,
8- or 16-port TempTrax Model E (Ethernet version).  Similiarly, the
check_temptraxf plugin is used to monitor probes attached to a 
TempTrax Model F (serial port version).  

### Installation

Download and extract the tarball from https://www.netways.org/projects/plugins/files

Run configure and make to compile the sources.

    ./configure
    make
    
### Usage

Execute the plugins without any arguments to get usage information.
Example:

    ./check_temptraxe
    ./check_temptraxf
