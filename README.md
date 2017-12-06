sudo apt install libicu57 libssl1.0.2 gstreamer0.10-base fontconfig freetype2

cd ~

git clone https://github.com/marcotini/phantomjs.git

chmod -x ~/phantomjs-raspberrypi/bin/phantomjs

chmod 775 ~/phantomjs-raspberrypi/bin/phantomjs

sudo ln -s /home/pi/phantomjs-raspberrypi/bin/phantomjs /usr/bin/
