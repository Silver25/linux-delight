# linux-delight
Introducing tested Linux distributions and their behaviour on the laptop with secure boot enabled.  
Adventurous transfer from Windows 10 to Linux.  

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
Dimensions (WxDxH): 29.1 cm x 21.1 cm x 2.12 cm<br>
Weight: 1.39 kg<br>
LCD Backlight Technology: LED backlight<br>
Widescreen: Yes<br>
Image Aspect Ratio: 16:9<br>
Max RAM Supported: 8 GB<br>
RAM Type: DDR3L SDRAM<br>
Speed: 1600 MHz<br>
Form Factor: SO-DIMM 204-pin<br>
Memory Allocation Technology: Shared Video Memory (UMA)<br>
Camera: Yes - 1280 x 720<br>
Camera Features: 720p HD movie recording, Acer Crystal Eye HD<br>
Sound: Stereo speakers, microphone<br>
Compliant Standards: High Definition Audio<br>
Wireless: 802.11b/g/n, Bluetooth 4.0<br>
Network Interface: Gigabit Ethernet<br>
Battery Capacity (Size): 2670 mAh<br>
Technology: 3-cell lithium polymer<br>
Input: AC 120/230 V (50/60 Hz)<br>
Output: 40 Watt, 19 V<br>
Interfaces: HDMI, Headphone/microphone combo jack, USB 3.0, USB 2.0, LAN<br>
Memory Card Reader: Yes (SD Card)<br>
</details><br>  

---

NOTE:  
All tests were done with each Linux distribution running first as a live session, and then second is an installation on the physical device.  
My decision to use real machine rather than virtual machine was because of two reasons:  
1. Laptop has Windows 10 Home installed so it need change to Linux [ can't be upgraded with Win 11 ]  
2. Testing Linux systems on real computer will give better and more realistic results for other interested in migration to Linux  

<details>
<summary>Linux distros installed and fully functional <b style="color: yellow;">(open here)</b></summary>  
<!-- comment -->
<p>
This Linux distributions installed and fully operational with all boxes checked - 'out-of-the-box'.</p>

<br><hr><br>

<p>
Voyager Live 25.04.2 "Plucky Puffin", 4.1 GB ISO - Based on Ubuntu, with GNOME desktop<br>
[ https://voyagerlive.org/voyager-25-04/ ] a French distro based on Xubuntu.<br>
** - what this Linux distribution has to offer takes the prize for being the most user-friendly and elegant<br>
[ https://www.zdnet.com/article/voyager-23-10-might-be-my-favorite-take-on-the-gnome-desktop-to-date ]<br>

*run from USB HDD Ventoy on secure boot<br>
*Installed and run over Secure Boot<br>
*as a distro based on Ubuntu linux, it's help system is available: https://help.ubuntu.com/<br>

- Internet connected [ Firefox default ]
- mouse left click as a touchpad tap
- mouse right [ menu ] click with two fingers tap and corner click on touchpad
- Brightness and volume over keyboard keys
- Bamboo Pad graphical tablet connected and works smoothly, movement is like with touchpad
- hidden taskbar popup on pointer move over
- Audio, video on Youtube and streaming [sflix.to] works
- App window control buttons in top right corner [ Windows like ]
- 'Software' rich manager for app installation [ Brave, Chromium, Opera, Bitwarden, VSChromium, Boxes, 4K Video Downloader ]
[ FBReader, Foliate, Kate, Pinta, Free Tube, Private, Shortwave-radio, KWrite, gedit ]
- Terminal~$ 'sudo apt install kate' can also work for CMD familiar
- 'Files' file manager with all user folder shortcuts in left window panel/side
- Integrated AI Chat GPT 'Chatty' in desktop
- Alt+Tab solution: Settings -> Keyboard -> Keyboard shortcuts -> Navigation -> Switch Apps [ edit shortcut ]
- PrtSc keyboard shortcuts: Shift + PrtSc [ full screen ], Alt + PrtSc [ active app window ] auto save in Picture folder
- Bitwarden starts from Menu or Dock [ can't start from App Dashboard ]
- Mahjongg installed

- opens network WDMyCloud easily

ISSUES:
- Alt+Tab keys doesn't work by default [ 'out of the box' ], instead is 'Super' + Tab, Ubuntu combination
- Suspend of the system coused by closed laptop lid, NO 'out of the box' settings option to disable</p>

<br><hr><br>

<p>
Fedora Linux 42 Workstation with Gnome desktop<br>

*Booted from USB as a Live Session [ Toshiba white ]<br>

- Internet connected [ Firefox default ]
- mouse left clik as a touchpad tap [ adjustment in settings ]
- mouse right [ menu ] click with two fingers on touchpad
- Brightness and volume over keyboard keys
- Easy window resize/adjustment
- 'Software' is app rich Software Management tool
- Mouse cursor/pointer smooth and fluid motions
- Windows scroller smooth movement
- Settings with Power and Mouse options to change
- Audio, video on Youtube works, streaming [sflix.to] NOT fluid
- Supporting browser Casting tab or full computer screen on TV

- opens network WDMyCloud easily [ Files -> Network -> MyCloud ]

ISSUES:
- Taskbar/Panel hidden, show with Win/Super key or three fingers slide on touchpad
- NO confirmation or approval before deleting any file, only for Shift+DEL [ permanent ]
- Secondary/right mouse click as a touchpad tap or corner click, NOT both
- Closed laptop lid suspend OS, send OS to sleep, NO settings option for that

*Fedora 42 Post Install Guide
- https://github.com/devangshekhawat/Fedora-42-Post-Install-Guide
*Curated Fedora Core 42 post-install notes
- https://paulsorensen.io/fedora-kde-plasma-post-installation-guide/
</p>

<br><hr><br>
</details>  

<details>
<summary>Linux distros installed, but without some functionalities <b style="color: yellow;">(open here)</b></summary>  
<!-- comment -->
<p>
The Linux distros listed here were installed successfully on a physical laptop with secure boot enabled, but failed to fulfil some tasks.</p>
<p></p>
</details>  

<details>
<summary>Distros FAILED to Install or to start as Installed <b style="color: yellow;">(open here)</b></summary>  
<!-- comment -->
<p>
Next Linux distros can be started from USB as a Live session, but refuse to install on laptop, or failed to start as installed.</p>
<p></p>
</details>  

#### FAILED Live session Boot from USB drive/HDD
[ DIDN'T even Start from USB because of the [Secure Boot](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/), Secure Boot is NOT supported on 'Arch' Linux ]:  
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