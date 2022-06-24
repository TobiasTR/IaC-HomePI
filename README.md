## with rpi-imager

write the raspbian iso to sd card using rpi-imager
add user/password and ssh-key in rpi-imager


## manually

expand filesystem "raspi-config --expand-rootfs"
reboot

update vars.yml, hosts, and templates


## with ansible

update system

install packages

set ssh passwordless to yes

set passwordless sudo true for sudo group

install fail2ban (config file etc)

setup docker

setup homeassistant

setup ESP home

setup pihole

