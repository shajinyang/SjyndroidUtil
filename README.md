![](sjylogo.png)
# 安卓开发工具类库（该类库还在升级完善中）
该库封装了常用的android开发常用工具，设备信息，app信息，日期处理，时间处理，正则，图片处理，屏幕，网络，文字，网页等等。具体看源码。
就不一一写了（有空再写）





### 如何使用

#### Android Studio
    第一步：
      在项目的gradle里配置
      allprojects {
        repositories {
            ...
            maven { url 'https://jitpack.io' }
        }
      }

      第二步：
      在module的gradle里配置
      dependencies {
         ...
      	 compile 'com.github.shajinyang:SjyndroidUtil:1.0.7'
      }



















