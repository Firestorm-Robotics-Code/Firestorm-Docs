# Documentation and code examples for the linux terminal, to consult when necessary.
## This is intended for the programmers on Firestorm Robotics, but anyone can view it (probably - I'm not sure how it works)

### Installing things from the linux terminal (ubuntu/debian)
* `sudo apt install package_name`: `sudo` elevates the command to root, `apt` is the package manager for Ubuntu/Debian, and `install` tells apt to install `package_name`
* `sudo snap install package_name`: Same as above, just snap this time. Snap packages are bulkier and closed-source, but thats about the only difference. Note: Arduino can be installed via apt, snap, or website. The website version isn't as good as the snap, and the apt one is pain. So install using snap.  
You can also install Slack Desktop and Atom via snap, both of which are very good packages.
### Filesystem stuff using the linux terminal (universal)
* `ls`: This is one of the simplest commands. It prints out all the files and directories in the current directory.
* `cd`: Another simple one. Takes a single (space-separated) argument, the directory to "Change Directory" into. You can also use `../` to move up a directory, and you can chain directories. `cd` without arguments moves to the home directory for the current user.
* `mv`: Move any number of source files or directories (first arguments) into a directory (last argument). Also can change the name of a single file or directory.
* `mkdir`: Create any number of directories, name specified in the arguments.
* `touch`: Create a file, works the same as above.
### Good software to install (and how) (ubuntu/debian)
* Slack desktop: `sudo snap install slack`
* Arduino IDE: `sudo snap install arduino`
* Atom (code editor): `sudo snap install atom`
* GCC (compilers - desktop c++ included, use the g++ command after installing): `sudo apt install build-essential`
* Wine (run EXE's on linux): `sudo apt install wine-stable`
* Pip3 (python package manager): `sudo apt install python3-pip`
* Chromium (open-source Google Chrome): `sudo apt install chromium-browser`
* Android Studio (not going to work on *somebodies* dinky little chromebook): `sudo snap install android-studio`
