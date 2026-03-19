# 🐱Cute-Table-Pet
一只可爱的四足机器人，桌宠机器人，或者叫他闪电猫机器人。使用FreeRTOS作为底层架构，能够实现番茄钟功能、表情显示功能和作出不同的动作招手磕头、行走和转向等。代码简单结构清晰，使用一颗18650电池进行供电，为了缩小体积充分利用空间，设计了一块stm32最小系统板和底板拓展板以及简易的外壳。Flash Cat is a compact, FreeRTOS-driven STM32 quadruped robot that merges productivity tools with interactive motion and expressions, optimized for space-efficient 18650-powered hardware.
使用的单片机是自制的stm32f103c8t6最小系统，这样可以实现把18650电池塞在单片机和底板的中间。
以前做的一个项目，做工比较随意，没有做好滤波和反接，使用的时候需注意。
【重】：底板拓展版的降压模块在即接st-link又接电池会有滋滋电流声（短时间内不会坏），单电池供电的时候是可以正常使用的，建议先烧完程序再焊上这块芯片实现电池给整车供电。也可以自己在LDO加一个二极管防止电流倒灌。
