# Android-
Android启动页黑屏及最优解决方案
参考 
https://blog.csdn.net/myfmyfmyfmyf/article/details/84965814
https://juejin.im/post/58ad90518ac2472a2ad9b684

android/app/src/main/res/values/strings.xml 添加样式

    <style name="APPTheme" parent="@android:style/Theme.Holo.NoActionBar">
        <item name="android:windowDisablePreview">true</item>
    </style>
    
android/app/src/main/AndroidManifest.xml  
添加样式主题，在 android:name="MainActivity"后
android:theme="@style/APPTheme"
