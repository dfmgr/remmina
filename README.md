## remmina  
  
remote desktop client written in GTK from the FreeRDP   
  
requires:    
```
apt install remmina
```  
```
yum install remmina
```  
```
pacman -S remmina
```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/remmina/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/remmina" "$HOME/.config/remmina.bak"
git clone https://github.com/dfmgr/remmina "$HOME/.config/remmina"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/remmina" target="_blank">remmina wiki</a>  |  
  <a href="https://remmina.org/" target="_blank">remmina site</a>
</p>  
