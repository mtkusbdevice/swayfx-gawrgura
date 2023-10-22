## Галерея
<img src="https://github.com/vidowner/swayfx-gawrgura/blob/main/img/photo_2023-08-12_17-44-11.jpg" width="350" align="center">
<img src="https://github.com/vidowner/swayfx-gawrgura/blob/main/img/photo_2023-08-12_17-44-13.jpg" width="350" align="center">
<img src="https://github.com/vidowner/swayfx-gawrgura/blob/main/img/photo_2023-08-12_17-44-14.jpg" width="350" align="center">
<img src="https://github.com/vidowner/swayfx-gawrgura/blob/main/img/photo_2023-08-12_18-03-12.jpg" width="350" align="center">

## Информация
|Distro|[ARCH](https://archlinux.org/)|
|:---:|:---:|
|WM|[SwayFx](https://github.com/WillPower3309/swayfx)|
|Bar|[Waybar](https://github.com/Alexays/Waybar)|
|Terminal|[Alacritty](https://github.com/alacritty/alacritty)|
|Shell|[Fish](https://fishshell.com/)|
|Icon|[Zorin](https://github.com/ZorinOS/zorin-icon-themes)|
|GTK3|[Zorin-Mint-Light](https://www.pling.com/p/1769479)|
|Cursors|[Default]|
|Fonts|[JetBrainsMono](https://www.jetbrains.com/lp/mono/)|
|Launcher|[wofi](https://sr.ht/~scoopta/wofi/)|
|Autotiling|[Autotiling](https://github.com/nwg-piotr/autotiling)|
  
## ВАЖНО!!!
Я делал данный райс на Arch Linux, все настройки идут от `~/.config/sway/themes/swayfx_gawr_gura/sway` В первую очередь необходимо открыть этот файл и закоментировать/раскоментировать то что тебе нужно.
  
Конфиги и обои берутся из `~/.config/sway/themes/swayfx_gawr_gura`
  
  
## Установка Swayfx
```
sudo pacman -S alacritty mesa base-devel wlroots wayland wayland-protocols pcre2  
json-c pango cairo gdk-pixbuf2 git messon cmake polkit  
  
git clone https://github.com/WillPower3309/swayfx  
cd swayfx
meson build/ -Dwerror=false  
ninja -C build/  
sudo ninja -C build/ install  
  
sway - для того что бы запустить
```
  
## Установка софта
```
sudo pacman -S pulseaudio pavucontrol firefox telegram-desktop mousepad gimp inkscape  
blender ghostscript obs-studio xdg-desktop-portal-wlr transmission-gtk python  
imv mpv nemo waybar grim slurp swaybg swaylock mako jq wofi htop cmus neofetch ranger unzip

yay cava
``` 
  
## Установка темы Gawr-Gura
```
Склонировать репозиторий командой(предварительно нужно поставить пакет git): 

git clone https://github.com/vidowner/swayfx-gawrgura
```  
  
```
Из ~swayfx-gawrgura/.config скопировать все в ~/.config
можно мышкой в файловом менеджере.
 
cp -r ~/swayfx-gawrgura/.config/ ~/.config
```  
  
```
Сделать исполняемыми все скрипты в ~/.config/sway/themes/swayfx_gawr_gura/scripts:
sudo chmod -R u+x .config/sway/themes/swayfx_gawr_gura/scripts
```  
  
```
Запустить данный sway можно командой sway -c .config/sway/themes/swayfx_gawr_gura/sway
```
