# WSL_CS
#Export\Import\etc  
wsl -l  
wsl --export Ubuntu C:\@WSL2\ubuntu.tar  
wsl --import UbuntuDev C:\@WSL\ubuntudev ubuntu.tar  
#GUIDs Location 
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\AppModel\StateRepository\Cache\PackageFamily\Data\\{d}{l}  
#DNS Fix  
$sudo vim /etc/wsl.conf   
[network]  
generateResolvConf = false   
$sudo vim /etc/resolv.conf   
#Google or whoever  
nameserver 8.8.8.8   
nameserver 8.8.4.4   
