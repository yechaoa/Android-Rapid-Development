# Android-Rapid-Development
Android快速开发整理（库、插件、常用网站）
# 一、官方支持库
#### compile 'com.android.support:appcompat-v7:25.3.1'
#### compile 'com.android.support:support-v4:25.3.1'
#### compile 'com.android.support:recyclerview-v7:25.3.1'
#### compile 'com.android.support:support-v13:25.3.1'
#### compile 'com.android.support:design:25.3.1'
#### 目前最新版本26.0.2，需要compileSdkVersion 26
<br>
# 二、第三方库
部分库是jitpack的发布方式，需要在project下的build.gradle中加上（可直接加上，一劳永逸）

```
allprojects {
	repositories {
        maven { url "https://jitpack.io" }
    }
}
```

### 1、Gson
* **compile 'com.google.code.gson:gson:2.8.1'**
* GitHub：https://github.com/google/gson
* 相关文章：[Gson 解析教程](http://blog.csdn.net/axuanqq/article/details/51441590)

### 2、Glide
* **compile 'com.github.bumptech.glide:glide:4.0.0-RC1'**
* **annotationProcessor 'com.github.bumptech.glide:compiler:4.0.0-RC1'**
* GitHub：https://github.com/bumptech/glide
* 相关文章：[Glide、Picasso和Fresco](http://blog.csdn.net/yechaoa/article/details/70948445)
					郭霖的[Android图片加载框架最全解析（一），Glide的基本用法](http://blog.csdn.net/guolin_blog/article/details/53759439)
					[Android图片加载框架最全解析（二），从源码的角度理解Glide的执行流程](http://blog.csdn.net/guolin_blog/article/details/53939176)
					[Android图片加载框架最全解析（三），深入探究Glide的缓存机制](http://blog.csdn.net/guolin_blog/article/details/54895665)
					
### 3、Glide Transformations
* **compile 'jp.wasabeef:glide-transformations:3.0.1'**
* Github：https://github.com/wasabeef/glide-transformations

### 4、Picasso
* **compile 'com.squareup.picasso:picasso:2.5.2'**
* 官网：http://square.github.io/picasso/
* GitHub：https://github.com/square/picasso
* 相关文章：[picasso-强大的Android图片下载缓存库](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2014/0731/1639.html)

### 5、Picasso Transformations
* **compile 'jp.wasabeef:picasso-transformations:2.1.2'**
* Github：https://github.com/wasabeef/picasso-transformations

### 6、Butter Knife
* **compile 'com.jakewharton:butterknife:8.8.1'**
* **annotationProcessor 'com.jakewharton:butterknife-compiler:8.8.1'**
* 官网：[http://jakewharton.github.io/butterknife/](http://jakewharton.github.io/butterknife/)
* GitHub：https://github.com/JakeWharton/butterknife
* 相关文章：[Butter Knife 配置和使用及插件](http://blog.csdn.net/yechaoa/article/details/52963196)

### 7、OkHttp
* **compile 'com.squareup.okhttp3:okhttp:3.9.0'**
* 官网：http://square.github.io/okhttp/
* GitHub：https://github.com/square/okhttp

### 8、okhttp-utils（鸿洋_）
* **compile 'com.zhy:okhttputils:2.6.2'**
* GitHub：https://github.com/hongyangAndroid/okhttputils
* 相关文章：[Android OkHttp完全解析 是时候来了解OkHttp了](http://blog.csdn.net/lmj623565791/article/details/47911083)

### 9、xUtils3
* **compile 'org.xutils:xutils:3.5.0'**
* GitHub：https://github.com/wyouflf/xUtils3

### 10、MVP
* 官方例子Github：https://github.com/googlesamples/android-architecture/tree/todo-mvp/
* 相关文章：[浅谈 MVP in Android（鸿洋_）](http://blog.csdn.net/lmj623565791/article/details/46596109)
                     [MVP快速开发框架](http://www.jianshu.com/p/d98013e0cd03)
		     
### 11、Retrofit
* **compile 'com.squareup.retrofit2:retrofit:2.3.0'**
* 官网：[http://square.github.io/retrofit/](http://square.github.io/retrofit/)
* GitHub：https://github.com/square/retrofit

### 12、RX系列：https://github.com/ReactiveX

### 13、RxJava
* **compile "io.reactivex.rxjava2:rxjava:2.1.3"**
* Github：https://github.com/ReactiveX/RxJava

### 14、RxAndroid
* **compile 'io.reactivex.rxjava2:rxandroid:2.0.1'**
* Github：https://github.com/ReactiveX/RxAndroid

### 15、RxKotlin
* **compile 'io.reactivex:rxkotlin:x.y.z'**
* Github：https://github.com/ReactiveX/RxKotlin
* Kotlin：[Kotlin中文文档](https://github.com/wangjiegulu/kotlin-for-android-developers-zh/blob/master/SUMMARY.md?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)

### 16、RxBinding
Platform bindings:

* compile 'com.jakewharton.rxbinding2:rxbinding:2.0.0'

'support-v4' library bindings:

* compile 'com.jakewharton.rxbinding2:rxbinding-support-v4:2.0.0'

'appcompat-v7' library bindings:

* compile 'com.jakewharton.rxbinding2:rxbinding-appcompat-v7:2.0.0'

'design' library bindings:

* compile 'com.jakewharton.rxbinding2:rxbinding-design:2.0.0'

'recyclerview-v7' library bindings:

* compile 'com.jakewharton.rxbinding2:rxbinding-recyclerview-v7:2.0.0'

'leanback-v17' library bindings:

* compile 'com.jakewharton.rxbinding2:rxbinding-leanback-v17:2.0.0'

* GitHub：https://github.com/JakeWharton/RxBinding

### 17、Dagger 2（Google）
* **compile 'com.google.dagger:dagger:2.x'**
* **annotationProcessor 'com.google.dagger:dagger-compiler:2.x'**
* Github：https://github.com/google/dagger

### 18、EventBus
* **compile 'org.greenrobot:eventbus:3.0.0'**
* Github：https://github.com/greenrobot/EventBus
* 相关文章：[EventBus使用详解(一)——初步使用EventBus](http://blog.csdn.net/harvic880925/article/details/40660137)
					[EventBus使用详解(二)——EventBus使用进阶](http://blog.csdn.net/harvic880925/article/details/40787203)
					
### 19、PermissionsDispatcher（6.0权限）
* **compile 'com.github.hotchemi:permissionsdispatcher:2.2.0'**
* **apt 'com.github.hotchemi:permissionsdispatcher-processor:2.2.0'**
* **classpath 'com.neenbedankt.gradle.plugins:android-apt:1.8'**
* GitHub：https://github.com/hotchemi/PermissionsDispatcher
* 相关文章：[Android6.0运行时权限。](http://blog.csdn.net/yechaoa/article/details/61920584)

### 20、Android Saripaar v2（表单校验）
* **compile 'com.mobsandgeeks:android-saripaar:2.0.3'**
* Github：https://github.com/ragunathjawahar/android-saripaar/
* 相关文章：[Android之表单验证，Validation三方集成。](http://blog.csdn.net/yechaoa/article/details/60875310)

### 21、Android View Animations（各种动画）
* **compile 'com.android.support:support-compat:25.1.1'**
* **compile 'com.daimajia.easing:library:2.0@aar'**
* **compile 'com.daimajia.androidanimations:library:2.2@aar'**
* GitHub：https://github.com/daimajia/AndroidViewAnimations

### 22、BottomBar（底部导航栏）
* **compile 'com.roughike:bottom-bar:2.3.1'**
* GitHub：https://github.com/roughike/BottomBar

### 23、Android PagerSlidingTabStrip（滑动导航栏）
* **compile 'com.astuetz:pagerslidingtabstrip:1.0.1'**
* GitHub：https://github.com/astuetz/PagerSlidingTabStrip

### 24、XRefreshView（支持各种控件刷新）
* **compile 'com.huxq17.xrefreshview:xrefreshview:3.6.9'**
* GitHub：https://github.com/huxq17/XRefreshView
* 相关文章：[打造android万能上拉下拉刷新框架——XRefreshView (一)](http://blog.csdn.net/footballclub/article/details/46422703)
					[打造android万能上拉下拉刷新框架——XRefreshView (二)](http://blog.csdn.net/footballclub/article/details/46678521)
					[打造Android万能上拉下拉刷新框架--XRefreshView（三）](http://blog.csdn.net/footballclub/article/details/46982115)
					
### 25、SuperRecyclerView
* **compile 'com.supercwn.superrecycleview:superlibrary:1.2.5'**
* GitHub：https://github.com/supercwn/SuperRecycleView

### 26、EasyRecyclerView
* **compile 'com.jude:easyrecyclerview:4.4.0'**
* GitHub：https://github.com/Jude95/EasyRecyclerView

### 27、vlayout（RecyclerView的LayoutManager扩展-阿里）
* **compile ('com.alibaba.android:vlayout:1.0.7@aar') {transitive = true}**
* GitHub：https://github.com/alibaba/vlayout

### 28、RichText（富文本解析器）
* **compile 'com.zzhoujay.richtext:richtext:2.5.2'**
* GitHub：https://github.com/zzhoujay/RichText

### 29、AndroidUtilCode（各种util）
* **compile 'com.blankj:utilcode:1.6.4'**
* GitHub：https://github.com/Blankj/AndroidUtilCode

### 30、ViewPagerIndicator
* **compile 'com.shizhefei:ViewPagerIndicator:1.1.5'**
* GitHub：https://github.com/LuckyJayce/ViewPagerIndicator

### 31、EasyIndicator
* **compile 'com.github.LuckSiege:EasyIndicator:v1.1.1'**
* GitHub：https://github.com/LuckSiege/EasyIndicator

### 32、ImagePicker（图片选择器）
* **compile 'com.lzy.widget:imagepicker:0.5.5'**
* GitHub：https://github.com/jeasonlzy/ImagePicker

### 33、PhotoView
* **compile 'com.github.chrisbanes:PhotoView:2.0.0'**
* GitHub：https://github.com/chrisbanes/PhotoView

### 34、Android-SpinKit（Android loading animations）
* **compile 'com.github.ybq:Android-SpinKit:1.0.5'**
* GitHub：https://github.com/ybq/Android-SpinKit
* 官网：http://ybq.github.io/Android-SpinKit/

### 35、Toasty
* **compile 'com.github.GrenderG:Toasty:1.2.5'**
* GitHub：https://github.com/GrenderG/Toasty

### 36、DialogPlus（各种样式的Dialog）
* **compile 'com.orhanobut:dialogplus:1.11@aar'**
* GitHub：https://github.com/orhanobut/dialogplus

# 三、各种好用的插件
#### 安装方法
##### 可能有的插件搜索不到，直接点击Search in repositories
![这里写图片描述](http://img.blog.csdn.net/20170605183814185?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQveWVjaGFvYQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
##### 点击install开始安装，安转成功之后会提示restart重启as，重启就好了。

### 1、GsonFormat
* 快速将json字符串转换成一个Java Bean
* 快捷键Alt+S

### 2、Android ButterKnife Zelezny
* 配合ButterKnife快速生成注解
* 光标放在布局文件ID上（如R.layut.activity_main），Ctrl+Shift+B

### 3、Android Methods Count
* 可查看依赖库中的方法数

### 4、Lifecycle Sorter
* 对Activity或者fragment的生命周期方法进行先后排序
* Ctrl + alt + K

### 5、JsonOnlineViewer
* 直接在as中请求接口，方便调试

### 6、genymotion
* 超快超好用的android模拟器

### 7、LeakCanary
* 检测内存泄露

# 四、各种常用的网站
### 1、Json在线解析
* http://www.sojson.com/

### 2、API文档管理
* https://apiview.com/

### 3、stackoverflow（IT技术问答网站）
* https://stackoverflow.com/

### 4、CSDN全球最大中文IT社区
* http://www.csdn.net/

### 5、ProcessOn免费在线作图，实时协作
* https://www.processon.com/

### 6、阿里巴巴矢量图标库
* http://www.iconfont.cn/

### 7、各种在线文档和工具（开源中国社区）
* http://tool.oschina.net/

### 8、Mob开放平台（天气、短信、分享等）
* http://www.mob.com/

### 9、融云（即时通讯）
* http://www.rongcloud.cn/

### 10、蚂蚁金服开放平台（支付宝）
* https://doc.open.alipay.com/

### 11、腾讯开放平台
* http://wiki.open.qq.com/wiki/首页

### 12、微信开放平台
* https://open.weixin.qq.com/

### 13、w3school（HTML）
* http://www.w3school.com.cn/tags/index.asp

### 14、友盟（推送统计）
* http://www.umeng.com/

### 15、360加固保
* http://jiagu.360.cn/

### GitHub
* https://github.com/

### 简书
* http://www.jianshu.com/

### Android开发技术周报
* http://androidweekly.cn/

<br><br><br>
#### 持续更新。。。
