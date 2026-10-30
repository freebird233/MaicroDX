
# Maicrodx V3模型指南
<br><img width="200" alt="微信图片_20261025023051_59_2" src="https://github.com/user-attachments/assets/b291b778-229c-4c78-aa2a-f10c4e70cfc5" />

现在制作框体所有必要的文件都已经上传。 <br>
All the necessary documents required for production have now been uploaded.<br><br>
如果您现在还能看到这句话，说明教程的部分内容仍在建设中……顺序可能较为混乱，谨此致歉。<br>
If you are still seeing this message, it means that certain sections of the tutorial are still under construction... The order may be somewhat disorganised, and we apologise for any inconvenience

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
打磨需要选购不同目数的砂纸，目数越低越粗糙，遵循从粗到细的原则，（推荐80->200->600->1000）
<div align="center"><img width="600"  alt="0265b2b383c8f8d9e084716329cb6e13" src="https://github.com/user-attachments/assets/b3544391-e254-4a38-a017-baae88b64e66" />
<br>
经过打磨处理后的外框 </div>
<br>
<br>

BOM内标注了电路板会使用到的电子元器件，对于这个项目，10P FPC底座,插针,平衡头底座不是必须的<br>
另外需要购买的器件如下：
<br>
DCDC可调降压模块 https://mobile.yangkeduo.com/goods2.html?ps=X5uzsILUIu
<br>
5V cob灯带 https://mobile.yangkeduo.com/goods1.html?ps=PZzBEKW0eg (3mm宽 1米)
<br>
ws2812灯珠 https://e.tb.cn/h.jez4mzi5QyXiVmW?tk=45fETDGuaXV (108灯珠规格 0.5米)
<br>
<br>

轮盘部分的复刻指南跳转>> [MaicroDX Controller](https://github.com/freebird233/MaicroDX-Controller/tree/main)
<br><br>

<div align="center"><img width="800"  alt="微信图片_20261026222227_75_2" src="https://github.com/user-attachments/assets/14f05b7e-5bca-4924-97aa-db1ea810b613" /><br>头灯走线示意图<br></div>
<br> **Step1** : ws2812输入端焊接三根长度适中的导线，沿着红色箭头方向安装,头壳的背后的斜孔进入，直到灯条完全填充u形的区域。
<br> **Step2** :将导线沿着上方全部抽出。
<br> **Step3** :将导线沿着蓝色箭头方向，穿过模型的垂直孔，向下走线。


<br><br>
<br> <div align="center">
ws2812灯光通讯逻辑： <br>
主控 --> FPC Din --> 轮盘 --> FPC Dout --> 主控 --> 头灯 <br>
当灯光出现问题，按照此逻辑排查问题
</div>




<br><br>
灯光布置取线长度

| 类型\尺寸 | 11英寸框 | 12英寸框 |
| :--- | :--- |  :--- |
| ws2812 | 25颗 | 31颗 |
| cob | 53cm | 61cm |
