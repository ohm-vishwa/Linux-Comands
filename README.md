# Linux-Comands
It Contains Helpful comands for Debian Based Linux Distro ( mainly for Ubuntu )

## Make terminal like look like Parrot OS
[Parrot Os .bashrc file](/.bashrc)
```bash
sudo nano .bashrc
```
> [!IMPORTANT]
> Paste at bottom

> Similarly,
```bash
sudo nano /root/.bashrc
```

---
 ## Install  Gome extension
```bash
sudo apt update

sudo apt install gnome-shell-extensions chrome-gnome-shell
```

---
 ## Stop Battery Charging at 80% in linux (Asus Laptop) 
> Open
```bash
sudo nano /etc/crontab
```
> paste inside ` /etc/crontab `
```bash
@reboot root echo 80 >  /sys/class/power_supply/BAT0/charge_control_end_threshold
```

---
## install (kali tools) Katoolin3 in Ubuntu
```bash 
git clone https://github.com/s-h-3-l-l/katoolin3
```
```bash
wget -q -O - https://archive.kali.org/archive-key.asc  | apt-key add
```
```bash
cd katoolin3
```
```bash
sudo nano install.sh
```
>[!WARNING] 
> Comment out\
> `#apt-key adv -qq --keyserver pool.sks-keyserver.net.....`

```bash
sudo +x ./install.sh
```
```bash
sudo nano .bashrc
```
> [!IMPORTANT]
> Paste at Bottom
```bash
export PATH=$PATH:~/katoolin3:/usr/bin/python3
```
---
## [View My GitHub Profile](https://github.com/ohm-vishwa) 
## [Keep Supporting on YouTube](https://www.youtube.com/@ohm_vishwa)