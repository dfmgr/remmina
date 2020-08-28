## remmina  
  
remote desktop client written in GTK from the FreeRDP  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/remmina/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install remmina
```  

Fedora Based:

```shell
yum install remmina
```  

Arch Based:

```shell
pacman -S remmina
```  

MacOS:  

```shell
brew install remmina
```
  
```shell
mv -fv "$HOME/.config/remmina" "$HOME/.config/remmina.bak"
git clone https://github.com/dfmgr/remmina "$HOME/.config/remmina"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/remmina" target="_blank" rel="noopener noreferrer">remmina wiki</a>  |  
  <a href="https://remmina.org" target="_blank" rel="noopener noreferrer">remmina site</a>
</p>  
