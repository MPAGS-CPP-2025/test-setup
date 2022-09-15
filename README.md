# test-setup
Test repo for students to check that their VSCode/Docker setup is working

## How to use
* Open VSCode
* Go to View -> Command Palette
* Start to type in "Remote-Containers: Clone Repository in Container Volume", and select this command as soon as it appears
* Enter the repository name: "MPAGS-CPP-2022/test-setup"
* Select "Create Unique Volume"
* Once the dev container has initialised and you can see the content of the cloned repository in the explorer, open a new terminal by going to Terminal -> New Terminal
* In the terminal issue the command `./runtest`
* You should see the following output:
```
================
git version:
git version 2.30.2
================
g++ version:
g++ (Debian 10.2.1-6) 10.2.1 20210110
Copyright (C) 2020 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

================
CMake version:
cmake version 3.18.4

CMake suite maintained and supported by Kitware (kitware.com/cmake).
================
Doxygen version:
1.9.1
================
```
