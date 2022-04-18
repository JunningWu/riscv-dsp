============
Migration-manual
============

Haawking HX2000 系列芯片基于开放指令集架构 RISC-V 开发，支持 RV32IMC 标准指令 集+DSP 自定义指令集，在程序开发的时候，高级语言开发的程序代码由编译器负责生成可 执行文件，汇编语言开发的代码，则需要手动根据 RISC-V 指令集进行修改。该模块比友商增加了 CLKDIV 寄存器，因为我们的主频是友商的 2 倍，所以如果客户需 要，需要先分频一次；详细信息请参阅我们用户手册。


Features
============

下载文档 ：`Haawking_DSC28027&034 数字信号控制_器迁移指南_V1.4`__

.. __: https://github.com/JunningWu/riscv-dsp/blob/master/docs/Migration-manual/Haawking_DSC28027%26034%20%E6%95%B0%E5%AD%97%E4%BF%A1%E5%8F%B7%E6%8E%A7%E5%88%B6_%E5%99%A8%E8%BF%81%E7%A7%BB%E6%8C%87%E5%8D%97_V1.4.pdf
