# Port-scanner
Code to scan ports and check if they are open or closed. To run code simply enter command
```
python portscanner.py
```

## Comments
Type in the ip address of which you wish to scan when asked for input. If you wish to scan several targets at once you can do this by seperating the ip addresses by "," at input. Next the program will ask how many ports you wish to scan. This is the max value of the ports, meaning the program will check if the ports up until this value are open or closed.

If termcolor module doesn't exist, run command 
```
pip install termcolor
```
or alternatively comment out line 2 of code in portscanner.py with its areas of use as it is not necessary to run, but merely for aesthetics.
