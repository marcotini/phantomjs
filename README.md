cd ~

git clone https://github.com/piksel/phantomjs-raspberrypi.git

chmod -x ~/phantomjs-raspberrypi/bin/phantomjs

chmod 775 ~/phantomjs-raspberrypi/bin/phantomjs

sudo ln -s /home/pi/phantomjs-raspberrypi/bin/phantomjs /usr/bin/
