# RTMPCHybirdEngine-Android
基于RTMP和RTC混合引擎的在线视频连麦互动直播


Android 直播（网络自适应码率RTMP publisher）、点播播放器（播放器经过专业优化，可实现秒开RTMP Player）、基于RTMP和RTC混合引擎的视频连麦互动（最多支持4人同时互动）


##简介
RTMPCHybirdEngine是为移动端应用量身打造的基于RTMP和RTC混合引擎的连麦互动流媒体直播系统。通过集成本SDK，只需几个简单API调用，便可实现一套完整的连线麦互动直播流媒体应用。包含了流媒体应用中：『采集->编码->传输->解码->播放->连麦视频互动』的所有步骤。</br>

#优势</br>
**超低延时**</br>
**超低内存**</br>
**无缝连接（原有方案不变的情况，直接嵌入SDK）**</br>
**文字互动、弹幕消息**</br>
**人员上下线**</br>
**多达4人同时在线连麦视频互动**</br>

#SDK包含
RTC 连麦互动</br>
RTMP 推流器</br>
RTMP 播放器</br>

##编译环境
**Android Studio**
**替换RTMPUrlHelper.java文件中的RTMP_PUSH_URL和RTMP_PULL_URL**

##支持的系统平台
**Android** 4.0及以上

##支持的CPU架构
**Android** armv7 arm64  

# 项目特点
**1，商业级开源代码，高效稳定**</br>
**2，超小内存占有率，移动直播针对性极致优化，代码冗余率极低**</br>
**3，iOS全平台适配，硬件编解码可保证99%的可用性**</br>
**4，接口极简，推流：2个   拉流：2个**</br>
**5，底层库C++核心库代码风格采用：Google code style**</br>
**6，极简内核，无需再去深扒复杂的FFMpeg代码**</br>
**7，实用主义，那些什么坑什么优化等概念请搜索相关文章**</br>
**8，OpenH264软件编码，FFMpeg软件解码，FAAC/FAAD软件编解码，适配不同系统的硬件编解码统统包含**</br>
**9，支持SRS、Nginx-RTMP等标准RTMP服务；同时支持各大CDN厂商的接入**</br>

##IOS版连麦互动Demo
[RTMPCHybirdEngine-IOS](https://github.com/AnyRTC/RTMPCHybirdEngine-IOS)

##商用授权
程序发布需商用授权，业务咨询请联系
QQ:809564859 </br>
QQ交流群:580477436</br>
联系电话:021-65650071</br>
Email:niuming@dync.cc</br>
##关于直播
本公司有一整套直播解决方案，特别针对移动端。本公司开发者平台[www.anyrtc.io](http://www.anyrtc.io)。除了基于RTMP协议的直播系统外，我公司还有基于WebRTC的时时交互直播系统、P2P呼叫系统、会议系统等。快捷集成SDK，便可让你的应用拥有时时通话功能。欢迎您的来电~
## License

RTMPCHybirdEngine is available under the MIT license. See the LICENSE file for more info.
