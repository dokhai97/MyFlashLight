* minSdkVersion 23 (android 6.0)

```
My_Flashlight
├── app
│   ├── build.gradle
│   ├── libs
│   ├── proguard-rules.pro
│   └── src
│       ├── androidTest
│       │   └── java
│       │       └── android
│       │           └── okok
│       │               └── my_flashlight
│       │                   └── ExampleInstrumentedTest.java
│       ├── main
│       │   ├── AndroidManifest.xml
│       │   ├── java
│       │   │   └── android
│       │   │       └── okok
│       │   │           └── my_flashlight
│       │   │               └── MainActivity.java
│       │   └── res
│       │       ├── drawable
│       │       │   └── ic_launcher_background.xml
│       │       ├── drawable-v24
│       │       │   └── ic_launcher_foreground.xml
│       │       ├── layout
│       │       │   └── activity_main.xml
│       │       ├── mipmap-anydpi-v26
│       │       │   ├── ic_launcher_round.xml
│       │       │   └── ic_launcher.xml
│       │       ├── mipmap-hdpi
│       │       │   ├── ic_launcher.png
│       │       │   └── ic_launcher_round.png
│       │       ├── mipmap-mdpi
│       │       │   ├── ic_launcher.png
│       │       │   └── ic_launcher_round.png
│       │       ├── mipmap-xhdpi
│       │       │   ├── ic_launcher.png
│       │       │   └── ic_launcher_round.png
│       │       ├── mipmap-xxhdpi
│       │       │   ├── ic_launcher.png
│       │       │   └── ic_launcher_round.png
│       │       ├── mipmap-xxxhdpi
│       │       │   ├── ic_launcher.png
│       │       │   └── ic_launcher_round.png
│       │       └── values
│       │           ├── colors.xml
│       │           ├── strings.xml
│       │           └── styles.xml
│       └── test
│           └── java
│               └── android
│                   └── okok
│                       └── my_flashlight
│                           └── ExampleUnitTest.java
├── build.gradle
├── gradle
│   └── wrapper
│       ├── gradle-wrapper.jar
│       └── gradle-wrapper.properties
├── gradle.properties
├── gradlew
├── gradlew.bat
├── local.properties
├── My_FLashlight.iml
├── README.md
└── settings.gradle

31 directories, 34 files
```

## activity_main.xml



```
2020-04-29 00:22:39.986 23269-23269/? I/ok.myflashligh: Late-enabling -Xcheck:jni
2020-04-29 00:22:40.020 23269-23269/? E/ok.myflashligh: Unknown bits set in runtime_flags: 0x8000
2020-04-29 00:22:40.114 23269-23269/android.okok.myflashlight I/Perf: Connecting to perf service.
2020-04-29 00:22:40.124 23269-23269/android.okok.myflashlight I/FeatureParser: can't find pyxis.xml in assets/device_features/,it may be in /system/etc/device_features
2020-04-29 00:22:40.136 23269-23269/android.okok.myflashlight E/libc: Access denied finding property "ro.vendor.df.effect.conflict"
2020-04-29 00:22:40.121 23269-23269/android.okok.myflashlight W/ok.myflashlight: type=1400 audit(0.0:8058): avc: denied { read } for name="u:object_r:vendor_displayfeature_prop:s0" dev="tmpfs" ino=21767 scontext=u:r:untrusted_app:s0:c245,c256,c512,c768 tcontext=u:object_r:vendor_displayfeature_prop:s0 tclass=file permissive=0
2020-04-29 00:22:40.146 23269-23298/android.okok.myflashlight E/Perf: Fail to get file list android.okok.myflashlight
2020-04-29 00:22:40.147 23269-23298/android.okok.myflashlight E/Perf: getFolderSize() : Exception_1 = java.lang.NullPointerException: Attempt to get length of null array
2020-04-29 00:22:40.148 23269-23298/android.okok.myflashlight E/Perf: Fail to get file list android.okok.myflashlight
2020-04-29 00:22:40.148 23269-23298/android.okok.myflashlight E/Perf: getFolderSize() : Exception_1 = java.lang.NullPointerException: Attempt to get length of null array
2020-04-29 00:22:40.149 23269-23298/android.okok.myflashlight E/Perf: Fail to get file list oat
2020-04-29 00:22:40.149 23269-23298/android.okok.myflashlight E/Perf: getFolderSize() : Exception_1 = java.lang.NullPointerException: Attempt to get length of null array
2020-04-29 00:22:40.285 23269-23299/android.okok.myflashlight I/AdrenoGLES: QUALCOMM build                   : 3f24407, I72742cdabd
    Build Date                       : 11/10/19
    OpenGL ES Shader Compiler Version: EV031.27.05.01
    Local Branch                     : 
    Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.UM.8.8.R1.10.00.00.545.051
    Remote Branch                    : NONE
    Reconstruct Branch               : NOTHING
2020-04-29 00:22:40.285 23269-23299/android.okok.myflashlight I/AdrenoGLES: Build Config                     : S P 8.0.11 AArch64
2020-04-29 00:22:40.288 23269-23299/android.okok.myflashlight I/AdrenoGLES: PFP: 0x016ee187, ME: 0x00000000
2020-04-29 00:22:40.289 23269-23299/android.okok.myflashlight W/AdrenoUtils: <ReadGpuID_from_sysfs:198>: Failed to open /sys/class/kgsl/kgsl-3d0/gpu_model
2020-04-29 00:22:40.289 23269-23299/android.okok.myflashlight W/AdrenoUtils: <ReadGpuID:222>: Failed to read chip ID from gpu_model. Fallback to use the GSL path
2020-04-29 00:22:40.281 23269-23269/android.okok.myflashlight W/RenderThread: type=1400 audit(0.0:8059): avc: denied { search } for name="kgsl-3d0" dev="sysfs" ino=44948 scontext=u:r:untrusted_app:s0:c245,c256,c512,c768 tcontext=u:object_r:sysfs_kgsl:s0 tclass=dir permissive=0
2020-04-29 00:22:40.304 23269-23299/android.okok.myflashlight W/Gralloc3: mapper 3.x is not supported


2020-04-29 00:23:08.124 23269-23287/android.okok.myflashlight W/CameraManagerGlobal: ignore the torch status update of camera: 63
2020-04-29 00:23:08.124 23269-23287/android.okok.myflashlight E/libc: Access denied finding property "camera.aux.packagelist"
2020-04-29 00:23:08.124 23269-23287/android.okok.myflashlight W/CameraManagerGlobal: ignore the torch status update of camera: 90
2020-04-29 00:23:08.125 23269-23287/android.okok.myflashlight E/libc: Access denied finding property "camera.aux.packagelist"
2020-04-29 00:23:08.125 23269-23287/android.okok.myflashlight W/CameraManagerGlobal: ignore the torch status update of camera: 91
2020-04-29 00:23:08.125 23269-23287/android.okok.myflashlight E/libc: Access denied finding property "camera.aux.packagelist"
2020-04-29 00:23:08.489 23269-23269/android.okok.myflashlight E/libc: Access denied finding property "camera.aux.packagelist"
2020-04-29 00:23:08.489 23269-23269/android.okok.myflashlight E/libc: Access denied finding property "camera.aux.packagelist"
2020-04-29 00:23:08.499 23269-23287/android.okok.myflashlight E/libc: Access denied finding property "camera.aux.packagelist

```
