# 康维嘉 · vega-thrive

嵌入式软件 / 机器人控制。做四轮麦克纳姆轮搬运机器人的整机固件：硬实时控制、三环 PID、比赛路线状态机、视觉伺服对准。

---

### 在做的事

- 🤖 **车型智能搬运机器人** —— 2026 中国机器人大赛暨 RoboCup 中国赛
  整车固件（STM32F407 @168 MHz），200 Hz 硬实时底盘控制 + 24 状态比赛路线机
- 👁 **视觉伺服** —— MaixCAM / MaixPy，YOLO 目标检测、椭圆拟合、10 字节串口帧协议
- 🐍 **Python 工程化小工具** —— 文件整理 / 查重 / 实验数据作图

### 技术栈

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![STM32](https://img.shields.io/badge/STM32F407-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Keil](https://img.shields.io/badge/Keil%20MDK-394049?style=flat-square&logoColor=white)
![CubeMX](https://img.shields.io/badge/CubeMX-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

![PID](https://img.shields.io/badge/PID%20Control-3%20Loops-blueviolet?style=flat-square)
![Peripherals](https://img.shields.io/badge/UART%20%7C%20PWM%20%7C%20Encoder-Drivers-informational?style=flat-square)
![LTspice](https://img.shields.io/badge/LTspice-Circuit%20Sim-orange?style=flat-square)
![SolidWorks](https://img.shields.io/badge/SolidWorks-3D%20Modeling-red?style=flat-square)

### 项目

| 项目 | 说明 | 技术 |
| --- | --- | --- |
| [**robocup-smart-carry-firmware**](https://github.com/vega-thrive/robocup-smart-carry-firmware) | 车型智能搬运机器人整车固件：200 Hz 三环 PID 底盘、24 状态比赛路线机、视觉伺服对准、8 路舵机机构时序 | C · STM32F407 · Keil |
| [**robocup-smart-carry-vision**](https://github.com/vega-thrive/robocup-smart-carry-vision) | MaixCAM 视觉端：七任务模式分发、霍夫圆对准、PP-OCR 冠亚季任意角度识别、10 字节串口帧协议 | Python · MaixPy · OpenCV |

### 联系

📮 [3458575934@qq.com](mailto:3458575934@qq.com)

<sub>欢迎交流嵌入式控制与机器人比赛相关的问题。</sub>
