 

https://github.com/TeamAmaze/AmazeFileManager/releases/tag/v3.6.7

https://github.com/provencher/MixedRealityToolkit-Unity
https://github.com/provencher/MRTK-Online
https://github.com/provencher/MRTK-Quest
https://github.com/jorgejgnz/HandTrackingPack-HapticFeedback/releases/tag/1.3


adb shell am broadcast -a com.oculus.vrpowermanager.prox_close
adb shell am broadcast -a com.oculus.vrpowermanager.automation_disable

# third-party app store :
- APKPure
- Aptoide


https://www.apkmirror.com/wp-content/uploads/2022/03/29/62212f3d44201/com.android.chrome_99.0.4844.58-484405820_minAPI24(armeabi-v7a)(nodpi)_apkmirror.com.apk?verify=1647055858-CzCG7ri3_67y6GWYGjwq9ZOwQRNvW3iD3GdWpT-jMg0


https://developer.android.com/studio/command-line/adb

C:\Program Files\Unity\Hub\Editor\2020.3.30f1\Editor\Data\PlaybackEngines\AndroidPlayer\SDK\platform-tools
$ ./adb devices          # list connected devices (-l for long output)
$ ./adb shell ip route   # check device IP address
$ ./adb tcpip 5555       # restart adb server listening on TCP on PORT
$ ./adb connect x.x.x.x:5555
$ ./adb disconnect


查詢APP，不指定App名稱，會列出全部，如下：
adb shell pm list packages

安裝App：
adb install c:\test\Test_App03.apk

查詢指定的APP
adb shell pm list packages test_app03
adb shell pm list packages -3 MRTK    # find 3rd-party app with keywork MRTK

移除/刪除App：
adb shell pm uninstall -k com.example.test_app03
adb shell pm uninstall --user 0 com.prvncher.MRTKQuest

```
  pm uninstall [-k] [--user USER_ID] [--versionCode VERSION_CODE] PACKAGE [SPLIT]
    Remove the given package name from the system.  May remove an entire app
    if no SPLIT name is specified, otherwise will remove only the split of the
    given app.  Options are:
      -k: keep the data and cache directories around after package removal.
      --user: remove the app from the given user.
      --versionCode: only uninstall if the app has the given version code.
```

package:com.android.chrome      # 搜尋&下載apk (也可用 Oculus Store 裡的 Firefox browser)
package:com.amaze.filemanager   # 瀏覽&管理apk
package:com.prvncher.MRTKQuest  # 目標 apk






https://ithelp.ithome.com.tw/articles/10241811


Normcore


WebVR
https://moonrider.xyz/
https://www.phoria.com.au/projects/paralympics-xr
https://plockle.com/play



https://xrshowcase.xyz/
https://xrsites.com/
https://constructarcade.com/


https://github.com/Rufus31415/Simple-WebXR-Unity
https://github.com/dilmerv/OculusQuestHandTrackingPhysicsURP


