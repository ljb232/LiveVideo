# LiveVideo
引用来疯开源库，仅供个人学习。谢谢！

1. 权限

在使用前需要添加相应的权限:
<code><uses-permission android:name="android.permission.CAMERA" />
<uses-permission android:name="android.permission.FLASHLIGHT" />
<uses-permission android:name="android.permission.CAMERA" />

<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
<uses-permission android:name="android.permission.RECORD_AUDIO"/>
<uses-permission android:name="android.permission.MODIFY_AUDIO_SETTINGS" />

<uses-permission android:name="android.permission.WAKE_LOCK" />
<uses-permission android:name="android.permission.INTERNET" />

<uses-feature android:name="android.hardware.camera" />
<uses-feature android:name="android.hardware.autofocus" /><code>
注意： 在Android 6.0以后很多权限需要动态申请. 如果你想快速使用，可以将项目的targetSdkVersion设置在23一下。
