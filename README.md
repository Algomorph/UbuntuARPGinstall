# UbuntuARPGinstall
A really long bash script for installing (and upgrading) ARPG packages on Ubuntu.
This script builds and installs *most* third-party dependencies. Custom-built protobuf is left out, because it seems to have conflict with existing protobuf packages on Ubuntu, removal of which breaks other things. Hence Ubuntu 15.10 vivid is recommended, since it provides the required protobuf 2.6. Trusty or Utopic will not work, as they only officially provide 2.5.

The script is likely to break as the ARPG packages and third-party requirements change, as well as with different conditions in different environments. If some part of the script fails on your machine, submit an issue or suggest a fix.

Kangaroo's routines seem to have problems during runtime. D-MoCap's future is currently uncertain. I have a compilable fork which might be (might have been?) merged into the ARPG mainstream.

