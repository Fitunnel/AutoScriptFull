Install dibawah ini ges!

Support :
Ubuntu : 18,20
Debian : 10,11

```
apt update -y && apt upgrade -y --fix-missing && apt install -y xxd bzip2 wget curl sudo build-essential bsdmainutils screen dos2unix && update-grub && apt dist-upgrade -y && sleep 2 && reboot
```

```
screen -S setup-session bash -c "wget -q https://raw.githubusercontent.com/Fitunnel/AutoScriptFull/main/install.sh && chmod +x install.sh && ./install.sh; read -p 'Tekan enter untuk keluar...'"
```
Perintah Untuk Update Script
```
wget -q https://raw.githubusercontent.com/Fitunnel/AutoScriptFull/main/update.sh && chmod +x update.sh && ./update.sh && rm -f update.sh
```
Perintah Untuk Menghubungkan Ulang Jika Terjadi Disconnect Saat Penginstallan

```
screen -r -d setup
```

Perintah untuk fix menu (manual via sftp)
taruh file menu ke /user/local/sbin/
lalu jalan kan perintah bawah ini
```
sudo chmod +x /usr/local/sbin/*
```
