# Weather Station
The goal of this project is to build a weather station with real time notifications for climatology monitoring, interactive it with a cloud platform and analyse
weather parameters.
 
## Project Details
The final submit consists of these part
* [weather-station-final.py](https://github.com/NitheshChandher/weather-station/blob/master/weather-station-final.py) - Code
* [README.me](https://github.com/NitheshChandher/weather-station/blob/master/README.md) - Instructions on how to run the code
* [Project_Report_Group_11.pdf](https://github.com/NitheshChandher/weather-station/blob/master/Project_Report_Group_11.pdf) - Report for our project Weather Station

### Setting up the project 
1. For running the code properly, you need Python 2. In our project, we have Python 2.7.13. Use this command line to check which version you have
    ```
    python --version
    ```
2. A Raspberry Pi 3 model B single-board computer.
3. A Sense HAT add-on board.
4. Download app "pushover notification" to your mobile device.
5. Create a firebase project [here](https://console.firebase.google.com/u/0/?pli=1).

### Installation
These python libraries need be installed properlly using pip:
```
pip install SenseHat time datetime httplib urllib firebase
```

### Running the code
```
python weather-station-final.py
```
