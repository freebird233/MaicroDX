# MaicroDX
A tablet-specific maimai model stand with 8 external buttons for gameplay.

<br>

[点击这里切换到中文版本](https://github.com/freebird233/MaicroDX/blob/main/README_zh.md)

<br>
<br>



https://github.com/user-attachments/assets/7f807ca8-5c6a-4d6a-9782-b4f848022885


<br>

This project does not provide software downloads.

<br>
Features: Utilizes tablet touchscreen, beginner-friendly wiring (no component soldering required), compatible with tablets up to 11 inches (without scaling the model proportions).


Current limitations: No lighting, no 1P button, low connector positioning accuracy.

<br>
<br> <br> <br>

About the License
-----

MaicroDX follows the by-nc-sa rules. Therefore, you can only DIY for yourself and your friends. You cannot make money from this project, such as paid commissions, selling complete units, etc.
https://creativecommons.org/licenses/by-nc-sa/4.0/



<br>
<br> <br> <br>




Bill of Materials
-----
Materials used in this project:
Qianhuozhidu PETG 1KG : 18.8 RMB
https://mobile.yangkeduo.com/goods.html?ps=Bo90h8nXsj

1423 Single-core silver-plated wire 30awg (at least 5m) : 4.49 RMB
https://e.tb.cn/h.hBCuZG2iKpiAnD6?tk=XCFL4pLFaQ9

Low-profile red switches (10-pack) : 11 RMB
https://mobile.yangkeduo.com/goods2.html?ps=eyPVs6rclm

Right-angled OTG adapter (C male to A female) : 2.73 RMB
https://mobile.yangkeduo.com/goods2.html?ps=BxALLyKNBC

Hongyue Electronic Module: USB 9-key programmable keyboard : 33.37 RMB
https://e.tb.cn/h.hByhHTJPLsIOH7V?tk=ob3u4ppTyxL

(Requesting pre-assembled PCB board + data cable from the seller can reduce workload, and the price may be negotiated lower)

-- Tools such as paint, brushes, soldering iron, glue, electrical tape, etc. are not listed here --

<br> <br> <br> <br>
Getting Started
------

-1 The default model of this project is adapted for Xiaomi Pad 5 & Xiaomi Pad 5 Pro models, but the release provides model project files that can be modified according to your device size.

(Consider creating a branch to upload your work? This will help more people.)








0 Open "[New] Electronic Control Buttons.SLDPRT". Parameters are located in the "mipad5" and "camera" sketches within the left feature tree. I have used annotation functions in the sketches to label various dimension meanings (length, height). For thickness (width) information, right-click on the feature to adjust parameters. Finally, export as STEP and re-slice and arrange.
<img width="720" alt="1756996362818" src="https://github.com/user-attachments/assets/24f96f36-5d1b-4a57-8a78-6013c7cfef21" />

<br> <br> <br> <br> 

`1` Print all model files with settings: 3 walls, 5% infill, 0.10mm layer height.<img width="720" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/ecc5b479-58e1-40e5-b402-3925117ec06d" />
After preliminary fixation of printed parts tray 2 and tray 3, apply a small amount of glue to the connection points.

<br> <br> <br> <br> 

`2` Connect the PCB keyboard to a computer, download the software provided by the seller, and program the key mappings. Consider turning off LEDs to save power consumption. <img src="https://github.com/user-attachments/assets/c978c0e6-fdb4-48b0-9297-3cd38f5da331" width="720px" ><img width="605" height="472" alt="80c00f655ec31978e7290bde7d4e652" src="https://github.com/user-attachments/assets/68191312-93d4-4be2-b3b4-c0a97311866e" />
Software setup: https://www.jianguoyun.com/p/DVZ2nxEQ1raWDRiXhOcFIAA

<br> <br> <br> <br> 

`3` Install the low-profile red switches into the 8 corresponding slots on the button wheel. The two pins of the switch should face toward the center of the wheel to be properly installed. <img width="720" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/4b009ba8-dc1f-4dcd-bda6-332664c53bbc" /><br> <br> <br> <br>
4 Solder wires to each button contact, measure the length to ensure they can pass through the headphone jack of the unit and connect to the main board inside the back. It is recommended to run separate wires for each button to ensure the buttons match exactly with the keys programmed on the PCB.
To prevent accidental screen touches after installation, cover the bottom of each button with electrical tape.

<img width="720" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/f6c62ac2-c91a-4544-923b-08250b3d07d5" />

A total of 16 wires, carefully organize and route them into the side slot of the headphone jack.
(The most challenging part of the entire project. Due to size constraints, there isn't much space for wiring. Please be patient and work slowly.)
<img width="720" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/de28197e-5f19-4377-9f73-a84c55812848" />

<br> <br> <br> <br>
5 Carefully try to install the tablet into the stand.
If there are protruding particles or support fragments, use a file to smooth them out.




<br>
<br> <br> <br>



6 Place the right-angled OTG adapter at the bottom of the tablet. The design allows about 1.5mm height margin. Consider using nano tape to increase height to ensure complete insertion into the tablet. After confirming no issues, apply glue for fixation (recommended to design your own fixture).
Use the data cable provided by the PCB board seller to connect the OTG adapter's A port to the PCB keyboard's C port. Check if the buttons output correctly.



<br>
<br> <br> <br>




Finally, paint, secure everything, and enjoy it!
<img src="https://github.com/user-attachments/assets/4c70c37c-ed36-499e-90de-66ae712c0d3a" width="720px">

