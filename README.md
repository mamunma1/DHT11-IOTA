# Send DHT11 sensor data to the IOTA Tangle using MAM and Raspberry Pi 2

This is a tutorial how to send DHT11 sensor data using Raspberry Pi 2 to IOTA Tangle using Masked Authenticated Messaging (MAM).




## Features

The project consists of 4 main files and should be executed on the Raspberry Pi.
- mam_publish.js: Publishes randomly generated numbers to the Tangle using MAM.
- mam_receive.js: Extract the stored data from the Tangle using MAM and display the data.
- sensor.js: The DHT11 sensor data (temperature and humidity) is read and displayed.
- mam_sensor.js: The DHT11 sensor data is read and published to the Tangle using MAM.





