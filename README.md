# HuaweiAntiUpdate
通过ADB禁用华为/荣耀手机自动更新功能

禁用自动更新:
```
adb shell pm disable-user com.huawei.android.hwouc
```
启用自动更新:
```
adb shell pm enable com.huawei.android.hwouc
```
