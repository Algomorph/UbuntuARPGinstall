# UbuntuARPGinstall
A really long bash script for installing (and upgrading) ARPG packages on Ubuntu.
This script installs *most* third-party dependencies. Protobuf is left out, because it seems to have conflict with existing protobuf packages on Ubuntu, removal of which breaks other things. Hence Ubuntu 15.10 vivid is recommended, since it has the required protobuf 2.6. Trusty will not work, as it only provides 2.5 officially.

The script is likely to break as the ARPG packages and third-party requirements change, as well as with different conditions in different environments. If some part of the script fails on your machine, submit an issue or suggest a fix.

Currently, Kangaroo and D-MoCap seem to be broken for different reasons. I can integrate the fix for Kangaroo into the script later. D-MoCap will probably have to wait until ARPG update it to work with the new HAL.

