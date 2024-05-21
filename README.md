# Internalization
Turn any iOS build into InternalUI build
# Guide
1) Download this: https://drive.google.com/file/d/1PbybHVf8Jf8WMQLTxI6D9c-iF5zs-mnW/view?usp=sharing
2) And download InternalPreferences.framework
3) Extract archives
4) Move AppleInternal folder to /
5) Move InternalPreferences.framework to /System/Library/PrivateFrameworks
6) Open /System/Library/CoreServices/SystemVersion.plist
7) Add string with name "ReleaseType"
8) Set string value to "Internal" 
9) Save plist file
10) To make apps open run "sudo chmod -R 777 /AppleInternal
11) On iOS 15+ apps require to resign with ldid
# Done!
Internal package is from build 17A508 (for TouchID iPhones, for X will be uploaded soon, on X you can use old one too)
