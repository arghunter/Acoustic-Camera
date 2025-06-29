---
title: "Acoustic Camera"
author: "Armaan Gomes"
description: "A Camera That Sees Sound"
created_at: "2025-05-27"
---
I know the file says created 5/28, but thats because I forgot to upload my entry from 5/27

# May 27th (trust)
I spent a while coming up with plans for the pcb and wiring of the acoustic camera. Not too much progress, mostly just the basics of daisy chaining,some work on the design and not much else.
![image](https://github.com/user-attachments/assets/398f55df-372e-4994-b780-8c332a1bc680)
![image](https://github.com/user-attachments/assets/7d273ed2-24b0-4257-b584-4bafa6ef2447)


**Time Spent: 1h**

# May 31st

**REMEMBER TO CHECK IF YOU NEED tO FLIP THE FPC CONNECTORS**

Ok today I designed the base microphone board schematic. They are pretty simple but this was my first time using kicad. Naturally this meant it took my a very long time to learn. Then I also struggled to find the correct parts and footprints and symbols. I got hte wrong micphone type initally and was so confused by the pin out. Eventually though I think I got it all sorted. I'll prolly make the layout tomorrow or later tonight. Also check fpc connectors.

![image](https://github.com/user-attachments/assets/09d48b6a-132b-4ea5-b8de-ca1a973ad1d0)

**Time spent: 2.5h**

# June 17th
Tomorrow, I suppose that was a joke. Anyway I spent 3.5 hours today assigning fottprints , making footprints and making the initial layout. I cannot believe it is this hard to get footpritns from jlcpcb to kicad, but it worked out in the end. I did the routing but still need to do the copper pour and edge cuts. Not many photos, its kinda just some text and schematic stuff.

**Time spent: 3.5h**

# June 21st
Today I finalized the design of the microphone board by adding test points and finalizing dimensions. To be honest, most of the work was procedural so not much to add here. However, referencing May 31st, it turns out that I DO need to flip the FPC connectors.
![image](https://github.com/user-attachments/assets/692bc256-3d1e-4eac-8715-50b82370b3fb)

**Time spent: 1h**
# June 22nd
Today I designed the left right connectors for the setup.The wiring is the same as the notebook sketches above. Its pretty simple. It uses LVDS and buffers to maintain signal coherance over long distances.
![image](https://github.com/user-attachments/assets/2e788848-cb68-4e25-bea0-068d3084501e)
**Time spent: 2.5h**

