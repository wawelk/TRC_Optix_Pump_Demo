Updated for FactoryTalk v1.5 release features.

The FactoryTalk Optix demo application is designed to work with a ControlLogix L8 CPU.  The ControlLogix program can run on a real controller (if available) or FactoryTalk Logix Echo v3.01 or higher.  The IP address of the controller in the Optix application is 127.0.0.1.  The Studio 5000 ACD v37 file can be downloaded from:
https://www.mediafire.com/file_premium/l8sb3383bqb9ep4/TRC_Optix_Pump_Demp.ACD/file

Demo project with the following features:

 - Reusable Graphics for a pump control widget/faceplate (MyWidgets --> PumpWidget) with an Alias to Pump_UDT

 - Summary display with pump widgets tied to pump1, pump2, and pump 3 UDTs

 - Pump1 display
   - Historical trending of Pump 101 flow
   - DataLogger1
   - EmbeddedDatabase1

 - Pump2 display
   - Historical trending of Pump 201 flow
   - DataLogger2
   - EmbeddedDatabase2

 - Pump3 display
   - Historical trending of Pump 301 flow
   - DataLogger3
   - EmbeddedDatabase3

 - Alarms display with Alarm Summary widget showing Logix tag-based alarms

 - Addition of a local MQTT Broker

 - Addition of a MQTT Client that publishes Pump1, Pump2 and Pump3 topics to the local Optix MQTT broker


Cloning the repository
There are multiple ways to download this project, here is the recommended one

Clone repository
 - Click on the green CODE button in the top right corner
 - Select HTTPS and copy the provided URL
 - Open FT Optix IDE
 - Click on Open and select the Remote tab
 - Paste the URL from step 2
 - Click Open button in bottom right corner to start cloning process   
