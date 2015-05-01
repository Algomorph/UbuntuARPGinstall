# UbuntuARPGinstall
A really long bash script for installing (and upgrading) ARPG packages on Ubuntu.
This script builds and installs *most* third-party dependencies. Custom-built protobuf is left out, because it seems to have conflict with existing protobuf packages on Ubuntu, removal of which breaks other things. Hence Ubuntu 15.10 vivid is recommended, since it provides the required protobuf 2.6. Trusty or Utopic will not work, as they only officially provide 2.5.

The script is likely to break as the ARPG packages and third-party requirements change, as well as with different conditions in different environments. If some part of the script fails on your machine, submit an issue or suggest a fix.

Currently, Kangaroo and D-MoCap seem to be broken for different reasons. I can integrate the fix for Kangaroo into the script later. D-MoCap will probably have to wait until ARPG update it to work with the new HAL.

