# [STM8L](https://github.com/sochub/STM8L) 

[![sites](SoC/SoC.png)](http://www.qitas.cn) 

#### 厂商：[ST](https://github.com/sochub/ST) 

#### 架构：[STM8](https://github.com/sochub/STM8)

## [描述](https://github.com/sochub/STM8L/wiki) 

STM8L低功耗低成本单片机，拥有全面的产品线和各种规格

* Lowest power mode: 0.35 µA
* Dynamic run mode: 180 µA/MHz

[![sites](SoC/STM8L.png)](https://www.st.com/en/microcontrollers-microprocessors/stm8l-series.html) 


### [资源收录](https://github.com/sochub/STM8L)

* [文档](docs/)
* [资源](src/)
* [工程](project/)
* [STM8资源](https://github.com/sochub/STM8) 

### [收录产品型号](https://github.com/sochub/STM8L)

* [STM8L0x](https://github.com/sochub/STM8L0) 
* [STM8L10x](https://github.com/sochub/STM8L10) 
* [STM8L15x](https://github.com/sochub/STM8L15) 

### [选型建议](https://github.com/sochub/STM8L)

使用STM8L进行相关设计，一般都在考虑量产的cost down阶段，产品的性能需求和资源需求不算强烈，往往只考虑使用成本和开发效率，或则相关历史资源继承。

STM8单片机应用范围接近传统的8051，开发方式接近STM32，往往不带有RTOS采用裸驱，低功耗设计模式趋近周期唤醒然后采集数据后传输，然后设置并休眠。

低成本低性能设计方案[STM8L0x](https://github.com/sochub/STM8L0) 和 [STM8L10x](https://github.com/sochub/STM8L10) 

较高性能和资源全面方案[STM32L0](https://github.com/sochub/STM32L0) 和 [STM8L15x](https://github.com/sochub/STM8L15) 

其他厂商低功耗方案替换 [MSP430](https://github.com/sochub/MSP430) 和 [MSP432](https://github.com/sochub/MSP432) 

需要注意点是，低功耗处理器只有在长时间的休眠过程中才能体现出低功耗的特点，如果是应用在持续工作的场景，可以考虑使用[STM8S](https://github.com/sochub/STM8S) 或 [N76E003](https://github.com/sochub/N76E003) ,同理，如果已经设计了硬件休眠定时唤醒，也大可不必局限于低功耗的MCU。

##  [SoC资源平台](http://www.qitas.cn)  

