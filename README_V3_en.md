# Maicrodx V3 Model Guide

<br>
<br>

[What's new?](https://github.com/user-attachments/files/34226053/what.s.new.1.pdf) (as of October 25, 2026)






<br>
<br>

# Printing the Model


The V3 model is divided into two versions: one for 11-inch tablets and one for 12.5+ inch tablets.<br>
Search online for the outer dimensions of your tablet.<br>
Download the [V3] model from MakerWorld.<br>
https://makerworld.com.cn/zh/models/1561531 <br>
<div align="center"><img width="500" alt="Snipaste_2026-10-26_17-49-43" src="https://github.com/user-attachments/assets/6c206ae4-638b-40e0-91c6-d5f1045adfbd" /> 
 <img width="350"  alt="image" src="https://github.com/user-attachments/assets/394a536e-dbd0-4ef1-bf3d-1ac52f8b2cb9" />

<br>Sliced files
</div>
<br>

Use the ruler tool in your slicing software to measure the frame dimensions and confirm whether the short edge of the tablet screen can fit inside. The thickness and length can be adjusted within the frame.<br>
<br>
Please be sure to measure the model dimensions and compare them with your own tablet dimensions before printing.

<br>
<br>

Post-processing
-----

If layer lines are too obvious after printing, sand the part as needed.<br>
Sanding requires sandpaper of different grits. Lower grit is coarser; gradually move from coarse to fine.
<div align="center"><img width="300"  alt="0265b2b383c8f8d9e084716329cb6e13" src="https://github.com/user-attachments/assets/b3544391-e254-4a38-a017-baae88b64e66" />
<br>
Frame after sanding </div>
<br>
<br><br><br>

# Purchasing Components
In addition to the components on the circuit board (BOM), you also need to purchase the following:
<br>
<img width="100"  alt="7f410a41bbb1690c873d6deabcacb916" src="https://github.com/user-attachments/assets/3c5693ba-8e29-4881-9f6d-408bb0c839b2" />DCDC adjustable buck module https://mobile.yangkeduo.com/goods2.html?ps=X5uzsILUIu
<br>
<img width="100"  alt="7d21361d32f2b419bc44bd6332f07f48" src="https://github.com/user-attachments/assets/7dd8d886-2a8f-474d-aa66-3ab99add5063" />
5V COB light strip https://mobile.yangkeduo.com/goods1.html?ps=PZzBEKW0eg (3 mm wide, 1 m)
<br>

<img width="100"  alt="366486b9eb7dd0acfdc6ddf0f57b6d35" src="https://github.com/user-attachments/assets/5ff13a28-e148-4ec9-a05a-f42681099d92" />WS2812 LEDs https://e.tb.cn/h.jez4mzi5QyXiVmW?tk=45fETDGuaXV (100 LEDs/m
 0.5 m bare board)
<br>
<img width="100"  alt="56d22c5dc6d6c641a3a653eefd909377" src="https://github.com/user-attachments/assets/c99a3a86-27e3-4646-9d53-7573cbeeb5fd" />C-to-C data cable https://mobile.yangkeduo.com/goods2.html?ps=SiMcasrXyJ (dual USB-C, 1 cable)
<br>

<img width="100"  alt="image" src="https://github.com/user-attachments/assets/b1845ebf-d027-4e17-94d1-083cf48674c6" /> Self-tapping screws https://e.tb.cn/h.j6yBLOpGoLmfVUH?tk=jGQt6YpXLq4  (optional, for decoration)
<br>
<img width="100" alt="image" src="https://github.com/user-attachments/assets/de1289ad-a48f-4fd2-b7ba-acf30c2b10e4" /> Low-profile switches https://e.tb.cn/h.jRXogoRPmuNxnyg?tk=RaZK6Yp5Pvr



<br>
<br>
<br>
<br>
<br>

# Main Controller Board SMT Soldering

<br>
<br>
Refer to this website for SMT soldering; it can improve efficiency.<br>

[V3 Interactive BOM.html](https://github.com/user-attachments/files/34361656/V3.BOM.html)

<br>
<br>
<div align="center">For this project, some components are not mandatory.<br> The main controller board should look like this after soldering. After flashing the program, when powered on and headphones are connected, three LEDs should be lit.<br>
<img width="280"  alt="8c8c32762c9862159e4f02e3d143df3d" src="https://github.com/user-attachments/assets/fc67a035-1699-4933-bede-161580ee5546" /><img width="500"  alt="dcb986164ce6d01910a24e40892780cf" src="https://github.com/user-attachments/assets/ddc6c8b3-db79-4d54-a223-659470e285bc" />
<br>
<br>
<br>
<br>
When the charging port is connected, the mobile device will show fast charging. The notification bar will show "physical keyboard" and "USB sound card".

<img width="500" alt="101338db0f6c94672967f020e723a215" src="https://github.com/user-attachments/assets/9ca87a61-b088-43f4-b22e-2688a6994ba9" /><img width="315" alt="8cec2a484f5962b6bd445f760a82fa79" src="https://github.com/user-attachments/assets/7f25c002-6f49-4bfc-806b-1d0611d9c0d1" />

</div><br>
<br>

Flashing the Firmware
-----
Download the flashing software [WCHISPStudio](https://www.wch.cn/downloads/WCHISPTool_Setup_exe.html) from the official website. <br> 
Download the hex firmware from [Releases](https://github.com/freebird233/MaicroDX/releases).<br>
 <br><div align="center">
<img width="720" alt="Snipaste_2026-07-02_20-34-18" src="https://github.com/user-attachments/assets/3abe23a6-3a7c-488c-9f09-9790bfdc47e0" /> <br>
WCHISPStudio interface</div><br><br>
- Connect the board to the computer; the device name will appear.<br>
- Check the flashing configuration as shown in the figure, then click Download.<br>
<br>

Troubleshooting
-----
  <br>
  Cannot find the device when flashing ---> Short BOOT and power on, then re-flash the firmware ---> Check whether GND, 5V, D+, and D- on the Type-C receptacle pads are solder-bridged or missing solder, or replace the MCU.<br> <br>
  Computer notification: **Unrecognized USB hardware** ---> Check whether D+ and D- on the Type-C receptacle pads are solder-bridged or missing solder, or replace the MCU.<br> <br>
  Computer notification: **Hardware exceeds maximum current load** ---> The main board has a short circuit.<br> <br>
  The status LED flashes after connecting headphones, with no audio output ---> Resolder U4.<br> <br>
  
<br>
<br>
<br>
<br>

# Sub-controller Board Soldering (Button Ring)
<br>
<br>
Download the Gerber files from the MaicroDX Controller repository. (The sub-controller board is updated in that project; the main controller board is maintained here.)
<br>
<br>

> Choose a thinner board thickness if possible.
<br><br>
Default: 2-layer board, 0.8 mm thick, white, OSP<br>
Sample order price is about 16 CNY per piece.<br><br>If a non-white color is selected, the PCB will be visible in the gaps on the left and right of the keys, affecting appearance.

<br><br><div align="center">
<img width="510"  alt="image" src="https://github.com/user-attachments/assets/786b21bc-3523-4812-9541-676310c09172" />
<img width="400"  alt="image" src="https://github.com/user-attachments/assets/2cf4c2b8-833b-4672-bba7-751d506be6a5" />
<br>The enclosure files in Releases fit Cherry low-profile switch series by default. You can also modify the footprint to fit other switches.<br>
For example, the build shown uses Kailh Baiyu / Heiyun / Zheshan 1353 Hitbox switches with all-white housings.</div>

<br>
<br>




https://github.com/user-attachments/assets/6a8587d2-b886-4417-bf86-0edc023bd731

<br>

- Check whether the indicator LEDs light up in sequence (as in the video above). Due to the serial signal transmission characteristic of WS2812, if a signal connection on one LED comes loose, all subsequent LEDs will go out.<br><div align="center"> **Communication series relationship = the order in which the LEDs light up** </div><br><br>

- Short the two pads of each key and check whether a key signal is output and the white LED turns yellow.<br>Note: [Key tester website](https://www.zfrontier.com/lab/keyboardTester)
<br>
<br>

Installing the Enclosure
-----

<br>  <br> 
The MaicroDX Controller enclosure consists of two parts. Please prioritize downloading the model files from MakerWorld (it is difficult for me to check and update on multiple platforms).<br>
<div align="center"><img width="800" alt="Snipaste_2026-07-02_23-48-56" src="https://github.com/user-attachments/assets/4cb6bfd1-12f3-4750-9b2f-d03b26c6ff84" /></div>
The "enclosure" and "enclosure base plate" are fixed by interference fit.<br> 
The switches and PCB are fixed with solder.<br> 
The PCB mounting slot in the enclosure has a relatively large overhanging area. When printing, it is best to use dual-material filament for the support interface; this can significantly improve efficiency and model quality. For example: PLA as support for PETG.<br> <br>
 <br>
 <br>  <br> 
<br>
<br>
<br>

 <div align="center"><img width="450"  alt="288eb6a0f2515d5845719e86907c26f6" src="https://github.com/user-attachments/assets/bb889b1b-5046-45f1-a36e-f809559b3be8" /><img width="450" alt="fdbd2daced42348d2717fd6a8a4ebf8e" src="https://github.com/user-attachments/assets/fcd528dc-98b8-4011-9126-efd84114448b" /></div>

<br><br>

# Frame Lighting Layout
This section describes the lighting inside the MDX frame. Before starting, determine the cut lengths for the two light strips.
<div align="center">
  
|  <div align="center"> Type \ Size   |   <div align="center">11-inch frame   |   <div align="center">12-inch frame   |
| :--- | :--- |  :--- |
|   <div align="center">WS2812   |   <div align="center">25 LEDs   |   <div align="center">31 LEDs   |
|   <div align="center">COB   |   <div align="center">≈53 cm   |   <div align="center">≈61 cm   |
<div align="center"><img width="700" alt="c71ba10e22d39109f54d0fa14471b119" src="https://github.com/user-attachments/assets/ccb61cf2-b615-46ca-a5cf-d419d992bd1b" />

</div>
<br>
<br><br>
<br>

<div align="center"><img width="800"  alt="WeChat image_20261026222227_75_2" src="https://github.com/user-attachments/assets/14f05b7e-5bca-4924-97aa-db1ea810b613" /><br>Headlight wiring diagram<br></div>
<br> 
</div>

**Step 1**
: Solder three appropriately long wires to the WS2812 input end, install along the red arrow direction, and enter through the angled hole behind the head shell until the light strip completely fills the U-shaped area.
<br> **Step 2**: Pull all wires out along the top.
<br> **Step 3**: Following the blue arrow direction, pass through the vertical hole in the model and route the wires downward.


<br><br>
<br> <div align="center">
<br>
<img width="600"  alt="image" src="https://github.com/user-attachments/assets/67dcd6f4-3446-4291-9c9e-c95facb81cda" />

<br>

WS2812 lighting communication logic: <br>
Main controller --> FPC Din --> Button Ring --> FPC Dout --> Main controller --> Headlight <br>
When lighting problems occur, troubleshoot according to this logic.
</div>


<br>
The COB light strip is fixed to the cabinet's button ring with its own adhesive backing. Brightness is manually controlled by the external DCDC board from the main controller. After cutting according to the table above, peel off a little adhesive and solder two wire-wrap wires to it.
<br>
<br><div align="center">
<img width="300"  alt="d2fab9166c778eb366c540e1b5e266a0" src="https://github.com/user-attachments/assets/d2a09b47-08b9-4c90-be0c-33421bb6d488" /> <img width="300"  alt="f224b8227ed809cb45b568eb8bb618cd" src="https://github.com/user-attachments/assets/91a8c40d-1ced-4517-93b1-fe33aa50c329" /> <img width="300"  alt="d43cacdae06dbfdb33d1740236994a43" src="https://github.com/user-attachments/assets/69c94f94-2a91-4aff-bf61-f0a9ebbd841f" />

Reinforce with hot glue.<br>
</div>
<br>
<br>
<br>

<br><br>


# Button Ring Without Lighting
<br>
<br>
If you do not need lighting, you can make a non-lit control button ring as follows. This makes the build easier. It can also be used on the V3 frame.
<br>
<br>
<br>
<br>
<div align="center"><br>
 https://makerworld.com.cn/zh/models/1561531<br>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/f20d0d59-8445-4485-8bdd-f4cf886d131d" /><br>
Print this configuration file.</div>
<br>
<br>
<div align="center">
<img width="500"  alt="image" src="https://github.com/user-attachments/assets/35f810d8-5e0c-46f0-a25a-82a08cb7a965" />
<br>
Solder only the necessary components on the external control board.
<br>
<br>
<br>
<br>
 <img width="900" alt="image" src="https://github.com/user-attachments/assets/0eea48f7-3ef0-465b-b602-967551f5211e" /><br>
Wire both pins of each switch: connect one pin to the numbered pad on the board that matches the number on the button ring enclosure, and connect the other pin to GND. This requires 16 wires in total.<br><br><br><br>
<img width="500"  alt="2c12e648aacdde16a89e48ecf2893bba" src="https://github.com/user-attachments/assets/33313f79-54bc-4519-9526-17a48ffc65d4" /><img width="500"  alt="403b71811d136e94a510ad45d4fbbbc9" src="https://github.com/user-attachments/assets/d2b3321e-67fe-4680-be17-75a06073881c" /><br>
Use pliers to cut the horizontal bar and route the cables in.
<br>
<br><br>
<br>
<img width="600"  alt="3e267254ec4e80eb1256ba0a3bd9d5b9" src="https://github.com/user-attachments/assets/a19a6863-5bf6-42cd-83d6-1fb2aff3efe0" /><img width="315"  alt="b8617a2020be5331d3dc222d81dfcb6f" src="https://github.com/user-attachments/assets/51834f00-f553-4d4e-9bb6-a1a90ddda0d4" /><br>
Put on the dust cover and add some hot glue on both sides of the cable to reinforce.
<br>
<br><br>
<br>
<img width="600"  alt="7862b3dba1522f253971b73db285749f" src="https://github.com/user-attachments/assets/f260eaf9-3d7d-4319-9159-7fbcb3d83d1a" /><br>
Final result.
<br>
</div>
Note: If you flash the firmware with lighting, after power-on you need to wait 5 s before it works.




<br><br>

# Assembly
This section covers assembly of the MaicroDX cabinet. Use two-part epoxy for bonding and masking tape to hold the parts in place while it cures.

Cabinet
----
<div align="center"><img width="535"  alt="image" src="https://github.com/user-attachments/assets/354b0d7a-d874-4eb4-85be-f2b8f98e27a5" /> <img width="300"  alt="image" src="https://github.com/user-attachments/assets/12715dd5-4319-4b0d-ae7e-50c7b4b8cefe" />
   <br>Exploded view and gluing sequence

 
 <br><br><br><br>



<img width="400" alt="a1fdb5a11cb966918c32aa63c62052e1" src="https://github.com/user-attachments/assets/81f639f1-d645-4597-b304-6bfd70f5e308" /> <img width="400"  alt="a831ab3301552025a71e331923ce9287" src="https://github.com/user-attachments/assets/aafa15a0-cf87-41aa-aba7-49db1ae3a105" />
<br>Button 9 is on the left side of the cabinet. No glue is needed: align it at the correct angle and push it in until it locks in place. Solder the wires, then use a crimping tool to attach a 2-pin connector.

<br><br><br><br>


<img width="450" alt="11d7263bc8986843a74345e70c14218e" src="https://github.com/user-attachments/assets/aec057f4-e420-4b95-a03c-bb1dec6f5953" /> <img width="450" alt="c89b90ba149ec5b63a2cfed46521ef2f" src="https://github.com/user-attachments/assets/81f3f4d0-50bf-4076-89ee-0e476ddc1cbc" />
<br>Cut approximately 1 mm wide double-sided mounting tape into small squares, stick them onto the cabinet's locating tabs, and install the button ring.
<br><br><br><br>


<img width="600"  alt="384697ccd015941b86f4e218af7f62a3" src="https://github.com/user-attachments/assets/f459b332-588b-4e9c-af25-0b5453a05f66" />

<br>**1** ---> WS2812 headlight
<br><br>**2** ---> COB light strip
<br><br>**3** ---> 1P button
<br><br><br><br>

Rainbow Trim
----
<br><br>
Option 1<br><img width="600"  alt="image" src="https://github.com/user-attachments/assets/5ae85412-738a-4703-b3e7-d773117511e7" />
<br>Print this profile using filament in the corresponding colors, or print everything in white and paint it afterward.
<br><br><br>
Option 2<br>
<img width="600" alt="4f0dbb332f1af8da2ebad8a157b2294a" src="https://github.com/user-attachments/assets/264a5e1b-e888-4269-816f-04ed868e11bb" />
<br>Download the CAD files from Releases and send them to an acrylic fabricator for custom production.<br>
<br><br>
Comparison of the two options<br>
<img width="600" alt="ad20721d1ef980eebc84f5f7680e1cd6" src="https://github.com/user-attachments/assets/033d5108-2375-4c96-b24e-b4ac05df29e4" />

<br><br><br><br>
Headphone Assembly
----


<br>
<div align="center"><img width="900"  alt="image" src="https://github.com/user-attachments/assets/22d8211d-7fac-4e9a-bed3-83a8942c2c78" />
<br>Exploded view   
<br><br>

<img width="280"  alt="image" src="https://github.com/user-attachments/assets/2cdbfab3-d747-48be-8b13-59c268d1b47f" />
<img width="400" alt="3926b9044590883553583c591ca888d2" src="https://github.com/user-attachments/assets/b1a4e1f2-e0be-401a-91fc-5e04bf457f5f" />
<img width="230"  alt="cefab52c16c0a22639bb79ff11d2c6f9" src="https://github.com/user-attachments/assets/30383f4b-40be-4939-bf0a-f74a5c2dd241" />
<br>For better results, resin-print the transparent housing.<br><br>
</div>
<br>
<br>
Left: 75 mm
<br>
Right: 210 mm


