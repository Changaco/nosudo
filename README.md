nosudo is a very simple bash script that fakes sudo using su. It is licensed under GPLv3.

## Changelog

* 0.3 : nosudo should now supports aliases that are in the .bashrc of the user who executes the command
* 0.2.3 : fixed the su arguments
* 0.2.2 : fixed bug with spaces in pwd
* 0.2.1 : show an error message when no valid command is found
* 0.2 :
  * support for the sudo `-l` option
  * handling of sudo options, actually we skip everything that isn't either `-l` or a program
* 0.1 : Initial release
