install :

cd ~/domoticz/plugins

mkdir somIO

sudo apt-get update

sudo apt-get install git

git clone https://github.com/Erwanweb/somIO.git somIO

cd somIO

sudo chmod +x plugin.py

sudo /etc/init.d/domoticz.sh restart

Upgrade :

cd ~/domoticz/plugins/somIO

git reset --hard

git pull --force

sudo chmod +x plugin.py

sudo /etc/init.d/domoticz.sh restart
