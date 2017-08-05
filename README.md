# android studio上插件的安装
Settings → Plugins → Browse repositories，搜索插件名然后安装。
 
安装分为在线安装和本地安装，为了避免出现兼容性问题，推荐在线安装。

# 插件推荐

所有插件均来自：[Android Studio Plugins](http://plugins.jetbrains.com/category/?androidstudio&category_id=all)

### GsonFormat
### GsonFormat是一个快速格式化json数据并可以自动生成实体类的插件，非常实用
插件下载地址：https://plugins.jetbrains.com/plugin/7654-gsonformat

插件源码地址：https://github.com/zzz40500/GsonFormat

![](images/gsonformat.png)
*****

### Markdown
### Markdown是一种可以使用普通文本编辑器编写的标记语言，通过类似HTML的标记语法，它可以使普通文本内容具有一定的格式
插件文档地址：https://github.com/nicoulaj/idea-markdown


*****

### Android Postfix completion
### 可根据后缀快速完成代码
插件下载地址：https://plugins.jetbrains.com/plugin/7775-android-postfix-completion

插件教程地址：http://blog.jetbrains.com/idea/2014/03/postfix-completion/

![](images/AndroidPostfixCompletion.png)
*****

### ADB WIFI
### 无需root就能wifi调试
插件下载地址：https://plugins.jetbrains.com/plugin/7856-adb-wifi

插件源码地址：https://github.com/layerlre/ADBWIFI

![](images/ADBWIFI.png)
*****

### Lifecycle Sorter
### 可以根据Activity或者fragment的生命周期对其生命周期方法位置进行先后排序
插件下载地址：https://plugins.jetbrains.com/plugin/7742-lifecycle-sorter

插件源码地址：https://github.com/armandAkop/Lifecycle-Sorter

![](images/lifecycle-sorter.png)
*****

### FindBugs-IDEA
### 通过FindBugs帮你找到隐藏的bug及不好的做法
插件下载地址：https://plugins.jetbrains.com/plugin/3847-findbugs-idea

插件源码地址：https://github.com/andrepdo/findbugs-idea/tree/master

![](images/FindBugs.png)
*****

### JavaDoc
### 添加注释，可自定义模板
插件下载地址：https://plugins.jetbrains.com/plugin/7157-javadoc

插件源码地址：https://github.com/setial/intellij-javadocs

*****


*****

### Freeline Plugin
### 阿里出品秒级编译工具
插件下载地址：https://plugins.jetbrains.com/plugin/8615-freeline-plugin

![](http://qiniu.apkfuns.com/54F6776E-B1A4-4693-8858-53E030DD9312.png)

*****

### pomodoro-tm
### 番茄工作法的 Android Studio / IDEA 插件
插件下载地址：https://plugins.jetbrains.com/plugin/4954-pomodoro-tm

插件源码地址：https://github.com/dkandalov/pomodoro-tm

![](https://raw.githubusercontent.com/dkandalov/pomodoro-tm/master/widget.png)

*****


### Material Theme UI
### MD 风格主题
插件下载地址：https://plugins.jetbrains.com/plugin/8006-material-theme-ui

插件源码地址：https://github.com/ChrisRM/material-theme-jetbrains

![](https://plugins.jetbrains.com/files/8006/screenshot_17032.png)

*****


### Android DPI Calculator
### DPI快速计算工具
插件下载地址：https://plugins.jetbrains.com/plugin/7832-android-dpi-calculator

插件源码地址：https://github.com/JerzyPuchalski/Android-DPI-Calculator

![](https://plugins.jetbrains.com/files/7832/screenshot_15115.png)

*****


### intellij-translation
### 一款将英文翻译为中文的插件
插件下载地址：https://plugins.jetbrains.com/plugin/8445-intellij-translation

插件源码地址：https://github.com/zyuyou/intellij-translation

![](https://plugins.jetbrains.com/files/8445/screenshot_15973.png)

*****


### Android Methods Count
### 展示安卓依赖库里方法数
插件下载地址：https://plugins.jetbrains.com/plugin/8076-android-methods-count

![](https://plugins.jetbrains.com/files/8076/screenshot_15509.png)

*****


### Genymotion
### 可能是目前位置速度最快，运行最流畅的安卓模拟器
插件下载地址：https://www.genymotion.com/#!/download

![](https://www.genymotion.com/wp-content/uploads/2016/09/screenshot_gmdesktop.jpg)

*****


### Android Drawable Importer
### 最常用的功能就是生成不同尺寸的图标
插件下载地址：https://plugins.jetbrains.com/plugin/7658-android-drawable-importer

插件源码地址：https://github.com/winterDroid/android-drawable-importer-intellij-plugin

![](https://plugins.jetbrains.com/files/7658/screenshot_15533.png)

*****


### lint-cleaner-plugin
### 清除项目中的无用资源

源码地址：https://github.com/marcoRS/lint-cleaner-plugin


Apply the plugin in your `build.gradle`:

```groovy
buildscript {
  repositories {
    mavenCentral()
  }
  dependencies {
    classpath 'com.android.tools.build:gradle:0.12.+'
    classpath 'com.droidtitan:lint-cleaner-plugin:0.3.0'
  }
}

apply plugin: 'android'
apply plugin: 'com.droidtitan.lintcleaner'
```


Finally, to remove unused resources use: 
     
    gradle lintClean

## Optional Configuration using DSL

```groovy
lintCleaner {
    // Exclude specific files
    exclude = ['com_crashlytics_export_strings.xml','config.xml']

    // Ability to ignore all resource files. False by default. 
    ignoreResFiles = true
    
    // Default path is build/outputs/lint-results.xml
    lintXmlFilePath = 'path/to/lint-results.xml'
}
```

*****
