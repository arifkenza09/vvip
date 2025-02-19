# install script

apt update -y && apt install -y wget git screen curl jq && wget -q https://raw.githubusercontent.com/arifkenza09/vvip/main/setup.sh && chmod +x setup.sh && screen -S install ./setup.sh

# update script 

wget -q https://raw.githubusercontent.com/arifkenza09/vvip/main/menu/update.sh && chmod +x update.sh && ./update.sh
