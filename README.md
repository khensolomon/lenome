# lenome

Gnome theme

```css
.panel-button{
  background-color: rgba(29, 29, 29, 0.575);
  border-radius: 0 0 5px 5px;
  margin: 0 1px 0 1px;
}
#dash {
  background-color: rgba(29, 29, 29, 0.575);
}
#panel {
  /*background-color: rgba(40,40,40,0.88);*/
  background-color: transparent;
  font-weight: bold;
  height: 1.83em;
  font-feature-settings: "tnum";
  transition-duration: 250ms; 
}
```

?
git config --global user.name "khensolomon"
$ git config --global user.email khensolomon@gmail.com

```properties
./install.sh -i ubuntu -N mojave

sudo apt install flatpak
sudo apt install gnome-software-plugin-flatpak
```

> Right-click new document

```bash
mkdir -p ~/Templates/Text
cd ~/Templates/Text
touch document
```

> Set solid background Color

```properties
gsettings set org.gnome.desktop.background picture-uri none
gsettings set org.gnome.desktop.background primary-color '#5a5a5a'
gsettings set org.gnome.desktop.background color-shading-type 'solid'
```

More: https://andrewmccarthy.ie/setting-a-blank-desktop-background-in-gnome.html

## Application and extension

```properties
# gnome
sudo apt install gnome-shell-extensions gnome-tweaks

# dconf
sudo apt install dconf-editor

# sassc
sudo apt-get update
sudo apt-get install sassc
sassc -M -t compact gtk.{scss,css}


sassc -M -t compact gtk.css MyCustomized.css
```

Oomox

## tmp?

gresource extract gnome-shell-theme.gresource /org/gnome/shell/theme/Yaru/gnome-shell.css > output.css
