## 👋 Welcome to dfmgr 🚀  

 Install configurations for dfmgr  
  
  
### Requires scripts to be installed

```shell
sudo bash -c "$(curl -q -LSsf "https://github.com/dfmgr/installer/raw/main/install.sh")" && sudo dfmgr install installer
```

OR

### Automatic install/update  

```shell
dfmgr update dfmgr
```
  
### requirements  
  
#### Debian based

```shell
apt install dfmgr
```  

#### Fedora Based

```shell
yum install dfmgr
```  

#### Arch Based

```shell
pacman -S dfmgr
```  

#### MacOS  

```shell
brew install dfmgr
```
  
#### Manual install  

```shell
APPDIR="$HOME/.local/share/CasjaysDev/dfmgr/dfmgr"
mv -fv "$HOME/.config/dfmgr" "$HOME/.config/dfmgr.bak"
git clone https://github.com/dfmgr/dfmgr "$APPDIR"
cp -Rfv "$APPDIR/etc/." "$HOME/.config/dfmgr/"
[ -d "$APPDIR/bin" ] && cp -Rfv "$APPDIR/bin/." "$HOME/.local/bin/"
curl -q -sS https://starship.rs/install.sh | sh
```

## Author  

🤖 casjay: [Github](https://github.com/casjay) 🤖  
⛵ dfmgr: [Github](https://github.com/dfmgr) ⛵  

## Links

<p align=center>
   <a href="https://travis-ci.com/github/dfmgr/dfmgr" target="_blank" rel="noopener noreferrer">
     <img src="https://travis-ci.com/dfmgr/dfmgr.svg?branch=master" alt="Build Status"></a><br />
  <a href="https://wiki.archlinux.org/index.php/dfmgr" target="_blank" rel="noopener noreferrer">dfmgr wiki</a>  |  
  <a href="dfmgr" target="_blank" rel="noopener noreferrer">dfmgr site</a>
</p>  
