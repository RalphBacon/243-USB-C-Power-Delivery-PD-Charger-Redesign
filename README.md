# #243 USB-C Power Delivery (PD) Charger Redesign
### My new phone is more sophisticated when it comes to charging requirements   
#### - and my Smart Phone Charger can't cope.

![vlcsnap-2022-04-20-13h12m07s993](https://user-images.githubusercontent.com/20911308/164229162-02005c98-6012-44a3-b5b5-ee93acb96452.png)  

[![JLCPCB-Purple](https://user-images.githubusercontent.com/20911308/159024530-3e083ca1-fea4-4ba9-97d3-a3af3fb979d2.png)](https://www.jlcpcb.com/cem)  

So, does *anyone* know about USB-C PD protocols?  

For 3-4 years I've used my Smart Phone Charger to protect the battery from overcharging. The phone sends the current battery charge to my Arduino Mini controller which decides whether to charge or stop charging - all well before the 100% mark is reached. 

But now I've got a USB-3 PD (Power Deliver) phone that uses adaptive charging rates which would destroy the Arduino Mini in an instant. A redesign is called for. But how to get those sockets wired up? 24 connections on a single USB socket! No way!  
