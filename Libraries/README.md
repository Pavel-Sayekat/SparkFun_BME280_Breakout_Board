SparkFun <PRODUCT NAME> Libraries
=================================

Libraries for use in different environments. 


Directory Contents
-------------------
* **/Arduino** -- [Arduino IDE](http://www.arduino.cc/en/Main/Software) libraries
* BME280ComponentLibrary.lbr -- Eagle shape for BME280 part



Update Library Instructions:
----------------------------
To get the most up-to-date version of the library, you must run the following git subtree command from the repo top level. 

$git subtree pull -P Libraries/<COMPILER NAME> --squash <product library repo URL> <tag>

Example:

$git subtree pull -P Libraries/Arduino --squash https://github.com/sparkfun/SparkFun_BME280_Arduino_Library.git V_1.1.0