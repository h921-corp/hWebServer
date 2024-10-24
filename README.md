# hWebServer
A USBWebserver alternative with a CLI instead of a GUI (because im lazy). All binaries (PHP, Apache & MySQL) can be drop in replaced.
The reason I made this is because i like using UsbWebserver, but the outdated binaries were slightly annoying, due to missing functions.

Unlike USBWebServer, all configs are NOT in one directory. The configs for each binary are in their respective folders. (example: Apache config = .\Apache24\conf\httpd.conf)

# Custom setup
If you wish to setup your own hWebServer, there are a few steps.
1. Make sure all folders are titled correctly.
   The Apache folder should be called "Apache24".
   The PHP folder should be called "php".
   The MySQL folder should be called "mysql".

2. Make sure to have a "bin" folder, where you have batch files for all binaries.
   The structure of the batch file should be as follows:
     @echo off
     start "EXECUTABLE NAME"
   Where you replace "EXECUTABLE NAME" with the EXE. (example: php.exe)

