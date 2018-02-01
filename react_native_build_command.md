- Test release build
    - ``` react-native run-android --variant=release ```


- Build release
    - ``` cd android && ./gradlew assembleRelease ```


- Install apk 
    - ``` adb install ./app/build/outputs/apk/app-release.apk ```


- debug apk install 
    - ``` adb install ./app/build/outputs/apk/app-release.apk ```


- Menu popup 
    - ``` adb shell input keyevent 82 ```


