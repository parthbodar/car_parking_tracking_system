# Car Parking Tracking System

This project implements a car parking tracking system using Python, OpenCV, and image processing techniques. It detects available parking spaces in a video feed and provides real-time visualization of the parking lot status.

## Features
- **Real-Time Detection**: Identifies free and occupied parking spaces in a video feed.
- **Interactive Configuration**: Allows you to set up and adjust parking space positions using a graphical interface.
- **Customizable Threshold**: Adjust the sensitivity to adapt to different lighting conditions or parking lot layouts.
- **Visualization**: Displays the number of free and total spaces on the video feed.

## Demo
Below is a preview of the system detecting parking spaces:
![Demo Image](demo_image.png)

## Project Structure
Car_Parking_Tracking_System/ 
├── carPark.mp4 # Input video for parking lot
├── carParkImg.png # Image used for parking space configuration
├── CarParkPos # File storing parking position data 
├── configure.py # Script to configure parking spaces 
├── main.py # Main parking detection script 
├── requirements.txt # Python dependencies 
└── README.md # Documentation

markdown

## How to Use
### 1. Set Up Parking Spaces
1. Run the `configure.py` script:
   ```bash
   python configure.py

Left-click to add parking spaces.
Right-click to remove parking spaces.
Positions are automatically saved to CarParkPos.
2. Run the Detection System
Run the main.py script:
bash

python main.py
The system will process the video feed and display real-time parking detection.
3. Adjust Threshold (Optional)
Modify the threshold in the main.py script (count < 900) for better detection accuracy based on your parking lot conditions.
Installation
Prerequisites
Python 3.8 or later
Libraries in requirements.txt


You can use the following example README.md file with a proper download link placeholder. Replace the placeholder (yourusername) with your actual GitHub username and upload it to your repository.

README.md
markdown
Copy code
# Car Parking Tracking System

This project implements a car parking tracking system using Python, OpenCV, and image processing techniques. It detects available parking spaces in a video feed and provides real-time visualization of the parking lot status.

## Features
- **Real-Time Detection**: Identifies free and occupied parking spaces in a video feed.
- **Interactive Configuration**: Allows you to set up and adjust parking space positions using a graphical interface.
- **Customizable Threshold**: Adjust the sensitivity to adapt to different lighting conditions or parking lot layouts.
- **Visualization**: Displays the number of free and total spaces on the video feed.

## Demo
Below is a preview of the system detecting parking spaces:
![Demo Image](demo_image.png)

## Project Structure
Car_Parking_Tracking_System/ ├── carPark.mp4 # Input video for parking lot ├── carParkImg.png # Image used for parking space configuration ├── CarParkPos # File storing parking position data ├── configure.py # Script to configure parking spaces ├── main.py # Main parking detection script ├── requirements.txt # Python dependencies └── README.md # Documentation

markdown
Copy code

## How to Use
### 1. Set Up Parking Spaces
1. Run the `configure.py` script:
   ```bash
   python configure.py
Left-click to add parking spaces.
Right-click to remove parking spaces.
Positions are automatically saved to CarParkPos.
2. Run the Detection System
Run the main.py script:
bash
Copy code
python main.py
The system will process the video feed and display real-time parking detection.
3. Adjust Threshold (Optional)
Modify the threshold in the main.py script (count < 900) for better detection accuracy based on your parking lot conditions.
Installation
Prerequisites
Python 3.8 or later
Libraries in requirements.txt
Install Dependencies
Install the required libraries using:


pip install -r requirements.txt
Download
You can download this project by cloning the repository or downloading the ZIP file:
git clone [https://github.com/yourusername/Car_Parking_Tracking_System.git](https://github.com/parthbodar/car_parking_tracking_system.git)
Download ZIP
License
This project is open-source and available under the MIT License.
