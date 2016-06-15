PVW launcher
=========

An Ansible role to install the ParaViewWeb launcher

Requirements
------------

This is intended to be run on a clean Ubuntu 14.04 or CentOS 7 system. ParaView must install on the system.

Role Variables
--------------

The following variables may be overridden:

* paraview_install_path: The path to ParaView install tree.
* pvw_user: The user to run the launcher as.
* pvw_launcher_log_path: The path to write the launcher logs to.
* pvw_launcher_config_path: The path to write the launcher configuration to.
* pvw_launcher_config_file_path: The launcher configuration file path.
* pvw_launcher_template: The template file to use to generate the launcher configuration
* pvw_launcher_library_path: Any extra directory to add to the library path, colon separted.

License
-------

Apache

