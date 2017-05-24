# UmengShareFullLib
友盟分享SDK -只包含分享到微信(包括支付)

原SDK版本:Android 社会化组件SDK v6.4.4（2017-5-12)

原SDK下载地址:http://dev.umeng.com/social/android/sdk-download

原文档:http://dev.umeng.com/social/android/quick-integration

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file Add it in your root build.gradle at the end of repositories:

    allprojects {
      repositories {
        ...
        maven { url 'https://jitpack.io' }
      }
    }

Step 2. Add the dependency

    dependencies {
        compile 'com.github.iyishengyuan:UmengShareFullLib:1.0.2'
    }
