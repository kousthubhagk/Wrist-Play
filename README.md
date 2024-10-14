# Wrist-Play
### Overview
Wrist-Play is a project that utilizes Movella DOT IMU sensors strapped to the wrists to control online and offline games using motion-based inputs. This project leverages the Movella DOT SDK, which has been modified for specific gaming use cases.
### Features
- Control games using wrist movements.
- Real-time data processing from the Movella DOT sensors.
- Compatible with various games using WSAD controls.
### Installation
#### Requirements
- Python 3.10
- Movella DOT SDK
#### Steps
- Download and install the [Movella DOT SDK](https://www.movella.com/support/software-documentation)
- Install required python libraries:
  ```pip install pynput```
- Clone the repository
### Usage
- For WSAD controls use ```WSAD.py```
- For AD controls use ```AD.py```
#### Controls
- Wrist rotation/Roll controls left/right arrow keys
- Wrist Tilt/Pitch controls up/down arrow keys
#### Stopping the application 
Press the Esc key to stop the application gracefully.
### Code structure
#### Main Scripts
- `WSAD.py`: Main script for WSAD control
- `AD.py`: Main script for AD control
- `xpchandler.py`: Handles connections and data communication with Movella DOT devices
- `user_settings.py`: Contains user-specific configurations and settings
