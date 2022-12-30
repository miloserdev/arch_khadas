# arch_khadas
Arch Linux for Khadas VIM4 

Download  
[khadas::Google Drive](https://drive.google.com/drive/folders/10nBijHh5i2y7tXED6OXy27OSWCEWTnEe?usp=sharing)  

Direct links  
`BOOT.tar.gz` https://drive.google.com/file/d/182mUjyBU37nLS-6uUri7NqeajZZLNU9R/view?usp=share_link  
`ROOTFS.tar.gz` https://drive.google.com/file/d/1rZCLRbPnfm6nSWx-7_sdqOJaOjFv526m/view?usp=share_link  


You can only extract `ROOTFS.tar.gz` if BOOT partition already contains U-Boot system.  

Unpack  
`sudo tar -zxvf BOOT.tar.gz -C /<BOOT mount point>`  
`sudo tar -zxvf ROOTFS.tar.gz -C /<ROOTFS mount point>`  

Some features may not work, official Arch Linux distro for Khadas VIM4 does not exist.  
