This is a modified version of Apple's CoreMediaIO v1.2 sample code from https://developer.apple.com/library/archive/samplecode/CoreMediaIO/Introduction/Intro.html.

The first commit is the sample code unzipped.

The second commit is some additional Apple sample code, portions of CoreAudio sample code from https://developer.apple.com/library/ios/samplecode/CoreAudioUtilityClasses/Introduction/Intro.html

The third commit are modifications I made to the sample code to get everything building and linking again. I claim no ownership over them and provide no guarantees that they actually work as expected; if you want to use them, have fun.

The fourth commit is this readme.

Note: There were some procedural changes to get everything safely pushed to GitHub; a couple files have been zipped up to stay under GitHub's file size limit. Be sure to:

```sh
unzip \
-x 'Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/Sample/KernelExtension/*.zip' \
-d 'Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/Sample/KernelExtension/'
```

after cloning the repo to ensure all resources are available.