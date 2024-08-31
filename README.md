<p align="center"><a href="https://ibb.co/DzZFK8v"><img src="https://i.ibb.co/FmF170y/BLACKBUNTU-LOGO-2.png" alt="BLACKBUNTU-LOGO-2" border="0" width="50%" height="50%"></a></p>

##
This is a fully themed installation build script to convert Ubuntu 24.04 LTS to Blackbuntu. It is recommended to execute on a clean installation. 

Download the latest Ubuntu ISO from here: ` https://ubuntu.com/download/desktop `

(Note this script and theme will not work correctly on older builds of ubuntu, such as 22.04 LTS, check this repo for one for 22.04 - https://github.com/andrewpayne68/BLACKBUNTU.2204)

Includes Thorium Browser, Brave Browser and Variety Wallpaper Changer.
##

```
sudo apt-get -y install git
```
```
git clone https://github.com/andrewpayne68/blackbuntu2404.git
```
```
cd blackbuntu2404
```
```
tar -xf blackbuntu-2404lts.tar.xz
```
```
cd blackbuntu-2404lts && ./build.sh
```

OR run the all-in-one bash command
```
sudo apt-get -y install git && git clone https://github.com/andrewpayne68/blackbuntu2404.git && cd blackbuntu2404 && tar -xf blackbuntu-2404lts.tar.xz && cd blackbuntu2404 && ./build.sh
```



 > After the first reboot, run 
 > ```
 > sudo nala update && sudo nala upgrade -y
 > ```
 > to update the system




![image-1](https://github.com/andrewpayne68/BLACKBUNTU.2310/blob/main/Blackbuntu-desktop-2310.PNG)


