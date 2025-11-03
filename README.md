# MLX90640_Thermal_Camera_with_ESP32

-----------------------------
This tutorial introduces the use of the MLX90640 Thermal Camera module via Adafruit-ESP32-FeatherV2 board + graphics visualization via Processing (P3)

More about
-
MLX90640 Thermal Camera: https://github.com/kingston-hackSpace/thermalCamera_MLX90640

ESP32: https://learn.adafruit.com/adafruit-esp32-feather-v2/overview

Processing: https://processing.org/

---
TUTORIAL
---
**STEP 1: Installing Processing**
- Install Processing if you haven't already:
    https://processing.org/download?processing

-

**STEP 2: Installing ESP32 dependancies**
- Open your Arduino IDE

- At the top menu, select:
    Arduino IDE > Preferences...

  Fill "Additional boards manager URLs" copying the following into it: 

    https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json
  
- Close/Re-open Arduino IDE
  
- Go to "Tools > Boards > Boards Manager"

- Search for "esp32 by Espressif Systems". Install. 

- Plug your ESP32 to your computer if you haven't alredy.
  
- Go to "Tools > Upload Speed > 115200"

- At the top of your Arduino IDE screen, select the board: "Adafruit Feather ESP32 V2"

- Go to "File > Examples > 01.Basics > Blink"

- Upload the Blink example into your board to test that everything has gone well in your installation process.

**STEP 3: Installing Thermal Camera dependancies**

- Go to "Scketch > Include Library > Manage Libraries..."
  
- Search for "Adafruit MLX90640 by Adafruit". Install.

- Go to "File > Examples > (scroll down until you find:)
                            Adafruit MLX90640 > MLX90640_simpleTest"
                            
- Upload this example into your board to test that everything has gone well in your installation process.

**STEP 5: Run the Arduino Sketch**

- Now open and upload the Arduino Code provided in this tutorial, named "MLX90640_CameraView.ino"

- Open your Serial Monitor, you should see data printed in it. If You get a "exit 2" error, you need to repeat the following step:

- Go to "Tools > Upload Speed > 125200"

- Close Arduino. You won't be able to run the Processing schetch if Arduino Serial Monitor is open.
    

**STEP 6: Run the Processing Sketch**

- Open and run any of the .pde sckeths provided (Yellow or Pink).

---
Debugging
---
If you get a "exit 2" error, check the communication speed 

- Go to "Tools > Upload Speed > 125200"



