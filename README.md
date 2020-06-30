# ffmpeg2webrtc

基于ffmpeg实现的H264数据转webrtc播放的服务
支持http、hls、rtmp、rtsp、rtp等协议H264数据转换
无需重新编码可将h264数据基于webrc发送给浏览器进行解码播放

运行方式：
执行ffmpeg2webrtc.exe
程序是用msys2 64位编译若压缩包中还缺其他依赖库，请在msys2 64位环境运行
在浏览器中输入http://172.168.10.180:8300 即可
livevideo选项主要针对直播流和点播流，开启后后台无脑转发，否则按实际帧率速度转发

转发hls和rtsp 建议开启livevideo选项

代码目前未做整理有需要的朋友留言吧，我抽空整理后开放出来

