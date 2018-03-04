# location
改变手机定位的当前位置，可以模拟手机打卡

1.创建一个空项目

2.将一个如下写有经纬度（lat/lon）的GPX文件拖到项目中
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<gpx
xmlns="http://www.topografix.com/GPX/1/1"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
xsi:schemaLocation="http://www.topografix.com/GPX/1/1 http://www.topografix.com/GPX/1/1/gpx.xsd"
version="1.1" 
creator="gpx-poi.com">
   <wpt lat="40.048098" lon="116.277146">
      <time>2017-01-23T07:01:25Z</time>
   </wpt>
</gpx>

3.将次项目跑在真机上，然后选择Debug/Simulate location下，刚才所添加的包含有经纬度的GPX文件

4.打开手机上面的地图，就可以看到所显示的位置就是刚才GPX中所设置的位置
