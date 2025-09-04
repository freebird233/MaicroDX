# MicroDX
一个专为平板设计的maimai模型支架，并提供8个可用于游戏的外置按键





Tablet-specific maimai model stand.




https://github.com/user-attachments/assets/7f807ca8-5c6a-4d6a-9782-b4f848022885




本项目不提供软件程序方面的介绍与下载方式

...


特点:由平板提供触摸, 友好的线路焊接，根据平板型号灵活修改工程文件(sldprt格式)，180mm的小打印平台也能兼容最大11寸平板（z轴拼接）。


目前的问题:无灯光, 平板放入时很难对准c口


...

  物料表

该项目使用的耗材 ：千货之都 PETG 1KG ：18.8元
https://mobile.yangkeduo.com/goods.html?ps=Bo90h8nXsj

1423单芯镀银线 30awg (至少5m) ：4.49元
https://e.tb.cn/h.hBCuZG2iKpiAnD6?tk=XCFL4pLFaQ9

矮红轴 (10颗装) ：11元
https://mobile.yangkeduo.com/goods2.html?ps=eyPVs6rclm

otg直角转接头 (C公 to A母)  2.73元
https://mobile.yangkeduo.com/goods2.html?ps=BxALLyKNBC

红悦电子模块 :USB 9键可编程键盘 33.37元
https://e.tb.cn/h.hByhHTJPLsIOH7V?tk=ob3u4ppTyxL

（向店家要求发成品pcb单板+数据线可减少一定程度的工作量，且价格似乎还能谈得更低）

--颜料，画笔，电烙铁，胶水，绝缘胶布等工具没有在此列出--

...

开始吧

0.打开 "[新]电控按键。SLDPRT"，修改位于左侧特征树内的"mipad5"与"camera"草图，导出step并重新摆盘
（小米平板5 & 5Pro 机型可忽略此步骤 ）
<img width="1280" height="687" alt="1756996362818" src="https://github.com/user-attachments/assets/24f96f36-5d1b-4a57-8a78-6013c7cfef21" />


1.打印3mf内的所有模型文件， 3层墙  5%填充  0.10mm层高
打印件初步固定后，使用少量胶水涂在连接处

2.将pcb键盘连接电脑，下载由店家提供的软件，进行键位烧写
你也应该考虑将led关闭以节省电源损耗
<img width="605" height="472" alt="80c00f655ec31978e7290bde7d4e652" src="https://github.com/user-attachments/assets/68191312-93d4-4be2-b3b4-c0a97311866e" />

设置软件:https://www.jianguoyun.com/p/DVZ2nxEQ1raWDRiXhOcFIAA

3.将矮红轴体装入按键轮盘对应的8个槽内，轴体的两根触针应该位于靠近轮盘圆心的方向才能被正确装入

4.把每个按键触点焊上导线，测量长度，确保能穿过机台的耳机孔并连接到背部的主板内，推荐每个按键单独走线，以使得按键能与pcb烧写的键位完全一致
为了防止安装后误触屏幕，用绝缘胶布贴住每个按键的底部。
![微信图片_20250904224124](https://github.com/user-attachments/assets/f6c62ac2-c91a-4544-923b-08250b3d07d5)


总计16根导线，慢慢理顺装进耳机孔的侧边槽位里
(全项目最难的部分，因为尺寸问题，没有太多走线的空间，这里请放平心态慢慢操作)
![微信图片_20250904224129](https://github.com/user-attachments/assets/de28197e-5f19-4377-9f73-a84c55812848)




5.到这里为止，你可以尝试将平板慢慢装入支架内部
如果有凸起的颗粒或支撑碎片，请用锉刀打磨

6.otg直角转接头放置在平板底部，设计时留有约1.5mm高度余量，请考虑用纳米胶增高，确保完全插入平板，没有问题后涂胶固定(推荐自行设计固定件)
用pcb板店家赠送的数据线，连接otg转接A口与pcb键盘C口，检查按键是否正常输出。

最后上色，固定，大功告成

