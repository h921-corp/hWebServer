# hWebServer
A USBWebserver alternative with a CLI instead of a GUI (because im lazy). All binaries (PHP, phpMyAdmin, Apache & MySQL) can be drop in replaced.<br>
The reason I made this is because i like using USBWebServer, but the outdated binaries were slightly annoying, due to missing functions.<br>

All config files can be found in the "conf" directory. There is no use in changing the configs inside the folders of the binaries themselves, since they will just be overwritten on restart.

# Install
Just extract the zip file to "C:\hWebServer", and run the hWebserver.bat file
The default login for phpMyAdmin and MySQL is the following:<br>
username: "root"<br>
password: "husb"

# Custom setup
If you wish to setup your own hWebServer, there are a few steps.
1. Make sure all folders are titled correctly.<br>
   The Apache folder should be called "Apache24".<br>
   The PHP folder should be called "php".<br>
   The MySQL folder should be called "mysql".<br>

2. Make sure to have a "bin" folder, where you have batch files for all binaries.<br>
   The structure of the batch file should be as follows:<br>
     @echo off<br>
     start "EXECUTABLE NAME"<br>
   Where you replace "EXECUTABLE NAME" with the EXE. (example: php.exe)

