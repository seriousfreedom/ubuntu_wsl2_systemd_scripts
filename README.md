# ubuntu-wsl2-systemd-scripts

Script to enable systemd support on current Ubuntu WSL2 images from the Windows store. 

I am not responsible for broken installations, so follow these steps if you understand what you are going to do.

Instructions from several forums all together put into this scripts to configure systemctl

## Usage
You need ```git``` to be installed for the commands below to work. Use
```sh
sudo apt install git
```
to do so.
### Run the script and commands
```sh
git clone https://github.com/SreekanthThummala/ubuntu_wsl2_systemd_scripts.git
cd ubuntu_wsl2_systemd_scripts/
bash ubuntu-wsl2-systemd-script.sh
```
### Then restart the Ubuntu shell and try running systemctl
```sh
systemctl

```
If you don't get an error and see a list of units, the script worked.

Have fun using systemd on your Ubuntu WSL2 image. You may use and change and distribute this script in whatever way you'd like. 

