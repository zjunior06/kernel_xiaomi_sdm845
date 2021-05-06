# SilverCore Kernel for Poco F1 (beryllium)

![SilverCore Kernel](https://github.com/PainKiller3/PainKiller3.github.io/raw/master/images/silvercore.jpg)

## Device specifications

Basic   | Specification
-------:|:-------------------------
SoC     | Qualcomm SDM845 Snapdragon 845
CPU     | Octa-core (4x2.8 GHz Kryo 385 Gold & 4x1.8 GHz Kryo 385 Silver)
GPU     | Adreno 630
Memory  | 6/8 GB RAM
Storage | 64/128/256 GB
Battery | Non-removable Li-Po 4000 mAh battery
Display | 1080 x 2246 pixels, 18:9 ratio, 6.18 inches, IPS LCD (~403 ppi density)
Camera  | 12 MP + 5MP, dual pixel PDAF, dual-LED (dual tone) flash
Release Date | August 2018

## Features
- Always updates with latest caf & linux tag.
- Compiled with EVA GCC (https://github.com/mvaisakh/gcc-build) with optimizations for sdm845 (cortex.a75 cortex.a55).
- Default TCP is BBR.
- Disabled a lot of debug drivers that are not required in production builds.
- Disabled QTI Core Control, Core Rotate and useless governors.
- Drivedroid Support.
- Kernelspace battery saver.
- Maple Iosched.
- Proper fast charging support according to temps.
- RCU Upstream from 4.14.
- Switched to Util clamp with uclamp assist to set values on init.
- Ships with LSE Atomics, Fast Multiplier, Optimized In-lining, Queued Spinlocks, Dead-Code-Elimination.
- Shipped with Berkley Packet Filter Just in Time compiler.
- Support Pixel Thermals.
- Sultan's perf critical IRQ framework to affine fast CPUs.
- Sultan's simple low memory killer.
- Check commit on git for more.

## Downloads
- [SilverCore Kernel For Beryllium](https://www.pling.com/p/1347883/#files-panel)

## Telegram Channel
- [Telegram Channel](https://t.me/reignzupdate)
- [Telegram Group](https://t.me/SilverCoreKernel)
