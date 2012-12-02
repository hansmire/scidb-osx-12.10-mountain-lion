SciDB 12.10 on OSX Mountain Lion
================================

Obtain the prerequisites:

* CMake 2.8, installed with MacPorts.
* SWIG 2.0, installed with MacPorts.
* Protobuf 2.4, installed with MacPorts.
* Log4CXX 0.10, installed with MacPorts.
* Boost 1.52, installed with MacPorts.
* libpqxx 3.1, compiled from source.
* PostgreSQL 8.4 server, installed with MacPorts.

Build SciDB with CMake, and install it to the default location in /opt/scidb.

Create an administrative user named scidb.  Follow the instructions in the
SciDB user guide to configure the scidb user environment and setup a SciDB
instance.  When creating /opt/scidb/12.10/etc/config.ini, be sure to use
"/Users/scidb" for the scidb home directory instead of "/home/scidb".


