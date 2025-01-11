项目目标：AI对话玩偶（智能桌宠）&激光雕刻台

1.AI对话玩偶
基于ESP32和ASRpro的智能对话玩偶：
此项目主要使用ESP32-S3实现一个AI语音聊天助手，可以通过该项目熟悉ESP32-S3 arduino的开发，百度语音识别，语音合成API调用，百度文心一言大模型API的调用方法，音频的录制及播放，SD卡的读写，Wifi的配置（smartconfig方式）等基本开发方法。本项目的所有软硬件工程开源，并配备了详细的教程文档，和对应的视频教程，对零基础的同学非常适用，希望能够帮助到大家。
具备的功能+ 支持小程序实现Wifi配网 + 语音唤醒词唤醒ESP32-S3 + 自定义唤醒词模型训练 + 百度语音识别语音合成api访问 + 百度文心一言大模型api访问
TTS | 一文总览语音合成系列基础知识资料来源https://blog.csdn.net/weixin_44649780/article/details/130889141?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522fe4f49d5651cf302df9860099f7774e0%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=fe4f49d5651cf302df9860099f7774e0&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-1-130889141-null-null.142
接入大模型教程
https://developer.volcengine.com/articles/7394071664679944202

2.激光雕刻台
主控板为uno r3驱动为A4988的二维雕刻台，通过两个丝杆配合电机控制激光头进行雕刻，烧录控制代码，接入微雕管家软件，通过软件控制X轴y轴运动
参考教学
https://www.bilibili.com/video/BV1dP411c7yV?vd_source=1091cce76fbb8f01ecd3f1fa1823c492
