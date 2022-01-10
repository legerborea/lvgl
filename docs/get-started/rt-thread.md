```eval_rst
.. include:: /header.rst
:github_url: |github_link_base|/get-started/rt-thread.md
```
# RT-Thread RTOS

<img src="https://raw.githubusercontent.com/RT-Thread/rt-thread/master/documentation/figures/logo.png" width=40% style="float: center;" >

## What is RT-Thread?

<a href="github.com/rt-thread/rt-thread">**RT-Thread**</a> is an [open source](https://github.com/RT-Thread/rt-thread), neutral, and community-based real-time operating system (RTOS). RT-Thread has **Standard version** and **Nano version**. For resource-constrained microcontroller (MCU) systems, the NANO kernel version that requires only 3 KB Flash and 1.2 KB RAM memory resources can be tailored with easy-to-use tools; And for resource-rich IoT devices, RT-Thread can use the **online software package** management tool, together with system configuration tools, to achieve intuitive and rapid modular cutting, seamlessly import rich software packages, thus achieving complex functions like Android's graphical interface and touch sliding effects, smart voice interaction effects, and so on.

Key features:

- Designed for resource-constrained devices, the minimum kernel requires only 1.2KB of RAM and 3 KB of Flash.
- A variety of standard interfaces, such as POSIX, CMSIS, C++ application environment.
- Has rich components and a prosperous and fast growing <a href="https://packages.rt-thread.org/en/">package ecosystem</a>
- Elegant code style, easy to use, read and master.
- High Scalability. RT-Thread has high-quality scalable software architecture, loose coupling, modularity, is easy to tailor and expand.
- Supports high-performance applications.
- Supports all mainstream compiling tools such as GCC, Keil and IAR.
- Supports a wide range of <a href="https://www.rt-thread.io/board.html">architectures and chips</a>.



## How to run LVGL on RT-Thread?

[中文文档](https://www.rt-thread.org/document/site/#/rt-thread-version/rt-thread-standard/packages-manual/lvgl-docs/introduction)

LVGL has registered as a [software package](https://packages.rt-thread.org/en/detail.html?package=LVGL) of RT-Thread. By using [Env tool](https://www.rt-thread.io/download.html?download=Env) or [RT-Thread Studio IDE](https://www.rt-thread.io/download.html?download=Studio), RT-Thread users can easily download LVGL source code and combine with RT-Thread project. RT-Thread community has port LVGL to several BSPs:

| BSP                                                          | Note |
| ------------------------------------------------------------ | ---- |
| [QEMU simulator](https://github.com/RT-Thread/rt-thread/tree/master/bsp/qemu-vexpress-a9) |      |
| [Visual Studio simulator](https://github.com/RT-Thread/rt-thread/tree/master/bsp/simulator) |      |
| [STM32L475 pandora](https://github.com/RT-Thread/rt-thread/tree/master/bsp/stm32/stm32l475-atk-pandora) |      |
| [STM32F407 explorer](https://github.com/RT-Thread/rt-thread/tree/master/bsp/stm32/stm32f407-atk-explorer/applications/lvgl) |      |
| [Nuvoton nk-980iot](https://github.com/RT-Thread/rt-thread/tree/master/bsp/nuvoton/nk-980iot/applications/lvgl) |      |
| [Nuvoton nk-n9h30](https://github.com/RT-Thread/rt-thread/tree/master/bsp/nuvoton/nk-n9h30/applications/lvgl) |      |
