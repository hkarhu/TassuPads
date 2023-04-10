# Tassu DDR Pads
DDR pads from 2009

 

People have been requesting me to write this tutorial on how to construct one of these DDR-pads I have designed. So this tutorial will teach you how to construct a hard DDR-pad without the controller logic. Though there will be instructions how to connect the pad to a controller logic, but you need to get the logic part from elsewhere until I release the schemes for building your own.  

```
if( TLDR && skill_level > enough){  
    Look through the images and use your imagination.  
} else {  
    continue;  
}  
```
  
Building can be divided into smaller sections that can be done independently, so if you have some friends to help you out, you can reduce the building time with many hours. Of course, with the proper (industrial) tools, you can also reduce the time drastically. Normally it will take 6-8 hours to build one by yourself. With proper tools, one person can make one pad in something like 4-5 hours. If you happen to have experienced building team of three or more persons and the proper toolset, I think you can manage with 2 hours. The cost will be something from 50€ to 80€, which is not bad for a hard pad.  
  

\[IMAGE\]  
The finished product will look something like this.  

  
Read the whole tutorial before you go shopping. You will save some money by making your own choises on some materials. Use your imagination if you encounter any problems, that's what I have been doing. Your pad might even end up being better than these ones. :P  
  

### 1\. Needed tools and items

Tools:  
\[to be inserted\]  
  
Screwdriver  
Drill  
Sanding paper

[TABLE1]


My Shopping List  


[TABLE2]
  
  
  

### 2\. Panels

The panels are just for making a contact between the signal wire and the ground plane. They can be any material that is durable enough and has a conductive bottom layer. I chose two pieces of plexiglass with some paper and aluminium tape to provide the artwork and conducting surface. The bottom layer can actually be replaced with something cheaper, like thin metal (probably aluminium) sheet. It just needs to be conductive and able to bend a bit without breaking. Also it should be strong enough to keep its form even after stepping on it few thousand times.  
  
The following picture (2.1) is probably most useful one if you just want to copy my technique. It basically explains the whole idea. The conductive surfaces are pretty close to each other, but only pressure will trigger clear enough signal to be detected by the controller. The washers can be even thinner for more sensitivity.  
  

![Panel overview](/images/panel2.png)
#### 2.1 Layering explained.

  
You should go making the top panels first. Because if you fail something, you can always use the failed pieces as one of the the lower panels. All panels have 4 holes, ~5mm in diameter, one in each corner. Use your washer to measure out enough from the corners. Something like 15-25mm should be enough. It doesn't have to be perfect, just close enough to look good. I just used my measuring eye to get the holes into the right positions. Also with proper drilling  equipment, you can do several pieces at a time.  
  

[![](img_1495_tn.jpg)](img_1495.jpg)

[![](img_1499_tn.jpg)](img_1499.jpg)

  

  

  
  
  
### 3\. The Base

[![](overview_tn.png)](overview.png)  
#### 3.1 An overview.  

  
The base is made out of MDF. MDF is good because it doesn't bend much even if exposed to moisture. Plywood ones tended to bend up or down depending on the humidity and sometimes it keeps the bent form. MDF can bend a little during the gluing phase, but it will return to it's original shape once dry.  
  
On the MDF there's a layer of cooking foil which will provide the GND for the contacts. This is glued onto the MDF with thinned glue. I used normal water based glue and added water to it until I got thin enough solution for painting the glue onto the MDF.  
  

![](img_1481_tn.jpg)  

![](img_1483_tn.jpg)  

![](img_1485_tn.jpg)  

  

  

  

  
The area needs to be divided into 9 sections. This can be done by dividing each edge into 3 sections of 26cm and then drawing lines between the corresponding marks on the opposite edges. I used duct tape to make this "first grid" but I think you can get better results and thinner pad by using just a marker.  
  
\[IMAGE\]  
  
After you know where the pads will be, place pieces of wheater strips to positions where you think the contact will be sufficient for the upper module. I used this kind of formation (x.x), just to make it as symmetric as possible.  
  
  
  
Before continuing, you should have the 9 top panels ready so you can measure the accurate places for the washers.  
  
Place the 9 top panels onto the pad and number them, so you can get them back into the places they were. Align them so that the lines are even and the edges look good. Then mark where the holes are located with a marker, or a screwdriver.  
  

[![](img_1506_tn.jpg)](img_1506.jpg)  
  

  
After you have clear marks on the MDF, place the washers on the marks. Tiny drops of superglue will help if you have troubles keeping them in place. If you are planning to use the washers as signal carriers, you might need to cut pieces out from the aluminium around the washers. Then the screws won't make contact between the washer and the GND plane.  
  
Next you will need the stripped wires.  
  
A grid made out of duct tape will help to keep the washers and wires in place. It will also reduce the possibility for false presses.  
  
Easiest way to make the grid is to start from one corner and move towards the opposite corner as explained in (x.x).  
  
  
  
  

### 4\. Electronics

I used the wheater stripping for keeping the signal wire pressed against the conductive surface of the panel. The panel just presses against the stripped wire when in place (not pressed yet). When the panel is pressed, it brings the signal wire it touches and the GND plane to contact and the controller detects the signal. The weather stripping can be substituted with something else or you can modify the panel freely, as long as it is conductive. One idea is to bring the signal up to the panel with the washers, but I haven't tested it yet. Just remember to keep the individual panels isolated enough so they won't relay others' signals.  

### [![](panel1_tn.png)](panel1.png)

#### 4.1 Wiring example.

  
The above image (4.1) explains the wiring for the exit point. Of course you would have  
  
  

### 5\. Putting it all together
