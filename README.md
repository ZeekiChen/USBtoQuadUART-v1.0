# USBtoQuadUART-v1.0<br>
一个基于沁恒微电子CH9344的USB转4串口模块，有助于减少多串口应用场景下电脑USB的占用<br>
本模块主要围绕沁恒微电子的CH9344芯片进行设计，实现USB转4组全双工的异步串口，支持115200bps以及最高达12Mbps 的通讯波特率。<br>
USB端使用Type-C接口，输入数据线带有ESD保护芯片，USB输入电源带500mA自恢复保险丝。<br>
4组串口均支持硬件流控，带有收发指示灯。所有引脚带有TVS二极管保护，串有限流电阻。<br>
本模块为纯硬件模块，PCB焊接完成即可使用，无需烧录任何固件，PC端需要安装相应的驱动程序。<br>
