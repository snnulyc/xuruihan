 This is a private memo that records some things that are easy to forget.
 # Windows10
 1、Check and confirm the disk file backup is complete
 2、Hide file information view
 3、Delete hidden files
 4、Full antivirus
 5、Uninstall software
 6、Windows10 restore factory
 7、Install QQ Chrome Office2016 Photoshop

 KaliLinux
 1、Sources.list
       sudo vim /etc/apt/sources.list
       deb http://mirrors.aliyun.com/kali kali-rolling main non-free contrib
       deb-src http://mirrors.aliyun.com/kali kali-rolling main non-free contrib
 2、Install VMware Tools
    Copy VNware Tools Desk
    tar -zxvf (           )
    cd vmware-tools-distrib
    ./vmware-install.pl
 2、Update KaliLinux
   sudo apt-get update
   sudo apt-get upgrade
   sudo apt-get install linux-source
 3、Install SouGouPinYin
    sudo apt-get install fcitx
    sudo apt-get install fcitx-libs-qt
    Download SouGouPinYin For Linux
    dpkg -i File.deb
    sudo apt-get --fix-broken install
 4、sudo apt-get install openvas
    openvas-setup
    openvas-check-setup
    openvasmd --user=admin --new-password=(           )
 