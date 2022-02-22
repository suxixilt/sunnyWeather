# SunnyWeather

## 项目概述

1. 可以搜索全球大多数国家的各个城市天气数据
2. 可以查看全球绝大多数城市的天气信息
3. 可以自由切换城市，查看其他城市的天气
4. 可以手动刷新实时天气

## API接口

1. 查询城市数据

   ```
   https://api.caiyunapp.com/v2/place?query=北京&token={token}&lang=zh_CN
   ```

2. 查询天气情况

   ```
   https://api.caiyunapp.com/v2.5/{token}/经度，纬度/realtime.json
   ```

3. 查询未来几日天气

   ```
   https://api.caiyunapp.com/v2.5/{token}/经度，纬度/daily.json
   ```

   

