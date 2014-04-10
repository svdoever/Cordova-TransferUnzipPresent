For a hybrid project I have a very simple requirement: 

- download zip file,
- unzip it, 
- serve content on a page from artifacts (html text, images).

This example uses plain Cordova 3.4+, with the command-line commands.

1. cordova create Cordova-TransferUnzipPresent com.svdoever.tranferunzippresent TransferUnzipPresent
2. cd Cordova-TransferUnzipPresent
3. cordova platform add android
4. cordova plugin add org.apache.cordova.file
5. cordova plugin add org.apache.cordova.file-transfer
6. cordova plugin add org.chromium.zip
7. Replace code in www\index.html with the code below
8. cordova emulate android

Works with iOS platform as well. The zip plugin does not work on wp8 (yet).