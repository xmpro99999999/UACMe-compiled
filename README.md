# UACMe-compiled
UACMe v3.6.5 compiled in Visual Studio 2022

# What is UACMe
* Defeating Windows User Account Control by abusing built-in Windows AutoElevate backdoor.

# System Requirements

* x86-32/x64 Windows 7/8/8.1/10/11 (client, some methods however works on server version too).
* Admin account with UAC set on default settings required.

# Usage

Run executable from command line: akagi32 [Key] [Param] or akagi64 [Key] [Param].

- First parameter is number of method to use, second is optional command (executable file name including full path) to run. 
- Second parameter can be empty - in this case program will execute elevated cmd.exe from system32 folder.
