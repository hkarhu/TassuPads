# Tassu DDR Pads
This is an old tutorial for cheap-ish hard/durable DDR pads I started writing in 2009 but never really finished it. I decided to release a draft so perhaps if someone decides to tackle the construction, I can finish this tutorial by patching the missing details and answering the questions.

So, here it is:


People have been requesting me to write this tutorial on how to construct one of these DDR-pads I have designed. So this tutorial will teach you how to construct a hard DDR-pad without the controller logic. Though there will be instructions how to connect the pad to a controller logic, but you need to get the logic part from elsewhere until I release the schemes for building your own.

```
if( TLDR && skill_level > enough){
	Look at the images and use your imagination.
} else {
	continue;
}
```

Building can be divided into smaller sections that can be done independently, so if you have some friends to help you out, you can reduce the building time with many hours. Of course, with the proper (industrial) tools, you can also reduce the time drastically. Normally it will take 6-8 hours to build one by yourself. With proper tools, one person can make one pad in something like 4-5 hours. If you happen to have experienced building team of three or more persons and the proper toolset, I think you can manage with 2 hours. The cost will be something from 50€ to 80€, which is not bad for a hard pad.


\[IMAGE\]
The finished product will look something like this.


Read the whole tutorial before you go shopping. You will save some money by making your own choises on some materials. Use your imagination if you encounter any problems, that's what I have been doing. Your pad might even end up being better than these ones. :P


### 1\. Needed tools and items

#### Tools:
\[to be inserted\]

1. Screwdriver
2. Drill
3. Sanding paper

#### Materials:

1. MDF
	- I used MDF for the base as normal plywood tends to curve over time. The moisture within the plywood won't get distributed evenly as the other side is covered. My previous plywood pads were rather unstable depending on the humidity.
2. Screws
	- To hold the panels in place. Buy these after you know the total depth of your pad.

3. Washers
	- To hold the panels up. Can also be used for getting the signal to the contact surface. I used 6x25x1,25mm ones.

4. Cooking(aluminium) foil and thinned wood/universal glue
	- To form the GND-plane. I cannot really think of a better material for this.
5. Duct tape
	- It will be used to keep the washers and the wires in place. It also isolates the GND from the contact surfaces. Never go without it.
6. Wheaterstripping
	To keep the signal wires touching the panel. If you change the design a bit, this might not be needed.
7. CAT5 cable
	- To get the signals out from each pad. You might allready have some of these, with broken clips. This is good opportunity to get yourself a new one and sacrifice the old for science!
8. Acrylic/polycarbonate sheet (~3mm)
	- For the panels and contact surface. If you choose to make the contact surface from another material, you can actually reduce the cost quite a bit by just getting 9 of these instead of 18.
9. Aluminium tape
	- For the contact surface, if you decided to use the acrylic or other non-conductive material.
10. A3 sized paper sheets and some spraypaint
	- For your artwork.


#### My Shopping List


||Amount|Item|Price(€)|
|--- |--- |--- |--- |
|1|1 pcs|780x780mm 10mm MDF|9.00|
|2|36 pcs|Screws|2.07|
|3|36 pcs|Washers|1.89|
|4|~ 2.5 m|Cooking foil (aluminium)|1.25|
|5|~ 10 m|Duct tape|3.95|
|6|~ 2 m|Open Cell Weatherstripping|1.29|
|7|~ 0.5 dl|Water based glue|1.20|
|8|~ 1 m|CAT5 Cable|~3.00|
|9|~ 30 cm|10 wire ribbon cable|~1.00|
|10|18 pcs|260x260mm 3mm Acrylic|55.00|
|11|> 0.6 m2|Spraypaint|2.99|
|12|9 pcs|A3 sized paper sheets|2.99|
|13|~ 10 m|Aluminium tape|3.99|




### 2\. Panels

The panels are just for making a contact between the signal wire and the ground plane. They can be any material that is durable enough and has a conductive bottom layer. I chose two pieces of plexiglass with some paper and aluminium tape to provide the artwork and conducting surface. The bottom layer can actually be replaced with something cheaper, like thin metal (probably aluminium) sheet. It just needs to be conductive and able to bend a bit without breaking. Also it should be strong enough to keep its form even after stepping on it few thousand times.

The following picture (2.1) is probably most useful one if you just want to copy my technique. It basically explains the whole idea. The conductive surfaces are pretty close to each other, but only pressure will trigger clear enough signal to be detected by the controller. The washers can be even thinner for more sensitivity.

![2.1 Panel overview](/images/panel2.png)

#### 2.1 Layering explained.

You should go making the top panels first. Because if you fail something, you can always use the failed pieces as one of the the lower panels. All panels have 4 holes, ~5mm in diameter, one in each corner. Use your washer to measure out enough from the corners. Something like 15-25mm should be enough. It doesn't have to be perfect, just close enough to look good. I just used my measuring eye to get the holes into the right positions. Also with proper drilling  equipment, you can do several pieces at a time.

![](/images/img_1495.jpg)

![](/images/img_1499.jpg)

### 3\. The Base

![](/images/overview.png)
#### 3.1 An overview.

The base is made out of MDF. MDF is good because it doesn't bend much even if exposed to moisture. Plywood ones tended to bend up or down depending on the humidity and sometimes it keeps the bent form. MDF can bend a little during the gluing phase, but it will return to it's original shape once dry.

On the MDF there's a layer of cooking foil which will provide the GND for the contacts. This is glued onto the MDF with thinned glue. I used normal water based glue and added water to it until I got thin enough solution for painting the glue onto the MDF.

![](/images/img_1481.jpg)

![](/images/img_1483.jpg)

![](/images/img_1485.jpg)

The area needs to be divided into 9 sections. This can be done by dividing each edge into 3 sections of 26cm and then drawing lines between the corresponding marks on the opposite edges. I used duct tape to make this "first grid" but I think you can get better results and thinner pad by using just a marker.

![](/images/img_1487.jpg)

After you know where the pads will be, place pieces of wheater strips to positions where you think the contact will be sufficient for the upper module. I used this kind of formation (x.x), just to make it as symmetric as possible.

Before continuing, you should have the 9 top panels ready so you can measure the accurate places for the washers.

Place the 9 top panels onto the pad and number them, so you can get them back into the places they were. Align them so that the lines are even and the edges look good. Then mark where the holes are located with a marker, or a screwdriver.

![](/images/img_1506.jpg)

After you have clear marks on the MDF, place the washers on the marks. Tiny drops of superglue will help if you have troubles keeping them in place. If you are planning to use the washers as signal carriers, you might need to cut pieces out from the aluminium around the washers. Then the screws won't make contact between the washer and the GND plane.

Next you will need the stripped wires.

A grid made out of duct tape will help to keep the washers and wires in place. It will also reduce the possibility for false presses.

Easiest way to make the grid is to start from one corner and move towards the opposite corner as explained in (x.x).

### 4\. Electronics

I used the wheater stripping for keeping the signal wire pressed against the conductive surface of the panel. The panel just presses against the stripped wire when in place (not pressed yet). When the panel is pressed, it brings the signal wire it touches and the GND plane to contact and the controller detects the signal. The weather stripping can be substituted with something else or you can modify the panel freely, as long as it is conductive. One idea is to bring the signal up to the panel with the washers, but I haven't tested it yet. Just remember to keep the individual panels isolated enough so they won't relay others' signals.

![](/images/panel1.png)

#### 4.1 Wiring example.

The above image (4.1) explains the wiring for the exit point. Of course you would have


### 5\. Putting it all together
