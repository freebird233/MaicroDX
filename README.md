# MaicroDX
A maimai model stand specifically designed for tablets, featuring 8 external buttons usable for gameplay.
<br> 
Tablet-specific maimai model stand.

<br> 

[点我切换中文](https://github.com/freebird233/MaicroDX/blob/main/README_zh.md)

<br> 
<br> 

https://github.com/user-attachments/assets/7f807ca8-5c6a-4d6a-9782-b4f848022885

<br>

    This project is essentially a model share. The buttons simulate keyboard input, and you need to handle the software aspects yourself.

<br> 

*   Features: Touch input provided by the tablet, friendly wiring (no need for PCB fabrication or soldering components).
<br>

*   Current Issues: No lighting.

<br> 
<br> 
<br>

[MaicroDX Technical Exchange Community (QQ Group)](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=uaJAwiIXVH5AWTCzZIfZjyvK5NMUc5RV&authKey=3EfBhaKBnfT3eZ%2F9ZlTbbR4r84ucNtt%2F%2FNDzzINnJAItXKx8PftKUk%2FCVn4rtrLw&noverify=0&group_code=1055571063)

<br>

Special Thanks
-----
- __@Fandorabox__ for naming this project.
<br><br>
- __@-云朵冰淇淋-__ for creating the PCB connecting ribbon cable and the membrane keyboard version for this project.
<br><br>
- __@糖球__ for uploading the iPad Air modification configuration file.
<br><br>
- __@Kaironomia__ and __@Lev/ia__ __@whowechina__ for the original inspiration.

<br> 
<br> 
<br>
<br>

Regarding Licensing
-----
I created this project in my personal time, without any financial gain or sponsorship. I will continue to improve it. I have done my best to ensure the accuracy and functionality of all content, but errors are always possible. I cannot be held responsible for any loss of time or money you may incur from using this open-source project. Thank you for your understanding. MaicroDX follows the by-nc-sa rule. Therefore, you can only DIY it for yourself and your friends. You cannot make money from this project, such as through paid commissions, selling complete units, etc. Note that group buys or joint orders for original components are reasonable, and selling off leftover components in a non-profit manner is also acceptable.
https://creativecommons.org/licenses/by-nc-sa/4.0/

If you wish to purchase a finished product from me or seek assistance, please contact me (QQ group, Xianyu (idle fish), or leave your contact information in the issue section).
<br> 
<br> 
<br> 
<br> 

Bill of Materials (BOM)
-------
Materials used in this project: 1KG PETG Filament: ¥18.8
https://mobile.yangkeduo.com/goods.html?ps=Bo90h8nXsj

1423 Single-core Silver-plated Wire 30AWG (at least 5m): ¥4.49
https://e.tb.cn/h.hBCuZG2iKpiAnD6?tk=XCFL4pLFaQ9

Low-profile Red Switches (pack of 10): ¥11
https://mobile.yangkeduo.com/goods2.html?ps=eyPVs6rclm

OTG Right-angle Adapter (C male to A female): ¥2.73
https://mobile.yangkeduo.com/goods2.html?ps=BxALLyKNBC

9-Key Reprogrammable USB Keyboard PCB: ¥33.37
https://e.tb.cn/h.hByhHTJPLsIOH7V?tk=ob3u4ppTyxL
<br>
(Requesting the seller to provide the finished PCB board + cable can reduce workload, and the price seems negotiable.)
<br>

<img width="200"  alt="tb_image_share_1757697274791 jpg" src="https://github.com/user-attachments/assets/2eeb53ed-5334-4e8b-ad33-d457dd837c52" />
<img width="200"  alt="tb_image_share_1757697274791 jpg" src="https://github.com/user-attachments/assets/dd938c2f-1f32-437b-aa07-9bfcfbf8c93e" />
<img width="200"  alt="tb_image_share_1757697274791 jpg" src="https://github.com/user-attachments/assets/683e814b-d544-4d7f-b1e1-082834c6a232" />
<img width="200"  alt="tb_image_share_1757697151349 jpg" src="https://github.com/user-attachments/assets/28892012-82ab-4240-aace-b1e2d40d3281" />

<br>
--Paints, brushes, soldering iron, glue, insulating tape, and other tools are not listed here--

<br> 
<br> 
<br> 
<br> 

Differences Between Versions
------
Currently, MaicroDX has two versions: 1.0 and 2.0. Each has its own advantages and disadvantages. You can choose based on your tablet model and making ability.
<br>
<br>
__1.0__: For 11-inch and smaller tablets. Moderate size and material usage. Modify the cutout dimensions in the Solidworks project file according to your tablet size. Recommended print bed size: 180mm.
<br>
(NOTE: Can be used for tablets larger than 11 inches, but you need to use scaling, which increases workload.)
<br>
<br>
__2.0__: Universal for 11-inch ~ 13-inch tablets. Larger size and material usage. Uses screws and sliders inside the model to adjust front/back, left/right, and up/down positions. Recommended print bed size: 256mm.
<br>
(NOTE: Due to size reasons, 11-inch tablets using this model will not be able to display the upper screen area (presumably referring to a specific game area).)
<br>
<br>

<br>
1.0 requires modification skills for optimal fit to your tablet. 2.0 has better details, allows for sliding key inputs, fits various tablet sizes, but is huge.<br><br><br><br>
If you decide to use the 2.0 version model, please [click here](https://github.com/freebird233/MaicroDX/blob/main/README_2.0.md)
<br><br>
If you decide to use the 1.0 version model, please __continue reading below__.
<br> 
<br> 
<br> 

Getting Started
------
<br>

`-1` Download the model project files provided in [releases](https://github.com/freebird233/MaicroDX/releases), and modify them according to your device dimensions. (Consider creating a fork to share your work? It will help more people.)
<br>
    The 1.0 file is a version limited to 180mm length/width, meaning you can use small printers like the Bambu Lab A1 mini to make it! When used with an 11-inch tablet, the game interface should be scaled to about 85%.

<br> 
<br> 
<br> 
`0` Open "[New]Electrical Buttons.SLDPRT". Parameters are located in the "mipad5" and "camera" sketches within the feature tree on the left. I have used notes within the sketches to label the meanings of various dimensions (length, height). For thickness (width) information, please right-click the feature to adjust parameters. Finally, export as STEP and re-slice and arrange for printing.
<br>
Important: After using the scale function, all tolerances will be scaled together. Also, ensure the dimensions for switch installation remain the original size.

<img width="720"  alt="1756996362818" src="https://github.com/user-attachments/assets/24f96f36-5d1b-4a57-8a78-6013c7cfef21" />

<br> 
<br> 
<br> 
<br> 

`1` Print all model files. Settings: 3 walls, 5% infill, 0.10mm layer height.

<img width="720" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/ecc5b479-58e1-40e5-b402-3925117ec06d" />

After preliminary assembly of printed parts '盘2' and '盘3', apply a small amount of glue to the joints.

<br> 
<br> 
<br> 
<br> 

`2` Disassemble the 9-key keyboard case and extract the PCB board.<br>
<img src="https://github.com/user-attachments/assets/c978c0e6-fdb4-48b0-9297-3cd38f5da331"  width="400" >
<br> The image above shows the effect after desoldering the black switch sockets with a soldering iron. The solder pads should be clearly visible. <br><br>
<img width="400"  alt="80c00f655ec31978e7290bde7d4e652" src="https://github.com/user-attachments/assets/b342f600-640d-496a-a27f-6eb37281e73f" />
<br> ↑ Alternatively, you can choose to solder wires directly onto the switch sockets.<br> After passing through the drilled holes, apply AB glue at the center point to secure the wires and prevent them from being broken by external force.<br><br>

Connect the PCB keyboard to a computer, download the software provided by the seller, and program the key mappings.
Consider turning off the LEDs to save power.
<img width="450"  alt="80c00f655ec31978e7290bde7d4e652" src="https://github.com/user-attachments/assets/68191312-93d4-4be2-b3b4-c0a97311866e" />    <img width="300"  alt="80c00f655ec31978e7290bde7d4e652" src="https://github.com/user-attachments/assets/13a27dda-3d21-4a31-9b79-2fc683db114c" />
<br>Setup software: https://www.jianguoyun.com/p/DVZ2nxEQ1raWDRiXhOcFIAA

<br> 
<br> 
<br> 
<br> 

`3` Install the low-profile red switches into the 8 corresponding slots on the button wheel. The two pins of the switch should face towards the center of the wheel for correct installation.
<img width="480" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/4b009ba8-dc1f-4dcd-bda6-332664c53bbc" /> <img width="310" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/80e9c5f5-3ccb-4673-8051-260165546d74" />

<br> 
<br> 
<br> 
<br> 

`4` Solder wires to each button contact. Measure the length to ensure they can pass through the headphone jack hole of the stand and connect to the main PCB at the back. It's recommended to wire each button individually to ensure the buttons correspond exactly to the programmed keys on the PCB.
To prevent accidental screen touches after installation, cover the bottom of each button with insulating tape.
<img width="480" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/f6c62ac2-c91a-4544-923b-08250b3d07d5" /> <img width="480" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/de28197e-5f19-4377-9f73-a84c55812848" />

A total of 16 wires. Carefully organize and thread them into the side groove of the headphone jack hole.
(The most difficult part of the entire project. Due to size constraints, there isn't much space for routing. Please be patient and work slowly.)

<br> 
<br> 
<br> 
<br> 

`5` Try to slowly insert the tablet into the stand.
If there are protruding particles or support fragments, please use a file to sand them down.
<br> 
<br> 
<br> 
<br> 

`6` Place the OTG right-angle adapter at the bottom of the tablet. The design leaves about 1.5mm of height allowance. Consider using nano tape to raise it, ensuring it is fully inserted into the tablet. After confirming it's working, apply glue to secure it (recommended to design your own mounting part).
Use the cable provided with the PCB board to connect the OTG adapter's A port to the PCB keyboard's C port. Check if the buttons output normally.

<img width="360" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/ae53ef03-bb40-40ce-80e1-a887f32c3a17" />

<br> 
<br>
