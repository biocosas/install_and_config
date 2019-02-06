install_and_config
==================

Some tips to install and configure Linux and some Linux applications used in bioinformatics.  

Started with Ubuntu 14.04 but currenly using __18.04__.




Create a pen drive for the installation
---------------------------------------

Download the appropriated __iso__ file from the ?Ubuntu web page and run: 

    usb-creator-gtk

or go to the _Startup Disk Creator_ application.

Insert the pen drive and follow the default steps.

See:

- <http://www.ubuntu.com/download/desktop/create-a-usb-stick-on-ubuntu>
- <http://www.ubuntu.com/download/desktop/install-ubuntu-desktop>
- <https://help.ubuntu.com/community/Installation/FromUSBStick>


Once ubuntu is installed you may want to run:

    sudo apt-get update
    sudo apt-get upgrade


Nice external references
------------------------

- <https://sites.google.com/site/installationubuntu>




Some __apt__ nice things
========================

To get the version of the application in repositories you can use:

    apt-cache madison APPLICATION



