# roaming-pollution-meter
Basically this is a sensor based project which is used to tell the ppm concentration of Carbon-di-Oxide in its vicinity.
this can be placed on a moving object which will tell the ppm of CO2 over a large area.

##REQUIREMENTS
  1. Arduino
  2. MQ135 pollution sensor

##this repo consist of 2 files
  1. wow_.ino- this code will take the sensor readings.
  2. pollution.py- this code will take all the readings and will plot them with time on a graph.
  
  
  As soon as you run the arduino code, you will have run the python code just after that in order to obtain the graph.
  
  in the pyhton code there is line(line no.10 including blank lines) which says:-   serialArduino = serial.Serial('PORT NAME', BAUD RATE)
  
  here write the port number of arduino in place of PORT NAME and your arduino baud rate in place of BAUD RATE.
  

    




  
