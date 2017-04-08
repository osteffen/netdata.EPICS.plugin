# netdata EPICS Plugin
This is a plugin for the [netdata](https://github.com/firehol/netdata/wiki) monitoring system.
It allows access to the [Experimental Physics and
Industrial Control System (EPICS)](http://www.aps.anl.gov/epics/index.php).

Warning: This project is in a very early state and probably not really useful yet.

## Prerequisites
  * Python 2.7 (3.x not testet)
  * EPICS (3.14)
  * [pyEpics](http://cars9.uchicago.edu/software/python/pyepics3/)
  * [netdata](https://github.com/firehol/netdata/wiki)
  
## How to install
Clone the repo and copy the `EPICS.plugin` file to the plugin folder of your netdata installation, usually `/usr/libexec/netdata/plugins.d`. Enable the plugin by adding this to your netdata.conf:
```
   [EPICS]
	    enabled = yes      
```
Restart netdata.

Make sure `PYTHONPATH` and `LD_LIBRARY_PATH` are correct and EPICS and pyEpics can be found.

## Configuration
...not possible yet. Edit the source code... for now.
