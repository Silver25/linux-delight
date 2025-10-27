# linux-delight

Introducing tested Linux distributions and their behaviour on the laptop with secure boot enabled.  
Adventurous transfer from Windows 10 to Linux.  
UPDATE: Windows 10 Extend Security Updates in the Europe are Now FREE! - Extend Windows 10 till October 2026!  

## Test Environment

Laptop:
Acer Aspire E3-112-C1GR - Pinky [ from 2014 ]  
Screen: 11.6'' with 1366 x 768 (HD)  
CPU: 2 × Intel® Celeron® N2840 @ 2.16GHz, 64-bit, Dual-Core  
RAM: 7.6 GiB [ upgrade from 4 GiB]  
SSD: 120 GiB [ upgrade from HDD 320 GiB ]  
GPU: Mesa Intel® HD Graphics  
Acer R2 (CPU 1) Motherboard  
<details>
<summary>If you wanna know more ... <b style="color: yellow;">(open here)</b></summary>  
<!-- comment -->
=> connection to Wi-Fi home/personal/mobile/public [ coffe shop/library ]<br>
=> pluged USB Wacom Bamboo Pad graphical tablet<br>
=> Network disk drive, WD MyCloude Home, access over private Wi-Fi<br>
=> Smart TV, Hisense, 'cast' connection<br><br>

Laptop details, continue:<br>
- Dimensions (WxDxH): 29.1 cm x 21.1 cm x 2.12 cm<br>
- Weight: 1.39 kg<br>
- LCD Backlight Technology: LED backlight<br>
- Widescreen: Yes<br>
- Image Aspect Ratio: 16:9<br>
- Max RAM Supported: 8 GB<br>
- RAM Type: DDR3L SDRAM<br>
- Speed: 1600 MHz<br>
- Form Factor: SO-DIMM 204-pin<br>
- Memory Allocation Technology: Shared Video Memory (UMA)<br>
- Camera: Yes - 1280 x 720<br>
- Camera Features: 720p HD movie recording, Acer Crystal Eye HD<br>
- Sound: Stereo speakers, microphone<br>
- Compliant Standards: High Definition Audio<br>
- Wireless: 802.11b/g/n, Bluetooth 4.0<br>
- Network Interface: Gigabit Ethernet<br>
- Battery Capacity (Size): 2670 mAh<br>
- Technology: 3-cell lithium polymer<br>
- Input: AC 120/230 V (50/60 Hz)<br>
- Output: 40 Watt, 19 V<br>
- Interfaces: HDMI, Headphone/microphone combo jack, USB 3.0, USB 2.0, LAN<br>
- Memory Card Reader: Yes (SD Card)<br>
</details><br>  

---

NOTE:  
All tests were done with each Linux distribution running first as a live session, and then second is an installation on the physical device.  
My decision to use real machine rather than virtual machine was because of two reasons:  
1. Laptop has Windows 10 Home installed so it need change to Linux [ can't be upgraded with Win 11 ]  
2. Testing Linux systems on real computer will give better and more realistic results for other interested in migration to Linux  <br><br>

<details>
<summary>Linux distros installed and fully functional <b style="color: yellow;">(open for more)</b></summary>  
<!-- comment -->

#### This Linux distributions installed and fully operational with all boxes checked - 'out-of-the-box'.

[Voyager Live 25.04.2 "Plucky Puffin"](readme_assets/voyager_25042.md), 4.1 GB ISO - based on Ubuntu, with GNOME desktop  

[Fedora Linux 42 Workstation](readme_assets/fedora_42_workstation.md), 2.23 GB ISO - with Gnome desktop  

[AnduinOS](readme_assets/anduinos.md), 1.8 GB ISO - a custom Ubuntu-based with GNOME-based desktop  

[Kubuntu 24.04.3](readme_assets/kubuntu_24043), 4.24 GB ISO - with KDE Plasma desktop  

[Ubuntu Budgie 22.04](readme_assets/ubuntubudgie.md), 4.1 GB ISO, with Budgie Desktop Environment, MacOS-like

[Ubuntu Unity](readme_assets/ubuntuunity.md), 3.56 GB ISO

[Linux Lite](readme_assets/linux_lite.md),  2.9GB, Based on Ubuntu LTS, XFCE desktop, low on resources

<br><hr><br>
</details><br>  

<details>
<summary>Linux distros installed, but without some functionalities <b style="color: yellow;">(open for more)</b></summary>  
<!-- comment -->

#### The Linux distros listed here were installed successfully on a physical laptop with secure boot enabled, but failed to fulfil some tasks.

Rhino Linux  

PureOS  

MiniOS 4 Ultra  

Ubuntu Mate  

XUbuntu  

Lubuntu  

Linux Mint Xfce  

Linux Mint 22.1 "Xia"  

FunOS  

OpenSUSE Tumbleweed  

OpenSUSE Leap  

<br><hr><br>
</details><br>  

<details>
<summary>Distros FAILED to Install or to start as Installed <b style="color: yellow;">(open for more)</b></summary>  
<!-- comment -->

#### Next Linux distros can be started from USB as a Live session, but refuse to install on laptop, or failed to start as installed.

! You should be aware that <a href="https://linuxvox.com/blog/secure-boot-linux/">Secure Boot</a> is considered a security feature and was implemented to make it harder for things like ransomware [ Malware ] to take hold of your pc.  

BlendOS  

Nobara-42-Official  

Makulu Linux  

Siduction  

Pop!_OS  

CachyOS  

EndeavourOS  

Garuda  

Parrot OS  

Bodhi Linux  

Linux MX Libretto  

BunsenLabs  

SDesk  

Bluestar Linux  

RefreshOS  

Tuxedo OS  

KDE Neon User edition  

Linux Tails  

<br><hr><br>
</details><br>  

<details>
<summary>FAILED Live session Boot from USB drive/HDD <b style="color: yellow;">(open for more)</b></summary>  
<!-- comment -->

#### [ DIDN'T even Start from USB because of the [Secure Boot](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/), Secure Boot is NOT supported on 'Arch' Linux ]:

- AntiX Linux 23.2 [ https://antixlinux.com/ ] Based on: Debian, Origin: Greece, fast, lightweight and easy-to-instal  
- Asmi Linux 25.04 based on Ubuntu and 13 based on Debian failed to download  
- Debian - start with grub> and after adjusting grub to boot from root, display that 'shim' is bad and stop  
- Deepin - offer only installation from USB, no live session, failed to start as installed  
- DSL [ Damn Small Linux ]  
- EndeavourOS 8 Mercury Neo - boot failed from Toshiba USB created by Rufus  
- HeliumOS 10 based on CentOS with KDE Plasma Desktop 3.8 GB ISO = only installation [ NO live session ]  
- iDealOS  
- Manjaro 25.0  
- PCLinuxOS  
- PepermintOS  
- PuppyOS  
- Q4OS Aquarius  
- Rocky OS  
- Slax  
- Ubuntu Kylin  
- Void Linux XFCE - error: shin_lock protocol not found  
- Solus Linux  

<br><hr><br>
</details><br>  


Test live Linux distro online: https://distrosea.com/ [ free registration to get Internet connection for distro test ]  