sudo apt-get install avahi-daemon avahi-discover libnss-mdns

sudo nano Axis-mdns-install.sh

sudo chmod 755 apple-mdns-install.sh

nano mdnsd-services.conf

systemctl stop mdns

sudo systemctl restart mdns
