# iOS/macOS/watchOS APP ICONS Generator

### Description
ios-icon-generator is a shell script which aim to generate iOS/macOS/watchOS APP icons easier and simply.
![image](https://github.com/anessence/ios-icon-generator/blob/master/ios-icon-generator.gif)
<pre>
VERSION: 2.0.0
USAGE:
    ./ios-icon-generator.sh srcfile dstpath

DESCRIPTION:
    This script aim to generate iOS/macOS/watchOS APP icons easier and simply.

    srcfile - The source png image. Preferably above 1024x1024
    dstpath - The destination path where the icons generate to.

AUTHOR:
    smallmuou<smallmuou@163.com>

EXAMPLE:
    ./ios-icon-generator.sh 1024.png ~/123

</pre>

### Usage

1. Clone
```bash
git clone https://github.com/anessence/ios-icon-generator
cd ios-icon-generator
chmod 777 ios-icon-generator.sh
```

2. Run
	
```bash
➜  ios-icon-generator git:(master) ✗ ./ios-icon-generator.sh 1024.png ./output
[INFO] Generate Icon-20.png ...
[INFO] Generate Icon-29.png ...
[INFO] Generate Icon-40.png ...
[INFO] Generate Icon-48.png ...
[INFO] Generate Icon-55.png ...
[INFO] Generate Icon-58.png ...
[INFO] Generate Icon-60.png ...
[INFO] Generate Icon-76.png ...
[INFO] Generate Icon-80.png ...
[INFO] Generate Icon-87.png ...
[INFO] Generate Icon-88.png ...
[INFO] Generate Icon-100.png ...
[INFO] Generate Icon-120.png ...
[INFO] Generate Icon-152.png ...
[INFO] Generate Icon-167.png ...
[INFO] Generate Icon-172.png ...
[INFO] Generate Icon-180.png ...
[INFO] Generate Icon-196.png ...
[INFO] Generate Icon-102.png ...
[INFO] Generate Icon-216.png ...
[INFO] Generate Icon-1024.png ...
[INFO] Congratulations! All icons for iOS/macOS/watchOS APP are generated to the directory: ./output.
```
PS: You can find out the icons in ./output directory.

### Refer
* [iOS Icons Size](https://developer.apple.com/design/human-interface-guidelines/ios/icons-and-images/app-icon/)
* [macOS Icons Size](https://developer.apple.com/design/human-interface-guidelines/macos/icons-and-images/app-icon/)	
* [watchOS Icons Size](https://developer.apple.com/design/human-interface-guidelines/watchos/icons-and-images/home-screen-icons/)

### History
* 2.0.0
    * Update iOS icons size
    * Support macOS icons size
    * Support watchOS icons size
    * Remove ImageMagick Dependency
    * Update code structure for add size more easy.

* 1.0.0
	* Generate all size icons for iPhone and iPad.

### License
This script follow MIT license.
