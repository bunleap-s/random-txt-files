## Themes : arc-theme
```bash
# Add Repo
sudo sh -c "echo 'deb http://download.opensuse.org/repositories/home:/Horst3180/xUbuntu_16.04/ /' >> /etc/apt/sources.list.d/arc-theme.list"
#Install Arc-theme
sudo apt-get update && sudo apt-get install arc-theme
#Download Key if can't install
wget http://download.opensuse.org/repositories/home:Horst3180/xUbuntu_16.04/Release.key
#Add Key to fix
sudo apt-key add - < Release.key
```

## Icons : Paper
```bash
#Add Repo
sudo add-apt-repository -u ppa:snwh/ppa
#Install Paper Icons
sudo apt install paper-icon-theme
```

## Styles : Arc-Dark
Already install, just need to configure
