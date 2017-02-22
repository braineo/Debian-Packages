1. Clone the git repo
```shell
    git clone https://github.com/chenxiaolong/Debian-Packages.git
    cd Debian-Packages/
```

2. Install the build dependencies.

Run the following command and install the packages it lists using apt-get/synaptic/etc.
```shell
    cd freetype-infinality/
    dpkg-checkbuilddeps
    cd ../fontconfig-infinality/
    dpkg-checkbuilddeps
```
3. Build the packages:
```shell
    cd ../freetype-infinality/
    ./build.sh
    cd ../fontconfig-infinality/
    ./build.sh
```

4. Install the deb files:
```shell
    cd ..
    sudo dpkg -i freetype-infinality/*.deb fontconfig-infinality/*.deb
```

You'll need to reboot after installing the deb files. Enjoy the better
looking fonts!
