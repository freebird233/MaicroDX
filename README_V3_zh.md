

# Maicrodx V3模型指南

<br>
<br>

[what's new?](https://github.com/user-attachments/files/34226053/what.s.new.1.pdf)


现在制作所需的所有必要的文件都已经上传。 <br>

如果您现在还能看到这句话，说明教程的部分内容仍在建设中……顺序可能较为混乱，谨此致歉。<br>



<br>
<br>

# 打印模型


V3模型分为适配 11英寸 与 12.5+英寸 平板的两个版本。<br>
在互联网查找您的平板外围尺寸<br>
下载makerworld网页内的[V3]模型<br>
https://makerworld.com.cn/zh/models/1561531 <br>
<div align="center"><img width="500" alt="Snipaste_2026-10-26_17-49-43" src="https://github.com/user-attachments/assets/6c206ae4-638b-40e0-91c6-d5f1045adfbd" /> 
 <img width="350"  alt="image" src="https://github.com/user-attachments/assets/394a536e-dbd0-4ef1-bf3d-1ac52f8b2cb9" />

<br>切片文件
</div>
<br>

使用切片软件内的尺子工具量取框体尺寸,确认平板屏幕的短边能否放入，厚度和长度在框体内可以调整<br>
<br>
请务必测量模型尺寸，对比您自己的平板尺寸，确认无误再打印

<br>
<br>

后处理
-----

如果打印后发现层纹过于明显，则需要视情况进行打磨<br>
打磨需要选购不同目数的砂纸，目数越低越粗糙，从粗逐步换到细
<div align="center"><img width="300"  alt="0265b2b383c8f8d9e084716329cb6e13" src="https://github.com/user-attachments/assets/b3544391-e254-4a38-a017-baae88b64e66" />
<br>
经过打磨处理后的外框 </div>
<br>
<br><br><br>

# 采购器件
除了电路板（BOM表）的器件外 还有另外需要购买的内容如下：
<br>
<img width="100"  alt="7f410a41bbb1690c873d6deabcacb916" src="https://github.com/user-attachments/assets/3c5693ba-8e29-4881-9f6d-408bb0c839b2" />DCDC可调降压模块 https://mobile.yangkeduo.com/goods2.html?ps=X5uzsILUIu
<br>
<img width="100"  alt="7d21361d32f2b419bc44bd6332f07f48" src="https://github.com/user-attachments/assets/7dd8d886-2a8f-474d-aa66-3ab99add5063" />
5V cob灯带 https://mobile.yangkeduo.com/goods1.html?ps=PZzBEKW0eg (3mm宽 1米)
<br>

<img width="100"  alt="366486b9eb7dd0acfdc6ddf0f57b6d35" src="https://github.com/user-attachments/assets/5ff13a28-e148-4ec9-a05a-f42681099d92" />ws2812灯珠 https://e.tb.cn/h.jez4mzi5QyXiVmW?tk=45fETDGuaXV (100灯/米
 0.5米 裸板)
<br>
<img width="100"  alt="56d22c5dc6d6c641a3a653eefd909377" src="https://github.com/user-attachments/assets/c99a3a86-27e3-4646-9d53-7573cbeeb5fd" />CtC数据线 https://mobile.yangkeduo.com/goods2.html?ps=SiMcasrXyJ (双头c 1条装)
<br>

<img width="100"  alt="image" src="https://github.com/user-attachments/assets/b1845ebf-d027-4e17-94d1-083cf48674c6" /> 自攻螺丝 https://e.tb.cn/h.j6yBLOpGoLmfVUH?tk=jGQt6YpXLq4  (可选，装饰用)
<br>
<img width="100" alt="image" src="https://github.com/user-attachments/assets/de1289ad-a48f-4fd2-b7ba-acf30c2b10e4" /> 矮轴 https://e.tb.cn/h.jRXogoRPmuNxnyg?tk=RaZK6Yp5Pvr



<br>
<br>
<br>
<br>
<br>

# 主控板贴片

<br>
<br>
参考该网站贴片，能提高一些效率<br>

[V3交互式BOM.html](https://github.com/user-attachments/files/34361656/V3.BOM.html)

<br>
<br>
<div align="center">对于这个项目，有部分器件不是必须的<br> 焊完后的主控板应该长这个样子。烧录程序后,上电并接入耳机时应该会有三个灯是亮着的<br>
<img width="280"  alt="8c8c32762c9862159e4f02e3d143df3d" src="https://github.com/user-attachments/assets/fc67a035-1699-4933-bede-161580ee5546" /><img width="500"  alt="dcb986164ce6d01910a24e40892780cf" src="https://github.com/user-attachments/assets/ddc6c8b3-db79-4d54-a223-659470e285bc" />
<br>
<br>
<br>
<br>
当充电口接入时，移动设备会显示快速充电。通知栏出现实体键盘与USB声卡字样

<img width="500" alt="101338db0f6c94672967f020e723a215" src="https://github.com/user-attachments/assets/9ca87a61-b088-43f4-b22e-2688a6994ba9" /><img width="315" alt="8cec2a484f5962b6bd445f760a82fa79" src="https://github.com/user-attachments/assets/7f25c002-6f49-4bfc-806b-1d0611d9c0d1" />

</div><br>
<br>

烧录程序
-----
在官网下载烧录软件[WCHISPStudio](https://www.wch.cn/downloads/WCHISPTool_Setup_exe.html) <br> 
在[Release处](https://github.com/freebird233/MaicroDX/releases)下载hex固件程序<br>
 <br><div align="center">
<img width="720" alt="Snipaste_2026-07-02_20-34-18" src="https://github.com/user-attachments/assets/3abe23a6-3a7c-488c-9f09-9790bfdc47e0" /> <br>
WCHISPStudio程序界面</div><br><br>
- 将板子连接电脑，此时会显示出设备名<br>
- 烧录配置按照图中样式勾选，点击下载<br>
<br>

基础故障诊断
-----
  <br>
  烧录程序找不到设备 ---> 短接BOOT上电，重新烧录固件 ---> 检查typeC母座焊盘GND 5v D+ D- 是否连锡，漏锡或更换单片机 <br> <br>
  电脑弹出通知： **无法识别的USB硬件**  ---> typeC母座焊盘 D+ D- 连锡，漏锡或更换单片机<br> <br>
  电脑弹出通知： **硬件超出电流最大载荷** ---> 主板短路 <br> <br>
  接入耳机后工作灯闪烁 无音频输出 ---> 重焊U4 <br> <br>
  
  
<br>
<br>
<br>
<br>

# 分控版贴片(轮盘)
<br>
<br>
在maicrodx controller的仓库里下载gerber文件 (分控板随着那个项目更新,主控板在这边)
<br>
<br>

> 尽可能选择较薄的板厚
<br><br>
默认: 双层板，0.8厚，白色，OSP<br>
样板订单单件价格约 16 CNY/张 <br><br>如果选择了非白色，在按键的左右间隙会看到电路板

<br><br><div align="center">
<img width="510"  alt="image" src="https://github.com/user-attachments/assets/786b21bc-3523-4812-9541-676310c09172" />
<img width="400"  alt="image" src="https://github.com/user-attachments/assets/2cf4c2b8-833b-4672-bba7-751d506be6a5" />
<br>Release内的外壳文件默认适配Cheery家的矮轴系列,你也可以自行修改封装来适配其他轴体.<br>
例如图示 改为了凯华白雨黑云遮山1353Hitbox 全白轴体</div>

<br>
<br>




https://github.com/user-attachments/assets/6a8587d2-b886-4417-bf86-0edc023bd731

<br>

- 检查信号灯是否依次亮起（就像上面的视频）由于WS2812的串联信号传输特性，当一个灯珠信号脱焊，会导致后面的所有灯熄灭。<br><div align="center"> **通讯串联关系=灯珠依次亮起的顺序** </div><br><br>

- 短接各按键的两个焊盘，检查是否有键控信号输出，且白灯转变为黄灯<br>附: [按键测试网站](https://www.zfrontier.com/lab/keyboardTester)
<br>
<br>

安装外壳
-----

<br>  <br> 
MaicroDX Controller外壳共由两部分组成。优先下载 makerworld上的模型文件(我难以检查并在多平台更新) <br>
<div align="center"><img width="800" alt="Snipaste_2026-07-02_23-48-56" src="https://github.com/user-attachments/assets/4cb6bfd1-12f3-4750-9b2f-d03b26c6ff84" /></div>
"外壳" "外壳底板" 通过过盈配合方式固定  <br> 
轴体与pcb板通过焊锡固定 <br> 
外壳的PCB安装槽有比较大的悬空区域，在打印时，最好选用双材料的耗材作为支撑接触面,这样能显著提高效率和模型质量。例如:PLA作为PETG的支撑 <br> <br>
 <br>
 <br>  <br> 
<br>
<br>
<br>

# 框体灯光布置
本节详细描述mdx框体内灯光部分内容,在开始前，先确定两种灯带的裁剪长度
<div align="center">
  
|  <div align="center"> 类型\尺寸   |   <div align="center">11英寸框   |   <div align="center">12英寸框   |
| :--- | :--- |  :--- |
|   <div align="center">ws2812   |   <div align="center">25颗   |   <div align="center">31颗   |
|   <div align="center">cob   |   <div align="center">≈53cm   |   <div align="center">≈61cm   |
<div align="center"><img width="700" alt="c71ba10e22d39109f54d0fa14471b119" src="https://github.com/user-attachments/assets/ccb61cf2-b615-46ca-a5cf-d419d992bd1b" />

</div>
<br>
<br><br>
<br>

<div align="center"><img width="800"  alt="微信图片_20261026222227_75_2" src="https://github.com/user-attachments/assets/14f05b7e-5bca-4924-97aa-db1ea810b613" /><br>头灯走线示意图<br></div>
<br> 
</div>

**Step1** 
: ws2812输入端焊接三根长度适中的导线，沿着红色箭头方向安装,头壳的背后的斜孔进入，直到灯条完全填充u形的区域。
<br> **Step2** :将导线沿着上方全部抽出。
<br> **Step3** :沿着蓝色箭头方向，穿过模型的垂直孔，向下走线。


<br><br>
<br> <div align="center">
<br>
<img width="600"  alt="image" src="https://github.com/user-attachments/assets/67dcd6f4-3446-4291-9c9e-c95facb81cda" />

<br>

ws2812灯光通讯逻辑： <br>
主控 --> FPC Din --> 轮盘 --> FPC Dout --> 主控 --> 头灯 <br>
当灯光出现问题，按照此逻辑排查问题
</div>


<br>
cob灯带是通过自带的背胶固定在框体轮盘上的，走主控的dcdc外接板来手动控制亮度，根据上面的表格裁切好后，撕掉一点背胶，焊两根ok线上去。
<br>
<br><div align="center">
<img width="300"  alt="d2fab9166c778eb366c540e1b5e266a0" src="https://github.com/user-attachments/assets/d2a09b47-08b9-4c90-be0c-33421bb6d488" /> <img width="300"  alt="f224b8227ed809cb45b568eb8bb618cd" src="https://github.com/user-attachments/assets/91a8c40d-1ced-4517-93b1-fe33aa50c329" /> <img width="300"  alt="d43cacdae06dbfdb33d1740236994a43" src="https://github.com/user-attachments/assets/69c94f94-2a91-4aff-bf61-f0a9ebbd841f" />

用热熔胶加固<br>
</div>
<br>
<br>
<br>

<br><br>


# 无灯光轮盘
<br>
<br>
如果不需要灯光,可以按照下文制作无灯光版本的控制轮盘，这样复刻难度会降低. 同样能在v3框体上使用
<br>
<br>
<br>
<br>
<div align="center"><br>
 https://makerworld.com.cn/zh/models/1561531<br>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/f20d0d59-8445-4485-8bdd-f4cf886d131d" /><br>
打印这个配置文件</div>
<br>
<br>
<div align="center">
<img width="500"  alt="image" src="https://github.com/user-attachments/assets/35f810d8-5e0c-46f0-a25a-82a08cb7a965" />
<br>
外控板只贴必要的元器件
<br>
<br>
<br>
<br>
 <img width="900" height= alt="image" src="https://github.com/user-attachments/assets/0eea48f7-3ef0-465b-b602-967551f5211e" /><br>
为每个按键的两个触角飞线，让轮盘外壳上的数字位对应板子上的数字，另一个触角接GND，一共需要飞16根线 <br><br><br><br>
<img width="500"  alt="2c12e648aacdde16a89e48ecf2893bba" src="https://github.com/user-attachments/assets/33313f79-54bc-4519-9526-17a48ffc65d4" /><img width="500"  alt="403b71811d136e94a510ad45d4fbbbc9" src="https://github.com/user-attachments/assets/d2b3321e-67fe-4680-be17-75a06073881c" /><br>
钳子剪开横条，把线缆布置进去
<br>
<br><br>
<br>
<img width="600"  alt="3e267254ec4e80eb1256ba0a3bd9d5b9" src="https://github.com/user-attachments/assets/a19a6863-5bf6-42cd-83d6-1fb2aff3efe0" /><img width="315"  alt="b8617a2020be5331d3dc222d81dfcb6f" src="https://github.com/user-attachments/assets/51834f00-f553-4d4e-9bb6-a1a90ddda0d4" /><br>
盖上防尘盖 , 线缆两边点一些热熔胶加固
<br>
<br><br>
<br>
<img width="600"  alt="7862b3dba1522f253971b73db285749f" src="https://github.com/user-attachments/assets/f260eaf9-3d7d-4319-9159-7fbcb3d83d1a" /><br>
最终效果<br>
<br>
</div>
备注: 烧录带灯的固件，上电需要等待5s才会工作


<br>
<br><br>
<br><br>

# 组装
本节将介绍Maicrodx的框体组装流程，推荐的胶水是ab环氧胶+美纹胶定型。

框体
----
<div align="center"><img width="900"  alt="image" src="https://github.com/user-attachments/assets/354b0d7a-d874-4eb4-85be-f2b8f98e27a5" /><br>爆炸图
<br><br>

彩虹装饰框
----
<br><br>
第一种方式<br><img width="600"  alt="image" src="https://github.com/user-attachments/assets/5ae85412-738a-4703-b3e7-d773117511e7" />
<br>打印这个配置文件，用对应的颜色耗材，或是全白打印后涂色
<br><br><br>
第二种方式<br>
<img width="600" alt="4f0dbb332f1af8da2ebad8a157b2294a" src="https://github.com/user-attachments/assets/264a5e1b-e888-4269-816f-04ed868e11bb" />
<br>下载Release内的cad文件，发给亚克力板厂做定制<br>
<br><br>
两种方案效果对比<br>
<img width="600" alt="ad20721d1ef980eebc84f5f7680e1cd6" src="https://github.com/user-attachments/assets/033d5108-2375-4c96-b24e-b4ac05df29e4" />

<br><br><br><br>
耳机
----


<br>
<div align="center"><img width="900"  alt="image" src="https://github.com/user-attachments/assets/22d8211d-7fac-4e9a-bed3-83a8942c2c78" />
<br>爆炸图
<br><br>

<img width="280"  alt="image" src="https://github.com/user-attachments/assets/2cdbfab3-d747-48be-8b13-59c268d1b47f" />
<img width="400" alt="3926b9044590883553583c591ca888d2" src="https://github.com/user-attachments/assets/b1a4e1f2-e0be-401a-91fc-5e04bf457f5f" />
<img width="230"  alt="cefab52c16c0a22639bb79ff11d2c6f9" src="https://github.com/user-attachments/assets/30383f4b-40be-4939-bf0a-f74a5c2dd241" />
<br>用光固化制作透明外壳能获得更好效果<br><br>
</div>
<br>
<br>
左 75mm
<br>
右 210mm


