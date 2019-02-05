# Softether-Autoinstall-Centos By Anonghost720
* Softether Auto Install Script for multi platforms updated version<br />
* Softether VPN server latest version v4.27-9666-beta-2018.04.21
* Revised to last known stable version due to compilation error from their latest release
* An open source VPN project from University of Tsukuba Japan<br />
* Centos 6 or 7 x64

# Buy ready to go and Ddos protected vpns at https://securityteamvpn.com
The best gaming vpns on the market, we sale gaming vpns with top ddos protection.
for just $9 you have access to over 30 locations from OVH, NFO, BLAZIN and many more.

# Instruction<br />
Choose your desired platform folder<br />
Download installer.sh using wget or transfer to your root directory using ftp<br /><br />

<b>Download and install the installer.sh by executing the commands below</b><br /><br />
<b>For centos and fedora</b> (copy all the codes below and paste on your terminal)<br /><br />
```yum install wget -y && wget https://raw.githubusercontent.com/Anonghost720/Softether-Autoinstall-Centos/master/installer.sh && chmod +x installer.sh && ./installer.sh ```<br /><br /><br />

# VPN server commands<br />
```/etc/init.d/vpnserver start - to start```<br />
```/etc/init.d/vpnserver restart - to restart```<br />
```/etc/init.d/vpnserver stop - to stop```<br /><br />

* vpncmd is at /usr/local/vpnserver<br /><br />

If you can't connect to your vpn server using VPN server manager. Open this ports on your firewall dashboard if you are using Google cloud, Amazon AWS, Alibaba Cloud and Digital Ocean<br />

TCP 443<br />
TCP 992<br />
TCP 1194<br />
TCP 5555<br />
