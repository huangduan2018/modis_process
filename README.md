This projection mainly used in processing Modis raster data. It Containing translate,merge,projection,mask and some other methods. It need support of GDAL and  written by Python.
This edition can be used both in single PC and HTCondor clusters. 

##依赖 ：
- python 2.7
- gdal-bin   >1.8
- python-gdal  > 1.8
- python-numpy


##执行： 

- main.py.py   主函数
- methods-on-modis.py   依赖模块
- viewTif.py   一个显示tif的辅助方法


##必要目录（程序会自动检测并建立)：
- /out	输出文件夹
- /data	元数据文件夹
- /shp	矢量数据文件夹
- /temp	暂存文件夹
