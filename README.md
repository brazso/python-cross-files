Python cross files (necessary ones to make win32 target from linux)

See [this small tutorial](https://stackoverflow.com/a/70474888) for more info.

Here is an example how to create a new package for Python 3.10.2:

After installed Python 3.10.2 Windows 64bit (python-3.10.2-amd64.exe) all files were removed except
+ include/
+ python310.dll
Then the following folder was removed
- include/internal/  
