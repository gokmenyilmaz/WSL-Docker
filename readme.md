# Kali linux install and remote desktop
Download kali linux from windows store
set username and password
cat /etc/os-release

wsl -l -v  
wsl --set-default kali-linux 2  
wsl -d kali-linux  

### sudo apt install nmap // nedir?

sudo apt update  
sudo apt install xfce4  
sudo apt install xrdp  
sudo /etc/init.d/xrdp start  

ifconfig    -- get ip number  

connect kali with windows 10 remote desktop  

## to delete
wsl --unregister kali-linux

## update
sudo apt update && sudo apt upgrade -y

## to see linux version
lsb_release -a  
