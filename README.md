# RASBERRYPI_SE20UARI042_SE20UARI092_SE20UARI91_SE20UARI170

# Raspberry Pi Temperature and Humidity Sensor Project

This project enables you to collect temperature and humidity data using a Raspberry Pi and a DHT11 sensor.

## Prerequisites
- Raspberry Pi (any model with GPIO pins)
- DHT11 temperature and humidity sensor
- MicroSD card with OS flashed.
- Internet access for package installation
- Jumper wires for connections.
- Powerbank for power supply to Raspberry Pi

## Installation

### Step 1: Install VNC Viewer

1. Install VNC Viewer on the computer to remotely access the Raspberry Pi's graphical interface.

   - Download VNC Viewer for  operating system from the official website: [VNC Viewer Downloads](https://www.realvnc.com/en/connect/download/viewer/).
   - Follow the installation instructions for the platform.

### Step 2: Set Up Raspberry Pi

1. Ensure  Raspberry Pi is set up and running with Raspbian OS.


  ![WhatsApp Image 2023-09-27 at 20 01 54](https://github.com/Rishika0702/RASBERRYPI_SE20UARI042_SE20UARI092_SE20UARI91_SE20UARI170/assets/128787886/8c081822-57b1-4406-ab79-cf109f5dba25)


### Step 3: Flash and Set Up the MicroSD Card

1. Download the Raspbian OS image from the official Raspberry Pi website: [Raspberry Pi Downloads](https://www.raspberrypi.org/downloads/raspbian/).

2. Use a tool like Etcher to flash the Raspbian OS image onto the microSD card.

3. Insert the microSD card into the Raspberry Pi.

### Step 4: Connect the DHT11 Sensor

1. Connect the DHT11 sensor to the Raspberry Pi using jumper wires:

   - VCC (Power): Connect to 3.3V on the Raspberry Pi.
   - Data: Connect to a GPIO pin. We used pin 23.
   - GND (Ground): Connect to a ground (GND) pin on the Raspberry Pi.
![WhatsApp Image 2023-09-27 at 20 23 20](https://github.com/Rishika0702/RASBERRYPI_SE20UARI042_SE20UARI092_SE20UARI91_SE20UARI170/assets/128787886/b52ad712-66b6-40c0-9a40-927cdfcad97a)

### Step 5: Connect the MicroSD Card to Raspberry Pi

1. Ensure the Raspberry Pi is powered off.

2. Insert the microSD card with Raspbian OS into the microSD card slot on the Raspberry Pi.

3. Power on the Raspberry Pi.

### Step 6: Enable GPIO on Raspberry Pi

1. Open the Raspberry Pi configuration tool:


2. Navigate to "Interfacing Options" and enable "GPIO."

### Step 7: Install Required Software

1. Update the package list and upgrade installed packages:
 ```sudo apt get update```

3. Install the required Python library for the DHT11 sensor:
```sudo python get-pip```

### Step 8: Write Python Code

1. Create a Python script (e.g., `Adafruit.py`) to read data from the DHT11 sensor. Use the provided example code in the project repository.

### Step 9: Run the Python Script

1. Run the Python script to read temperature and humidity data from the sensor:


2. Observe the console output for the collected data.

### Step 10: Optional - Store Data

1. Modify the Python script to store collected data in a file, a database, or upload it to a cloud service for further analysis.


# Creating a Firebase Account and Project

This section provides step-by-step instructions for creating a Firebase account, setting up a new project, and generating a service account key.

## Sign in to Firebase

1. **Sign in to Firebase:** Visit the Firebase website and log in to the Firebase account.

## Create a New Project

2. **Create a New Project:**
   - Click on the "+ Add project" button.
   - Follow the prompts to create a new project.
   - You can give the project any name you prefer.

## Access Project Configuration

3. **Access Project Configuration:**
   - After the project is successfully created, you will be directed to the project configuration page.

## Generating a Service Account Key

4. **Navigate to Service Accounts:**
   - In the Firebase Console, open the "Settings" menu, and select "Service Accounts."

5. **Generate a New Private Key:**
   - In the Service Accounts section, click on "Generate New Private Key."
   - Confirm this action by clicking "Generate Key."

We have successfully created a Firebase account, set up a project, and generated a private key for the service account. This key will be used to authenticate and interact with Firebase services from application.
Data collected in Firebase
![image](https://github.com/Rishika0702/RASBERRYPI_SE20UARI042_SE20UARI092_SE20UARI91_SE20UARI170/assets/128787886/77378538-ebfb-41a4-9b84-00e65ff557c1)

