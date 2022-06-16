

# webSpeech 说明

# 语音播报
采用SpeechSynthesisUtterance来实现，支持离线语音播报；

# 语音识别

采用webkitSpeechRecognition来实现，支持重连，原理很简单，在结束时（onend）一直打开（start)即可;

# 注意
    1、需要在谷歌浏览器中访问127.0.0.1ip或者localhost；
    2、当前客户端需要能够访问谷歌浏览器（也就是打开vpn），不然会一直抛出错误"network"(网络)"问题；

# 启动

```
live-server
# or
http-server
```
