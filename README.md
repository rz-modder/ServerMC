## Minecraft Server on Termux
Jalankan server minecraft di android tanpa pc.

### Requirements
- Termux (Download from [f-droid](https://f-droid.org/))
- Install Linux on Termux (You can using proot-distro)

### How to setup linux
- Jalankan perintah berikut untuk menginstall paket proot pada termux
```
pkg update -y && pkg upgrade -y && pkg install proot-distro -y
```
- Jalankan perintah berikut untuk menginstall linux distro menggunakan proot (Saya menyarankan anda untuk menggunakan linux ubuntu/debian jika ram ponsel anda dibawah 4gb)
```
proot-distro install (ubuntu/debian)
```
```
proot-distro login (ubuntu/debian/...)
```
### How to setup ServerMC
```
apt update -y
apt upgrade -y
apt install sudo -y
sudo apt install git -y
git clone https://github.com/rz-modder/ServerMC
chmod +x ServerMC/*
cd ServerMC
```
