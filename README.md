<style>
  li{display: inline-block;}
</style>


<h1 align="center">
  <a href=https://www.ventoy.net/>Ventoy</a>
</h1>

<p align="center">
  <img src="https://img.shields.io/github/release/ventoy/Ventoy.svg?style=for-the-badge">
  <img src="https://img.shields.io/github/license/ventoy/Ventoy?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/ventoy/Ventoy?style=for-the-badge">
  <img src="https://img.shields.io/github/downloads/ventoy/Ventoy/total.svg?style=for-the-badge">
  <img src="https://img.shields.io/github/actions/workflow/status/ventoy/Ventoy/ci.yml?label=actions&logo=github&style=for-the-badge">
</p>

<p>Ventoy is an open source tool to create bootable USB drive for ISO/WIM/IMG/VHD(x)/EFI files.</p>
<p>With ventoy, you don't need to format the disk over and over, you just need to copy the image files to the USB drive and boot it.</p> 
<p>You can copy many image files at a time and ventoy will give you a boot menu to select them.</p>
<p>You can also browse ISO/WIM/IMG/VHD(x)/EFI files in local disk and boot them.</p>
<p>x86 Legacy BIOS, IA32 UEFI, x86_64 UEFI, ARM64 UEFI and MIPS64EL UEFI are supported in the same way.</p>
<p>Both MBR and GPT partition style are supported in the same way.</p>
<p>Most platforms are supported, including Windows, WinPE, Linux, Unix, ChromeOS, VMware, Xen &hellip;</p>
<p>Over 1,100 <a href="https://www.ventoy.net/en/isolist.html">ISO files</a> have been tested. Over 90% of <a href="https://distrowatch.com/">distrowatch.com</a> <a href="https://www.ventoy.net/en/distrowatch.html">distributions</a> are supported.</p>

<h2>Tested Operating Systems</h2>

<h3>Windows</h3>

<ul>
  <li>Windows 7</li>
  <li>Windows 8</li>
  <li>Windows 8.1</li>
  <li>Windows 10</li>
  <li>Windows 11</li>
  <li>Windows Server 2012</li>
  <li>Windows Server 2012 R2</li>
  <li>Windows Server 2016</li>
  <li>Windows Server 2019</li>
  <li>Windows Server 2022</li>
  <li>WinPE</li>
</ul>

<h3>Linux</h3>

<ul>
  <li>3CX Phone System</li>
  <li>4MLinux</li>
  <li>Absolute Linux</li>
  <li>AcademiX</li>
  <li>Acronis</li>
  <li>Active.Boot</li>
  <li>Adelie Linux</li>
  <li>AlmaLinux</li>
  <li>alpine</li>
  <li>ALT Linux</li>
  <li>Anarchy</li>
  <li>Android-x86</li>
  <li>antiX</li>
  <li>AOMEI</li>
  <li>APODIO</li>
  <li>Arcabit Rescue Disk</li>
  <li>Arch</li>
  <li>ArchBang</li>
  <li>Archcraft</li>
  <li>ArchLabs</li>
  <li>Archman</li>
  <li>ArchStrike</li>
  <li>ArcoLinux</li>
  <li>Artix Linux</li>
  <li>Arya</li>
  <li>Asianux</li>
  <li>Astra Linux</li>
  <li>Ataraxia Linux</li>
  <li>Austrumi</li>
  <li>AV Linux</li>
  <li>Avira Rescue System</li>
  <li>BackBox Linux</li>
  <li>batocera</li>
  <li>BEE free</li>
  <li>Berry Linux</li>
  <li>Bicom</li>
  <li>BigLinux</li>
  <li>bitdefender</li>
  <li>BlackArch</li>
  <li>blackPanther</li>
  <li>Blackweb Security OS</li>
  <li>BlankOn</li>
  <li>Bliss-OS</li>
  <li>BlueOnyx</li>
  <li>Bluestar</li>
  <li>Boot.Repair</li>
  <li>BOSS</li>
  <li>BunsenLabs</li>
  <li>CachyOS</li>
  <li>CAELinux</li>
  <li>CAINE</li>
  <li>Calculate Linux</li>
  <li>CDlinux</li>
  <li>CentOS(6/7/8/9)</li>
  <li>Chalet OS</li>
  <li>ChallengerOS</li>
  <li>Chapeau</li>
  <li>Checkra1n Linux</li>
  <li>Clear Linux</li>
  <li>ClearOS</li>
  <li>CloneZilla</li>
  <li>Clover</li>
  <li>Clu Linux Live</li>
  <li>CRUX</li>
  <li>Cucumber</li>
  <li>Daphile</li>
  <li>DaRT</li>
  <li>dban</li>
  <li>Debian</li>
  <li>Deepin</li>
  <li>Desa OS</li>
  <li>Devuan</li>
  <li>DietPi</li>
  <li>Dragora</li>
  <li>Drauger OS</li>
  <li>DRBL Linux</li>
  <li>DuZeru</li>
  <li>Easy OS</li>
  <li>Easy Recovery Essentional</li>
  <li>EasyNAS</li>
  <li>EasyStartup</li>
  <li>EasyUEFI</li>
  <li>Elastix</li>
  <li>Elementary OS</li>
  <li>Elive</li>
  <li>Emmabuntüs</li>
  <li>EndeavourOS</li>
  <li>Endian Firewall</li>
  <li>Endless OS</li>
  <li>Enso Linux</li>
  <li>ESET SysRescue Live,Nova Linux</li>
  <li>Eset SysRescue</li>
  <li>EuroLinux(6/7/8/9)</li>
  <li>Exe GNU/Linux</li>
  <li>ExTiX</li>
  <li>Fatdog</li>
  <li>Fedora</li>
  <li>Feren</li>
  <li>Finnix</li>
  <li>ForLEx</li>
  <li>foxclone</li>
  <li>FreedomBox</li>
  <li>Freespire</li>
  <li>Frost Linux</li>
  <li>Frugalware</li>
  <li>Garuda Linux</li>
  <li>GeckoLinux</li>
  <li>Gentoo</li>
  <li>gNewSense</li>
  <li>GNU Guix</li>
  <li>GoboLinux</li>
  <li>Grml</li>
  <li>Hamara</li>
  <li>HamoniKR</li>
  <li>Hanthana</li>
  <li>Hash Linux</li>
  <li>HefftorLinux</li>
  <li>HelenOS</li>
  <li>Holo</li>
  <li>HP SPP</li>
  <li>Hyperbola</li>
  <li>Ikki Boot</li>
  <li>iKuai</li>
  <li>IPFire</li>
  <li>Kaisen Linux</li>
  <li>Kali</li>
  <li>KANOTIX</li>
  <li>Karoshi</li>
  <li>Kaspersky Rescue</li>
  <li>KDE neon</li>
  <li>Kerio Control</li>
  <li>Kibojoe Linux</li>
  <li>Knoppix</li>
  <li>KolibriOS</li>
  <li>Kubuntu</li>
  <li>Kwort</li>
  <li>Kylin</li>
  <li>KylinSec</li>
  <li>Lakka</li>
  <li>Lenovo BIOS Update</li>
  <li>Lenovo Diagnostics</li>
  <li>LibreELEC</li>
  <li>LinHES</li>
  <li>Linpack Xtreme</li>
  <li>Linspire</li>
  <li>Linux Lite</li>
  <li>Linux Mint</li>
  <li>LinuxConsole</li>
  <li>LinuxFX</li>
  <li>Linx</li>
  <li>Live Raizo</li>
  <li>LliureX</li>
  <li>Lubuntu</li>
  <li>Lunar</li>
  <li>LXLE</li>
  <li>Mabox Linux</li>
  <li>Macrium</li>
  <li>Mageia</li>
  <li>mAid</li>
  <li>MakuluLinux</li>
  <li>Manjaro</li>
  <li>Maui</li>
  <li>MemTest86+</li>
  <li>MemTest86</li>
  <li>Minimal Linux Live</li>
  <li>MiniNo</li>
  <li>MiniTool Partition Wizard</li>
  <li>MiyoLinux</li>
  <li>Mll</li>
  <li>MocaccinoOS</li>
  <li>MorpheusArch</li>
  <li>MX Linux</li>
  <li>Namib Linux</li>
  <li>Neptune</li>
  <li>netboot.xyz</li>
  <li>NethServer</li>
  <li>Netrunner</li>
  <li>Network Security Toolkit</li>
  <li>NHVBOOT</li>
  <li>Nitrux</li>
  <li>NixOS</li>
  <li>Nobara</li>
  <li>NuTyX</li>
  <li>O-O.DiskImage</li>
  <li>OB2D</li>
  <li>Obarun</li>
  <li>Omarine</li>
  <li>Omoikane</li>
  <li>OpenAnolis</li>
  <li>openEuler</li>
  <li>openKylin</li>
  <li>OpenMamba</li>
  <li>OpenMandriva</li>
  <li>OpenMediaVault</li>
  <li>openSUSE</li>
  <li>OpenWrt</li>
  <li>Oracle Linux</li>
  <li>OSGeoLive</li>
  <li>paladin</li>
  <li>paldo</li>
  <li>Palen1x</li>
  <li>Parabola</li>
  <li>Pardus Topluluk</li>
  <li>Pardus</li>
  <li>Parrot OS</li>
  <li>Parted Magic</li>
  <li>PClinuxOS</li>
  <li>Peach OSI</li>
  <li>Pearl</li>
  <li>pearOS</li>
  <li>Pentoo</li>
  <li>Peppermint</li>
  <li>Peux OS</li>
  <li>Phoenix OS</li>
  <li>Photon</li>
  <li>Pinguy</li>
  <li>Pisi</li>
  <li>Plamo</li>
  <li>Ploplinux</li>
  <li>Pop OS</li>
  <li>Porteus</li>
  <li>PrimeOS</li>
  <li>PrimTux</li>
  <li>Proxmox VE</li>
  <li>Puppy Linux</li>
  <li>Pure OS</li>
  <li>Pyabr</li>
  <li>Q4OS</li>
  <li>Qubes</li>
  <li>R-Drive</li>
  <li>R-DriveImage</li>
  <li>RancherOS</li>
  <li>RebeccaBlackOS</li>
  <li>Reborn OS</li>
  <li>Recalbox</li>
  <li>RED OS</li>
  <li>Redcore</li>
  <li>Redo</li>
  <li>Refracta</li>
  <li>Regata OS</li>
  <li>Rescuezilla</li>
  <li>Resilient Linux</li>
  <li>Revenge OS</li>
  <li>ReviOS</li>
  <li>RHEL(6/7/8/9)</li>
  <li>RoboLinux</li>
  <li>Rocks Cluster</li>
  <li>Rocky Linux</li>
  <li>ROSA</li>
  <li>Runtu</li>
  <li>Sabayon</li>
  <li>Scientific</li>
  <li>SeaTools</li>
  <li>Secure-K OS</li>
  <li>Security Onion</li>
  <li>SELKS</li>
  <li>Septor</li>
  <li>SereneLinux </li>
  <li>Shark Linux</li>
  <li>ShredOS</li>
  <li>siduction</li>
  <li>Simplicity Linux</li>
  <li>SkyWave Linux</li>
  <li>Slackel</li>
  <li>Slackware</li>
  <li>Slax</li>
  <li>SLES</li>
  <li>Slitaz</li>
  <li>SME Server</li>
  <li>Smoothwall</li>
  <li>Snail Linux</li>
  <li>Solus</li>
  <li>Source Mage</li>
  <li>Springdale Linux</li>
  <li>Star Linux</li>
  <li>SteamOS</li>
  <li>StorageCraft SCRE</li>
  <li>SuperGamer</li>
  <li>SuperGrub2Disk</li>
  <li>SuperX</li>
  <li>Swift Linux</li>
  <li>SystemRescueCD</li>
  <li>T2</li>
  <li>Tails</li>
  <li>TeLOS</li>
  <li>TENS</li>
  <li>Thinstation</li>
  <li>TinyCore</li>
  <li>Todo en Uno</li>
  <li>ToOpPy LINUX</li>
  <li>Trident</li>
  <li>Trisquel</li>
  <li>TROM-Jaro</li>
  <li>TROMjaro</li>
  <li>Tsurugi Linux</li>
  <li>TurnKey</li>
  <li>tuxtrans</li>
  <li>UBOS</li>
  <li>Ubuntu Budgie</li>
  <li>Ubuntu DP</li>
  <li>Ubuntu Kylin</li>
  <li>Ubuntu MATE</li>
  <li>Ubuntu Studio</li>
  <li>Ubuntu</li>
  <li>Ufficio Zero</li>
  <li>Univention</li>
  <li>Untangle</li>
  <li>Uruk</li>
  <li>Vanilla OS</li>
  <li>veket</li>
  <li>Vine</li>
  <li>Virage Linux</li>
  <li>Void Linux</li>
  <li>Volumio</li>
  <li>Voyager</li>
  <li>VyOS</li>
  <li>Webconverger</li>
  <li>XeroLinux</li>
  <li>Xubuntu</li>
  <li>YunoHost</li>
  <li>Zentyal</li>
  <li>Zenwalk</li>
  <li>Zeroshell</li>
  <li>ZFSBootMenu</li>
  <li>Zorin</li>
  <li>ZStack</li>
</ul>


