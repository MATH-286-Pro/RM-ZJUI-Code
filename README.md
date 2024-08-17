# 文档说明

该文档用于 开发板C STMF407IGH6 芯片的开发  

可以切换为 DAP-Link, J_Link, ST-Link 调试  

工具链配置：arm-none-eabi-gcc + mingw64 + openocd

## 开启外设
- GPIO 10 蓝色LED (也可以使用TIM5 CH通道控制)
- GPIO 11 绿色LED (也可以使用TIM5 CH通道控制)
- GPIO 12 红色LED (也可以使用TIM5 CH通道控制)

## FreeRTOS 任务表