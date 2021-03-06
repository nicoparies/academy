---
id: injection
title: Build an Injection Machine
sidebar_label: Injection
---

<div class="videocontainer">
  <iframe width="800" height="400" src="https://www.youtube.com/embed/qtZv96ciFIU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<style>
:root {
  --highlight: #f29094;
  --hover: #f29094;
}
</style>

# Build an Injection Machine

<div class="videoChapters">
<div class="videoChaptersMain">

### Title

The injection machine has a quick production output with high precision, while it takes a little bit more effort in the beginning with designing and making a mold, you’ll be amazed at what you can create. Shredded plastic enters the hopper and is heated and pressed through a long barrel into your mold. The output colour is often unpredictable when mixing colours in the barrel, allowing for beautiful (and surprising) patterns that can add to your one-of-a-kind products.


> Tip: tippy tip

</div>
<div class="videoChaptersSidebar">

### Video Chapters

- 00:07 Introduction
- 00:43 Hopper
- 02:01 Barrel
- 03:58 Nozzle
- 04:53 Framework
- 06:55 Electronics
- 10:30 How it works


</div>
</div>

![PP Image](assets/injection.jpg)

# 📓 Technical information

📓 Type | Injection
--- | ---
💎 Version | 1.0
💰 Cost in Netherlands | €300
💰 Scrap cost in Netherlands | €131
⚖️ Weight | 23 kg
📦 Dimensions | 830 x 700 x 1300 mm
⚙️ Barrel volume | 150 cm³
⚙️ Leverage | 3
⚙️ Injection pressure | 45 bars
⚙️ Max mould size | 360 x 330 mm
⏱ Injections p/h | 10 - 30    
🔌 Voltage | 220V    
⚡️ AMP | 2.6A

# 🛠 Required machinery & skills

<img style="margin-left: 0;" src="../assets/injection_cad.jpg" width="300"/>

## Machines needed

- Drill press
- Welding machine (not specific)
- Angle grinder


## Skills needed

- Welding (intermediate) <i>icon/illustrations needed for levels</i>
- Assembling (intermediate)
- Electronics (intermediate)

# 🛠 Electronic box

Explanation of electric component roles

<b>PID Controller:</b> the brains of the machine where you can set your desired temperatures. It will send power to the heaters until PV (point variable) matches the SV (set value). It does this using readings from the thermocouple and the SSR.

<b>SSR:</b> the Solid State Relay is an electronic ‘switch’ that opens and closes depending on the signal it receives (from the PID).

<b>Thermocouple:</b> basically a thermometer.

<b>Band heater:</b> heating element that fits around a pipe.

<b>Power switch:</b> mechanical switch.

<b>LED indicator:</b> LED that will shine with power (often found with Power switch).

<b>Power cable:</b> common household power cable.

<i>< Schematic link > </i>

[Jerry’s BIG ELECTRONICS topic](https://davehakkens.nl/community/forums/topic/the-big-electronics-topic/)

# 🛠 Tips & tricks while making

- Take care welding around the hopper tabs. The heat can easily distort the barrel, ruining that perfect slide.
- Adding an insulated barrel cover will increase efficiency and reduce the chances of the user accidentally touching the barrel when hot.  
- When building, the lever is stronger as a circular profile when compared to a square profile. Which will reduce the likelihood of bending it.


# ♻️ Input & Output


<b>Type:</b> HDPE, LDPE, PP, PS<br>
<b>Output:</b> 10-30 injections per hour depending on mould<br>

# ⚙️ Run & maintain

<br>
You can create beautiful, consistent products with the injection machine very efficiently, but it takes a little work upfront - making moulds, for example. The more precise the mould, the easier and more streamlined your production will be.

Some quick tips:

1. Depending on the plastic type, you’ll need one or sometimes two people to pull down the lever.

2. Before injecting into the mould, make sure the plastic in the barrel is completely melted in order to fill all areas of the mould. To achieve this, run the machine a few degrees higher than usual to ensure the plastic is fully molten.

<br>

### How to operate the injection machine

### Startup

1. Turn the machine on and set the temperature to 20° more than the desired temperature. Make sure the lever is at its lowest position.
2. Wait for at least 20 minutes.
3. Turn the temperature down and fill the barrel with the desired plastic.
4. Wait another 15 minutes for the plastic to melt - the first batch of plastic is used to rinse the machine and to get rid of plastic from previous sessions.
5. Press the first batch of plastic out of the machine.
6. The machine is now ready for production!


### Production

1. The machine is now warm and ready to use with your moulds
2. Fill the barrel with your chosen plastic.
3. Press the lever in the barrel.
4. Pull the lever up every 5 to 10 minutes and add more plastic.
5. Wait at least 10 minutes.
6. Now for the mould - unscrew the brass screw at the bottom.
7. Screw in the mould (be quick or plastic will start to flow out!)
8. Once the mould is secured to the machine pull the lever down as far as possible, don’t be scared to give it a lot of pressure, it can easily hold 100kg.
9. Unscrew the mold from the machine.
10. Pull the lever up.
11. Screw the brass screw in place.
12. Fill the machine for a new product.
13. Let the mould cool.
14. Open the mould once it is cooled down.

### Cooldown

1. When you turn on the machine, empty the barrel completely - this makes it easier for the next person using the machine.
2. Leave the machine with the lever all the way down.
3. Turn the machine off.

### Tips & Tricks while using

1. The hotter the plastic the greater the sink marks on the final product.
2. Clean the mould from plastic when still warm, it will be harder to clean later.
3. Use mould release on the mould, it helps with release.
4. Keep the barrel full with plastic at all times, adding a bit of plastic with each injection.
5. When you are finished working with the injection machine, empty the plastic from the barrel.
6. To create an efficient process it is advisable to run the machine for a few hours once it is on - don’t start and stop the machine too often as the process will be very inefficient.




# 🌦 Pros & cons

Pros | Cons
--- | ---
Easy to manufacture     | Process can be tedious
Runs on 220V | Only a small amount of waste recycled
Relatively cheap |
Batch production |

# 🔧 Most common hacks


- [How to Make a Quick Release Mould](https://community.preciousplastic.com/how-to/make-a-quick-release-opening-system-for-injection-moulds)<br>
- [Benchtop Injector](https://davehakkens.nl/community/forums/topic/benchtop-smaller-machines/)<br>
- [Injection Nozzle Refinement](https://davehakkens.nl/community/forums/topic/injectionextrusion-nozzle-refinement/)

# 🔓 Troubleshooting
1. If the plastic is clogging at the end of the barrel and doesn’t come out even when applying higher pressure, raise the temperature of the nozzle heater to fully melt the plastic and release the block.<br>
2. The final product might get stuck to the mould making it hard to release, if this happens gently re-heat the mould to soften the plastic and help release.

# 🙌 Useful Links
- [How-to: Carabiner](https://community.preciousplastic.com/how-to/make-a-carabiner-cnc-or-laser-cut-mould)<br>
- [How-to: Quick Release](https://community.preciousplastic.com/how-to/make-a-quick-release-for-the-extrusion-machine)<br>
- [How-to: Cast Aluminium Moulds](https://www.youtube.com/watch?v=5LhHUBz9uL0)<br>
- [How-to: CNC iPhone Case Mould](https://www.youtube.com/watch?v=ZYFoWP-3MYE)<br>
- [How-to: Geodesic Dome](https://community.preciousplastic.com/how-to/build-a-geodesic-dome)<br>
- [How-to: Precious Plastic Monash Machine](https://www.preciousplasticmonash.com/download-kit)<br>
- [How-to: Handplane](https://community.preciousplastic.com/how-to/make-a-handplane-simple-mould)<br>
- [How-to: Broom Hanger](https://community.preciousplastic.com/how-to/make-a-broom-hanger)<br>
- [The Story Behind the Piranhaclamp](https://davehakkens.nl/community/forums/topic/the-story-behind-the-piranhaclamp/)<br>


# 🌎 Built by the community

![PP Image](assets/ppimage.jpg)
