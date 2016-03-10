# Emotiv Epoch EEG Data Logger - Windows

## Installation

1. Install Python 2.7
2. Go in to windows poweshell and run:
`[Environment]::SetEnvironmentVariable("Path", "$env:Path;C:\Python27\;C:\Python27\Scripts\", "User")`
3. Quit powershell with `exit` and re open the terminal window
4. Download this repo:
https://github.com/openyou/emokit
5. Download and install the Microsoft Visual C++ 9.0 Library from http://aka.ms/vcpython27
6. Install the following python dependencies with easy_install:

* `easy_install pywinusb`
* `easy_install pycrypto`
* `easy_install gevent`
