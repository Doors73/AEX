
AospExtended Nougat
===========
AospExtended is just an extension to AOSP, through which we 
are trying to provide a stock AOSP experience along with some important 
customization features. We have cherry-picked the features from many 
other projects and hence we are very thankful to them.



##How to Build?

To initialize your local repository using the AospExtended trees, use a 
command like this:
````bash
repo init -u git://github.com/Doors73/AEX.git -b 7.1.1
```
Then to sync up:
````bash
repo sync -c -jx --force-sync
```
Finally to build:
````bash
. build/envsetup.sh
lunch
1. enter
mka bacon
```
