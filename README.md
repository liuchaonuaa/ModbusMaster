# ModbusTool
用于调试Modbus通信的工具软件
# 开发进度
* 2020/3/4 建仓，确定应用UI及功能
* 2020/3/5 修改ui,Qlinedit自动调整焦点,限制输入十六进制字符
* 2020/3/10 实现点击按钮发送数据功能,可以选择发送RTU或者ASCII模式,添加CRC校验码
* 2020/3/11 修改点击按钮发送数据功能,可以省略0字符,添加清空按钮用于清空Log信息
* 2020/3/11 添加ASCII模式,可以显示原始的接收数据，微调ui,log显示采用时间标志
* 2020/3/13 对接收帧计算CRC,判断是否接收到一帧完整数据
* 2020/3/15 接收数据帧解析,03H
## ver 1.0
* 2020/3/16  支持常用的通信指令:03H,04H,06H,10H,可以解析响应数据帧.可以填充多条数据帧，可以定时发送多条数据。
支持RTU和ASCII两种模式。支持自动保存控件数据值
## preview
[preview](preview.png)
