# MaicroDX
一个专为平板设计的maimai模型支架，并提供8个可用于游戏的外置按键
<br> 
Tablet-specific maimai model stand.

<br> 

[Click here change to English](https://github.com/freebird233/MaicroDX/blob/main/README.md)

<br> 

[测试手元](https://b23.tv/kszsryM)

<br>

[快速介绍](https://b23.tv/HjXk9pg)

<br>

https://github.com/user-attachments/assets/7f807ca8-5c6a-4d6a-9782-b4f848022885

<br>

    该项目本质为模型分享，按键通过模拟键盘输入，您需要自行解决软件方面的问题。

<br> 


 * 特点: 由平板提供触摸, 友好的线路焊接（无需焊接元件），兼容最大11寸平板（不缩放模型比例的前提下）。
<br>


 * 目前的问题: 无灯光，无1p键，连接口定位精度低
<br> 
<br> 
<br>
<br>

关于许可证
-----
MaicroDX遵循 by-nc-sa规则 。所以你只能给自己和你的朋友 DIY，不能利用这个项目赚钱，比如收费的代做，出售整机等。
https://creativecommons.org/licenses/by-nc-sa/4.0/
<br> 
<br> 
<br> 
<br> 

物料表
-------
该项目使用的耗材 PETG 1KG ：18.8元
https://mobile.yangkeduo.com/goods.html?ps=Bo90h8nXsj

1423单芯镀银线 30awg (至少5m) ：4.49元
https://e.tb.cn/h.hBCuZG2iKpiAnD6?tk=XCFL4pLFaQ9

矮红轴 (10颗装) ：11元
https://mobile.yangkeduo.com/goods2.html?ps=eyPVs6rclm

otg直角转接头 (C公 to A母)  2.73元
https://mobile.yangkeduo.com/goods2.html?ps=BxALLyKNBC

:USB 9键可烧写键盘 33.37元
https://e.tb.cn/h.hByhHTJPLsIOH7V?tk=ob3u4ppTyxL


<img width="200"  alt="tb_image_share_1757697274791 jpg" src="https://github.com/user-attachments/assets/2eeb53ed-5334-4e8b-ad33-d457dd837c52" />
<img width="200"  alt="tb_image_share_1757697274791 jpg" src="https://github.com/user-attachments/assets/dd938c2f-1f32-437b-aa07-9bfcfbf8c93e" />
<img width="200"  alt="tb_image_share_1757697274791 jpg" src="https://github.com/user-attachments/assets/683e814b-d544-4d7f-b1e1-092834c6a232" />
<img width="200"  alt="tb_image_share_1757697151349 jpg" src="https://github.com/user-attachments/assets/28892012-82ab-4240-aace-b1e2d40d3281" />
<br> 
<br> 
--颜料，画笔，电烙铁，胶水，绝缘胶布等工具没有在此列出--
<br> 
<br> <br> <br> 

<img width="120"  alt="1756996362818" src="https://github.com/user-attachments/assets/94ff99b4-a543-4434-914d-c2336afb59d7" />

<br> 
（向店家要求发成品pcb单板+数据线可以减少工作量，且价格似乎还能谈）

<br> 
<br> 


<br> 
<br> 
<br> 
<br> 

开始
------
`-1`本项目默认的模型为适配小米平板5 & 小米平板5Pro 型号，[release](https://github.com/freebird233/MaicroDX/releases)中提供了模型工程文件，你可以根据自己的设备尺寸修改它。 (考虑开一个分支上传您的作品？这将会帮助更多的人)
<br> 
    1.0文件为限制长宽180mm的版本，这意味着你可以使用拓竹的a1mini等其他小打印机来制作它！为11寸平板使用时，游戏比例缩放至85%左右
    
 

<br> 
<br> 
<br> 
`0`打开 "[新]电控按键.SLDPRT"，参数位于左侧特征树内的"mipad5"与"camera"草图，我在草图内使用了注释功能标注各个尺寸含义（长度，高度），关于厚度(宽度)信息请右键特征，调整参数。最终导出step并重新切割与摆盘
<br> 
需要注意:使用比例缩放功能后，所有的公差都将一同被放大，还需要保证轴体安装处的尺寸为原来的大小。

<img width="720"  alt="1756996362818" src="https://github.com/user-attachments/assets/24f96f36-5d1b-4a57-8a78-6013c7cfef21" />

<br> 
<br> 
<br> 
<br> 

`1`打印所有模型文件， 3层墙  5%填充  0.10mm层高


<img width="720" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/ecc5b479-58e1-40e5-b402-3925117ec06d" />


打印件盘2与盘3初步固定后，使用少量胶水涂在连接处


<br> 
<br> 
<br> 
<br> 

`2`将pcb键盘连接电脑，下载由店家提供的软件，进行键位烧写
考虑将led关闭以节省电量损耗
<img src="https://github.com/user-attachments/assets/c978c0e6-fdb4-48b0-9297-3cd38f5da331"  width="400" > <img width="400"  alt="80c00f655ec31978e7290bde7d4e652" src="https://github.com/user-attachments/assets/68191312-93d4-4be2-b3b4-c0a97311866e" />
<br> 图一为使用电烙铁拆下黑色轴座后的效果,焊点应该是清晰可见的 <br>
设置软件:https://www.jianguoyun.com/p/DVZ2nxEQ1raWDRiXhOcFIAA

<br> 
<br> 
<br> 
<br> 

`3`矮红轴体装入按键轮盘对应的8个槽内，轴体的两根触针应该位于靠近轮盘圆心的方向才能被正确装入
<img width="480" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/4b009ba8-dc1f-4dcd-bda6-332664c53bbc" /> <img width="310" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/80e9c5f5-3ccb-4673-8051-260165546d74" />

<br> 
<br> 
<br> 
<br> 

`4`把每个按键触点焊上导线，测量长度，确保能穿过机台的耳机孔并连接到背部的主板内，推荐每个按键单独走线，以使得按键能与pcb烧写的键位完全一致
为了防止安装后误触屏幕，用绝缘胶布贴住每个按键的底部。
<img width="480" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/f6c62ac2-c91a-4544-923b-08250b3d07d5" /> <img width="480" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/de28197e-5f19-4377-9f73-a84c55812848" />

总计16根导线，慢慢理顺装进耳机孔的侧边槽位里
(全项目最难的部分，因为尺寸问题，没有太多走线的空间，这里请放平心态慢慢操作)



<br> 
<br> 
<br> 
<br> 


`5`尝试把平板慢慢装入支架内部
如果有凸起的颗粒或支撑碎片，请用锉刀打磨
<br> 
<br> 
<br> 
<br> 

`6`otg直角转接头放置在平板底部，设计时留有约1.5mm高度余量，请考虑用纳米胶增高，确保完全插入平板，没有问题后涂胶固定(推荐自行设计固定件)
用pcb板店家赠送的数据线，连接otg转接A口与pcb键盘C口，检查按键是否正常输出。

<img width="360" alt="3711083a9521bbc4f4f6488003fff1e" src="https://github.com/user-attachments/assets/ae53ef03-bb40-40ce-80e1-a887f32c3a17" />

<br> 
<br> 
<br> 
<br> 
最后上色，固定，enjoy it!
<img src="https://github.com/user-attachments/assets/4c70c37c-ed36-499e-90de-66ae712c0d3a" width="360px">
