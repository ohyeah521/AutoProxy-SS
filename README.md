AutoProxy-SS
============

It is to find the fastest proxy server with ShadowSocks. Currently it could work on Linux with Python 2.7.

It is based on shadowsocks. So the shadowsocks must be installed.

It will scan free shadowsocks ID from www.shadowsocks.net/get. You can 
also add the ID to id.ini.

Usage
============
1. Install dependency package

	*. $sudo apt-get install python-pip python-m2crypto python-dev libzbar-dev

	*. $sudo pip install zbar qrcode shadowsocks socksproxy
2. Go to this project

	*. $python ss.py
