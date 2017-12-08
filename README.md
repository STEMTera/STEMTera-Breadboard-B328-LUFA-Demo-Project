STEMTera Breadboard B328 LUFA Demo Projects
===========================================
![Image of STEMTera Breadboard Black](https://ksr-ugc.imgix.net/assets/013/802/899/bbadd26de0db2ed45bcaaae6ba0681be_original.jpg?w=680&fit=max&v=1474365591&auto=format&q=92&s=24632ecbf3e3ddc46b2484f247c5ecff)

Supported SKU : 
* STM100001
* STM100002
* STM100003
* STM100004
* STM100005
* STM100006
* STM100007

Summary
-------
STEMTera Breadboard is an innovation in breadboard history. It is the first breadboard with an Arduino compatible built-in that works with thousands of shields. With ATmega16U2/32U2 exposed, native USB projects can be easily developed using the LUFA framework. The LEGO® compatible bottom cover empowers projects to be built beyond imagination. 

Prerequisite
------------
1. [Atmel AVR 8-bit and 32-bit Toolchain 3.4.1 - Windows 98MBytes](http://www.atmel.com/tools/studioarchive.aspx)
2. [dfu-programmer](https://sourceforge.net/projects/dfu-programmer/files/dfu-programmer/0.7.2/)
3. [MinGW](http://www.mingw.org), install mingw32-base and msys-base package

Repository Contents that are used by STEMTera Breadboard
--------------------------------------------------------
* **/LUFA** - LUFA Framework
* **/Demo** - Projects Demo
	* **/Device** 
		* **/ClassDriver** 
			* **/Keyboard** - Turn STEMTera Breadboard into a HID keyboard, showing up as *LUFA Keyboard Demo* or *HID Keyboard Device* in Device Manager.
			* **/MIDI** - Turn STEMTera Breadboard into a MIDI device, showing up as *LUFA MIDI Demo* in Device Manager.
			* **/Joystick** - Turn STEMTera Breadboard into a joystick, showing up as *LUFA Joystick Demo* or *USB Input Device* in Device Manager.

Description
-----------
Projects demo using the ATmega16U2/ATmega32U2 micro controller. The demos are basically default from LUFA with some minor modification to the makefile and added Drivers/Board/AVR8/STEMTERA folder. These projects require the STEMTera Breadboard to be in the DFU Mode.

Putting STEMTera Breaboard B328 into DFU Mode and Flashing Keyboard Demo
------------------------------------------------------------------------
Detailed instructions here [http://learn.stemtera.com/en/setup/lufa](http://learn.stemtera.com/en/setup/lufa)
