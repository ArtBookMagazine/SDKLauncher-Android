_Note:  Please don't use the zip download feature on this repo as this repo uses submodules and this is not supported at present by github and will result in an incomplete copy of the repo._


Launcher-Android
---------------------
A small Android application to serve as a launcher/testbed for the Readium SDK. 

Jenkins build status
----------------------
master [![Build Status](http://jenkinsmaster.datalogics-cloud.com:8080/buildStatus/icon?job=Readium-SDK-Launcher-Android-master)](http://jenkinsmaster.datalogics-cloud.com:8080/view/Readium-Launcher/job/Readium-SDK-Launcher-Android-master/)

develop [![Build Status](http://jenkinsmaster.datalogics-cloud.com:8080/buildStatus/icon?job=Readium-SDK-Launcher-Android-develop)](http://jenkinsmaster.datalogics-cloud.com:8080/view/Readium-Launcher/job/Readium-SDK-Launcher-Android-develop/)

How to get source from github
-------------------------------
 git clone --recursive https://github.com/readium/Launcher-Android.git

How to build Readium SDK
-------------------------------
````
cd readium-sdk/Platform/Androidmantano-test-lcp.epub
./ndk-compile.sh build your-ndk-path
````
How to open eclipse project
----------------------
Use File->Import... menu, don't use File->New menu 

Test LCP
--------

We provide in this repository an LCP encrypted epub : epub-samples/mantano-test-lcp.epub
You can push this book in /sdcard/epubtest directory on your device

To decrypt this epub, you will be required to enter the following passphrase: White whales are huge!
If you do not you will be unable to open this epub

Licensing info
----------------
Licensing information can be found in the file license.txt in the root of the repo, as well as in the source code itself.
