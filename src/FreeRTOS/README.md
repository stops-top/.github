# [FreeRTOS](https://github.com/OS-Q/RTQ)

FreeRTOS操作系统是完全免费的操作系统，具有源码公开、可移植、可裁减、调度策略灵活的特点，可以方便地移植到各种单片机上运行。

FreeRTOS 在OS-Q中用于L2-L3级别的处理器进行任务调度

## FreeRTOS系统开发优势

* 高适用性和低成本
    * RTOS（FreeRTOS）适用的硬件平台广泛，覆盖高性能的CPU和低端的MCU
    * FreeRTOS为开源系统无相关的版权问题费用，相关的资料丰富，应用广泛
    * FreeRTOS作为RTOS入门学习系统，基于C语言编程，开发人群庞大，软件开发及维护成本低
    * FreeRTOS对系统资源的占用非常小，相同硬件资源下响应更快，或者选用更低成本的处理器可以到达相同的目的
    * FreeRTOS源码可移植可裁减，任务调度策略及问题应对策略灵活，定位问题简单，维护成本较低
* 高可靠性和安全性
    * FreeRTOS是mini实时操作系统内核，系统的代码规模相对linux非常小，系统的运行逻辑清晰简单，潜在风险低
    * FreeRTOS安全性和可靠性经过时间检验，SafeRTOS便是基于FreeRTOS而来，前者是经过安全认证的付费版RTOS（类比redhat和centos），FreeRTOS系统足够成熟稳定

### [FreeRTOS API调用例程](https://github.com/OS-Q/FreeRTOS)