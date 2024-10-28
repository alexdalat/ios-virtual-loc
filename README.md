# iOS Location Simulation with Wireless Route Planning

## Features
- **iOS Location Update**: Wired and wireless, real-time updates to the device’s location on iOS 17 and iOS 18.
- **Route Planning**: Simulates a journey, mimicking a realistic route between points.
- **Simple Integration**: Easy-to-use Python script with an even easier to use HTML interface.

## Installation

To get started, make sure you have Python 3 installed. Then follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/alexdalat/ios-virtual-loc.git
    cd ios-virtual-loc
    ```

2. Set up a virtual environment:
    ```bash
    python3 -m venv env
    source env/bin/activate
    ```

3. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Installing **pymobiledevice3**. Follow the [instructions here](https://github.com/doronz88/pymobiledevice3?tab=readme-ov-file#working-with-developer-tools-ios--170) to activate developer mode on iOS.

## Usage

1. Run the main script, will prompt for sudo access:
    ```bash
    python main.py
    ```
    See https://github.com/alexdalat/ios-virtual-loc/blob/d4caf7dba2b81363f28bccead66611149874ef7e/TunnelService.py#L27 for the sudo command.

2. Visit the URL displayed in the console (usually `http://127.0.0.1:5432`) in your browser.

3. Double click to change device location, the rest is self-explanatory.

## Pictures

![Console Output Example](imgs/berlin-route-demo.png)

![Route Map Example](imgs/berlin-route-demo-gmaps.png)