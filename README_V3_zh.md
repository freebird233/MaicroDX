
# Maicrodx V3模型指南
<br><img width="200" alt="微信图片_20261025023051_59_2" src="https://github.com/user-attachments/assets/b291b778-229c-4c78-aa2a-f10c4e70cfc5" />

施工中...
<br>
<br>

开始前准备
-----

V3模型分为适配 11英寸 与 12.5+英寸 平板的两个版本。<br>
在互联网查找您的平板外围尺寸<br>
下载makerworld网页内的[V3]模型<br>
https://makerworld.com.cn/zh/models/1561531 <br>
<img width="500" alt="Snipaste_2026-10-26_17-49-43" src="https://github.com/user-attachments/assets/6c206ae4-638b-40e0-91c6-d5f1045adfbd" />
<br>

使用切片软件内的尺子工具量取框体尺寸
确认无误后，开始打印

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

轮盘部分的复刻指南在我的Maicrodx Controller的项目内
<br>

ws2812灯光通讯逻辑： <br>
主控 --FPC-Din--> 轮盘 --FPC-Dout--> 主控 ----> 头灯
当灯光出现问题，按照此逻辑排查问题
