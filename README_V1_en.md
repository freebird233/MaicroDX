# MaicroDX V1 Build Guide
This guide provides detailed instructions for building the V1 cabinet. For other cabinet versions, open the corresponding README files in the repository root.


Bill of Materials
-------
Filament used in this project: 1 kg PETG, CNY 18.8
https://mobile.yangkeduo.com/goods.html?ps=Bo90h8nXsj
<br> <br> 
1423 single-core silver-plated wire, 30 AWG (at least 5 m): CNY 4.49
https://e.tb.cn/h.hBCuZG2iKpiAnD6?tk=XCFL4pLFaQ9
<br> <br> 
Original version: Outemu low-profile switches<br> 
Updated print profile: Cherry low-profile red switches (pack of 10), CNY 11<br> 
<br> <br> 
Right-angle OTG adapter (USB-C male to USB-A female): CNY 2.73<br> 
https://mobile.yangkeduo.com/goods2.html?ps=BxALLyKNBC
<br> <br> 
Programmable 9-key USB keypad: CNY 33.37<br> 
https://e.tb.cn/h.hByhHTJPLsIOH7V?tk=ob3u4ppTyxL
<br>


<img width="200"  alt="tb_image_share_1757697274791 jpg" src="https://github.com/user-attachments/assets/2eeb53ed-5334-4e8b-ad33-d457dd837c52" />
<img width="200"  alt="tb_image_share_1757697274791 jpg" src="https://github.com/user-attachments/assets/dd938c2f-1f32-437b-aa07-9bfcfbf8c93e" />
<img width="200"  alt="tb_image_share_1757697274791 jpg" src="https://github.com/user-attachments/assets/683e814b-d544-4d7f-b1e1-092834c6a232" />
<img width="200"  alt="tb_image_share_1757697151349 jpg" src="https://github.com/user-attachments/assets/28892012-82ab-4240-aace-b1e2d40d3281" />

<br>
Paint, brushes, a soldering iron, glue, electrical tape, and other tools and supplies are not included in this list.


<br> 
<br> 
<br> 
<br> 



Step 1
------
<br>

Download the model project files from [Releases](https://github.com/freebird233/MaicroDX/releases) and modify them to fit your device. Consider creating a branch and sharing your build to help others!
<br> 
The 1.0 files are designed to fit within a 180 mm × 180 mm build area, so you can use a small printer such as the Bambu Lab A1 mini! When using an 11-inch tablet, set the game scale to approximately 85%.
    
 

<br> 
<br> 
<br> 

Step 2
------

Open "[新]电控按键.SLDPRT" (the original project filename). The parameters are in the "mipad5" and "camera" sketches in the feature tree on the left. Sketch annotations explain the dimensions, such as length and height. To adjust thickness (width), right-click the relevant feature and edit its parameters. Finally, export the model as STEP, split it again, and arrange the parts on the build plates.
<br> 
Note: Scaling the model also scales all tolerances. Make sure the switch mounting features retain their original dimensions.

<img width="720"  alt="1756996362818" src="https://github.com/user-attachments/assets/24f96f36-5d1b-4a57-8a78-6013c7cfef21" />

<br> 
<br> 
<br> 
<br> 

Step 3
------

Print all model files with 3 wall loops, 5% infill, and a 0.10 mm layer height.


<img width="720" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/ecc5b479-58e1-40e5-b402-3925117ec06d" />


Once the printed parts from plates 2 and 3 are held in place, apply a small amount of glue to their joints.


<br> 
<br> 
<br> 
<br> 

Step 4
------
 
 Remove the housing from the 9-key keypad and take out the PCB.<br> 
<img src="https://github.com/user-attachments/assets/c978c0e6-fdb4-48b0-9297-3cd38f5da331"  width="400" > 
<br> The image above shows the PCB after the black switch sockets have been desoldered with a soldering iron. The solder pads should be clearly visible. <br><br> 
<img width="400"  alt="80c00f655ec31978e7290bde7d4e652" src="https://github.com/user-attachments/assets/b342f600-640d-496a-a27f-6eb37281e73f" />    
<br> ↑ Alternatively, solder the wires directly to the switch sockets.<br> After routing the wires through the opening, secure them at the center with two-part epoxy to prevent external pulling forces from breaking them.<br><br> 

Connect the keypad PCB to your computer, download the software provided by the seller, and program the key assignments.
Consider turning off the LEDs to reduce power consumption.
<img width="450"  alt="80c00f655ec31978e7290bde7d4e652" src="https://github.com/user-attachments/assets/68191312-93d4-4be2-b3b4-c0a97311866e" />    <img width="300"  alt="80c00f655ec31978e7290bde7d4e652" src="https://github.com/user-attachments/assets/13a27dda-3d21-4a31-9b79-2fc683db114c" />   
<br>Configuration software: https://www.jianguoyun.com/p/DVZ2nxEQ1raWDRiXhOcFIAA

<br> 
<br> 
<br> 
<br> 

Step 5
------

Install the low-profile red switches in the eight matching slots in the button ring. For the switches to fit correctly, their two pins must face toward the center of the ring.
<img width="480" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/4b009ba8-dc1f-4dcd-bda6-332664c53bbc" /> <img width="310" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/80e9c5f5-3ccb-4673-8051-260165546d74" />
<br> 
<br> 
October 2026 update: The design now uses Cherry low-profile switches. This is the recommended print profile for new builds. It fixes many issues and allows the buttons to be printed horizontally to reduce visible layer lines.<br> 
https://makerworld.com/zh/models/1769239 <br> <img width="592" height="592" alt="image" src="https://github.com/user-attachments/assets/ebc0b0ce-c38f-4b8d-b397-9fa83f22b950" />



<br> 
<br> 
<br> 

Step 6
------

Solder wires to each switch contact. Measure the required length so the wires can pass through the cabinet's headphone opening and reach the PCB at the back. Route each button separately so its wiring matches the key assignment programmed into the PCB.
Cover the bottom of each button with electrical tape to prevent unintended touchscreen input after assembly.
<img width="480" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/f6c62ac2-c91a-4544-923b-08250b3d07d5" /> <img width="480" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/de28197e-5f19-4377-9f73-a84c55812848" />

There are 16 wires in total. Carefully organize them and tuck them into the side channel beside the headphone opening.
(This is the hardest part of the project: the compact dimensions leave very little room for wiring. Be patient and take your time.)



<br> 
<br> 
<br> 
<br> 

Step 7
------

Carefully slide the tablet into the holder.
Use a file to remove any raised bumps or remaining support material.
<br> 
<br> 
<br> 
<br> 


Step 8
------

Place the right-angle OTG adapter at the bottom of the tablet. The design leaves approximately 1.5 mm of extra height; consider using nano tape as a spacer so the connector seats fully in the tablet. Once the fit is correct, glue it in place. Designing your own mounting bracket is recommended.
Use the data cable supplied by the PCB seller to connect the OTG adapter's USB-A port to the keypad PCB's USB-C port, then check that all buttons register correctly.

<img width="360" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/ae53ef03-bb40-40ce-80e1-a887f32c3a17" />

<br> 
<br> 
<br> 
<br> 
Finally, paint the cabinet, secure everything in place, and enjoy!
<img src="https://github.com/user-attachments/assets/4c70c37c-ed36-499e-90de-66ae712c0d3a" width="360px">
