UPDATE (OCTOBER 2024):

NOW HAS JOYCON CONNECTOR & OFFICIAL CHARGER USEAGE WITH BETTER DESIGN
NOW ADDED A BETTER LCD FOR DISPLAYING PERCENTAGE & BATTERY VOLTAGE
ONCE DESIGN IS FINAL I WILL UPLOAD THE GERBERS & STL'S

# Switch_Battery_Charger
Charger board for the Switch battery - Standard & Lite

Free open source Battery charger for the switch & lite battery.

Based around the popular TP4056 battery charger.  Idea comes from Micro Mage Repair & developed
within Joey Does Tech Discord.

This was created to help not only myself but others in charging the standard Switch & Switch Lite
battery when you are workingg on the main boards for repairs, so that you dont need to use a donor
board to charge the battery which can be a pain with two shells open.

![OpenXenium Assembled](https://github.com/victor7376/Switch_Battery_Charger/blob/main/Images/Charger.jpg?raw=true)

#######################################################################################

The charger can be wired up to 2 different Battery indicators via the two OUTPUT pads above the Switch Battery connectors:

18650 Li-po Lithium Battery Capacity Indicator Module Meter (shown)

Or

Diy Kits LM3914 3.7V Lithium Battery Capacity Indicator 

The first is just a drop in module, but you will need to add a switch between the module & the charger.

The 2nd verssion is a kit that you make yourself & you will need to calibrate it first to a FULL battery, then
to a depleted battery for the 10 bar indicaator to recognise the percentage.  Please follow the instructions that
come with this indicator kit.  But I will say that this kit is a hit and miss on how close it is in showing hte percentage
unlike the drop in module.

Drop in Module:
Red Boarder Flashing = 2.9 - 3v = EMPTY
Red Boarder = 3.1 - 3.2V
1/4 LED = 3.3 - 3.4V
2/4 LED = 3.5 - 3.6v
3/4 LED = 3.7 - 3.8v
4/4 LED & Reb Boarder = 3.9 - 4.2v = FULL

10 BAR Indicator:
1 BAR = 3.2v
2 BAR = 3.3v
3 BAR = 3.4v
4 BAR = 3.5v
5 BAR = 3.6v
6 BAR = 3.7v
7 BAR = 3.8v
8 BAR = 3.9v
9 BAR = 4.0v
10 BAR = 4.1v

#######################################################################################

The screw terminals & USB-C port can only be used separately, do NOT use them at the same time.

The charger supports 5V 1AMP.

I've included BOM, Gerbes & STL's for the chaarger so that anyone can make one themselves.

I highly recommend JLCPCB as they can install the USB-C port for those that are not keen on installing it themselves.
