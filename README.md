# #243 USB-C Power Delivery (PD) Charger Redesign
### My new phone is more sophisticated when it comes to charging requirements   
#### <ul>- and my Smart Phone Charger can't cope.</ul>

![vlcsnap-2022-04-20-13h12m07s993](https://user-images.githubusercontent.com/20911308/164229162-02005c98-6012-44a3-b5b5-ee93acb96452.png)  

[![JLCPCB-Purple](https://user-images.githubusercontent.com/20911308/159024530-3e083ca1-fea4-4ba9-97d3-a3af3fb979d2.png)](https://www.jlcpcb.com/cem)  

So, does *anyone* know about USB-C PD protocols?  

For 3-4 years I've used my Smart Phone Charger to protect the battery from overcharging. The phone sends the current battery charge to my Arduino Mini controller which decides whether to charge or stop charging - all well before the 100% mark is reached. 

But now I've got a USB-3 PD (Power Deliver) phone that uses adaptive charging rates which would destroy the Arduino Mini in an instant. A redesign is called for. But how to get those sockets wired up? 24 connections on a single USB socket! No way!  

The main problem is that the USB-C (PD) protocol requires that not only are the power lines connected, but also the data lines so that the phone can negotiate with the charger what voltage and current it will get.

The voltage can be anything from 5v to 20v with currents ranging from zero to 3A - a maximum of 33W of power that charges up my phone in minutes. Quite a difference from my old, 5v @ 1A phone.

#### If you know the answers I ask in the video please do let me know!

### My new phone
![Xiami Redmi Note 10 ](https://user-images.githubusercontent.com/20911308/164232561-ba25b48e-c87f-4022-9067-161095e5a3be.jpg)  
Xiaomi Redmi Note 10 Pro - Smartphone 6+128 GB, 6,67” 120Hz AMOLED DotDisplay, Snapdragon 732G, 108MP Quad Camera, 5020mAh, Onyx Gray (UK Version + 2 Years Warranty)  
https://amzn.to/3OmIF1D  
Wireless carrier	Unlocked for All Carriers  
Included components	Camera  
Brand	Xiaomi  
Model name	Redmi Note 10 Pro  
Battery power	5020  
Cellular technology	4G  
Other camera features	Rear, Front  
Memory storage capacity	128 GB  
Connectivity technology	Bluetooth, Wi-Fi, Infrared, USB, NFC  
Colour	Onyx Gray  
https://amzn.to/3OmIF1D  

► List of all my videos
(Special thanks to Michael Kurt Vogel for compiling this)  
http://bit.ly/YouTubeVideoList-RalphBacon

► If you like this video please give it a thumbs up, share it and if you're not already subscribed please consider doing so and joining me on my Arduinite (and other μControllers) journey

My channel, GitHub and blog are here:  
\------------------------------------------------------------------  
• https://www.youtube.com/RalphBacon  
• https://ralphbacon.blog  
• https://github.com/RalphBacon  
• https://buymeacoffee.com/ralphbacon  
\------------------------------------------------------------------

