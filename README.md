# olympe_npnt

The link to download and build is here - https://developer.parrot.com/docs/olympe/installation.html

Steps to build Olympe Initially Locally, Run the following - 

1) cd $HOME
2) mkdir -p code/parrot-groundsdk
3) cd code/parrot-groundsdk
4) repo init -u https://github.com/Parrot-Developers/groundsdk-manifest.git
5) repo sync
6) ./products/olympe/linux/env/postinst
7) ./build.sh -p olympe-linux -A all final -j
8) To start the virtual enviroment - source ./products/olympe/linux/env/shell


Steps to sync the project for future updates.

1) repo sync
2) ./products/olympe/linux/env/postinst
3) ./build.sh -p olympe-linux -A all final -j