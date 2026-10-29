# 滕鑫胜 · vega-thrive

嵌入式软件 / 机器人控制。做四轮麦克纳姆轮搬运机器人的整机固件：硬实时控制、三环 PID、比赛路线状态机、视觉伺服对准。

🏆 **2026 中国机器人大赛暨 RoboCup 中国赛 · 车型智能搬运** —— 国赛三等奖 · 专项赛三等奖

---

### 在做的事

- 🤖 **车型智能搬运机器人** —— 2026 中国机器人大赛 · 工程竞技类
  两辆车的软件：一辆**从零实现**（53 状态路线机 / 1.2 万行业务代码），另一辆在队伍交接中断后**一周内接手调通**（国赛三等奖）
- 👁 **嵌入式视觉** —— MaixCAM / MaixPy：霍夫圆对准、HSV 形状判别、低算力平台上的多角度字符识别
- 🧠 **模型自训练** —— 手机实拍采集 + 人工标注（6 类 / 1 394 实例）+ YOLO11n 训练 + INT8 量化部署

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

### 精选项目

| # | 项目 | 定位 | 关键内容 |
| --- | --- | --- | --- |
| 1 | [**robocup-smart-carry-firmware**](https://github.com/vega-thrive/robocup-smart-carry-firmware) | 一周接手 · 国赛三等奖 | 24 状态路线机、200 Hz 三环 PID、视觉伺服对准、8 路舵机时序 |
| 2 | [**robocup-smart-carry-firmware-team2**](https://github.com/vega-thrive/robocup-smart-carry-firmware-team2) | 从零实现 · 专项赛三等奖 | 53 状态路线机、转盘库存管理、VOFA 在线调参、五周开发时间线 |
| 3 | [**robocup-smart-carry-vision**](https://github.com/vega-thrive/robocup-smart-carry-vision) | MaixCAM 视觉端 | 七任务分发、霍夫圆对准、低算力下的任意角度字符识别 |

### 联系

📮 [3458575934@qq.com](mailto:3458575934@qq.com)

<sub>欢迎交流嵌入式控制与机器人比赛相关的问题。</sub>
