# Animal Detection 
    -using OpenCV Python
The prototype is based on image detection technology.The real time image is the input of the prototype
It detects the presence of the particular animals
We blend machine learning and open-source software with the Raspberry Pi ecosystem. One of the open-source software used here is OpenCV, which helps solve real-time computer vision and image processing problems. This project is a foray into the OpenCV landscape with the Raspberry Pi and involves using a pre-trained library from the COCO (Common Objects in Context) dataset. This will enable the Raspberry Pi to identify various objects and animals in real-time.

Hardware Requirements
-> RASPBERRY PI [RASPBERY PI 4B MODULE HAS BEEN USED BY US]
-> RASPBERRY PI CAMERA MODULE 
-> 7” HD DISPLAY
-> HDMI CABLE 
-> USB CABLE
-> 5V ADAPTER X 2
-> SD CARD

Code Demonstration and Explaination:

Step 1: Flash a micro-SD card with Raspberry Pi OS
        Download Raspberry Pi Imager: Download the Raspberry Pi Imager from the official Raspberry Pi website.
        Insert the micro-SD card: Insert your micro-SD card into your computer using an appropriate adapter.
        Flash the OS:
        Open the Raspberry Pi Imager.
        Select "Choose OS" and pick Raspberry Pi OS.
        Select "Choose SD Card" and pick your inserted micro-SD card.
        Click "Write" to flash the OS onto the micro-SD card.
        With the Micro-SD Card flashed you can install it into your Raspberry Pi
Step 2: Set up the Raspberry Pi
        Insert the micro-SD card: Once the flashing process is complete, insert the micro-SD card into your Raspberry Pi.
        Connect peripherals:
            -Connect a monitor to your Raspberry Pi.
            -Connect a keyboard and mouse.
        Ensure the Raspberry Pi Camera is connected to the correct slot with the ribbon cable facing the correct way.
        Power on: Power on your Raspberry Pi by connecting it to a power source.
Step 3: Install OpenCV
        Update and upgrade: Open a terminal and run the commands given in opencvfile to update and upgrade your system:
Step 4: Enable the Camera
        Open Raspberry Pi Configuration:
        Click on the Menu (top left corner).
        Navigate to Preferences and select "Raspberry Pi Configuration".
        Enable Camera:
          -Go to the Interfaces tab.
          -Enable the Camera option.
        Reboot: Restart your Raspberry Pi to apply the changes.
Step 5: Prepare the Code and Data
        Download the ZIP file: Download the ZIP file containing the code and trained library data.
        Unzip contents:
        Extract the contents of the ZIP file.
        Move the extracted files to /home/pi/Desktop.
Step 6: Run the Object Recognition Code
        Open Thonny or Geany IDE:
        Open the code file object-indent.py using Thonny or Geany IDE.
        You can open Thonny from the Menu -> Programming -> Thonny Python IDE.
        Alternatively, right-click on the object-indent.py file and open it with Thonny.
        Run the code:
        With the code file open in the IDE, click on the Run button.
Step 7: View the Output
        Live feed: A window will open displaying a live feed from the Raspberry Pi Camera.
        Object detection: The code will detect objects, draw green boxes around them, label them, and provide a confidence rating. Multiple objects will be detected and labeled individually.



