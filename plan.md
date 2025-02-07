# 计划

## 已完成

- 画布(AVCanavs)
  - 移动、旋转、翻转、等比缩放、变形
  - 媒体来源：摄像头、麦克风、分享屏幕
  - 资源类型：视频、音频、图片、文字
- 音视频剪辑 (AVCliper)
  - mp4、mp3、图片、文字 按时间线合成 
  - 视频消音、音频混流、音量控制、音频循环、音频重采样
  - 动画：x, y, w, h, opacity, angle
- [AVRecorder](packages/av-recorder/README.md)
  - 从 MediaStream、AVCanvas 中录制视频

## 开发中
- 文档、示例
- 内存优化，避免大文件导致内存溢出
- 单测
- 编解码等任务转移到 worker 中

### 基础能力 
- 素材拖动的磁吸效果  
  - 水平、垂直中线、四周边界
  - 素材对齐
  - 鼠标移动速度检测
  - 旋转角度 pi/4, pi/2, pi...
- 音视频SDK
  - 视频裁剪、合成、截帧
  - 消音、重配音
  - 调整分辨率、播放速度、压缩
- 操作菜单

### 应用场景
- 直播
  - 素材管理
  - 推流到服务器  
  - 背景替换
  - 面部特效：贴纸、眼镜等等
  - 美颜
- 视频教程制作
  - 导出：MP4、GIF
- 视频制作
  - Timeline
  - 滤镜
  - 动画：转场、元素动效

