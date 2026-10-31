
# Maicrodx V3模型指南
<br><img width="200" alt="微信图片_20261025023051_59_2" src="https://github.com/user-attachments/assets/b291b778-229c-4c78-aa2a-f10c4e70cfc5" />

现在制作框体所有必要的文件都已经上传。 <br>

如果您现在还能看到这句话，说明教程的部分内容仍在建设中……顺序可能较为混乱，谨此致歉。<br>


<br>
<br>

开始前准备
-----

V3模型分为适配 11英寸 与 12.5+英寸 平板的两个版本。<br>
在互联网查找您的平板外围尺寸<br>
下载makerworld网页内的[V3]模型<br>
https://makerworld.com.cn/zh/models/1561531 <br>
<div align="center"><img width="500" alt="Snipaste_2026-10-26_17-49-43" src="https://github.com/user-attachments/assets/6c206ae4-638b-40e0-91c6-d5f1045adfbd" /> 
<br>切片文件
</div>
<br>

使用切片软件内的尺子工具量取框体尺寸,只需要确认平板屏幕的短边能否放入，厚度和长度在框体内可以调整<br>
确认无误后，开始打印

<br>
<br>
如果打印后发现层纹过于明显，则需要进行打磨。否则安装灯条后层纹会被照得更加明显。<br>
打磨需要选购不同目数的砂纸，目数越低越粗糙，遵循从粗到细的原则，（对这个来说用80 200 600 1000就够了）
<div align="center"><img width="300"  alt="0265b2b383c8f8d9e084716329cb6e13" src="https://github.com/user-attachments/assets/b3544391-e254-4a38-a017-baae88b64e66" />
<br>
经过打磨处理后的外框 </div>
<br>
<br>
<br>
<br>
<br>
<br>

除了BOM内标注了电路板会使用到的电子元器件 还有另外需要购买的器件如下：
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
<br>
<br>
<br>
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

</div>


<br>
<br>
<br>
<br>

<br><br>

<div align="center"><img width="800"  alt="微信图片_20261026222227_75_2" src="https://github.com/user-attachments/assets/14f05b7e-5bca-4924-97aa-db1ea810b613" /><br>头灯走线示意图<br></div>
<br> 

**Step1** 
: ws2812输入端焊接三根长度适中的导线，沿着红色箭头方向安装,头壳的背后的斜孔进入，直到灯条完全填充u形的区域。
<br> **Step2** :将导线沿着上方全部抽出。
<br> **Step3** :沿着蓝色箭头方向，穿过模型的垂直孔，向下走线。


<br><br>
<br> <div align="center">
ws2812灯光通讯逻辑： <br>
主控 --> FPC Din --> 轮盘 --> FPC Dout --> 主控 --> 头灯 <br>
当灯光出现问题，按照此逻辑排查问题
</div>


<br>
<br>
<br>
<br>

<br><br>
灯光布置取线长度

| 类型\尺寸 | 11英寸框 | 12英寸框 |
| :--- | :--- |  :--- |
| ws2812 | 25颗 | 31颗 |
| cob | 53cm | 61cm |
