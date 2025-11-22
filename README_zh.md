# MaicroDX
一个专为平板设计的maimai模型支架，并提供8个可用于游戏的外置按键
<br> 
Tablet-specific maimai model stand.

<br> 

[Click here change to English](https://github.com/freebird233/MaicroDX/blob/main/README.md)


<br> 
<br> 

https://github.com/user-attachments/assets/7f807ca8-5c6a-4d6a-9782-b4f848022885

<br>

    该项目本质为模型分享，按键通过模拟键盘输入，您需要自行解决软件方面的问题。

<br> 


 * 特点: 由平板提供触摸, 友好的线路焊接（无需打板、焊接元器件）。
<br>

 * 目前的问题: 无灯光

<br> 
<br> 
<br>

[MaicroDX技术交流社区](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=uaJAwiIXVH5AWTCzZIfZjyvK5NMUc5RV&authKey=3EfBhaKBnfT3eZ%2F9ZlTbbR4r84ucNtt%2F%2FNDzzINnJAItXKx8PftKUk%2FCVn4rtrLw&noverify=0&group_code=1055571063)

<br>


特别感谢
-----
- __@Fandorabox__ 为本项目命名 
<br><br>
- __@-云朵冰淇淋-__ 为本项目制作pcb连接排线,与薄膜键盘版本
<br><br>
- __@糖球__ 制作了ipad air改模文件
<br><br>
- __@Kaironomia__ __@Lev/ia__  创意灵感来源

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
<br>
（向店家要求发成品pcb单板+数据线可以减少工作量，且价格似乎还能谈）
<br>

<img width="200"  alt="tb_image_share_1757697274791 jpg" src="https://github.com/user-attachments/assets/2eeb53ed-5334-4e8b-ad33-d457dd837c52" />
<img width="200"  alt="tb_image_share_1757697274791 jpg" src="https://github.com/user-attachments/assets/dd938c2f-1f32-437b-aa07-9bfcfbf8c93e" />
<img width="200"  alt="tb_image_share_1757697274791 jpg" src="https://github.com/user-attachments/assets/683e814b-d544-4d7f-b1e1-092834c6a232" />
<img width="200"  alt="tb_image_share_1757697151349 jpg" src="https://github.com/user-attachments/assets/28892012-82ab-4240-aace-b1e2d40d3281" />

<br>
--颜料，画笔，电烙铁，胶水，绝缘胶布等工具没有在此列出--


<br> 
<br> 
<br> 
<br> 


各版本区别
------
目前Maicrodx共有两个版本,分别为1.0与2.0。它们各有各的优势与不足，你可以根据自己的平板型号与制作能力综合选择。
<br>
<br>
__1.0__ ：11英寸及以下，适中的体积与耗材用量，根据自己的平板尺寸修改Solidworks工程文件内的切除尺寸。推荐180mm打印板尺寸 
<br>
（NOTE:超出11寸也可以使用该模型，但你需要使用缩放比例功能，这意味着会增加一些工作量）
<br>
<br>
__2.0__ ：11英寸~13英寸通用，较大的体积与耗材用量，使用模型内部的螺丝与滑块调节前后、左右、上下的位置。可以扫键了，推荐256mm打印板尺寸
<br>
（NOTE：出于尺寸原因，11寸平板使用该模型将无法显示上屏幕）
<br>
<br>

# 说人话 <br>
1.0要会改模，适配最大化能省点耗材钱。2.0结构精良体验更佳，大小板子通吃，但体积巨大。<br><br><br><br>
如果您决定使用2.0版本模型，请[点我](https://github.com/freebird233/MaicroDX/blob/main/README_2.0zh.md)
<br><br>
如果您决定使用1.0版本模型，请 __继续往下阅读__
<br> 
<br> 
<br> 

开始
------
<br>

`-1`下载，[release](https://github.com/freebird233/MaicroDX/releases)内提供的模型工程文件，根据自己的设备尺寸修改它。 (考虑开一个分支上传您的作品？这将会帮助更多的人)
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

`2` 拆除九键键盘外壳，取出pcb板
<img src="https://github.com/user-attachments/assets/c978c0e6-fdb4-48b0-9297-3cd38f5da331"  width="400" > 
<br> 上图为使用电烙铁拆下黑色轴座后的效果,焊点应该是清晰可见的 <br>
<img width="400"  alt="80c00f655ec31978e7290bde7d4e652" src="https://github.com/user-attachments/assets/b342f600-640d-496a-a27f-6eb37281e73f" />    
<br> ↑也可以选择直接将导线焊接在轴座上<br> 穿过打孔区域后，在圆心涂抹ab胶水凝固线材，防止受外力扯断。<br>

将pcb键盘连接电脑，下载由店家提供的软件，进行键位烧写
考虑将led关闭以节省电量损耗
<img width="450"  alt="80c00f655ec31978e7290bde7d4e652" src="https://github.com/user-attachments/assets/68191312-93d4-4be2-b3b4-c0a97311866e" />    <img width="300"  alt="80c00f655ec31978e7290bde7d4e652" src="https://github.com/user-attachments/assets/13a27dda-3d21-4a31-9b79-2fc683db114c" />   
<br>设置软件:https://www.jianguoyun.com/p/DVZ2nxEQ1raWDRiXhOcFIAA

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
