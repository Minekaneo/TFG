# Federated Learning with Arduino Nano 33 BLE Sense

Final degree project for the Bachelor's Degree in Computer Science of the [Universitat Politècnica de Catalunya](https://www.upc.edu/ca) - [Facultat d'informàtica de Barcelona](https://www.fib.upc.edu/).


## How tu use it
1. Configure the Arduino Nano 33 BLE Sense boards like in the image. ![board setup]
2. Open the project with PlatformIO and flash the firmware to all the boards.
3. Run the fl_server.py using Python3
    1. Specify the number of devices used
    2. Specify the Serial ports of each device
4. Start training the devices using the buttons.
    * First button takes a photo
    * Second button changes between modes (1,2,3 for training each class and 4 for predictions)
5. Every 10 seconds there will be a FL iteration to merge the trained models.

## Authors
- Ivan Ramirez
