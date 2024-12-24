# This project involves creating a Bluetooth-controlled car using an ESP32 microcontroller and an L298N motor driver. The ESP32 provides both Wi-Fi and Bluetooth capabilities, enabling wireless communication and control. The L298N motor driver is used to control the car's DC motors, allowing for forward, backward, and directional movement. Using a Bluetooth-enabled device, users can send commands to the ESP32, which then controls the motor driver to navigate the car. This project demonstrates the integration of wireless communication and motor control, showcasing the capabilities of the ESP32 in IoT and robotics applications.

We are using only two motors
So, connect motor wires to the control units A and B of L298N.Now connect the ESP32 and the motor driver in the following way:

L298N-		                 ESP32
IN1- 			D12
IN2- 			D14
IN3- 			D27
IN4- 			D26

Connect the battery terminals to L298N and power up the ESP32 from the 5V terminal of the motor driver to the Vin of the ESP32.

Make the necessary connections and check again if the power is supplied to all the components.
Compile and upload the code onto the microcontroller, connect the Bluetooth onto your mobile device.
Download the application “ARDUINO CAR” and choose the device name to integrate it with the application.
Now, navigate the car using the mobile controller.
Thus, your Bluetooth controlled car is ready!


