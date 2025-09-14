# linux-delight
Introducing tested Linux distributions and their behaviour on the laptop with secure boot enabled.  
Adventurous transfer from Windows 10 to Linux.  

## Test Environment

Laptop:
Acer Aspire E3-112-C1GR - Pinky  
Screen: 11.6'' with 1366 x 768 (HD)  
CPU: 2 × Intel® Celeron® N2840 @ 2.16GHz, 64-bit, Dual-Core  
RAM: 7.6 GiB [ upgrade from 4 GiB]  
SSD: 120 GiB [ upgrade from HDD 320 GiB ]  
GPU: Mesa Intel® HD Graphics  
Acer R2 (CPU 1) Motherboard  

NOTE:  
All tests were done with each Linux distribution running first as a live session, and then second is an installation on the physical device.  
My decision to use real machine rather than virtual machine was because of two reasons:  
1. Laptop has Windows 10 Home installed so it need change to Linux [ can't be upgraded with Win 11 ]  
2. Testing Linux systems on real computer will give better and more realistic results for other interested in migration to Linux  

<details>
<summary>Linux distros installed and fully functional <b style="color: yellow;">(open here)</b></summary>  
<!-- comment -->
This Linux distributions installed and fully operational with all boxes checked.
</details>  

<details>
<summary>Linux distros installed, but without some functionalities <b style="color: yellow;">(open here)</b></summary>  
<!-- comment -->
The Linux distros listed here were installed successfully on a physical laptop with secure boot enabled, but failed to fulfil some tasks.
</details>  

<details>
<summary>Distros FAILED to Install or to start as Installed <b style="color: yellow;">(open here)</b></summary>  
<!-- comment -->
</details>  

#### FAILED Live session Boot from USB drive/HDD
[ DIDN'T even Start from USB because of the Secure Boot, Secure Boot is NOT supported on 'Arch' Linux ]:  
- HeliumOS 10 based on CentOS with KDE Plasma Desktop 3.8 GB ISO = only installation [ NO live session ]  
- Asmi Linux 25.04 based on Ubuntu and 13 based on Debian failed to download  
- Deepin - offer only installation from USB, no live session, failed to start as installed  
- PepermintOS  
- Manjaro 25.0  
- PuppyOS  
- Slax  
- DSL [ Damn Small Linux ]  
- EndeavourOS 8 Mercury Neo - boot failed from Toshiba USB created by Rufus  
- Ubuntu Kylin  
- Void Linux XFCE - error: shin_lock protocol not found  
- Q4OS Aquarius  
- AntiX Linux 23.2 [ https://antixlinux.com/ ] Based on: Debian, Origin: Greece, fast, lightweight and easy-to-instal  
- Rocky OS  
- Linux Solus  
- iDealOS  
- PCLinuxOS  
- Debian - start with grub> and after adjusting grub to boot from root, display that 'shim' is bad and stop  

Test live Linux distro online: https://distrosea.com/ [ free registration to get Internet connection for distro test ]  