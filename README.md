# vdieocapture-read
- 为了获取视频，应该创建一个VideoCapture对象。其参数可以是设备的索引号，或者是一个视频文件。
- 设备索引号就是在指定要使用的摄像头。参数通常设置0.你也可以通过设置成1或其他的来
- 选择别的摄像头。之后，你就可以一帧一帧的捕获视频。但是最后，别忘了停止捕获视频。
-  cap.read（）返回一个布尔值（True/False).
