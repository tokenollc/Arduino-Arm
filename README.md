Tuesday, 2/26/19


Terminology: Raspi = Raspberry Pi


#### Preliminary Description of Intended Work:

**Take arduino and modify firmware so that is accepts control inputs over USB.**

We are going to create application on the Raspberry Pi which interfaces with the arduino over USB. This application runs on the Raspi itself.

There is a webapp which communicates with this application on the Raspi to set the values of these control input values using sliders. (Read and write values) (This will probably be written in [ReactJS](https://reactjs.org/))

We are going to set up the Raspi so that it uses [MJpeg](https://en.wikipedia.org/wiki/Motion_JPEG) streaming from the camera sensor. We are then going to make a view in the [ReactJS](https://reactjs.org) webapp which displays this stream.

And **just to reiterate,** our current quote is $1,855 assuming you're giving us money to buy the parts for you. The quote explaining the hourly breakdown is attached in the email.

The cost would be charged half up front, which would work out to $927.50 = ~$925.

If when we start working on the project we find out that our estimates were inaccurate in some significant way, we will immediately stop work and contact you to re-evaluate what we should do. If you're at Hexlab on the day we're doing this work, it'll be even easier to follow up. However, this is not necessary at all and you should do whatever seems best for your needs/schedule. We will do what works.

I would also like to ask again for more information about your timeline and a HARD deadline for the work we're doing to be finished, so that you're able to get the project moving on your desired schedule. I remember you telling Stefan and I something like March 20th being the day you present your report? I would like to have these details ironed out and recorded.

Stefan and I are preliminarily thinking that we will give you three full hours of over the phone (or email) follow-up time. 

We will take a little bit of time pro bono to consult with you or figure out how you should proceed with the project **after** we have finished all our proposed work. We don't normally do this but it feels right for your context as a client. We reserve the right to revise this offer as the project progresses.


#### BOM:

*   [Raspi 3 B+](https://www.amazon.com/dp/B07BDR5PDW/ref=sr_1_3?keywords=raspberry+pi&qid=1551337154&s=gateway&sr=8-3)
    *   Did you need the Raspi screwed onto the base next to the Arduino, or did you want to have it in a case so you can place it wherever you need to?
    *   We have the kit that comes with [This](https://www.amazon.com/dp/B07BC7BMHY/ref=sr_1_5?keywords=raspberry+pi+3+b%2B+case&qid=1551337744&s=gateway&sr=8-5) Raspberry Pi case and will provide it to you for free because we don't really need it.
*   MicroUSB to USB-A cable (this should be the correct length to attach the Raspi to the Arduino board wherever you decide that the Raspi should be located.) If you need clarification on what this means, please feel free to call or ask via email!
*   [2A power supply (for Raspi)](https://www.amazon.com/dp/B00MARDJZ4/ref=sr_1_3?keywords=raspberry+pi+charger&qid=1551338032&s=gateway&sr=8-3).
*   [Camera Sensor](https://www.amazon.com/dp/B01G01JJJ0/ref=sr_1_9?keywords=raspberry+pi+camera+sensor&qid=1551338086&s=gateway&sr=8-9) (chose this one because it needs to be specifically Raspi compatible)
*   Long camera cable (NEEDS to be long enought to reach from the mounting point to the raspi, which is gonna be located somewhere else).
    *   Exercise for the customer: grab a string and run it from the camera sensor position to wherever the Pi would be located in the intended setup.