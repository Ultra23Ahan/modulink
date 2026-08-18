---
title: 'ModuLink'
author: 'Ahan Das'
description: 'A 90% 3d printed modular system of custom motors, gears, and more.'
created_at: '2026-05-20'
---

# May 20: Did research and did a small test print

So I researched a about planetary gearboxes. I first thought of one like one I found online in the Torospin - Ruco which has a single shaft output by haviing spokes which follow the roation of the planet gears and make the pletary gear system more toroidal but I decided that the motor would make the output faster as if it is fast you can just use gear ratios and make it have more torque. I also learnt about involute gear teeth and how they work(as I thought it would be useful). I decided to use Herringbone gears as they are self aligning and tus the model can be made print-in-place and thus have no assembly required. I made a small test print of the core of the motor, and adjusted the settings to make it as lighter to reduce resistance. Still have to change settings and modify the design.

![](/images/journal/planetary-gearbox-test.jpeg)

**Total time spent: 2 hours**

# May 21: Printed gears, planned, and designed motor core

I printed these gears, for the second last one I heated up the motor and pressed it into the hole, it worked pretty good, but I need to find a better and easier way to hold it in place.

![](/images/journal/IMG_0494.jpeg)

I tried to do a test and heat inserted the motor into one of the planetary gears, it worked but I decided that gears are far better.

![](/images/journal/IMG_0496.jpeg)

I modified the original planetary gear system to be lighter and I added indents for the gears that attach to the motors. The torerances are a bit too tight, so I adjusted the XY hole compensation to -0.035mm and that version is printing right now.

![](/images/journal/IMG_0495.jpeg)

I modeled the motor core in Fusion 360 with motors and gears to see how it will all look when the motor core is assembled. I used negative parts from Bambu Studio to modify it, but this(↓) kept happening but I finally fixed it.

![](/images/journal/failed-mesh-boolean.png)

![](/images/journal/ss-motor-core.png)

Okay, so this is a bit later but the fixed tolerances core is done and the gears almost fit but they don't quite fit. I need to increase XY hole compensation a bit more.

**Total time spent: 4.5 hours**

# May 23: Fixed tolerances, and planned more

I did a bunch of prints and in each print I changed this value called XY hole compensaton, but I thought that making it -ve would make the holes smaller, but it didn't. I realised that after like 3 prints, I could have saved so much filament. Also, I realised later on that I could also have just printed 1 gear instead of everything, and I would have saved a lot more filament. Well, you make mistakes, and you learn from them.

Photos:

Gear fits on motor perfectly

![](/images/journal/23052026/IMG_0498.jpeg)

Final motor gear(3 as I am using 3 motors) and planetary gear, this is when I realised I could just print 1 gear and save filament and time

![](/images/journal/23052026/IMG_0499.jpeg)

Total failed prints today:

![](/images/journal/23052026/IMG_0502.jpeg)

So, my plan for the future is that I will first create a "fast" motor as it is easier to make and I have already planned it out, and then later on I will either make a motor with torque or I will make an attachment for the fast motor that give it torque, but probably the latter.

Note: From now on I will be making folders for each day for the images to keep it more organised and so that I don't have to name them.

**Total time spent: 6 hours**

# May 24: Planned more and decided shaft shape

I didn't do much today(mostly because I have an exam tomorrow) except for choosing a shape to make the shaft, I didn't want to make a round shaft as it would slip, and in the end I chose to make a D shaped shaft(similar to the one below, image is from Google). Tomorrow, I will design the shaft in fusion and print the final motor core design , but I might make some more tweaks though.

![](/images/journal/24052026/2026-05-24_20.06.54.png)

**Total time spent: 1 hour**

# May 26: Designed the shaft and printed the motor core with correct gear tolerances

I designed the shaft in Fusion 360 and I printed the motor core with the correct tolerances for the gear indent. Since the shaft would easily break if it was directly attached to the sun gear by shear force, I designed the shaft to be attached to the sun gear by screw threads, but I think I shuld change the attachment method if this dosent work, as this is hard to do with tolerances.

Fusion 360 design:

![](/images/journal/26052026/ss.png)

Motor core print:

The XY hole compensation made the outer ring's hole bigger too, making the planetary gears loose but I found a way to fix it, I just need to colour paint the outer ring and then the XY hole compensation will not be applied to it. I'm going to print the shaft and new motor core tomorrow.

![](/images/journal/26052026/IMG_0517.jpeg)

**Total time spent: 3.5 hours**

# May 29: Printed the shaft and central gear

Today is my birthday! :D I printed the shaft and the central gear, and tested some tolerances. The best result I got was with putting CA glue to fix it in place. The only problem I have left to resolve now is that the sun gear and planetary gears require different XY hole compensation values, and this model is hard to disassemble and reassemble, so I need to find out a fix for this.

I printed 3 test models for the tolerance testing(below), and I will print the final motor core tomorrow after finding a fix for this problem. Right now I'm thinking to either resolve it in cad or make people disassemble it and have different files, but that gets complicated.

The first model is just the screw and thread, but the last 2 are with CA glue. The last one with the black mark is the final model for the sun gear.

![](/images/journal/29052026/IMG_0533.jpeg)

**Total time spent: 2 hours**

# June 2: Finished motor core

I did some tolerance testing and I finished the motor core.

The final model I ended up with was just the most simple solution I could think of.
What I did:
I knew the planetary gears and the the sun gear had different XY hole compensation values(0.35mm and 0.175mm respectively), and I knew that the shaft was a teeny bit loose and same for the gear holes. I didn't want to change it in fusion because the model fit perfecty so I just took the mean for the values which was 0.2625mm :P.

Finished motor core:

![](/images/journal/02062026/IMG_0536.jpeg)

Gear fits perfectly!

![](/images/journal/02062026/IMG_0537.jpeg)

Also, now I have decided to make Modulink a full robotics system. I'm thinking to maybe make it a tier 3 project, but idk rn. After making the motor and gears, I will make an 18650 holder. I will also split this project into each of its modules because I need different parts for each module which all need to be shipped separately.

**Total time spent: 2.5 hours**

# June 3: Planned things

I was looking at the motor core and I realised that the shaft's flat part is much more than that of commercially sold motors, and also it isnt completely a D all the way through, it has a round part near where it connects to the sun gear, so I have decided to reduce the flat part of the shaft. Also, the shaft wobbles a bunch and this means that there is more room for error when you apply the CA glue, but I found that it levels flat by itself, so I don't think that should be much of a problem down the line, but I will scale the shaft up slightly to compensate for it.

Pictures of the shaft tilt:

![](/images/journal/03062026/IMG_0542.jpeg)
![](/images/journal/03062026/IMG_0543.jpeg)
![](/images/journal/03062026/IMG_0544.jpeg)

**Total time spent: 0.35 hours**

# June 4: Decisions, choices, and dilemmas

I was thinking about how I could connect the motor core to the shell of the motor, and I thought about connecting it with the motors, and by that I mean I will make a ring that fits aorund the 3 DC motors(place where ring has to go is in img below) and make that connect to the core instead of connecting the ring to the shell as the ring needs to spin for the motors to stay in place.

![](/images/journal/04062026/1.png)

**Total time spent: 0.25 hours**

# June 10: Upgraded shaft

I discovered that the shaft had a weak point(I maaaayyy have dropped an IKEA Skadis on it but we don't talk about that) so I reduced the flat area of the shaft, reduced the amount that the D went, and filleted the part where it becomes a D in order to make it stronger.

Photos:
![](/images/journal/10062026/IMG_0572.jpeg)

Design
![](/images/journal/10062026/ss2.png)

**Total time spent: 0.25 hours**

# June 13: Printed new shaft, motor core is FINALLY over

I printed the new shaft and it fits perfectly as expected, and looks much better and more realistic to actual DC D shafts.

Photos:
![](/images/journal/13062026/IMG_0616.jpeg)
![](/images/journal/13062026/IMG_0617.jpeg)
![](/images/journal/13062026/IMG_0618.jpeg)

**Total time spent: 0.25 hours**

# June 23: Tested finished motor core, planned for the future of the motor

I tested the finished motor core with 1 DC motor, and I observed that it vibrated A LOT, but I think this is mainly due to there only being 1 motor and me holding it in my hand a a bit due to the tolerance of the outer ring. I think 3 would stabilize it when running at the same time, and also this vibration should be gone when the motor is actually connected to something(hopefully - this is an educated prediction, but a prediction nonetheless). I have also decided to make the motor shell a different project, and get the batteries and BMS etc for the motor core as this is the part which will actually do the spinning. It would also not make sense to require electronic components for just the shell, and the reason I am making it a different project is because I need the completed final WORKING motor core to design the shell(you might not understand why as of now, but you will understand after the shell in completed).

I did some research on what batteries to use and at first I thought of using alkaline batteries but I checked the types of batteries(yes, almost EVERY single type) and now had a dilemma between 21700s and 18650s. 21700s are more modern and have more capacity, but 18650s are more readily availabe and most people already own them. I wanted this project to be made as cheaply as possible and that meant going with the more readily available option and thus I decided to use 18650 batteries to run this(and a lot of research on the specific 18650 batteries I will be buying because I don't own them, and yes this contradicts my point of them being fairly common but we don't talk abt that). I am currently divided between using 2 batteries, 3 batteries in a 3S or 3P configuration, and 4 batteries in a 2P2S confoguration. Currently I am not sure, but I will do some research later on(aka tomorrow) and see what the best configuration is.

Motor vibration:
![](/images/journal/23062026/IMG_0634.jpeg)

**Total time spent: 2.5 hours**

# June 24: Selected battery configuration, and did some wiring

I decided to use 2 18650 batteries in a 2S configuration, because I realized that a 2P2S was just too overkill for 3 tiny DC motors, and I don't need more than 45 of continuous runtime, and I don't think anyone else does either, but in care they do I will make battery packs later of various sizes after the first one(which is a 2S). For now, this is not a battery pack, it is only some loose batteries wired, I am going to make a battery holder later on as a seperate project.

I attempted to use KiCad but then realized that I don't know how to use it, tried to learn it for some time, then gave up, and I then proceeded to get stuck on the BMS part because KiCad does not have a BMS component and I did not have the knowledge and patience to figure it out, so I made a wiring diagram(using AI).

I got to here in KiCad:
![](/images/journal/24062026/ss.png)

AI wiring diagram:
![](/images/journal/24062026/ai_wiring.png)

The AI diagram is so much easier to understand than a KiCad one, the motor wiring is off, but I don't really think that affects how you understand how the wiring will be.

**Total time spent: 2.1 hours**

# June 26: Increased sun gear infill, etc stuff

I think this project is finally over, now I just have to make the BOM for the BMS and the batteries.

I found a fatal flaw in the sun gear, it was too hollow so i increased the infill to 45% gyroid to make it stronger. The other gears are fine with less infill.

So this happened
![](/images/journal/26062026/IMG_0640.jpeg)

Hollowness of the sun gear
![](/images/journal/26062026/IMG_0641.jpeg)
![](/images/journal/26062026/IMG_0642.jpeg)

I also updated the 3MF. Currently it's only for Bambu Studio.

**Total time spent: 1.5 hours**

# June 29: Did a bunch of research, started making BOM

I did way too much research on the battery. At first I was thinking of using some random 18650s off of Robocraze which were surprisingly cheap. I looked into it more and found out that the batteries are not ideal for....anything basically except very lowend projects(in a 2S at least). I then looked on Robu and found a plethora(yes, plethora).I couldnt decide between the samsung 30Q and the sony murata vtc6, but I decided the latter as it is(according to the internet and reputable sources I could find) better.
I just CANNOT find a 2S BMS for the battery, but I found one on robu which is out of stock, so I will likely use that.

The BMS I want is the last one of this list:
![](/images/journal/29062026/bmss.png)

Current BOM
![](/images/journal/29062026/WIPBOM.png)

**Total time spent: 4 hours**

# July 4: Finished BOM and thus the project

I did research to find the BMS. I looked everywhere that I knew and had this absolutely genius idea of looking at the forge docs as I had remembered that there was a section about reputable marketplaces that accepted HCB cards. I had already checked Robocraze and Robu, and EBhoot was taken down? I then went to MakerBazar and instantly found it :P. So now I finished the BOM, and I think the project is oficially done now!

![](/images/journal/04072026/ss.png)

The battery holder I selected is currently out of stock, but I presume it will be available soon.

I also decided that the motor shell would have a USB-C port(yes, I have added it to the BOM) so you can charge it directly and then you don't have to use a diferent charger. The only thing I'm unsure about is if the motors will also run while its charging, but that can also been good because if the motors move, they smoothen out the motor core and it runs better overall. Or you can just disassemble the motor core(aka remove the planetary gear system so only the gears turn).

**Total time spent: 1.25 hours**

# July 22: Made finished wiring diagram

So I may have asked AI to make the wiring diagram because idk how to use KiCad and its also too overkill for this simple project and diagram.

![](/images/journal/21072026/wiring.png)

**Total time spent: 0.166 hours**

# July 30: Feedback!!!

So, my project got returned(again) and ace6rings gave me stuff to improve on and re-submit for review.

"Hey! Cool idea, but I have to return this because your project will most likely not work. Planetary gear systems can take multiple input motors at the same time but having multiple on the planet gears won't work. The motors would need to be perfectly synced for the system to not stall and the wires will go all over the place when it runs. Also, use step files instead of stl in your repo and ai generated wiring diagrams are not allowed."

The motor core will work, I tested it, and you are right about the wires going all over the place BUT only if the outer ring dosen't spin. In my motor core, the outer ring DOES spin, letting the motors stay in one place, and let the shaft still run, with the caveat of the outer ring spinning so I have to find a different way to hold the motor core in place inside the shell.

The motors don't need to be perfectly synced, if one motor is slightly too fast more load will be on that motor and the rest of the motors will work fine, making the shaft stable. I also have a balance BMS, which _should_ make them more stable and in sync.

For today I'll only change the stl files into STEP.

![](/images/journal/30072026/stlnowstepfiles.png)
**Total time spent: 0.25 hours**

# August 9: Re-did wiring

So I may have procrastinated a bit.....
I also couldn't find any software which was easy to use and didnt have a learning curve so I had this absolutely transcendent idea to just make it on paper :P

So here is the wiring:

![](/images/journal/09082026/wiring.jpeg)

**Total time spent: 0.166 hours**

# August 18: Made journals more detailed

More Feedback!!!:

"hey, can you add some detail to your journals, especially the research ones?" from vulcan

So I made the journals more detailed, thats about it.
Maybe a bit **too** detailed...
![](/images/journal/18082026/ss.png)
**Total time spent: 0.25 hours**
