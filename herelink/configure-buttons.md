---
description: >-
  Herelink's button's and gimbal control now controls functions within the
  supported application such as Solex via the telemetry connection via Mavlink.
---

# Configure Buttons & Wheel

## Button Configuration

### **To Configure in Solex TX**

* Open Solex TX App 
* Click 3 line in top left corner

![](../.gitbook/assets/button-mapping-0.jpg)

* Select 'Button Mapping' 

![](../.gitbook/assets/button-mapping-1.jpg)

* Choose desired button

![](../.gitbook/assets/button-mapping-2.jpg)

* Select either 'Click' or 'Long Click' \(**Note** this allows you to set two functions to each button\) 

![](../.gitbook/assets/button-mapping-2.5.jpg)

* Click on drop down to select the function you want

![](../.gitbook/assets/button-mapping-3.png)

* Click on small cog to select option with-in selected function  

![](../.gitbook/assets/button-mapping-6.jpg)

* Select function option

![](../.gitbook/assets/button-mapping-5.png)

* Repeat for each button assignment and click 'Save Buttons' in bottom corner to finish

![](../.gitbook/assets/button-mapping-7.jpg)

### **To Configure in QGC**

* Open QGC
* Click the 3 cogs in top left corner

![](../.gitbook/assets/qgc-button-1.jpg)

* Select 'Buttons' 
* Tick the box next to the desired button
* Click on drop down to select function
* Repeat for each button 

![](../.gitbook/assets/screenshot-2020-03-16-at-22.35.57.png)

## Hardware Wheel

The hardware wheel is permanently mapped to SBUS channel 5. It can also be configured in Solex TX to Servo output channels 1-16 on the Cube Autopilot, you also have the ability to switch the servo output via a button in Solex TX.

### **To Configure Wheel in Solex TX**

* Open Solex TX App 
* Click 3 line in top left corner
* Select 'Button Mapping' as above
* Click 'Wheel Settings' in the bottom corner

![](../.gitbook/assets/wheel-1.jpg)

* Select the desired servo channel from 1- to 16

![](../.gitbook/assets/wheel-2.jpg)

* Select the PWM output range for your application

![](../.gitbook/assets/wheel-4.jpg)

* Click the 'Enabled' box to activate the output

![](../.gitbook/assets/wheel-5.png)

* Finish by clicking OK and click 'Save Buttons' in bottom corner
* To configure a button to change the wheel servo output configure the button to 'Wheel Settings' 

![](../.gitbook/assets/wheel-6.jpg)

* Click the cog and set new channel and PWM values and click OK and then 'Save Buttons' in bottom corner.  

![](../.gitbook/assets/wheel-7.png)

Once changed the wheel will output on the new selected channel, to return to its original servo output you will need to program one button function to 'Clear Wheel Settings' as shown above.

