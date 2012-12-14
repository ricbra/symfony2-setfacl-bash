symfony2-setfacl-bash
=====================

Simple bash script for setting up permissions correctly for your Symfony2 project using setfacl

Installation
------------
The installation is as easy as:

    curl -s https://raw.github.com/ricbra/symfony2-setfacl-bash/master/setup_permissions >> ~/bin/sf2_setfacl && chmod 0755 ~/bin/sf2_setfacl

Usage
-----
Navigate to your Symfony2 project root, e.g.:

    cd /var/www/my-superb-project

Just call the script and it will set your permission according to the input you gave:

    sf2_setfacl


