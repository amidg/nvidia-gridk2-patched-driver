# nvidia-gridk2-patch
This repository contains Nvidia Linux 64-bit patched vBIOS .rom file to be used along with 367 legacy driver for the new linux distros (e.g. Ubuntu 20.04). I use this driver in my homelab setup for remote gaming and GPU-accelerated applications. 

This driver supports:
- Grid K2 
- Tesla K10 (repurposed as Grid K2, that's what I use)

Tested OS:
- Hypervisor: Proxmox VE 6.3
- Linux with 5.x Kernel (tested on Ubuntu 20.04 and Ubuntu 20.04 Server)
- Windows 10 Pro

How to convert Tesla K10 to Grid K2?
https://www.eevblog.com/forum/general-computing/hacking-nvidia-cards-into-their-professional-counterparts/1025/
