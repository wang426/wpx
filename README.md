# 2020年新工科联盟-Xilinx暑期学校（Summer School）项目。
项目名称： 创客彩灯
---------
项目概要<br>
---------
A、我们组所设计的是创客彩灯，他是通过外接摄像头来识别颜色，进而将数据传入FPGA板，通过处理在RGB灯上面显示出相应的颜色。<br>
B、 计划实现功能：摄像头驱动、颜色识别并能对所有目标颜色成功亮起相应彩灯。<br>
C、技术方向：SPI串行通信、Camera-IP核、RGB数据转换<br>

技术方向<br>
----------
在整个设计过程中，我们先熟悉了SEA开发板的使用流程、了解了SPI串行通信协议，最后通过调用IP核、编写头文件、RGB信号转换等手段，将摄像头识别到的数据通过转换传到板载RGB彩灯上，并完成相应颜色的识别。<br>

已实现的功能<br>
------------
能成功进行图像处理，能对红绿蓝三原色成功识别并亮灯；但由于光线等其他原因，器件对其他颜色的识别有一定的误差。

小组成员<br>
------------
王鹏旭<br>
武占翔<br>

工具版本<br>
------------
Vivado2018.3<br>

板卡型号和外设列表<br>
---------
板卡型号：SEA<br>
芯片型号：SPARTAN 7 xc7s15<br>
外设列表：OV5647<br>

仓库目录介绍<br>
--------
ExecutableFiles<br>
    bit流文件<br>
       <br>
Color recognize<br>
    实现彩灯识别和点亮的整个工程<br>
    <br>
Sourcecode<br>
    所有源代码<br>
    Camera_Demo.v<br>
    Driver_Bayer_To_RGB.v<br>
    Driver_Csi_To_Dvp.v<br>
    Driver_IIC.v<br>
    Driver_MIPI.v<br>
    Driver_SK6805.v<br>
    OV5647_Init.v<br>
    RGB.v<br>
    TEST.v<br>
    Trigger_Generator.v<br>
    <br>
Images<br>
    所有图片以及影像资料<br>
    
    
    
    
    
  
