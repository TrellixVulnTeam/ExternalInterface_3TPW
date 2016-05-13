External user irnterface with usb
===================================
Project tags:
  - MCP2210
  - Displat with "IST3020"
  - Joystick
  - Python library

Project tree:
- hw
  - board with buttons on the left side - KiCad files - schematics and pcb
  - board with buttons next to joystick - KiCad files - schematics and pcb
  - caseing - FreeCad projects for caseing this user interface (3D pronting)
- sw
  - Python 3.4 project lib

It contains:
- [SW lib.](https://github.com/misisnik/ExternalInterface/tree/master/sw)
- [HW board 1](https://github.com/misisnik/ExternalInterface/tree/master/hw/board_buttons_next_to_joystick)
- [HW board 2](https://github.com/misisnik/ExternalInterface/tree/master/hw/board_buttons_on_the_other_side)
- [HW 3D casing](https://github.com/misisnik/ExternalInterface/tree/master/hw/caseing)

Installation
------------

	-Raspbian Jesee
	---------------
			$ apt-get update
			$ sudo apt-get install git python3.4 python3-dev

		install pip3 from git
			$ git clone https://github.com/pypa/pip
			$ cd pip
			$ python3.4 setup.py install
			$ cd ..
			$ rm -r pip

		install cython
			$ apt-get install cython3

		libusb
			$ apt-get install libusb-1.0.0 libusb-1.0.0-dev libudev-dev

		install cython-hidapi
			$ git clone https://github.com/gbishop/cython-hidapi.git
			$ cd cython-hidapi
			$ python3 setup.py build
			$ python3 setup.py install
			$ cd ..
			$ rm -r cython-hidapi

		install Pillow
			$ apt-get install libjpeg-dev
			$ pip3 install pillow

		install pyserial
			$ pip3 install pyserial

		-- display LIB
		git clone https://github.com/misisnik/ExternalInterface


Examples
---------------

to dooooooooooooo
