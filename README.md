# kali-linux-fix-tp-link-tl-wn722n

apt-get install build-essential

apt-get install libelf-dev

apt-get install linux-headers-`uname -r`

sudo apt-get install linux-headers-`uname -r`

apt install dkms

sudo rmmod r8188eu.ko

rmmod r8188eu.ko

git clone https://github.com/aircrack-ng/rtl8188eus

cd rtl8188eus

sudo -i

echo "blacklist r8188eu" > /etc/modprobe.d/realtek.conf"

exit

reboot

apt-get update

cd rtl8188eus

make

make install

modprobe 8188eu

cd

iwconfig
