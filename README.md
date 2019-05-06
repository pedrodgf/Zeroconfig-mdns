sudo apt-get install avahi-daemon avahi-discover libnss-mdns

sudo nano axis-mdns-install.sh

sudo chmod 755 axis-mdns-install.sh

nano mdnsd-services.conf

systemctl stop mdns

sudo systemctl restart mdns
