YO THIS IS MY ROBOSAPIEN PROJECT, FORKED FROM SOME OLD REPO
Things to be done:

	Web interface(pull from chandler's robot and push to this one)
	Implement Walk forward, walk backward, turn left, and turn right
		See the python scripts on how to move
	Implement maintenence scripts (auto updating, continuous integration)
	Implement install scripts (automate instalation of these tools so it is easy to setup a controllable robosapien)
	Implement firewall stuff?
	Implement authentication methods so not everyone can control this
	Research API for letsrobot.tv
	Update README
	Come up with ideas of where to go with this and add to a txt file
	










commands to install necessary stuff:
sudo apt install ufw vim python-pigpio apache2
sudo apt-get install libjpeg-dev gettext libmicrohttpd-dev libavformat-dev libavcodec-dev libavutil-dev libswscale-dev libavdevice-dev libwebp-dev mysql-common libmariadb3 libpq5
sudo wget https://github.com/Motion-Project/motion/releases/download/release-4.2.1/pi_stretch_motion_4.2.1-1_armhf.deb
sudo dpkg -i pi_stretch_motion_4.2.1-1_armhf.deb
