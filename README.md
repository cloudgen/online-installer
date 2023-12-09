# online-installer

This is a demonstration of how python script can be used as an online-installer.

## Requirements
 1. Online system inspections.
 2. Download file automatically.
 3. Install automatically (globally if current user is root, otherwise install locally)
 4. Can be uninstalled
 5. Allow online update check.
 6. Support all Ubuntu, Debian, CentOS, MacOS, Alpine Linux and most of the linux distro.
 7. Support the following shell: ash, bash, cmd, dash, fish shell, git bash, zsh.

## Run this online installer.

First, you should install curl and any python (python2, python3, pypy or pypy3).  Then type the following commands:

For python3 installed:
~~~
curl -fsSL https://dl.leolio.page/online-installer | python3
~~~

For python2 installed:
~~~
curl -fsSL https://dl.leolio.page/online-installer | python2
~~~

For pypy installed:
~~~
curl -fsSL https://dl.leolio.page/online-installer | pypy
~~~

For pypy3 installed:
~~~
curl -fsSL https://dl.leolio.page/online-installer | pypy3
~~~

## Functions
To show the information (in Windows environment, please use 'online-installer.bat' instead of 'online-installer'):
~~~
online-installer
~~~

To check if update is available:
~~~
online-installer check-update
~~~

To uninstall:
~~~
online-installer uninstall
~~~

To installed from git source code:
~~~
./online-installer install
~~~


