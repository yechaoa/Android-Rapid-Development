# Android-Rapid-Development
Android快速开发整理（库、插件、常用网站）

> **转载请明显标注出处**

# 一、官方支持库

#### implementation "androidx.core:core-ktx:1.3.2"
#### implementation "androidx.appcompat:appcompat:1.2.0"
#### implementation "com.google.android.material:material:1.2.1"
#### ...

> 建议迁移到androidx

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

<br>

> ## 工具

<br>

### Gson
* **implementation 'com.google.code.gson:gson:2.8.6'**
* GitHub：https://github.com/google/gson
* 相关文章：[Gson 解析教程](http://blog.csdn.net/axuanqq/article/details/51441590)

### Glide
* **implementation 'com.github.bumptech.glide:glide:4.11.0'**
* **annotationProcessor 'com.github.bumptech.glide:compiler:4.11.0'**
* GitHub：https://github.com/bumptech/glide
* 相关文章：[带你全面了解Glide 4的用法](http://blog.csdn.net/yechaoa/article/details/78886125)

### Glide Transformations
* **implementation 'jp.wasabeef:glide-transformations:4.1.0'**
* Github：https://github.com/wasabeef/glide-transformations

### Picasso
* **implementation 'com.squareup.picasso:picasso:2.71828'**
* 官网：http://square.github.io/picasso/
* GitHub：https://github.com/square/picasso
* 相关文章：[picasso-强大的Android图片下载缓存库](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2014/0731/1639.html)

### Picasso Transformations
* **implementation 'jp.wasabeef:picasso-transformations:2.2.1'**
* Github：https://github.com/wasabeef/picasso-transformations

### Butter Knife
* **implementation 'com.jakewharton:butterknife:10.2.0'**
* **annotationProcessor 'com.jakewharton:butterknife-compiler:10.2.0'**
* 官网：[http://jakewharton.github.io/butterknife/](http://jakewharton.github.io/butterknife/)
* GitHub：https://github.com/JakeWharton/butterknife
* 相关文章：[Butter Knife 配置和使用及插件](http://blog.csdn.net/yechaoa/article/details/52963196)

### Dagger 2（Google）
* **implementation 'com.google.dagger:dagger:2.22.1'**
* **annotationProcessor 'com.google.dagger:dagger-compiler:2.22.1'**
* Github：https://github.com/google/dagger

### EventBus
* **implementation 'org.greenrobot:eventbus:3.2.0'**
* Github：https://github.com/greenrobot/EventBus
* 相关文章：[EventBus使用详解(一)——初步使用EventBus](http://blog.csdn.net/harvic880925/article/details/40660137)
					[EventBus使用详解(二)——EventBus使用进阶](http://blog.csdn.net/harvic880925/article/details/40787203)

### greenDAO(数据库)
* **implementation 'org.greenrobot:greendao:3.2.2'**
* Github：https://github.com/greenrobot/greenDAO
* 相关文章：[玩转Android之数据库框架greenDAO3.0使用指南](http://blog.csdn.net/yechaoa/article/details/79363096)

### LitePal(数据库)
* **implementation 'org.litepal.guolindev:core:3.2.2'**
* Github：https://github.com/guolindev/LitePal
			
### PermissionsDispatcher（6.0权限）
* **implementation "com.github.hotchemi:permissionsdispatcher:4.6.0"**
* **annotationProcessor "com.github.hotchemi:permissionsdispatcher-processor:4.6.0"**
* GitHub：https://github.com/hotchemi/PermissionsDispatcher
* 相关文章：[Android6.0运行时权限。](http://blog.csdn.net/yechaoa/article/details/61920584)

### RxPermissions（6.0权限）
* ** implementation 'com.github.tbruyelle:rxpermissions:0.10.2'**
* GitHub：https://github.com/tbruyelle/RxPermissions

### PermissionX（6.0权限）
* ** implementation 'com.permissionx.guolindev:permissionx:1.4.0'**
* GitHub：https://github.com/guolindev/PermissionX

### Android Saripaar v2（表单校验）
* **implementation 'com.mobsandgeeks:android-saripaar:2.0.3'**
* Github：https://github.com/ragunathjawahar/android-saripaar/
* 相关文章：[Android之表单验证，Validation三方集成。](http://blog.csdn.net/yechaoa/article/details/60875310)

### YUtils（Android快速开发工具集合）
* **implementation 'com.github.yechaoa:YUtils:3.1.1'**
* GitHub：https://github.com/yechaoa/YUtils

### AndroidUtilCode（各种util）
* **implementation 'com.blankj:utilcode:1.29.0'**
* GitHub：https://github.com/Blankj/AndroidUtilCode

<br>

> ## 网络

<br>

### OkHttp
* **implementation("com.squareup.okhttp3:okhttp:4.9.0")**
* 官网：http://square.github.io/okhttp/
* GitHub：https://github.com/square/okhttp

### okhttp-utils（鸿洋_）
* **implementation 'com.zhy:okhttputils:2.6.2'**
* GitHub：https://github.com/hongyangAndroid/okhttputils
* 相关文章：[Android OkHttp完全解析 是时候来了解OkHttp了](http://blog.csdn.net/lmj623565791/article/details/47911083)

### OkGo
* **implementation 'com.lzy.net:okgo:3.0.4'**
* GitHub：https://github.com/jeasonlzy/okhttp-OkGo

### xUtils3
* **implementation 'org.xutils:xutils:3.8.3'**
* GitHub：https://github.com/wyouflf/xUtils3

### Retrofit
* **implementation 'com.squareup.retrofit2:retrofit:2.9.0'**
* 官网：[http://square.github.io/retrofit/](http://square.github.io/retrofit/)
* GitHub：https://github.com/square/retrofit

### RX系列：https://github.com/ReactiveX

### RxJava
* **implementation "io.reactivex.rxjava2:rxjava:3.0.7"**
* Github：https://github.com/ReactiveX/RxJava

### RxAndroid
* **implementation 'io.reactivex.rxjava2:rxandroid:2.1.1'**
* Github：https://github.com/ReactiveX/RxAndroid

### RxKotlin
* **implementation 'io.reactivex:rxkotlin:2.4.0'**
* Github：https://github.com/ReactiveX/RxKotlin
* Kotlin：[Kotlin中文文档](https://github.com/wangjiegulu/kotlin-for-android-developers-zh/blob/master/SUMMARY.md?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)

<br>

> ## UI

<br>

### MaterialEditText
* **implementation 'com.rengwuxian.materialedittext:library:2.1.4'**
* GitHub：https://github.com/rengwuxian/MaterialEditText

### Android View Animations（各种动画）
* **implementation 'com.android.support:support-compat:25.1.1'**
* **implementation 'com.daimajia.easing:library:2.0@aar'**
* **implementation 'com.daimajia.androidanimations:library:2.2@aar'**
* GitHub：https://github.com/daimajia/AndroidViewAnimations

### hellocharts-android（图表）
* **implementation 'com.github.lecho:hellocharts-android:v1.5.8'**
* GitHub：https://github.com/lecho/hellocharts-android

### BottomBar（底部导航栏）
* **implementation 'com.roughike:bottom-bar:2.3.1'**
* GitHub：https://github.com/roughike/BottomBar

### BottomNavigationViewEx
* **implementation 'com.github.ittianyu:BottomNavigationViewEx:1.2.4''**
* GitHub：https://github.com/ittianyu/BottomNavigationViewEx

### Banner（图片轮播控件）
* **implementation 'com.youth.banner:banner:1.4.10'**
* GitHub：https://github.com/youth5201314/banner

### Dachshund-Tab-Layout
* **implementation 'com.github.Andy671:Dachshund-Tab-Layout:v0.3.3'**
* GitHub：https://github.com/Andy671/Dachshund-Tab-Layout

### Android PagerSlidingTabStrip（滑动导航栏）
* **implementation 'com.astuetz:pagerslidingtabstrip:1.0.1'**
* GitHub：https://github.com/astuetz/PagerSlidingTabStrip

### EasyRecyclerView
* **implementation 'com.jude:easyrecyclerview:4.4.2'**
* GitHub：https://github.com/Jude95/EasyRecyclerView

### BaseRecyclerViewAdapterHelper
* **implementation 'com.github.CymChad:BaseRecyclerViewAdapterHelper:3.0.4'**
* GitHub：https://github.com/CymChad/BaseRecyclerViewAdapterHelper

### vlayout（RecyclerView的LayoutManager扩展-阿里）
* **implementation ('com.alibaba.android:vlayout:1.2.8@aar') {transitive = true}**
* GitHub：https://github.com/alibaba/vlayout

### RichText（富文本解析器）
* **implementation 'com.zzhoujay.richtext:richtext:3.0.8'**
* GitHub：https://github.com/zzhoujay/RichText

### ViewPagerIndicator
* **implementation 'com.shizhefei:ViewPagerIndicator:1.1.9'**
* GitHub：https://github.com/LuckyJayce/ViewPagerIndicator

### EasyIndicator
* **implementation 'com.github.LuckSiege:EasyIndicator:v1.1.3'**
* GitHub：https://github.com/LuckSiege/EasyIndicator

### ImagePicker（图片选择器，okgo作者）
* **implementation 'com.lzy.widget:imagepicker:0.6.1'**
* GitHub：https://github.com/jeasonlzy/ImagePicker

### PictureSelector
* **implementation 'com.github.LuckSiege.PictureSelector:picture_library:v2.3.9'**
* GitHub：https://github.com/LuckSiege/PictureSelector

### Matisse（知乎）
* **implementation 'com.zhihu.android:matisse:0.5.3-beta3'**
* GitHub：https://github.com/zhihu/Matisse

### PhotoView
* **implementation 'com.github.chrisbanes:PhotoView:2.3.0'**
* GitHub：https://github.com/chrisbanes/PhotoView

### Android-SpinKit（Android loading animations）
* **implementation 'com.github.ybq:Android-SpinKit:1.4.0'**
* GitHub：https://github.com/ybq/Android-SpinKit
* 官网：http://ybq.github.io/Android-SpinKit/

### Toasty
* **implementation 'com.github.GrenderG:Toasty:1.4.2'**
* GitHub：https://github.com/GrenderG/Toasty

### DialogPlus（各种样式的Dialog）
* **implementation 'com.orhanobut:dialogplus:1.11@aar'**
* GitHub：https://github.com/orhanobut/dialogplus

### MaterialDateTimePicker
* **implementation 'com.wdullaer:materialdatetimepicker:4.2.3'**
* GitHub：https://github.com/wdullaer/MaterialDateTimePicker

### FloatingActionButton
* **implementation 'com.github.clans:fab:1.6.4'**
* GitHub：https://github.com/Clans/FloatingActionButton

### CityPicker
* **implementation 'liji.library.dev:citypickerview:5.1.0'**
* GitHub：https://github.com/crazyandcoder/citypicker

### VerticalTabLayout
* **implementation 'q.rorbin:VerticalTabLayout:1.2.5'**
* GitHub：https://github.com/qstumn/VerticalTabLayout

### SmartRefreshLayout(下拉刷新框架)
* **implementation 'com.scwang.smartrefresh:SmartRefreshLayout:1.1.0-alpha-21'**
* GitHub：https://github.com/scwang90/SmartRefreshLayout

### AgentWeb(WebView框架)
* **api 'com.just.agentweb:agentweb:4.1.2'**
* GitHub：https://github.com/Justson/AgentWeb

### FragmentRigger(Fragment管理框架)
* **接入引导：https://github.com/JingYeoh/FragmentRigger/wiki/%E9%A6%96%E9%A1%B5**
* GitHub：https://github.com/JingYeoh/FragmentRigger

### GSYVideoPlayer(视频播放器)
* **implementation 'com.shuyu:GSYVideoPlayer:7.1.6'**
* GitHub：https://github.com/CarGuo/GSYVideoPlayer

### SwipeBackLayout(滑动返回)
* **implementation 'me.imid.swipebacklayout.lib:library:1.1.0'**
* GitHub：https://github.com/ikew0ng/SwipeBackLayout

### BGASwipeBackLayout-Android
* **implementation 'cn.bingoogolapple:bga-swipebacklayout:latestVersion@aar'**
* GitHub：https://github.com/bingoogolapple/BGASwipeBackLayout-Android

### recyclerview-animators(recyclerview动画)
* **implementation 'jp.wasabeef:recyclerview-animators:3.0.0'**
* GitHub：https://github.com/wasabeef/recyclerview-animators

### XPopup(各种弹窗)
* **implementation 'com.lxj:xpopup:2.1.4'**
* GitHub：https://github.com/li-xiaojun/XPopup

### FlowLayout(流式布局)
* **implementation 'com.hyman:flowlayout-lib:1.1.2'**
* GitHub：https://github.com/hongyangAndroid/FlowLayout

### Switcher(切换按钮)
* **implementation 'com.bitvale:switcher:1.1.0'**
* GitHub：https://github.com/bitvale/Switcher

### EasyFloat(悬浮窗框架)
* **implementation 'com.github.princekin-f:EasyFloat:1.3.4'**
* GitHub：https://github.com/princekin-f/EasyFloat

### GuideView(新手引导库)
* **implementation 'com.binioter:guideview:1.0.0'**
* GitHub：https://github.com/binIoter/GuideView

### StatusBarUtil(状态栏工具类)
* **implementation 'com.jaeger.statusbarutil:library:1.5.1'**
* GitHub：https://github.com/laobie/StatusBarUtil

### ImmersionBar(状态栏工具类)
* **implementation 'com.gyf.immersionbar:immersionbar:3.0.0'**
* GitHub：https://github.com/gyf-dev/ImmersionBar


# 三、各种好用的插件


#### 安装方法

##### 可能有的插件搜索不到，直接点击Search in repositories
![这里写图片描述](http://img.blog.csdn.net/20170605183814185?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQveWVjaGFvYQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
##### 点击install开始安装，安转成功之后会提示restart重启as，重启就好了。

### GsonFormat
* 快速将json字符串转换成一个Java Bean
* 快捷键Alt+S

### Android ButterKnife Zelezny
* 配合ButterKnife快速生成注解
* 光标放在布局文件ID上（如R.layut.activity_main），Ctrl+Shift+B

### Android Methods Count
* 可查看依赖库中的方法数

### Lifecycle Sorter
* 对Activity或者fragment的生命周期方法进行先后排序
* Ctrl + alt + K

### JsonOnlineViewer
* 直接在as中请求接口，方便调试

### genymotion
* 超快超好用的android模拟器

### LeakCanary
* 检测内存泄露
* github：https://github.com/square/leakcanary

### Dart
* Dart开发插件

### Flutter
* Flutter开发插件

### Json To Kotlin Class
* json转kotlin bean对象

### Android Drawable Preview
* 可对drawable及mipmap下的资源文件预览


# 四、各种常用的网站


### AndroidDevTools（各种android相关工具下载）
* http://www.androiddevtools.cn/index.html

### 在线文档-JDK
* http://tool.oschina.net/apidocs/apidoc?api=jdk_7u4

### 在线文档-Android
* https://developer.android.google.cn/develop/index.html

### 在线文档-Kotlin
* https://github.com/wangjiegulu/kotlin-for-android-developers-zh/blob/master/SUMMARY.md

### 在线文档-Glide
* https://muyangmin.github.io/glide-docs-cn/

### 在线文档-Flutter
* https://flutterchina.club/widgets-intro/

### Material Design（参考文档）
* https://materialdoc.cn/components/autocomplete/

### GitHub
* https://github.com/

### Font Awesome Icons
* http://fontawesome.io/icons/

### Json在线解析
* http://www.sojson.com/

### API文档管理
* https://apiview.com/

### stackoverflow（IT技术问答网站）
* https://stackoverflow.com/

### CSDN全球最大中文IT社区
* http://www.csdn.net/

### 简书
* http://www.jianshu.com/

### 玩安卓
* https://www.wanandroid.com/

### HenCoder
* https://hencoder.com/

### Android开发技术周报
* http://androidweekly.cn/

### ProcessOn免费在线作图，实时协作
* https://www.processon.com/

### 阿里巴巴矢量图标库
* http://www.iconfont.cn/

### 各种在线文档和工具（开源中国社区）
* http://tool.oschina.net/

### Mob开放平台（天气、短信、分享等）
* http://www.mob.com/

### 聚合数据（各种开放API）
* https://www.juhe.cn/

### 融云（即时通讯）
* http://www.rongcloud.cn/

### 网易云信（即时通讯）
* https://netease.im/

### 蚂蚁金服开放平台（支付宝）
* https://doc.open.alipay.com/

### 阿里移动热修复
* https://help.aliyun.com/product/51340.html

### 阿里移动推送
* https://www.aliyun.com/product/cps

### 腾讯开放平台
* http://wiki.open.qq.com/wiki/首页

### 微信开放平台
* https://open.weixin.qq.com/

### 腾讯信鸽推送
* https://xg.qq.com/docs/android_access/jcenter.html

### 腾讯Bugly
* https://bugly.qq.com/v2/

### 腾讯地图
* https://lbs.qq.com/

### 百度地图
* http://lbsyun.baidu.com/

### w3school（HTML）
* http://www.w3school.com.cn/tags/index.asp

### Bootstrap*组件
* http://v3.bootcss.com/components/

### 友盟（推送统计）
* http://www.umeng.com/

### 360加固保
* http://jiagu.360.cn/

### 乐固
* http://legu.qcloud.com/

<br>

#### CSDN：https://blog.csdn.net/yechaoa/article/details/72870470


<br><br>
#### 持续更新。。。

<br><br>
```
   License

   Copyright 2017 yechaoa

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
