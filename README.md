# A9 hdwificam Android


An Android Studio project that uses the [`Node.js on Mobile`]( https://github.com/janeasystems/nodejs-mobile) shared library. In order to run [`A9_PPPP`](https://github.com/datenstau/A9_PPPP) javascript code on the nodejs(node=v12.19.0) environment. 

## How to run
1. download the release APK (for your cam-wifi-prefix (DOGA-/DOGC-)). Or clone this project and build yourself.
 - Download Android ndk=16.1.4479499 (setup in local.properties)
 - Android SDK=semeru-1.8.0_392
 - look at [`README.md from A9_PPP`](https://github.com/datenstau/A9_PPPP/blob/master/readme.md) for info about diffrence in Versions (DOGA/DOGC)
2. this app works in AP mode only.
 - connect to the Wifi(DGOC-/DGOA-)
 - open App and click connect

## Problems/TODO
1. uses old [`Node.js on Mobile`]( https://github.com/janeasystems/nodejs-mobile) sampleproject, which uses very old gradle version (v2.3.3). Because of this adding dependencies is hard.
