# Weather-Forcasting-mini-Station-IOT-

This is mini Project on how to use multiple sensors with arduino (Weather forcasting station miniv) 

1) you need I2c Library and DHT Library you can find it on internet ( but be carefull while installing i2c library it might not detect your i2c module ) 
   so try different types of i2c library.

--------------------------------------------------------------------------------------------------------------------

2) First Connect your lcd i2c module to your arduino (anymodel) i have used arduino-uno.
   connect it with your Arduino-IDE and copy and paste code from I2c-Located.txt file and compile and run the code.
   and don't forget to set serial.begin(9600) you can change however you fill good just change
   the serial monitor value to (...)whatever you used and run it.
   now you can see the i2c address so we can compunicate with it.
   in my case I2C_ADDR 0x27.you might have same but always look first.  :)
--------------------------------------------------------------------------------------------------------------------

3) follow Connections_to_arduino.txt for clear and easy connection for your sensors to arduino-Uno.

--------------------------------------------------------------------------------------------------------------------

4) copy paste the code from  Weather_station_main.txt to your IDE(Arduino) and before compling and
   running check the Instruction mentioned in comment.

--------------------------------------------------------------------------------------------------------------------

5) You are good to go i will provide a scymetic for connections . 

--------------------------------------------------------------------------------------------------------------------

A tip before compiling and running the code Read it first try to understand it :)
