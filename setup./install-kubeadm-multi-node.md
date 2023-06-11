On all Servers 

echo "Change hostname"
hostnamectl set-hostname

echo "update and upgrade"
apt update ; apt upgrade -y

echo "install tools"
apt install -y wget git vim bash-completion curl htop net-tools dnsutils \
               atop sudo software-properties-common telnet axel jq iotop
