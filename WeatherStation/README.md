Hello!

Welcome to our general guide for our GW4054.

If you are here to view our data:

[Try Here](http://www.findu.com/cgi-bin/wxpage.cgi?call=GW4054&last=48)

If you are here to download our data for research Purposes:

[Try Here]()

Guide incoming...
[ (Resources and Tools for Weather and Climate Research for the Built Environment)](https://libguides.nyit.edu/architecture/SAME)

# Dashboard Set Up:

We are building our earliest prototypes using NODE-RED:

Here is the guide we followed:
https://pysselilivet.blogspot.com/2022/02/weatherlink-weather-template-api-v2.html

## Steps:
- [x] means we have verified it works!


- [x] Install NodeJS:
https://nodejs.org/en/download/prebuilt-installer

- [x] Install npm:
https://nodered.org/docs/user-guide/runtime/adding-nodes\

- [x] Install Node-Red
https://nodered.org/docs/getting-started/local
In terminal, enter "node-red" to open a node-red pallet.
You can access the dashboard by pointing your browser to:
http://127.0.0.1:1880/

- [x] Install the Dashboard Utility:
https://dashboard.flowfuse.com/getting-started.html

- [x] Download the Weatherlink Dashboard Flow
https://github.com/MatsA/Davis-Weatherlink-dashboard

- [x] Deploy a blank default dashboard Weatherlink Dashboard Flow
      With a open node-red pallet find "insert" in the menu and use the downloaded Weatherlink Dashboard Flow file.
      Click Deploy get it running.
      It will be available at:
      http://127.0.0.1:1880/ui/

- [ ] Enter your Weatherlink API Key
  
This is almost working. Currently looks like this:
![image](https://github.com/user-attachments/assets/e9bcc7c4-2d47-4c79-9728-5623d9b28250)

I am using (and verified) the Weatherlink API V2 key and secret inserted into the metadata stored here:
![image](https://github.com/user-attachments/assets/33baf68e-5bb4-45e7-96cb-24519f10fd2d)

It knows the location so it must have the station ID... but no weather data?

![image](https://github.com/user-attachments/assets/fc02bedc-a09c-4c35-9f22-32aec6187a0a)






