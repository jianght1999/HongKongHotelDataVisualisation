# HK_Hotel_Data_Vis
The dataset was downloaded from a tableau course in bilibili. The name of the uploader is '未名学院'. It describes the detailed information of the hotels in Hong Kong, including their locations, prices and so forth. I'm trying to use the matplotlib, pandas and numpy packages to visualize the data.


**Data description**
The data describes the informations about the hotels in Hong Kong. The file includes two sheets, sheet one has 10 columns('名字'(name),'类型'(type),'城市'(city),'地区'(region),'地点'(location),'评分'(rate),'评分人'(number of ratings),'价格'(price),'价格等级'(price level),'热门等级'(popular level)), and sheet two has only 2 columns('地区'(region),'目标均价'(average prices)).
It's a dataset with simple structure, so I'd like to visualize it to make the imformation more clear.


**1.Regional distribution of hotels**

This is a bar chart which shows the regional distribution of hotels in HK.

![barchart](https://github.com/jianght1999/HongKongHotelDataVisualisation/assets/80138413/6f59c554-816f-4655-8671-cc449571a4b8)



**2.Proportion of different types of hotels**

This is a pie chart shows the proportion of different types of hotel. And I chose the four hotel types with the highest percentage to show their labels, and the rest were categorised as "其他类型".

![piechart](https://github.com/jianght1999/HongKongHotelDataVisualisation/assets/80138413/9057a6d6-54d8-4684-aaa6-4955a60979b0)



**3.Hong Kong maps with numbers of hotels**

I drew the number of the hotel on the map of Hong kong, and the darker the colour, the more hotel. The .shp data was downloaded from http://datav.aliyun.com/portal/school/atlas/area_selector, and was transformed from .json to .shp on https://mapshaper.org/. Latitude and longitude are marked using the DMS marking method. Thanks to Mr.'诺若落跺拓' on the CSDN!

![map](https://github.com/jianght1999/HongKongHotelDataVisualisation/assets/80138413/fd43ef5c-87d4-4e12-af9f-d6f3cb913bd3)
