# acurite-sensor-read
Code adapted from https://rayshobby.net/wordpress/reverse-engineer-wireless-temperature-humidity-rain-sensors-part-2/.
thank you for this and all the helpful comments.
This works for the Acurite 06002M on raspberry pi.

I am not a c++ coder and any stupidity or mistakes in the code was probably added by me.

The main idea behind this is for me to learn how to use git (and c++) and to share the code with someone else that might find it useful.


to compile:

c++ -std=c++0x humidity_display.cpp -o humidity_display.debug -lwiringPi


you will need to install wiringPi for this to work
