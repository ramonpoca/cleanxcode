# WARNING: This script IS SEVERELY OUTDATED. Please do not use. Archiving for reference only.

# cleanxcode
A simple interactive terminal script to clean up Xcode DerivedData, stale simulators, etc

Requires [HomeBrew](http://brew.sh) and  [ThoughtBot's Pick](https://github.com/thoughtbot/pick) tool.

# WARNING: This script deletes data. Use at your own risk!

Don't come to me crying if it deleted something you didn't expect

# Usage

    chmod +x cleanxcode
    ./cleanxcode
 
This will:
    
1. Clean Docset disk images  (.dmg) from `$HOME/Library/Caches/com.apple.dt.Xcode/Downloads/`.
2. Interactively pick and remove plugged device symbols from `$HOME/Library/Developer/Xcode/iOS DeviceSupport`.
3. Interactively pick and remove build artifacts from `$HOME/Library/Developer/Xcode/DerivedData`.
4. Interactively pick and remove build artifacts from `$HOME/Library/Caches/AppCode*/DerivedData`.
5. Clean stale CoreSimulator devices.

# LICENSE

Licensed under GPLv3. See the LICENSE file.
