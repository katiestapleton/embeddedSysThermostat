# Thermostat Embedded System Project
The program is designed to be a thermostat with an automatic temperature adjuster. The system checks for user input on increasing and decreasing the temparature through buttons. The room temperature is surveyed and recorded using a in-built temperature reader. 

I created a thermostat program using C language and an embedded system. The embedded system is the TI C3220 SimpleLink LaunchBoard embedded system. For the coding, a timer executes tasks at different intervals. The timer intervals are necessary to process live data and execution the corresponding actions. The buttons and LED are controlled using the GPIO peripheral. The temperature readings are processed by the I2C peripheral. The data compiling and client-server data transfers are handled by the UART peripherals.

Before this point, I had not worked with embedded systems. With studying and practice, I understand the basis of embedded systems. My goal during this project focused on functionality and understanding limitations. Further developers will integrate an improved focus on memory management and system performance.

