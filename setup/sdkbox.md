#SDKBOX

## README
information files inside .sdkbox_package.json
setting $PATH : 
```ruby
#Add environment variable COCOS_CONSOLE_ROOT for cocos2d-x
export COCOS_CONSOLE_ROOT=/Users/$user/lib/cocos2d-x-3.8.1/tools/cocos2d-console/bin
export PATH=$COCOS_CONSOLE_ROOT:$PATH

# Add environment variable COCOS_TEMPLATES_ROOT for cocos2d-x
export COCOS_TEMPLATES_ROOT=/Users/$user/lib/cocos2d-x-3.8.1/templates
export PATH=$COCOS_TEMPLATES_ROOT:$PATH

export ANT_ROOT=/Users/$user/lib/apache-ant-1.9.6/bin
export PATH=$ANT_ROOT:$PATH

export ANDROID_SDK_ROOT=/Users/$user/Library/Android/sdk
export PATH=$ANDROID_SDK_ROOT:$PATH

export NDK_ROOT=/Users/$user/lib/android-ndk-r10e
#export NDK_ROOT=/Users/$uesr/lib/android-ndk-r9d
export PATH=$NDK_ROOT:$PATH

export ANDROID_HOME=/Users/$user/Library/Android/sdk
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.7.0_79.jdk/Contents/Home

# code for Visual Studio Code
code () { VSCODE_CWD="$PWD" open -n -b "com.microsoft.VSCode" --args $* ;}

export PATH=~/Library/Android/sdk/platform-tools:$PATH
```
## Update
`sdkbox update` current version 1.0.0.7
`sdkbox-google` 2.1.1.2
`iap` 2.1.1.2

## Adcolony
`sdkbox import adcolony` version 2.1.1.2

## IAP
`sdkbox import iap` version 2.1.1.2

## ChartBoost
`sdkbox import chartboost` version v2.1.1.2

안드로이드에서는

`<uses-permission android:name="android.permission.ACCESS_WIFI_STATE" />

이게 자동으로 추가 안돼서 따로 추가해야된다.

reference : http://docs.sdkbox.com/en/plugins/chartboost/v3-cpp/
