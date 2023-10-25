
# PiDisplaySleep

A powersaver code written in python3 to put your Pi's display to sleep when you are not near it (checks if your phone is connected to the wifi !). This code is mainly aimed to run on smart mirrors.



## Requirements

This project uses the nmap package to do network scans

```
sudo apt-get install nmap
```
## Installation and Usage

Clone this repo ```git clone https://github.com/vincenthoehn/PiDisplaySleep.git```.

Enter your phone's or whatever devices' IP address in the script. Run the script at boot OR just run the main.py as : " python main.py & " through ssh and exit ssh with Ctrl + D. This will run the script in background until the next power down.
    
## Authors

- [@RpDp-git](https://www.github.com/RpDp-git)

This project is a fork from [PiDisplaySleep](https://github.com/RpDp-git/PiDisplaySleep)
