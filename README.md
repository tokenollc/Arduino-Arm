Tuesday, 2/26/19


Today Mike called Stefan with a project.

A client has a robot arm powered by some Arduino, and he wants to be able to interface with it over bluetooth.

Made to control via USB.

In theory, the project would involve making a bluetooth module interface with an Arduino over serial and so some of the arduino code would have to be rewritten for that.



10 days for potty project

3D print through Bennett? Client will pay

Figure out schedule for tomorrow

3pm or before noon.



Meeting started at 6:30pm
Ended at 8:30pm. We charged him only the one hour.

*   Needs board for application
*   Should come back with a estimated number of hours and follow up at a certain interval.
*   Arduino is very under-powered for the camera.
*   Wireless cameras usually have an antenna. Is that a problem? Clarify this statement with Stefan afterward. Are Analog cameras ok?
*   Single camera so only have to worry about one channel.
*   Arduino doesn't have the memory for the camera.
*   BLE probably required: BLE removes a requirement for approval from Apple to control via BlueTooth.
*   Looking at Android phone and windows 10 laptop.
*   Transmitting signals from the physical controls to serial, and then getting the bluetooth controls to work. Latter is more work.
*   H264 H265
*   Not much we can do with the stream on the board level.
*   Figure out what the budget is, over the phone if necessary.
*   What is MDNS? Multicast DNS
*   May need to build 3rd party discovering service if we were to do a wifi camera.
*   Get him added on slack or figure out how we're going to stay in contact with him.
*   Get phone number.
*   Make clear BOM is charged to client.
*   Having over wire and over bluetooth makes things more complicated.
*   Motors might need to be re-allocated.
*   Do we need to perform bitbanging?
*   Report by anytime tonight.
*   Presentation is March 20th or so.
*   Can email the code to us
*   UART is RS485 compatible, but might need to add more chips.
*   Would be much better if everything is controlled via the power supply, battery powered for the servo is not ideal.
*   Does the windows computer have BLE?
*   Client has a samsung Galaxy S5: See if this phone would work for the Android application.
*   BLE became adapted around 2016 mainstream by Android.
*   Classic bluetooth to serial wouldn't have these problems.
*   10-20 feet reach? We should try to figure out for the client what it would be, but say that the result is not gauranteed.
*   Research einit.
*   Set estimates by the end of the day and get back to the client.

#### Bare Minimum:

*   Camera
*   Bluetooth communication

#### Options:

*   Bluetooth option:
    *   Hardware:
        *   Replace usb-serial with bluetooth-serial
    *   Software:
        *   Figure out how to interface with android and windows.
*   Wifi Option:
    *   Possibly 5 days of work.
    *   With this option we would have to create a separate AP bridge, and the transmission of signals would be more complicated because you'd have to have packet acknowledgement and we would have to program this ourselves.
        *   See if this is still the case. Stefan hasn't touched an 8266 in a VERY long time.
    *   Arduino with built in wifi-is this an option? Needs to be researched.
    *   Yun was just a shitty Arduinio
    *   Raspberry Pi: give one day budget.
    *   List the bill of materials for the client by the end of the night.
    *   In addition to the work we do we should try to give him a list of people who might be able to help him.
    *   Raspi camera sensor
    *   Pi powered separately
    *   Client gave us $100
*   Expensive: board control, servo applications, and mobile apps:


#### Preliminary Description of Intended Work:

Take arduino and modify firmware so that is accepts control inputs over USB.

We are going to create applicatoin on the raspberry pi which interfaces with the arduino over USB. This application runs on the Raspi.

There is a webapp which communicates with this application on the Rasi to set the values of these control input values using sliders. (Read and write)

We are going to set up the Raspi so that it uses MJpeg streaming from the camera sensor. We are then going to make a view in the webapp which displays this stream.

And just to reiterate, our current quote is $1,855 assuming you're giving us money to buy the parts for you. The quote explaining the hourly breakdown is attached in the email.

The cost would be charged half up front, which would work out to $927.50 = ~$925

If when we start working on the project we find out that our estimates were inaccurate in some significant way, we will immediately stop work and contact you to re-evaluate what we should do. If you're at Hexlab on the day we're doing this work, it'll be even easier to follow up. However, this is not necessary at all and you should do whatever seems best for your needs/schedule.

I would also like to ask again for more information about your timeline and a HARD deadline for the work we're doing to be finished, so that you're able to get the project moving on your desired schedule. I remember you telling Stefan and I something like March 22nd being the day you present a report? I would like to have these details ironed out and recorded.

Stefan and I are preliminarily thinking that we will give you three full hours of over the phone (or email) follow-up time. We will take a little bit of time pro bono to consult with you or figure out how you should proceed with the project after we have finished all our work. We don't normally do this but it feels right for your context as a client. We may revise this proposal as the project progresses.





Terminology:
Raspi = Raspberry Pi

#### BOM:

*   [Raspi 3 B+](https://www.amazon.com/dp/B07BDR5PDW/ref=sr_1_3?keywords=raspberry+pi&qid=1551337154&s=gateway&sr=8-3)
    *   Did you need the Raspi screwed onto the base next to the Arduino, or did you want to have it in a case so you can place it wherever you need to?
    *   We have the kit that comes with [This](https://www.amazon.com/dp/B07BC7BMHY/ref=sr_1_5?keywords=raspberry+pi+3+b%2B+case&qid=1551337744&s=gateway&sr=8-5) Raspberry Pi case and will provide it to you for free because we don't really need it.
*   MicroUSB to USB-A cable (this should be the correct length to attach the Raspi to the Arduino board wherever you decide that the Raspi should be located.) If you need clarification on what this means, please feel free to call or ask via email!
*   [2A power supply (for Raspi)](https://www.amazon.com/dp/B00MARDJZ4/ref=sr_1_3?keywords=raspberry+pi+charger&qid=1551338032&s=gateway&sr=8-3).
*   [Camera Sensor](https://www.amazon.com/dp/B01G01JJJ0/ref=sr_1_9?keywords=raspberry+pi+camera+sensor&qid=1551338086&s=gateway&sr=8-9) (chose this one because it needs to be specifically Raspi compatible)
*   Long camera cable (NEEDS to be long enought to reach from the mounting point to the raspi, which is gonna be located somewhere else).
    *   Exercise for the customer: grab a string and run it from the camera sensor position to wherever the Pi would be located in the intended setup.


#### Payment Options:

*   PayPal
*   Credit Card
*   Venmo
*   Zelle
*   Check


#### Potential Contacts For Future Help:

*   Miguel Guerrero
    *   Sophomore Electrical Engineering @ CSUN
    *   Ph#: 8187912206
    *   miguel.guerrero.327@my.csun.edu


#### Things to give Juan (cc Mike and Stefan)

*   BOM (with links). Chk.
*   Short description of intended work. Chk.
*   Quote. Chk.
*   List all possible payment methods. Chk.
*   State intent to give potential contacts to the client following completion of work. Chk.
*   Re-iterate that project would be half up-front. Chk.
*   State that if we find out engineering hour estimates were wrong we will immediately communicate with the customer and figure out what he wants to do. Chk.
*   Request reiteration of the HARD deadline, gauge his availability and figure out what days he could come to the valley and if he'd like to sit with us on the day(s) that we do most of the work. Chk.
*   Give him a certain amount of hours of free followup time, maybe cap it at 3 hours. Chk.